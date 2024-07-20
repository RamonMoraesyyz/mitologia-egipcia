<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
  <!-- Conteúdo esquerdo (imagem) -->
        <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
          <img src="/public/deuses/seth.jpg" class="w-full h-full object-cover" />
        </div>
       
        <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
            <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
              Set
          </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            
  
            <p>Set (também conhecido como Seth, Setesh, Sutekh ou Setekh) é uma das divindades mais complexas e controversas da mitologia egípcia. Ele é o deus do caos, da tempestade, da desordem, da violência e da guerra. No entanto, ele também é visto como um protetor necessário contra as forças do caos que ameaçam a ordem do mundo.


                Set é filho de Geb, o deus da Terra, e Nut, a deusa do Céu. Ele é irmão de Osíris, Ísis e Nephthys. Set é frequentemente representado com a cabeça de um animal que não pode ser identificado, conhecido como o "animal de Set", que possui orelhas quadradas e focinho curvo, refletindo sua natureza enigmática e única.</p>
  
            <p>Set teve vários filhos, sendo um dos mais conhecidos Anúbis, o deus dos funerais e da mumificação, que ele teve com Nephthys. Em algumas tradições, no entanto, Anúbis é descrito como filho de Osíris e Nephthys, tendo sido criado por Set após a morte de Osíris.


                Set é mais famoso pelo mito do assassinato de seu irmão Osíris. Enciumado e ambicioso, Set conspirou para matar Osíris e usurpar seu trono. Ele enganou Osíris para entrar em um caixão que foi selado e jogado no Nilo, resultando na morte de Osíris. Ísis, esposa de Osíris, recuperou o corpo do marido, mas Set o desmembrou e espalhou suas partes pelo Egito. Ísis, com a ajuda de Nephthys, Thoth e Anúbis, reuniu os pedaços e ressuscitou Osíris, que se tornou o governante do submundo.

                O mito de Set também inclui sua luta contínua com Hórus, o filho de Osíris e Ísis, que buscou vingar a morte de seu pai e reivindicar o trono do Egito. As batalhas entre Set e Hórus representam o conflito entre a ordem e o caos, com Hórus eventualmente prevalecendo.

                Embora Set seja frequentemente retratado como um vilão, ele também desempenha um papel vital na proteção do barco solar de Rá durante sua jornada noturna pelo submundo. Set defende o barco contra a serpente Apófis (Apep), uma personificação do caos absoluto que tenta devorar o sol.</p>
  
          
  
            <p>Uma curiosidade interessante sobre Set é sua adoração em diferentes períodos da história egípcia. Durante o período inicial, Set era visto de maneira mais neutra e até mesmo benéfica em algumas áreas, sendo adorado como uma deidade protetora. No entanto, após a unificação do Egito e as dinastias subsequentes, sua imagem tornou-se mais negativa, especialmente após ser associado com governantes estrangeiros como os hicsos. No Novo Reino, Set ainda era adorado em alguns contextos, mas sua associação com o caos e a desordem se tornou predominante.</p>
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
  :root {
    --header-height: 64px; /* Ajuste esse valor conforme necessário */
  }
  
  .bg-brown-dark {
    background-color: #211512;
  }
  
  
  .fixed-image {
    position: relative;
  }
  
  .text-container {
    margin-left: auto;
  }
  </style>
  