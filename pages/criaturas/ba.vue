<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/ba.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Ba
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Na mitologia egípcia, o Ba é um dos componentes da alma humana, distinto do corpo físico. O conceito de Ba é complexo e profundo, refletindo a crença dos antigos egípcios na natureza multifacetada da alma e da vida após a morte. O Ba é frequentemente representado como um pássaro com cabeça humana, simbolizando sua capacidade de movimento entre os mundos dos vivos e dos mortos.

            Acredita-se que o Ba, junto com outros aspectos da alma como o Ka (força vital) e o Akh (espírito glorificado), seja essencial para a existência eterna no além. Após a morte, o Ba é livre para deixar o corpo e viajar, mas precisa retornar ao corpo ou à tumba todas as noites para se regenerar.

            <p class="mb-2 text-l">
                O Ba desempenha um papel crucial nas crenças funerárias e no conceito de vida após a morte:

                Interação com o Mundo dos Vivos: Após a morte, o Ba mantém a capacidade de visitar o mundo dos vivos. Ele pode mover-se livremente, visitar os entes queridos, participar de rituais fúnebres, e até influenciar eventos no mundo dos vivos. Essa característica fazia do Ba um intermediário importante entre os mortos e os vivos.
                Retorno ao Corpo: À noite, o Ba retorna ao corpo ou à tumba para se regenerar. Este ciclo diário de partida e retorno simboliza a continuidade da vida e a renovação eterna, um conceito central na religião egípcia.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre o Ba é a maneira como ele é retratado em artefatos funerários e textos sagrados. Os antigos egípcios frequentemente colocavam estátuas ou imagens do Ba em tumbas, representando-o como um pássaro com cabeça humana. Essas imagens serviam para garantir que o Ba tivesse um lugar para retornar e se regenerar, assegurando a continuidade da existência do falecido no além.

                Além disso, a ideia do Ba influenciou profundamente os rituais funerários egípcios. Muitos amuletos, encantamentos e rituais foram desenvolvidos para proteger o Ba e garantir seu retorno seguro ao corpo. Um exemplo famoso é o "Livro dos Mortos", que contém feitiços e orientações para ajudar a alma a navegar pelo além e alcançar a vida eterna.
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