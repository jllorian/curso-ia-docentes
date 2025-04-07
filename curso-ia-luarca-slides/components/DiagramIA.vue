<template>
    <div class="diagram-container">
      <svg viewBox="-10 100 1500 1200" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <!-- Círculos -->
          <path id="4.cu_sy_dl2hha1q79o21-fill" d="M 298 586C 457.058 586 586 457.058 586 298C 586 138.942 457.058 10 298 10C 138.942 10 10 138.942 10 298C 10 457.058 138.942 586 298 586ZM 298 586C 417.294 586 514 489.294 514 370C 514 250.706 417.294 154 298 154C 178.706 154 82 250.706 82 370C 82 489.294 178.706 586 298 586Z" fill="#ffebf7"/>
          <path id="3.cu_sy_958zcu1q79oub-fill" d="M 226 442C 345.294 442 442 345.294 442 226C 442 106.7065 345.294 10 226 10C106.7065,10,10,106.7065,10,226C10,345.294,106.7065,442,226,442ZM226,442C146.471,442,82,377.529,82,298C82,218.471,146.471,154,226,154C305.529,154,370,218.471,370,298C370,377.529,305.529,442,226,442Z" fill="#ffeceb"/>
          <path id="2.cu_sy_9lz3y1q79pn1-fill" d="M154,298C233.529,298,298,233.529,298,154C298,74.4715,233.529,10,154,10C74.4715,10,10,74.4715,10,154C10,233.5295,74.4715,298,154,298ZM154,298C114.2355,298,82,265.7645,82,226C82,186.2355,114.2355 ,154 ,154 ,154 C193 .764 ,154 ,226 ,186 .2355 ,226 ,226 C226 ,265 .7645 ,193 .764 ,298 ,154 ,298 Z" fill="#fff2e5"/>
          <path id="1.cu_sy_1uuwiym1q79q87-fill" d="M 154 82C 154 121.765 121.765 154 82 154C 42.2355 154 10 121.765 10 82C 10 42.2355 42.2355 10 82 10C 121.765 10 154 42.2355 154 82Z" fill="#fffbda"/>
  
          <!-- Strokes -->
          <<path id="4.cu_sy_dl2hha1q79o21-stroke" 
            fill="none" 
            stroke-linecap="round" 
            stroke-linejoin="round" 
            stroke-miterlimit="4" 
            stroke="#de58a9" 
            stroke-width="2" 
            d="M 298 586C 457.058 586 586 457.058 586 298C 586 138.942 457.058 10 298 10C 138.942 10 10 138.942 10 298C 10 457.058 138.942 586 298 586ZM 298 586C 417.2935 586 514 489.2935 514 370C 514 250.7065 417.2935 154 298 154C 178.7065 154 82 250.7065 82 370C 82 489.2935 178.7065 586 298 586Z"/>
          <path id="3.cu_sy_958zcu1q79oub-stroke" fill="none" stroke="#e55753" stroke-width="2" d="M 226 442C 345.294 442 442 345.294 442 226C 442 106.7065 345.294 10 226 10C106.7065,10,10,106.7065,10,226C10,345.294,106.7065,442,226,442ZM226,442C146.471,442,82,377.529,82,298C82,218.471,146.471,154,226,154C305.529,154,370,218.471,370,298C370,377.529,305.529,442,226,442Z"/>
          <path id="2.cu_sy_9lz3y1q79pn1-stroke" fill="none" stroke="#de8431" stroke-width="2" d="M154 298C233.529 298 298 233.529 298 154C298 74.471 233.529 10 154 10C74.471 10 10 74.471 10 154C10 233.529 74.471 298 154 298Z"/>
          <path id="1.cu_sy_1uuwiym1q79q87-stroke" fill="none" stroke="#e0cb15" stroke-width="2" d="M154 82C154 121.765 121.765 154 82 154C42.2355 154 10 121.765 10 82C10 42.2355 42.2355 10 82 10C121.765 10 154 42.2355 154 82Z"/>
  
          <!-- Textos -->
          <text id="tx_intelige_m7yuim1q7b40a-fill"
            stroke="none"
            fill="#de58a9"
            style="font: bold 30px Roboto, sans-serif; white-space: pre;"
            font-weight="bold"
            font-size="20px"
            font-family="Roboto, sans-serif">
            <tspan x="12" y="34" dominant-baseline="ideographic">Inteligencia Artificial</tspan>
          </text>
          <text id="tx_aprendiz_8x4t8e1q7b2fg-fill"
            stroke="none"
            fill="#e55753"
            style="font: bold 30px Roboto, sans-serif; white-space: pre;"
            font-weight="bold"
            font-size="20px"
            font-family="Roboto, sans-serif">
            <tspan x="12" y="34" dominant-baseline="ideographic">Aprendizaje Automático</tspan>
          </text>
          <text id="tx_aprendiz_4hbb3y1q7b37q-fill"
            stroke="none"
            fill="#de8431"
            style="font: bold 30px Roboto, sans-serif; white-space: pre;"
            font-weight="bold"
            font-size="20px"
            font-family="Roboto, sans-serif">
            <tspan x="12" y="34" dominant-baseline="ideographic">Aprendizaje Profundo</tspan>
          </text>
          <text id="tx_iagenera_1hszi1q7b400-fill"
            stroke="none"
            fill="#e0cb15"
            style="font: bold 30px Roboto, sans-serif; white-space: pre;"
            font-weight="bold"
            font-size="20px"
            font-family="Roboto, sans-serif">
            <tspan x="12" y="34" dominant-baseline="ideographic">IA Generativa</tspan>
          </text>

        </defs>
  
        <!-- Grupos interactivos -->
        <g class="interactive-group" transform="translate(600, 99)" @click="navigateToSlide(21)">
          <use href="#4.cu_sy_dl2hha1q79o21-fill"/>
          <use href="#4.cu_sy_dl2hha1q79o21-stroke"/>
          <use href="#tx_intelige_m7yuim1q7b40a-fill" x="-250"/>
          <line x1="-390" y1="50" x2="250" y2="50" stroke="#de58a9" stroke-width="2"/>
          <image href="../recursos/venn/vennIA.svg" x="250" y="0" width="100" height="100"/>
        </g>
  
        <g class="interactive-group" transform="translate(672, 243)" @click="navigateToSlide(21)">
          <use href="#3.cu_sy_958zcu1q79oub-fill"/>
          <use href="#3.cu_sy_958zcu1q79oub-stroke"/>
          <use href="#tx_aprendiz_8x4t8e1q7b2fg-fill" x="-302"/>
          <line x1="-465" y1="50" x2="180" y2="50" stroke="#e55753" stroke-width="2"/>
          <image href="../recursos/venn/vennML.svg" x="177" y="0" width="100" height="100"/>
        </g>
  
        <g class="interactive-group" transform="translate(744, 387)" @click="navigateToSlide(21)">
          <use href="#2.cu_sy_9lz3y1q79pn1-fill"/>
          <use href="#2.cu_sy_9lz3y1q79pn1-stroke"/>
          <use href="#tx_aprendiz_4hbb3y1q7b37q-fill" x="-390"/>
          <line x1="-540" y1="50" x2="100" y2="50" stroke="#de8431" stroke-width="2"/>
          <image href="../recursos/venn/vennDL.svg" x="104" y="0" width="100" height="100"/>
        </g>
  
        <g class="interactive-group" transform="translate(820, 531)" @click="navigateToSlide(22)">
          <use href="#1.cu_sy_1uuwiym1q79q87-fill"/>
          <use href="#1.cu_sy_1uuwiym1q79q87-stroke"/>
          <use href="#tx_iagenera_1hszi1q7b400-fill" x="-520"/>
          <line x1="-610" y1="50" x2="25" y2="50" stroke="#e0cb15" stroke-width="2"/>
          <image href="../recursos/venn/vennGenAI.svg" x="30" y="0" width="100" height="100"/>
        </g>
      </svg>
    </div>
  </template>
  
  <script setup>
  const navigateToSlide = (num) => {
    $slidev.nav.go(num)
  }
  </script>
  
  <style>
  /* Fuente Roboto importada globalmente */
  .diagram-container {
    padding: 2rem;
    border-radius: 12px;
  }
  
  .interactive-group {
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  
  text {
    font-family: 'Roboto', sans-serif;
    text-anchor: middle;
  }

  tspan {
  dominant-baseline: middle;
  }

  svg {
  width: 135%;
  height: auto;
}
  </style>