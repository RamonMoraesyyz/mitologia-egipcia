<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses/atum.jpg" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Atum
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          Atum é geralmente descrito como um deus auto-gerado que emergiu das águas primordiais de Nun (o caos) no início dos tempos. Ele é frequentemente representado como um homem usando a coroa dupla do Egito, simbolizando sua associação com a realeza e a unificação das duas terras do Egito (Alto e Baixo Egito).
          <p class="mb-2 text-l">
            Atum teve dois filhos principais, Shu (deus do ar) e Tefnut (deusa da umidade), que ele criou ao se masturbar ou ao cuspir, dependendo da versão do mito. Shu e Tefnut, por sua vez, geraram Geb (deus da terra) e Nut (deusa do céu), que completaram a primeira geração de deuses. Através deles, Atum é o ancestral de Osíris, Ísis, Set e Néftis, entre outros.


          Atum é conhecido principalmente por seus feitos de criação:

          Criação do Universo: Atum foi responsável pela criação do universo a partir do caos primordial. Ele criou os primeiros deuses, Shu e Tefnut, estabelecendo a ordem cósmica.

          Proteção e Sustentação: Atum era visto como um deus que sustentava o cosmos e garantida a estabilidade do mundo. Ele era frequentemente invocado para proteger o faraó e o Egito.

          Renovação Diária: Atum também estava associado ao ciclo diário do sol, particularmente ao pôr do sol, quando ele se tornava Atum-Rá e descia ao submundo, Renascendo a cada amanhecer como Khepri, o deus escaravelho, simbolizando o renascimento e a regeneração.
          </p>
          <p class="mb-2 text-l">
            Uma curiosidade interessante sobre Atum é sua conexão com a serpente. Na iconografia egípcia, Atum às vezes é representado como uma serpente ou associado a elas. Este simbolismo está ligado ao conceito de renovação e eternidade, já que as serpentes são vistas como criaturas que se renovam ao trocar de pele. Além disso, no fim dos tempos, Atum era esperado a retornar ao seu estado original de serpente, reabsorvendo o universo e retornando ao caos primordial de Nun.
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
