<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/serpopardo.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Serpopardo
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            O Serpopardo é uma criatura mítica da antiga mitologia egípcia, frequentemente retratada em artefatos e monumentos. Esta criatura é uma fusão entre uma serpente e um leopardo, combinando a agilidade e ferocidade de ambos os animais.

           
            A origem do Serpopardo remonta ao período pré-dinástico do Egito, por volta de 3500 a.C. Ele aparece em várias representações artísticas, como a Paleta de Narmer, um artefato histórico que marca a unificação do Alto e Baixo Egito. O Serpopardo é geralmente mostrado com um corpo longo e flexível semelhante a uma serpente, mas com as patas e a cabeça de um leopardo.

            <p class="mb-2 text-l">
                Embora não haja muitos relatos detalhados sobre feitos específicos do Serpopardo na mitologia egípcia, ele é frequentemente associado a conceitos de caos e desordem. Sua imagem é utilizada para representar forças selvagens e indomáveis da natureza, que os faraós e deuses precisam subjugar para manter a ordem e a harmonia no reino. Na Paleta de Narmer, por exemplo, os Serpopardos são retratados com seus pescoços entrelaçados, simbolizando a união e o controle do caos durante a unificação do Egito.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre o Serpopardo é sua presença em outras culturas além do Egito. Artefatos encontrados na Mesopotâmia também apresentam criaturas semelhantes ao Serpopardo, sugerindo que essa criatura mitológica possa ter sido parte de uma tradição iconográfica compartilhada entre diferentes civilizações antigas. Além disso, a combinação de características de animais diferentes em uma única criatura é uma prática comum em muitas mitologias, simbolizando a fusão de forças naturais diversas.
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