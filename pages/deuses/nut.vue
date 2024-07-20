<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/nut.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Nut
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Nut é a deusa do céu na mitologia egípcia, uma figura central no panteão egípcio. Ela é frequentemente retratada como uma mulher arqueada sobre a Terra, simbolizando o céu noturno cheio de estrelas.


            Nut é filha de Shu, o deus do ar, e Tefnut, a deusa da umidade. Ela é irmã e esposa de Geb, o deus da Terra. Juntos, eles formam uma das mais importantes parelhas divinas da mitologia egípcia.
            <p class="mb-2 text-l">
                Nut e Geb são os pais de alguns dos deuses mais importantes do panteão egípcio:

                Osíris: deus da ressurreição e governante do submundo.
                Ísis: deusa da magia e da maternidade.
                Set: deus do caos e da guerra.
                Nephthys: deusa da proteção e dos rituais funerários.
                Hórus (em algumas tradições): frequentemente considerado filho de Osíris e Ísis, mas também às vezes associado a Nut.

                Um dos mitos mais notáveis sobre Nut é sua luta contra a maldição de Rá, o deus do sol. Rá proibiu Nut de dar à luz em qualquer dia do ano, temendo que seus filhos pudessem ameaçar seu trono. Nut, desesperada para ter seus filhos, buscou ajuda de Thoth, o deus da sabedoria. Thoth desafiou a Lua para um jogo de senet (um jogo de tabuleiro) e ganhou luz suficiente para criar cinco novos dias, adicionando-os ao calendário egípcio. Esses cinco dias, conhecidos como os "dias epagomenais," permitiram que Nut desse à luz seus filhos.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade fascinante sobre Nut é sua representação no céu noturno. Em muitos templos e tumbas, ela é mostrada com o corpo coberto de estrelas, arqueando-se sobre Geb, com a cabeça a oeste e os pés a leste. Essa imagem simboliza a abóbada celeste e a jornada diária do sol. Durante o dia, o sol viaja por seu corpo, e à noite, ele renasce do ventre de Nut, simbolizando o ciclo contínuo de morte e renascimento.

                Nut, com sua imensa presença no céu e sua associação com o ciclo diário do sol, é uma deusa que incorpora a ordem cósmica e a proteção, desempenhando um papel crucial na mitologia e religião egípcia.
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
  