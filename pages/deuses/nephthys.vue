<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/nephthys.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Nephthys
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Nephthys, conhecida na mitologia egípcia como "Nebet-Het," é uma deusa associada à noite, proteção dos mortos e aos rituais funerários. Ela é filha de Geb (deus da Terra) e Nut (deusa do Céu), e irmã de Ísis, Osíris e Set.

            Nephthys é frequentemente retratada como uma mulher com um hieróglifo representando uma casa ou um cesto sobre sua cabeça. Ela é uma deusa protetora e desempenha um papel crucial nos mitos sobre a morte e a ressurreição de Osíris. Embora esteja casada com Set, o deus do caos e da destruição, a relação deles é muitas vezes descrita como tensa.
            <p class="mb-2 text-l">
                Nephthys é mãe de Anúbis, o deus dos mortos e da mumificação. Anúbis nasceu de sua união com Osíris, não com Set, e desempenha um papel vital na proteção das almas dos mortos e na condução das cerimônias funerárias.


                Nephthys desempenhou um papel importante no mito de Osíris. Quando Osíris foi assassinado e desmembrado por Set, Nephthys ajudou sua irmã Ísis a encontrar e reunir os pedaços do corpo de Osíris. Juntas, elas realizaram rituais que permitiram a ressurreição temporária de Osíris, o que permitiu que ele se tornasse o rei do submundo.

                Nephthys é também associada à proteção dos mortos e é frequentemente representada nas tumbas, onde ela aparece ao lado de Ísis, proporcionando proteção aos falecidos. Nos textos funerários, Nephthys e Ísis são vistas como as guardiãs do trono de Osíris, ajudando a garantir a passagem segura dos mortos para a vida após a morte.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Nephthys é que, apesar de sua associação com a morte e o submundo, ela não era vista como uma deusa malévola. Pelo contrário, Nephthys era venerada por suas qualidades de proteção e cuidado, especialmente nos contextos funerários. Sua dualidade de estar casada com Set, mas ainda assim ser uma aliada de Ísis e Osíris, reflete a complexidade das relações e mitologias egípcias.
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
  