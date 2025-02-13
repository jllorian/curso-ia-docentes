<template>
    <div class="glossary-card">
      <div class="term-header">
        <h3>{{ term }}</h3>
        <a v-if="source" :href="source" target="_blank" class="source-link">
          <carbon:link class="source-link"/>
        </a>
      </div>
      <p class="definition">{{ definition }}</p>
    </div>
  </template>
  
  <script setup>
  defineProps({
    term: String,
    definition: String,
    source: String
  })
  </script>
  
  <style>
  .glossary-card {
    background: rgba(255,255,255,0.1);
    border-radius: 8px;
    padding: 1.5rem;
    margin: 0.5rem 0;
    margin-left: 0.5rem;
    margin-bottom: 0.5rem;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: all 0.3s ease;
  }
  
  .term-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 0.5rem;
  }
  
  .source-link {
    position: relative;
    color: #4EC5D4;
    display: flex;
    align-items: center;
    gap: 0.3rem;
  }
  </style>
  