<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
  <!-- Conteúdo esquerdo (imagem) -->
        <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
          <img src="/public/deuses/bastet.jpg" class="w-full h-full object-cover" />
        </div>
       
        <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
            <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
              Bastet
          </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            
  
            <p>Bastet, também conhecida como Bast, é uma das deusas mais veneradas do panteão egípcio. Originalmente uma deusa leoa guerreira do sol, sua imagem e atributos mudaram com o tempo, tornando-se associada à fertilidade, música, dança, alegria, amor, e proteção dos lares.


                Bastet era filha de Rá, o deus do sol, e foi uma deusa central na religião do Antigo Egito. Seu culto principal estava localizado em Bubastis (moderna Tell Basta), no Delta do Nilo.</p>
  
          
  
            <p>Bastet era conhecida por sua dualidade: por um lado, ela era uma protetora feroz, especialmente dos faraós e do Egito, lutando contra o caos e as forças malignas. Por outro lado, ela também era uma deusa benigna e maternal, associada ao lar, à fertilidade, e à cura. A transformação de seu caráter de uma deusa leoa agressiva para uma deusa gato mais dócil reflete a mudança cultural e religiosa ao longo do tempo.

                Uma curiosidade interessante sobre Bastet é sua associação com gatos. Os egípcios reverenciavam os gatos domésticos, acreditando que eles possuíam uma essência divina de Bastet. Matar um gato, mesmo acidentalmente, era considerado um crime grave. Além disso, a cidade de Bubastis, onde seu templo principal estava localizado, era famosa por realizar grandes festivais em sua honra, que incluíam procissões, música, dança e sacrifícios rituais. Durante esses festivais, milhares de gatos mumificados eram oferecidos à deusa, evidenciando a profunda reverência que os egípcios tinham por Bastet e pelos felinos.

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
  :root {
    --header-height: 64px; /* Ajuste esse valor conforme necessário */
  }
  
  .bg-brown-dark {
    background-color: #211512;
  }
  
  
  .fixed-image {
    position: relative;
  }
  
  .text-container {
    margin-left: auto;
  }
  </style>
  