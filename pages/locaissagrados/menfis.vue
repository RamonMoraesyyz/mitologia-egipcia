<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/menfis.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Menfis
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Mênfis foi fundada por volta de 3100 a.C. pelo faraó Menés (ou Narmer), que unificou o Alto e o Baixo Egito, tornando-a a primeira capital do Egito unificado. A cidade estava estrategicamente situada na fronteira entre o Alto e o Baixo Egito, facilitando o controle administrativo e a defesa do reino.


            Durante o Antigo Reino (c. 2686-2181 a.C.), Mênfis floresceu como capital do Egito. A cidade era o centro político e administrativo do país, onde os faraós construíram palácios e templos grandiosos. As pirâmides de Gizé, localizadas nas proximidades, foram construídas durante esta época, simbolizando o poder e a divindade dos faraós.

            <p class="mb-2 text-l">
                O principal templo de Mênfis era dedicado a Ptah, o deus criador e patrono dos artesãos. Ptah era uma das divindades mais importantes do panteão egípcio, e seu templo, o Hut-ka-Ptah ("Mansão do Ka de Ptah"), era um dos maiores e mais reverenciados do Egito. A adoração a Ptah fez de Mênfis um centro religioso significativo, atraindo peregrinos e sacerdotes de todo o país.


                Perto de Mênfis, a necrópole de Saqqara serviu como um importante cemitério real e nobre. A pirâmide de Djoser, uma das primeiras pirâmides construídas no Egito, está localizada em Saqqara e é um testemunho da inovação arquitetônica e religiosa do Antigo Reino. A necrópole continuou a ser usada durante toda a história do Egito, com tumbas e monumentos que datam de várias dinastias.
            </p>
            <p class="mb-2 text-l">
                Mênfis era o coração administrativo do Egito, abrigando os escritórios e residências dos vizires, escribas e outros oficiais do governo. A cidade era um centro de tomada de decisões, onde as políticas e estratégias do reino eram formuladas e implementadas.

                Devido à sua localização estratégica, Mênfis era um importante centro de comércio. A cidade facilitava o comércio entre o Alto e o Baixo Egito, bem como com outras civilizações do Mediterrâneo e do Oriente Médio. A produção de bens artesanais, como cerâmica, têxteis e joias, também era uma atividade econômica crucial.


            Com o advento do período romano, a importância de Mênfis começou a declinar. A cidade foi gradualmente eclipsada por Alexandria, que se tornou a nova capital e principal centro cultural e econômico do Egito. Apesar disso, Mênfis continuou a ser habitada e a servir como um centro religioso até os primeiros séculos d.C.
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