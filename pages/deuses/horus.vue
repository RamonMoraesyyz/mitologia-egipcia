<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/horus.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hórus
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Hórus é filho de Osíris, o deus dos mortos, e Ísis, a deusa da magia e da maternidade. Sua origem está profundamente ligada ao mito de Osíris. Após Osíris ser assassinado por seu irmão Set, Ísis ressuscitou Osíris temporariamente para conceber Hórus. Assim, Hórus nasceu com a missão de vingar a morte de seu pai e restaurar a ordem no Egito.
            <p class="mb-2 text-l">
                Embora Hórus seja principalmente conhecido como filho de Osíris e Ísis, ele também é creditado com descendência. Em algumas tradições, Hórus teve quatro filhos chamados Imsety, Hapi, Duamutef e Qebehsenuef, conhecidos como os Filhos de Hórus. Eles desempenhavam um papel crucial na proteção dos órgãos internos dos mortos durante o processo de mumificação.


                Hórus é famoso por sua luta contra seu tio Set, o deus do caos e da desordem. Esta batalha é um dos mitos centrais da mitologia egípcia:

                Vingança de Osíris: Hórus enfrentou Set em uma série de combates épicos para vingar a morte de seu pai e reivindicar o trono do Egito. Em algumas versões do mito, Hórus perdeu um olho durante a luta, que foi restaurado por Toth, o deus da sabedoria. Este olho, conhecido como o "Olho de Hórus" ou "Udjat", tornou-se um poderoso símbolo de proteção e cura.

                Unificação do Egito: Após derrotar Set, Hórus unificou o Alto e o Baixo Egito, tornando-se o faraó legítimo. A figura de Hórus como rei simbolizava a continuidade e a legitimidade do poder faraônico.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Hórus é o símbolo do "Olho de Hórus", que se tornou um amuleto muito popular no Antigo Egito e ainda hoje é usado como símbolo de proteção. O olho direito de Hórus representava o sol e o olho esquerdo representava a lua. A luta com Set foi tão feroz que Hórus perdeu o olho esquerdo, que simbolicamente representava a lua, explicando assim as fases lunares na mitologia egípcia.

                Hórus, como deus do céu, também era associado aos faraós, sendo considerado a encarnação divina do poder real. Cada faraó era visto como a manifestação terrena de Hórus, reforçando a autoridade e a legitimidade do seu reinado.
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
  