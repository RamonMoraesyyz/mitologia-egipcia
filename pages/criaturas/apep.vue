<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/apep.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Apep
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Apep, também conhecido como Apophis, é uma das figuras mais temidas da mitologia egípcia. Ele é a personificação do caos e da destruição, frequentemente retratado como uma serpente gigante ou dragão. Apep é o inimigo jurado do deus solar Rá, representando as forças do mal que ameaçam a ordem cósmica.

            Apep surge das águas primordiais do caos e tenta incessantemente destruir Rá e impedir o ciclo diário do sol. Ele é associado à escuridão, ao caos e às forças destrutivas que ameaçam o equilíbrio do universo.

            <p class="mb-2 text-l">
                Apep desempenha um papel central na cosmologia egípcia, sendo o principal antagonista das forças da ordem e da luz:

                Batalha Diária com Rá: Cada noite, enquanto Rá viaja pelo Duat (o submundo) em sua barca solar, Apep tenta devorá-lo e impedir que o sol nasça novamente. Esta batalha cósmica simboliza a luta eterna entre ordem e caos. Os deuses, especialmente Set, frequentemente ajudam Rá a derrotar Apep e assegurar que o sol nasça novamente.
                Eclipses e Tempestades: Apep é frequentemente responsabilizado por eventos naturais destrutivos, como eclipses solares e tempestades. Quando ocorriam eclipses, acreditava-se que Apep estava ganhando a batalha contra Rá, causando grande medo entre os egípcios.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Apep é a existência de rituais específicos para proteger o Egito contra ele. Os sacerdotes realizavam rituais de banimento e recitavam encantamentos para enfraquecer Apep e garantir a vitória de Rá. Um desses textos sagrados é o "Livro de Apep", também conhecido como "Livro de Apophis", que contém feitiços e instruções para combater o deus-serpente.

                Além disso, representações de Apep frequentemente mostram a serpente sendo derrotada de maneira brutal, com deuses ou sacerdotes cortando-o em pedaços ou queimando-o. Esses atos simbólicos eram realizados para garantir a proteção do mundo contra as forças do caos e reafirmar o poder da ordem e da justiça.
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