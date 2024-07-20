<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/faraos/khufu.jpg" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Khufu
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          O faraó Khufu, também conhecido como Quéops, foi o segundo faraó da Quarta Dinastia do Egito, governando por volta de 2589 a.C. a 2566 a.C. Ele é mais famoso por construir a Grande Pirâmide de Gizé, uma das Sete Maravilhas do Mundo Antigo.


        Khufu era filho do faraó Sneferu e da rainha Hetepheres I. Ele nasceu em uma família real poderosa e, com a morte de seu pai, assumiu o trono do Egito. A linhagem real de Khufu e sua conexão com Sneferu ajudaram a consolidar seu poder e influência durante seu reinado.
          <p class="mb-2 text-l">
            O reinado de Khufu ocorreu aproximadamente entre 2589 a.C. e 2566 a.C., durando cerca de 23 anos. Este período é parte do Reino Antigo do Egito, uma era marcada por grandes avanços em arquitetura, arte e administração.


          Khufu é mais conhecido pela construção da Grande Pirâmide de Gizé, a maior das pirâmides construídas no planalto de Gizé. Esta pirâmide, originalmente com cerca de 146,6 metros de altura, foi a estrutura mais alta feita pelo homem por mais de 3.800 anos. A construção da pirâmide envolveu uma engenharia avançada e uma organização de mão-de-obra impressionante, demonstrando o poder e os recursos disponíveis durante o reinado de Khufu.

        Além da Grande Pirâmide, Khufu também é creditado com a construção de várias outras estruturas menores e templos. Seu reinado foi marcado por uma centralização do poder e uma administração eficiente, que ajudou a manter a estabilidade e a prosperidade do Egito.
          </p>
          <p class="mb-2 text-l">
            Uma curiosidade interessante sobre Khufu é sua representação na história e na cultura popular. Embora seja lembrado principalmente pela construção da Grande Pirâmide, ele também foi descrito de maneira ambivalente em textos antigos. Por exemplo, o "Papiro Westcar", um texto literário do Segundo Período Intermediário do Egito, retrata Khufu como um governante cruel e impiedoso, em contraste com seu pai, Sneferu, que era lembrado como um rei benevolente. Essa dualidade na percepção de Khufu pode refletir a complexidade de seu reinado e a forma como seu legado foi interpretado ao longo dos séculos.
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
