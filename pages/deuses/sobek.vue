<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/sobek.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Sobek
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Sobek é um deus da mitologia egípcia associado à água, fertilidade, força e proteção. Ele é frequentemente retratado como um homem com a cabeça de um crocodilo ou simplesmente como um crocodilo, refletindo sua conexão com o rio Nilo e os crocodilos que habitavam suas margens.


            Sobek é filho da deusa Neith, uma antiga deusa da guerra e da caça, associada também à sabedoria e à tecelagem. Neith é uma das divindades mais antigas do panteão egípcio, e Sobek herda dela aspectos de poder e proteção.
            <p class="mb-2 text-l">
                Sobek não é amplamente conhecido por ter filhos divinos. Sua principal função é ser um deus protetor e poderoso, associado à fertilidade e ao poder do Nilo, e não tanto à prole divina. No entanto, ele é frequentemente vinculado à linhagem de outros deuses através de mitos e sincretismos, mas não há menção direta de filhos específicos.


                Sobek é reverenciado como uma deidade protetora e poderosa. Ele é conhecido por sua associação com o rio Nilo, cuja inundação anual era crucial para a fertilidade das terras ao seu redor. Como tal, ele era adorado como um deus que trazia prosperidade, fertilidade e força ao Egito.

                Sobek também desempenhava um papel importante na proteção do faraó e do reino. Sua natureza feroz e a força do crocodilo eram vistas como qualidades protetoras, e ele era invocado para proteger o Egito de inimigos e perigos. Em muitos templos, especialmente no Faium, Sobek era adorado com rituais e oferendas, e crocodilos vivos eram mantidos em lagos sagrados como representações vivas do deus.

            
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Sobek é o seu culto em Kom Ombo, onde havia um templo dedicado a ele e ao deus falcão Hórus. Esse templo, conhecido como o Templo de Kom Ombo, é único por ser dedicado a duas divindades diferentes, com duas entradas, duas salas hipostilas e dois santuários, um para Sobek e outro para Hórus. O culto dual demonstra a importância de Sobek e a complexidade das crenças religiosas egípcias.

                Sobek também era visto como um deus criador em algumas tradições, acreditando-se que ele ajudou a formar o mundo e a separar as águas do caos inicial. Isso reforça sua ligação com a criação e a fertilidade, atributos que complementam sua natureza protetora.
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
  