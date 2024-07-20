<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/sekhmet.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Sekhmet
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Sekhmet é uma das deusas mais poderosas e temidas da mitologia egípcia, conhecida como a deusa da guerra, da destruição e da cura. Seu nome significa "a poderosa" ou "aquela que é poderosa". Ela é frequentemente retratada como uma mulher com a cabeça de uma leoa, simbolizando sua ferocidade e força.


            Sekhmet é filha de Rá, o deus do sol. Em alguns mitos, ela nasceu do olho de Rá, enviado para punir a humanidade quando esta se rebelou contra ele. Ela é muitas vezes associada a outras divindades, como Bastet, a deusa do lar e da fertilidade, e Hathor, a deusa da alegria e do amor, refletindo diferentes aspectos de sua natureza.
            <p class="mb-2 text-l">
              Sekhmet é casada com Ptah, o deus criador e patrono dos artesãos, e juntos eles têm um filho, Nefertum, o deus das flores de lótus e da renovação. Nefertum é frequentemente associado à cura e à medicina, refletindo o lado curativo de Sekhmet.


            Sekhmet é famosa por sua participação no mito da destruição da humanidade. Segundo a história, Rá ficou furioso com a humanidade por seu comportamento rebelde e enviou Sekhmet para punir os homens. Sekhmet se transformou em uma deusa implacável e começou a massacrar a humanidade, causando grande destruição. Para impedir a aniquilação total, Rá enganou Sekhmet, fazendo-a beber uma bebida vermelha (frequentemente descrita como cerveja tingida de vermelho para parecer sangue). A deusa ficou embriagada e adormeceu, salvando assim a humanidade da extinção.

            Além de sua natureza destrutiva, Sekhmet também é reverenciada como uma deusa da cura. Ela é associada a médicos e curandeiros, e muitos acreditavam que suas bênçãos poderiam curar doenças e proteger contra pragas.
            </p>
            <p class="mb-2 text-l">
              Uma curiosidade interessante sobre Sekhmet é a existência de uma grande quantidade de estátuas dedicadas a ela no Templo de Karnak, em Luxor. No reinado do faraó Amenhotep III, mais de 700 estátuas de Sekhmet foram erigidas para apaziguar a deusa e ganhar seu favor. Esses esforços mostravam o temor e respeito que os antigos egípcios tinham por ela, reconhecendo tanto seu poder destrutivo quanto sua capacidade de cura.
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
  