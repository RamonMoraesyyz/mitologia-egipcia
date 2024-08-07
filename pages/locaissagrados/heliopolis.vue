<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/heliopolis.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Heliópolis
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Heliópolis, conhecida como Iunu pelos antigos egípcios, foi uma das mais antigas e importantes cidades do Egito Antigo. Localizada próxima ao moderno Cairo, Heliópolis significa "Cidade do Sol" em grego, refletindo sua dedicação ao culto do deus-sol Rá.


            A história de Heliópolis remonta aos primeiros períodos dinásticos do Egito, e a cidade atingiu seu apogeu durante o Reino Antigo (cerca de 2686-2181 a.C.). Foi um centro religioso e intelectual de grande renome, atraindo sacerdotes, estudiosos e filósofos.

            Durante o Reino Antigo, Heliópolis se tornou o principal centro de culto ao deus-sol Rá. Os faraós da Quinta Dinastia (cerca de 2494-2345 a.C.) especialmente promoveram o culto solar, construindo templos e obeliscos em homenagem a Rá. A influência de Heliópolis cresceu tanto que suas práticas religiosas e cosmológicas influenciaram todo o Egito.

            <p class="mb-2 text-l">
                Heliópolis era considerada a cidade da criação na mitologia egípcia. Segundo a cosmogonia heliopolitana, foi em Heliópolis que o deus-sol Rá emergiu do caos primordial, iniciando o processo de criação. A Enéade de Heliópolis, um grupo de nove deuses importantes (Rá, Shu, Tefnut, Geb, Nut, Osíris, Ísis, Set e Néftis), era central para as crenças religiosas do local.

                Os sacerdotes de Heliópolis desempenhavam um papel crucial na administração religiosa e na interpretação de textos sagrados. Eles eram responsáveis por realizar rituais diários, festivais anuais e cerimônias para manter a ordem cósmica, conhecida como Ma'at.
            </p>
            <p class="mb-2 text-l">
                Além de sua importância religiosa, Heliópolis era um centro de aprendizado e conhecimento. Muitos dos maiores estudiosos e filósofos da antiguidade, incluindo Platão e Heródoto, visitaram a cidade para estudar suas tradições e aprender com seus sacerdotes. A cidade era famosa por sua biblioteca e suas escolas, onde a astronomia, a matemática e outras ciências eram estudadas.


                O declínio de Heliópolis começou durante o período tardio do Egito Antigo e continuou sob o domínio persa e, posteriormente, romano. A fundação de Alexandria e a mudança do centro de poder religioso e intelectual contribuíram para a diminuição da importância de Heliópolis. Com o tempo, muitos de seus templos foram saqueados ou desmantelados, e seus materiais reutilizados em outras construções.
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