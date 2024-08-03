<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/bennu.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Bennu
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Bennu é uma ave mitológica da antiga mitologia egípcia, frequentemente associada à criação e ao renascimento. Acredita-se que Bennu tenha inspirado o mito grego da fênix. Na mitologia egípcia, Bennu é visto como um símbolo do ciclo de morte e renascimento, e está intimamente ligado aos deuses Rá e Osíris.

            A Bennu é frequentemente descrita como uma garça-real ou uma ave grande e majestosa, às vezes com penas vermelhas e douradas, que representavam o sol. Bennu está associado ao rio Nilo e à fertilidade que suas enchentes traziam, sendo também um símbolo de regeneração.

            <p class="mb-2 text-l">
                Na mitologia egípcia, Bennu desempenha um papel crucial na criação e na continuidade da vida:

                Símbolo da Criação: Bennu é considerado um dos primeiros seres a emergir da escuridão e do caos das águas primordiais de Nun. Em algumas versões, Bennu pousa em uma pedra benben, um monte primordial, e emite um grito que marca o início do tempo.
                Ligação com Osíris e Rá: Bennu é frequentemente associado a Osíris, o deus da ressurreição, e a Rá, o deus do sol. Acredita-se que Bennu represente a alma de Rá, e que seu ciclo de morte e renascimento esteja ligado ao ciclo diário do sol e ao ciclo anual do Nilo.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Bennu é a sua conexão com o calendário egípcio. O surgimento de Bennu era associado ao início do ano egípcio, que coincidia com a aparição da estrela Sirius no céu e com as enchentes anuais do Nilo. Essas enchentes eram vitais para a agricultura e a sobrevivência do Egito, e Bennu, portanto, simbolizava a renovação e a continuidade da vida.
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
  