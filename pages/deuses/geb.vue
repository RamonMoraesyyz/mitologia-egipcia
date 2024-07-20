<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/geb.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Geb
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Geb, na mitologia egípcia, é o deus da terra, frequentemente representado deitado sob Nut, a deusa do céu. Sua origem e atributos são fundamentais para a cosmologia egípcia, simbolizando a terra fértil e as forças naturais que sustentam a vida.


            Geb é filho de Shu, o deus do ar, e Tefnut, a deusa da umidade. Ele é um dos membros da Enéade de Heliópolis, um grupo de nove deuses que foram cruciais na criação do mundo. Seus irmãos são Nut, a deusa do céu, e juntos, eles são os pais dos deuses Osíris, Ísis, Set, Néftis e, em algumas versões, Hórus, o Velho.
            <p class="mb-2 text-l">
                Geb é o pai de:

                Osíris: Deus da ressurreição e rei dos mortos.
                Ísis: Deusa da magia e mãe de Hórus.
                Set: Deus do caos e da guerra.
                Néftis: Deusa da proteção e dos mortos.
                Hórus, o Velho (em algumas versões): Deus do céu e protetor dos faraós.
                
                Geb tem um papel importante na mitologia como o governante da terra e o juiz das disputas entre deuses. Um de seus feitos notáveis é a participação no julgamento de Osíris, onde ele lamentou a morte do filho e ajudou na restauração da ordem. Além disso, Geb foi associado ao trono do Egito, sendo visto como aquele que passa a realeza para os faraós, consolidando a ligação divina dos reis com o panteão egípcio.


            
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Geb é que ele era associado ao riso e à fertilidade da terra. Diz-se que seus risos faziam a terra tremer, o que era uma maneira dos antigos egípcios explicarem os terremotos. A representação de Geb muitas vezes inclui símbolos de vegetação e animais, refletindo seu domínio sobre a terra fértil e a vida que dela surge.
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
  
