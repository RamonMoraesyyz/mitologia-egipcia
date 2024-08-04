<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/tjesuheru.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Tjesu Heru
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Tsesu Heru é originária da antiga religião egípcia, onde Hórus era um dos deuses mais importantes. Hórus é o deus do céu, da guerra e da caça, e é frequentemente representado como um falcão ou um homem com cabeça de falcão. Tsesu Heru, como uma extensão de Hórus, simboliza a precisão, a força e a vigilância.

            <p class="mb-2 text-l">
                Tsesu Heru é conhecido por seus feitos heroicos, especialmente na batalha contra as forças do caos. Ele é frequentemente descrito como uma entidade protetora que acompanha os faraós em batalhas, garantindo a vitória e a proteção do reino egípcio. A precisão de Tsesu Heru, simbolizada pela flecha, representa a capacidade de Hórus de atingir seus inimigos com precisão infalível.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Tsesu Heru é que ele também está associado ao olho de Hórus, um poderoso amuleto de proteção e cura na mitologia egípcia. O olho de Hórus, também conhecido como "Udjat," é um símbolo de poder real e proteção divina. A conexão de Tsesu Heru com este símbolo reforça sua associação com a proteção e a vigilância constante.
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