<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

<!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/amon.jpg" class="w-full h-full object-cover" />
      </div>
     
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
          <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Amon
        </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          

          <p>Amon, também conhecido como Amun, Ammon ou Amen, é uma divindade proeminente na mitologia egípcia. Sua importância aumentou significativamente durante o Novo Império (c. 1550–1070 a.C.), quando foi reverenciado como o rei dos deuses e patrono dos faraós.


          Amon originalmente era um deus local de Tebas, e seu nome significa "O Oculto" ou "O Invisível". Ele foi associado ao ar e ao vento, simbolizando sua natureza intangível e onipresente. Amon começou como uma divindade menor, mas sua influência cresceu à medida que Tebas se tornou uma cidade poderosa.</p>

          <p>Amon foi casado com a deusa Mut, e juntos formavam uma tríade divina com seu filho Khonsu, o deus da lua. Essa tríade foi particularmente venerada em Tebas, onde o Templo de Karnak foi dedicado a eles.


          Amon desempenhou um papel crucial na unificação do Egito e na consolidação do poder dos faraós. Durante o Novo Império, ele foi identificado com o deus-sol Rá, tornando-se Amon-Rá, uma combinação que enfatizava sua supremacia e onipotência. Como Amon-Rá, ele era considerado o criador do universo e o mantenedor da ordem divina (Maat).

          Os faraós frequentemente se declaravam "Filhos de Amon" e acreditavam que sua legitimidade e poder provinham do deus. O culto a Amon levou à construção de enormes templos, incluindo o Templo de Karnak, um dos maiores complexos religiosos do mundo antigo.</p>

        

          <p>Uma curiosidade interessante sobre Amon é a forma como seu culto se expandiu além do Egito. Amon foi adorado na Núbia (sul do Egito), e seu culto chegou até mesmo à Grécia e Roma. Na Grécia, ele foi identificado com Zeus, o rei dos deuses, e em Roma, com Júpiter. O oráculo de Amon em Siwa, no deserto ocidental do Egito, era famoso por suas profecias e foi visitado por figuras históricas como Alexandre, o Grande.</p>
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
