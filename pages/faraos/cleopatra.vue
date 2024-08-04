<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos/cleopatra.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Cleópatra
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Cleópatra VII, a última rainha do Egito, é uma figura histórica fascinante conhecida por sua inteligência, carisma e habilidades políticas. Ela nasceu em 69 a.C. em Alexandria, Egito, e foi a última governante da dinastia Ptolemaica, que governou o Egito após a morte de Alexandre, o Grande.


            Cleópatra era filha de Ptolemeu XII Auletes, o faraó do Egito. A dinastia Ptolemaica era de origem macedônica-grega, estabelecida por Ptolemeu I Sóter, um dos generais de Alexandre, o Grande. Embora de ascendência grega, Cleópatra destacou-se por sua capacidade de se integrar à cultura egípcia. Ela foi a primeira de sua dinastia a aprender a língua egípcia e a adotar ativamente os costumes e religiões locais.
            <p class="mb-2 text-l">
                Cleópatra é conhecida por suas alianças políticas e românticas com alguns dos homens mais poderosos de Roma. Inicialmente, co-governou com seu irmão e esposo Ptolemeu XIII, mas depois de conflitos e uma guerra civil, consolidou seu poder.

                Aliança com Júlio César: Após a derrota de Ptolemeu XIII, Cleópatra se aliou a Júlio César, com quem teve um filho chamado Cesarião. Essa aliança fortaleceu seu poder no Egito e ajudou a estabilizar seu reinado.

                Relação com Marco Antônio: Após a morte de César, Cleópatra formou uma aliança com Marco Antônio. Juntos, tiveram três filhos. Esta aliança foi tanto política quanto romântica, e juntos, eles tentaram desafiar o poder de Otaviano, o futuro imperador Augusto.

                Batalha de Ácio: Em 31 a.C., as forças de Marco Antônio e Cleópatra foram derrotadas na Batalha de Ácio por Otaviano. Após a derrota, eles retornaram ao Egito, onde enfrentaram a iminente invasão romana.

                Suicídio e Fim da Dinastia Ptolemaica: Em 30 a.C., Cleópatra e Marco Antônio cometeram suicídio. A morte de Cleópatra marcou o fim da dinastia Ptolemaica e o início do Egito como uma província do Império Romano.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Cleópatra é que, apesar de sua reputação como uma das mulheres mais belas da história, muitas fontes antigas destacam que seu verdadeiro poder residia em seu intelecto e carisma. Plutarco, um historiador grego, escreveu que sua beleza física não era incomum, mas sua inteligência, sua voz encantadora e sua presença cativante a tornavam irresistível. Ela era fluente em várias línguas e bem versada em matemática, filosofia, oratória e astronomia.
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
  