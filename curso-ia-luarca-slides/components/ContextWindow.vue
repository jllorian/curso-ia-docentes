<template>
    <!-- Ventana de Contexto (destino final) -->
    <div 
      class="context-window"
      v-motion
      :initial="{ opacity: 0, scale: 0.8 }"
      :enter="{ opacity: 1, scale: 1 }"
      :click-1="{ scale: 1.02 }"
    >
      <TransitionGroup name="message-merge">
        <MessageBox 
          v-for="(msg, index) in contextMessages"
          :key="msg.id"
          :type="msg.type"
          :title="msg.title"
          :icon="msg.icon"
          :class="['merged-message', `z-${index + 1}`]"
        >
          {{ msg.content }}
        </MessageBox>
      </TransitionGroup>
    </div>
  
    <!-- MessageBox originales con animación de fusión -->
    <TransitionGroup name="message">
      <MessageBox 
        v-if="currentStep < 4"
        type="system" 
        title="Mensaje del sistema" 
        icon="../recursos/icon/systemIcon.svg"
        v-click="1"
        class="original-pos-system"
      >
        <!-- Contenido del system message -->
      </MessageBox>
  
      <MessageBox 
        v-if="currentStep < 5"
        type="user" 
        title="Mensaje del usuario" 
        icon="../recursos/icon/userIcon.svg"
        v-click="2"
        class="original-pos-user"
      >
        <!-- Contenido del user message -->
      </MessageBox>
    </TransitionGroup>
  </template>
  
  <script setup>
  import { ref, computed } from 'vue'
  
  const currentStep = ref(0)
  const contextMessages = ref([])
  
  // Lógica para manejar los pasos y llenar la ventana de contexto
  const handleClickStep = (step) => {
    currentStep.value = step
    if(step === 4) {
      contextMessages.value = [
        { id: 1, type: 'system', title: 'Contexto Sistema', content: 'Eres un experto pedagogo...', icon: '../recursos/icon/systemIcon.svg' },
        { id: 2, type: 'user', title: 'Contexto Usuario', content: '"Periodistas por un día"...', icon: '../recursos/icon/userIcon.svg' }
      ]
    }
  }
  </script>
  
  <style>
  /* Animación de fusión */
  .message-move,
  .message-merge-move {
    transition: all 0.8s cubic-bezier(0.68, -0.55, 0.27, 1.55);
  }
  
  .context-window {
    @apply fixed top-4 left-1/2 -translate-x-1/2 w-3/4 bg-white/90 backdrop-blur-sm 
           rounded-lg shadow-xl p-4 transform origin-top;
  }
  
  .original-pos-system {
    @apply absolute top-12 left-12;
  }
  
  .original-pos-user {
    @apply absolute top-48 right-12;
  }
  
  .merged-message {
    @apply w-full mb-2 scale-90 hover:scale-95 transition-transform;
    transform-origin: top center;
  }
  
  /* Animaciones personalizadas */
  .message-enter-from {
    opacity: 0;
    transform: translateY(20px) scale(0.8);
  }
  
  .message-leave-to {
    opacity: 0;
    transform: 
      translate(
        calc(var(--target-x, 0) - var(--current-x, 0)),
        calc(var(--target-y, 0) - var(--current-y, 0))
      ) 
      scale(0.5);
  }
  
  .message-merge-enter-from {
    opacity: 0;
    transform: scale(0.8) rotateZ(-5deg);
  }
  </style>
  