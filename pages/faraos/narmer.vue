<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/faraos/narmer.jpg" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Narmer
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          Narmer, também conhecido como Menés, é amplamente considerado um dos primeiros faraós do Egito antigo e um unificador das terras do Alto e Baixo Egito. Ele viveu durante o período protodinástico, por volta de 3150 a.C., e é frequentemente creditado com a fundação da Primeira Dinastia do Egito.


        Narmer é frequentemente identificado com o rei Menés, mencionado por historiadores antigos como o primeiro unificador do Egito. Embora haja debate entre os egiptólogos sobre a identidade exata de Narmer e Menés, muitos acreditam que eles são a mesma pessoa ou sucessores imediatos.
          <p class="mb-2 text-l">
            O reinado de Narmer ocorreu aproximadamente no final do período protodinástico, que antecedeu o início do período dinástico do Egito. Estima-se que ele tenha governado por volta de 3150 a.C., marcando o início da Primeira Dinastia.


          Narmer é mais famoso por ter unificado o Alto e o Baixo Egito em um único reino, um feito que é simbolizado pela famosa Paleta de Narmer. Esta paleta de pedra, descoberta em Hieracômpolis, mostra Narmer usando as coroas do Alto e do Baixo Egito, indicando seu domínio sobre ambos os territórios. Ele é frequentemente representado subjugando inimigos e estabelecendo a ordem, o que simboliza a consolidação do poder real e a centralização do governo egípcio.

          Além da unificação, Narmer estabeleceu a cidade de Mênfis como a capital administrativa do Egito, uma localização estratégica entre o Alto e o Baixo Egito. Essa mudança ajudou a consolidar a autoridade do faraó e a administrar de forma mais eficiente o vasto território egípcio.
          </p>
          <p class="mb-2 text-l">
            Uma curiosidade interessante sobre Narmer é a importância de sua esposa, Neithhotep. Ela é uma das primeiras rainhas conhecidas do Egito e desempenhou um papel significativo na dinastia. Neithhotep é frequentemente mencionada em inscrições e tumbas, indicando que ela possuía uma grande influência política. O casamento entre Narmer e Neithhotep pode ter sido uma estratégia política para fortalecer ainda mais a unificação do Egito.
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
