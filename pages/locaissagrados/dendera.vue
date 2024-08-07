<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/dendera.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Dendera
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Dendera, conhecida como Iunet ou Tentyris no antigo Egito, é uma cidade localizada na margem ocidental do rio Nilo, ao norte de Luxor. É famosa principalmente pelo Templo de Hathor, um dos complexos de templos mais bem preservados do Egito.


            Dendera foi habitada desde o período pré-dinástico, mas ganhou proeminência durante o período faraônico. Durante o Reino Antigo, a cidade já era um centro importante de culto, mas foi no período greco-romano que Dendera realmente floresceu. Os faraós Ptolomaicos e os imperadores romanos continuaram a construir e a embelezar o templo, resultando no magnífico complexo que vemos hoje.

            <p class="mb-2 text-l">
                O Templo de Hathor, dedicado à deusa do amor, beleza, música, maternidade e alegria, é a principal atração de Dendera. Hathor era uma das divindades mais populares do Egito e era frequentemente associada com Ísis e Bastet. O templo, construído principalmente durante o período ptolomaico (332-30 a.C.) e concluído pelos romanos, é notável por sua arquitetura e decoração impressionantes.

                O templo apresenta um salão hipostilo com 24 colunas ricamente decoradas, uma série de capelas, e o famoso zodíaco de Dendera, um mapa celestial que decora o teto de uma das câmaras. Este zodíaco é um dos primeiros exemplos conhecidos de representações astronômicas, combinando símbolos zodiacais gregos com imagens egípcias tradicionais.


                Dendera era também um centro de aprendizado, especialmente em astronomia e medicina. O complexo de templos contém uma série de textos médicos esculpidos nas paredes, que fornecem informações sobre os tratamentos utilizados na época. A deusa Hathor, além de suas outras associações, era vista como uma deusa curadora, e o templo servia como um local onde os doentes buscavam cura.
            </p>
            <p class="mb-2 text-l">
                O templo de Hathor em Dendera é famoso por sua arte detalhada e bem preservada. As paredes internas e externas são cobertas com relevos e inscrições que documentam rituais religiosos, oferendas aos deuses e celebrações festivas. A decoração do templo é um testemunho da continuidade das tradições religiosas egípcias, mesmo sob domínio estrangeiro.


                Com a chegada do cristianismo, muitos templos egípcios foram abandonados ou convertidos em igrejas. Durante a Idade Média, o templo de Hathor foi parcialmente enterrado sob a areia do deserto, o que ajudou a preservá-lo até sua redescoberta no século XIX.


                Hoje, Dendera é uma das atrações turísticas mais importantes do Egito, oferecendo aos visitantes uma visão profunda da religião, arte e ciência do Egito Antigo. A preservação excepcional do Templo de Hathor permite aos arqueólogos e historiadores estudar aspectos da vida e crença egípcia em detalhes.
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