<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/grifo.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Grifo
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            O Grifo Egípcio é uma criatura mitológica que combina características de várias criaturas, mais comumente um leão e uma águia. No entanto, ao contrário dos grifos da mitologia grega e romana, que são mais conhecidos, o grifo egípcio pode ter algumas variações em sua representação. Este ser é um símbolo de poder, proteção e autoridade.

            Na mitologia egípcia, o grifo é uma criatura que incorpora a força do leão, o rei dos animais terrestres, e a majestade da águia, o rei dos céus. Essa combinação simboliza um ser que possui domínio tanto sobre a terra quanto sobre o ar, tornando-o uma figura poderosa e protetora.

            <p class="mb-2 text-l">
                Embora o grifo egípcio não tenha uma mitologia tão detalhada quanto outros seres mitológicos, ele é frequentemente associado a funções protetoras e simbólicas:

                Guardião: Como muitas outras criaturas híbridas na mitologia egípcia, os grifos eram vistos como guardiões dos lugares sagrados e dos tesouros. Eles eram frequentemente retratados em relevos e esculturas nos templos e túmulos, protegendo os deuses e os faraós.
                Símbolo de Realeza e Divindade: Os grifos também serviam como símbolos de realeza e divindade, representando a proteção dos deuses e a autoridade do faraó. Eles eram um lembrete visual do poder e da proteção divina que cercavam os governantes e os lugares sagrados do Egito.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade sobre o grifo egípcio é sua influência e conexão com outras culturas. A imagem do grifo, especialmente como um guardião poderoso, foi adotada e adaptada por várias culturas ao longo do tempo, incluindo a grega, romana e persa. Essas culturas incorporaram a figura do grifo em sua própria mitologia e arte, demonstrando a influência duradoura da iconografia egípcia.

                Além disso, em algumas representações, o grifo egípcio é mostrado com as asas estendidas, em uma postura de ataque ou proteção, o que reforça sua função como guardião e defensor. Essa postura dinâmica não só simboliza poder e prontidão, mas também transmite uma sensação de movimento e vida, destacando a habilidade artística e a simbolismo profundo da arte egípcia.
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