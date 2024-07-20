<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/isis.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Ísis
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Ísis é uma das deusas mais importantes e reverenciadas do panteão egípcio, conhecida por sua habilidade mágica, sabedoria e seu papel como mãe e protetora. Ela desempenha um papel central em muitos mitos egípcios e sua influência se estendeu além do Egito, sendo adorada também no mundo greco-romano.


            Ísis é filha dos deuses Geb, o deus da terra, e Nut, a deusa do céu. Ela é irmã e esposa de Osíris, e juntos eles formam um dos casais mais importantes da mitologia egípcia. Ísis também é irmã de Néftis e Set.
            <p class="mb-2 text-l">
                Ísis e Osíris tiveram um filho, Hórus, o deus falcão. Após a morte de Osíris pelas mãos de Set, Ísis usou suas habilidades mágicas para ressuscitar temporariamente Osíris e conceber Hórus. Ela então criou Hórus em segredo para protegê-lo de Set e para que ele pudesse vingar a morte de seu pai e reclamar o trono do Egito.


                Ísis é conhecida por vários feitos notáveis na mitologia egípcia:

                Ressurreição de Osíris: Ísis foi fundamental na ressurreição de Osíris. Depois que Set assassinou Osíris e espalhou seus pedaços pelo Egito, Ísis reuniu e reconstituiu o corpo de Osíris, trazendo-o de volta à vida temporariamente para conceber Hórus.

                Proteção de Hórus: Ísis protegeu seu filho Hórus durante sua infância, escondendo-o de Set e usando sua magia para curar e proteger Hórus de diversos perigos.

                Deusa da Magia e Sabedoria: Ísis era considerada uma deusa extremamente poderosa, especialmente conhecida por sua habilidade em magia. Ela era frequentemente invocada em feitiços e rituais de cura e proteção.

                Protetora dos Mortos: Ísis, junto com sua irmã Néftis, era uma protetora dos mortos e frequentemente representada nas tumbas e sarcófagos, ajudando os mortos em sua jornada para o além.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Ísis é a sua popularidade e culto que se estendeu além do Egito, especialmente no mundo greco-romano. Templos dedicados a Ísis foram encontrados em várias partes do Império Romano, incluindo na Grécia e em Roma. Seu culto era conhecido por ser inclusivo, aceitando pessoas de diferentes origens e status sociais, o que contribuiu para sua ampla popularidade.
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
  