<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/mehetweret.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Mehet Weret
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Mehet-Weret é uma divindade primordial que remonta ao Antigo Reino do Egito (cerca de 2686 a.C. - 2181 a.C.). Seu nome significa "Grande das Águas," refletindo sua associação com as águas primordiais do Nun, o caos aquático do qual se acreditava que o mundo emergiu. Ela é geralmente retratada como uma vaca celestial que dá à luz o sol, conectando-a aos ciclos diários de renascimento e criação.

            <p class="mb-2 text-l">
                Mehet-Weret é conhecida por seu papel na criação e na sustentação do cosmos. Segundo a mitologia, ela deu à luz o sol todas as manhãs, permitindo que ele navegasse pelo céu em sua barca solar. Este ato diário de renascimento simboliza a continuidade da vida e a renovação constante do universo. Além disso, Mehet-Weret é associada ao rio Nilo e às suas inundações, que traziam fertilidade e sustento ao Egito, garantindo colheitas abundantes e a prosperidade do reino.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Mehet-Weret é a forma como sua imagem foi incorporada em várias representações artísticas e religiosas. Em muitos textos funerários, como o Livro dos Mortos, ela é descrita como uma vaca celestial que atravessa os céus, trazendo a luz do sol para o mundo. Em alguns mitos, ela também é mencionada como a mãe de Ra, o deus do sol, destacando ainda mais sua importância na cosmologia egípcia. Sua representação como uma vaca celestial também se reflete em outras culturas do antigo Oriente Próximo, onde o simbolismo da vaca está frequentemente ligado à fertilidade e à maternidade divina.
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