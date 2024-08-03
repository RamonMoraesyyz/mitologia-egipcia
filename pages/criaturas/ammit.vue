<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/ammit.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Ammit
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Ammit, também conhecida como "Devoradora de Almas," é uma figura temida na mitologia egípcia. Ela é uma criatura híbrida, com a cabeça de um crocodilo, o tronco de um leão ou leopardo, e a parte traseira de um hipopótamo. Esses três animais eram considerados os mais perigosos para os egípcios, simbolizando a ameaça máxima para os mortos no além.

            Ammit não é uma deusa, mas uma entidade demoníaca associada ao julgamento das almas no Duat, o submundo egípcio. Ela é uma das figuras centrais no processo de pesagem do coração, um ritual descrito no "Livro dos Mortos".

            <p class="mb-2 text-l">
                Ammit desempenha um papel crucial no julgamento das almas dos mortos:

                Pesagem do Coração: Após a morte, o coração do falecido era pesado contra a pena de Maat, a deusa da verdade e justiça, por Anúbis, o deus da mumificação e guardião dos mortos. Se o coração fosse mais leve ou igual à pena, a alma era considerada justa e permitida a entrada no Aaru, o paraíso egípcio. No entanto, se o coração fosse mais pesado devido aos pecados cometidos em vida, Ammit devorava o coração, condenando a alma à inexistência e ao esquecimento eterno.
                Guardião da Ordem: Ao devorar os corações impuros, Ammit assegurava que apenas as almas dignas alcançassem a vida eterna, mantendo a ordem e a justiça no universo.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Ammit é sua representação na iconografia egípcia. Apesar de sua natureza assustadora, Ammit não era vista como maligna. Em vez disso, ela era uma figura de justiça, servindo como um instrumento do equilíbrio cósmico. Seu papel era essencial para a manutenção da ordem no além, reforçando a importância da moralidade e da verdade na vida dos antigos egípcios.

                Além disso, o conceito de Ammit e o ritual da pesagem do coração destacam a sofisticação da visão egípcia sobre a vida após a morte, onde o comportamento moral durante a vida terrena determinava o destino eterno da alma. Ammit, portanto, não apenas simboliza o medo da condenação, mas também a esperança de justiça e retribuição divina.
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
  