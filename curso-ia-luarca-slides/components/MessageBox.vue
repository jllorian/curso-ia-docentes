<template>
    <div class="message" :class="type" v-click="clickStep">
      <div class="header">
        <span class="title">{{ title }}</span>
        <img
          :src="icon"
          class="icon"
          alt="icono"
          @load="handleIconLoad"/>
      </div>
      
      <div class="content" :class="{ 'code-format': isCode }">
        <slot></slot>
      </div>
    </div>
  </template>
  
  <script setup>
  const handleIconLoad = () => {
  console.log('Icono cargado');
  };

  defineProps({
    type: {
      type: String,
      default: 'system',
      validator: v => ['system', 'user', 'ai'].includes(v)
    },
    title: String,
    icon: String,
    clickStep: Number,
    isCode: Boolean
  })
  </script>
  
  <style>
    @keyframes message-entry {
    from { opacity: 0; transform: translateY(20px); }
    to { opacity: 1; transform: translateY(0); }
  }

  .message {
    margin: 1rem auto;
    padding: 1.2rem;
    border-radius: 8px;
    width: 85%;
    opacity: 0;
    animation: message-entry 4s ease-out forwards;
    box-shadow: 0 3px 6px rgba(0,0,0,0.1);
    overflow: visible;
  }
  
  .system {
    border-left: 4px solid #2196F3;
    background: #f0f8ff url('data:image/svg+xml;utf8,<svg ...>') no-repeat 98% 10px;
    float: left;
  }
  
  .user {
    border-left: 4px solid #4CAF50;
    background: #e8f5e9 url('data:image/svg+xml;utf8,<svg ...>') no-repeat 98% 10px;
    float: right;
  }
  
  .ai {
    border-left: 4px solid #FF9800;
    background: #fff3e0 url('data:image/svg+xml;utf8,<svg ...>') no-repeat 98% 10px;
    float: left;
  }
  
  .header {
    display: flex;
    justify-content: space-between;
    margin-bottom: 0.4rem;
  }
  
  .title {
    font-weight: 600;
    color: #616161;
  }
  
  .icon {
    width: 20px;
    height: 20px;
    position: absolute;
    top: 20px;
    right: 20px;
    opacity: 1;
    animation: none;
    transition: none;
    scale: 3.5;
  }
  
  .code-format {
    font-family: 'Fira Code', monospace;
    background: rgba(0,0,0,0.05);
    padding: 0.8rem;
    border-radius: 4px;
  }
  </style>
  