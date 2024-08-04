<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/ouroboros.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Ouroboros
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Ouroboros é uma criatura mítica que aparece em várias culturas antigas, incluindo a mitologia egípcia, onde é um símbolo poderoso e multifacetado. É tradicionalmente representado como uma serpente ou um dragão devorando a própria cauda, formando um círculo contínuo.


            A origem do Ouroboros remonta ao Egito Antigo, onde ele é associado ao deus Ra, o deus do sol. Acredita-se que o símbolo tenha sido utilizado pela primeira vez por volta de 1600 a.C. no Egito, e posteriormente adotado por outras culturas, incluindo os gregos e os nórdicos. No Egito, o Ouroboros é frequentemente relacionado ao ciclo eterno da vida, morte e renascimento, simbolizando a natureza cíclica do universo.


            <p class="mb-2 text-l">
                Ouroboros não é conhecido por feitos específicos como criaturas ou deuses em narrativas mitológicas tradicionais, mas seu simbolismo é profundo e abrangente. Ele representa a ideia de eternidade e o ciclo infinito de renovação. No contexto egípcio, ele também simboliza a proteção e a continuidade, um conceito vital para a crença egípcia na vida após a morte. Em algumas representações, Ouroboros circunda o mundo, protegendo e mantendo a ordem no cosmos.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Ouroboros é sua influência duradoura em várias culturas e filosofias ao longo dos séculos. Além de sua origem egípcia, ele aparece em textos gnósticos, alquímicos e esotéricos. Na alquimia, por exemplo, Ouroboros representa a unidade dos opostos, como a vida e a morte, e a natureza cíclica da transformação. Esse símbolo também foi adotado por Carl Jung, o famoso psicólogo, como um arquétipo do inconsciente coletivo, representando a totalidade psíquica.
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