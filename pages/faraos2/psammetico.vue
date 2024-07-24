<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/psammeticus.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Psammetico
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Psammetico I, também conhecido como Psamtik I, foi o fundador da 26ª Dinastia e governou de 664 a.C. a 610 a.C.


            Psammetico I era filho de Necao I, um príncipe do Delta do Nilo que havia sido nomeado governador pelos assírios. Após a morte de seu pai, Psammetico I conseguiu reunir apoio suficiente para declarar-se faraó e expulsar os assírios do Egito.
            <p class="mb-2 text-l">
              Durante seu reinado, Psammetico I conseguiu reunificar o Egito, que estava dividido e enfraquecido devido ao domínio estrangeiro e às lutas internas. Ele conseguiu isso através de alianças estratégicas e da contratação de mercenários gregos, conhecidos como "os homens de bronze", que o ajudaram a consolidar seu poder. Psammetico I também promoveu a recuperação econômica e cultural do Egito, restaurando templos e incentivando o comércio.

              Uma de suas realizações mais notáveis foi a fundação de uma nova capital em Sais, no Delta do Nilo, que se tornou um importante centro administrativo e cultural. Ele também foi um grande patrono das artes e da religião, patrocinando várias obras de construção e restauração em todo o Egito.
            </p>
            <p class="mb-2 text-l">
              Uma curiosidade interessante sobre Psammetico I é o experimento linguístico que ele supostamente conduziu. De acordo com o historiador Heródoto, Psammetico I quis determinar qual era a língua mais antiga do mundo. Para isso, ele isolou duas crianças desde o nascimento, sem permitir que ouvissem qualquer fala humana. As crianças foram criadas por um pastor que não falava com elas. Quando as crianças finalmente falaram, a primeira palavra que disseram foi "bekos," que era a palavra frígia para "pão". Psammetico I concluiu que a língua frígia era a mais antiga. Embora a veracidade deste experimento seja questionável, a história ilustra a curiosidade intelectual de Psammetico I e seu interesse pelas origens da linguagem e cultura.
            </p>
          </label>
        </div>
  
        <div class="mt-4 text-center">
          <nuxt-link to="/">
            <button class="bg-yellow-300 hover:bg-yellow-400 text-black text-xl font-bold py-2 px-4 rounded">
              Menu
            </button>
          </nuxt-link>
        </div>
      </div>
    </div>
  </template>
  
  <style scoped>
  .bg-brown-dark {
    background-color: #211512;
  }
  </style>
  