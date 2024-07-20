<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/maat.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Ma'at
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Ma'at é filha de Rá, o deus do sol, e, portanto, está intimamente ligada ao ciclo diário de renovação e ordem cósmica que Rá simboliza. Sua origem está associada à criação e ao estabelecimento da ordem no universo, sendo fundamental para a estabilidade do mundo e do Egito.


            Ma'at não é tradicionalmente associada a filhos na mitologia egípcia. Ela é uma deusa abstrata e conceitual, representando princípios universais mais do que relações pessoais ou familiares.
            <p class="mb-2 text-l">
                Os feitos de Ma'at estão mais relacionados à manutenção da ordem cósmica e social do que a ações mitológicas específicas. Alguns dos papéis e atributos mais importantes de Ma'at incluem:

                Personificação da Ordem Cósmica: Ma'at representa a ordem e a estabilidade do universo. Seu conceito era central na religião e na vida diária dos egípcios, e a manutenção de Ma'at era considerada vital para a prosperidade e harmonia.

                Juízo dos Mortos: No julgamento das almas dos mortos, Ma'at desempenhava um papel crucial. O coração dos falecidos era pesado contra a pena de Ma'at para determinar se a pessoa havia vivido uma vida justa e equilibrada. Se o coração era mais leve ou igual ao peso da pena, a alma era considerada digna de entrar no paraíso; se fosse mais pesado, a alma era devorada por Ammit, um monstro demoníaco.

                Símbolo de Justiça e Verdade: Ma'at era um padrão para o comportamento humano e governamental. Os faraós se viam como defensores de Ma'at, encarregados de manter a justiça e a ordem em seu reino.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade sobre Ma'at é que seu conceito de ordem e justiça não era apenas um princípio abstrato, mas um aspecto central da vida diária e da administração no Egito Antigo. Os tribunais egípcios e os funcionários do governo juravam seguir Ma'at em todas as suas ações, e o faraó, como representante de Ma'at na terra, tinha a responsabilidade de governar de acordo com seus princípios. As leis, a moralidade, e até a estrutura social estavam fundamentadas na ideia de manter a Ma'at, refletindo sua importância abrangente na cultura egípcia.
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
  