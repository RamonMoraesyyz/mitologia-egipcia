<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/khepri.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Khepri
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Khepri é uma divindade antiga do panteão egípcio, cuja adoração remonta ao período do Antigo Reino (cerca de 2686 a.C. - 2181 a.C.). O nome Khepri deriva da palavra egípcia "kheper," que significa "vir à existência" ou "tornar-se." Este deus está associado ao escaravelho, um inseto que rola bolas de esterco, simbolizando o movimento do sol no céu e o ciclo contínuo de renascimento.

            <p class="mb-2 text-l">
                Khepri é principalmente conhecido por seu papel na criação e no ciclo diário do sol. Ele era acreditado como aquele que empurrava o sol através do céu, desde o nascimento no leste até o ocaso no oeste, simbolizando o renascimento diário do sol. Esse processo de renovação diária também está ligado à regeneração da vida e à continuidade da criação. Khepri, como aspecto de Ra, ajuda a manter a ordem e a harmonia no cosmos ao assegurar que o sol nasça a cada dia.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Khepri é que o escaravelho, seu símbolo, tinha uma enorme importância na vida cotidiana e religiosa dos antigos egípcios. Amuletos em forma de escaravelho eram comumente usados como símbolos de proteção e renovação. Esses amuletos eram frequentemente colocados sobre o coração dos mortos durante o processo de mumificação, acreditando-se que eles ajudariam na renovação da alma na vida após a morte. A reverência ao escaravelho e sua associação com Khepri também refletem a observação dos antigos egípcios sobre o ciclo natural de vida, morte e renascimento.
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