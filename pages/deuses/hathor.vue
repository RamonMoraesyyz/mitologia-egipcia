<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/hathor.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Hathor
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Hathor é uma das deusas mais importantes e multifacetadas do panteão egípcio. Ela era adorada como a deusa do amor, beleza, música, dança, maternidade, e alegria. Hathor também tinha um papel importante como deusa do céu e protetora dos mortos.


            Hathor era frequentemente descrita como a filha de Rá, o deus do sol, embora em algumas mitologias ela fosse também considerada a mãe ou a esposa de Hórus, o deus falcão. Seu nome, "Hathor", significa "Casa de Hórus", refletindo seu papel maternal e protetor.
            <p class="mb-2 text-l">
                Hathor era mãe de vários filhos, mas o mais famoso entre eles é Ihy, o deus da música e da alegria, frequentemente representado como um menino tocando um sistro (um instrumento musical associado a Hathor). Ihy personificava o êxtase e a exuberância da música e da dança, refletindo os aspectos alegres e festivos do culto a Hathor.


                Hathor desempenhou muitos papéis significativos na mitologia egípcia:

                Protetora dos Mortos: Ela era vista como uma guia benevolente para os mortos, ajudando-os na transição para a vida após a morte e garantindo que fossem bem recebidos no além.

                Deusa do Amor e da Alegria: Hathor era invocada em celebrações, casamentos e festivais. Sua presença era sinônimo de alegria, amor e beleza.

                Poder Destrutivo: Em algumas mitologias, Hathor também tinha um aspecto destrutivo. Como a "Olho de Rá", ela se transformava em Sekhmet, a deusa leoa da vingança, para punir a humanidade. Contudo, após sua missão de destruição, ela voltou à sua forma benevolente como Hathor.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade fascinante sobre Hathor é a sua conexão com a vaca sagrada. Hathor frequentemente era retratada como uma mulher com orelhas de vaca ou com um toucado que incluía chifres de vaca segurando o disco solar. A vaca era um símbolo de maternidade e nutrição, refletindo os aspectos cuidadosos e protetores de Hathor.

                Além disso, Hathor tinha um papel importante na economia do Antigo Egito. Ela era a patrona dos mineiros, especialmente daqueles que trabalhavam nas minas de turquesa e cobre no Sinai. Os mineiros frequentemente dedicavam suas descobertas a Hathor, acreditando que ela os protegia e lhes trazia sorte.
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
  