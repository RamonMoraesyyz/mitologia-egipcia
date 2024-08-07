<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/locais/saqqara.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Saqqara
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Saqqara é uma vasta necrópole situada a cerca de 30 quilômetros ao sul do Cairo, no Egito. Este sítio arqueológico é conhecido principalmente por abrigar a pirâmide de Djoser, a mais antiga pirâmide de pedra do Egito, e por ser um importante centro funerário ao longo de várias dinastias egípcias.


            Saqqara tem uma história longa e complexa que remonta à Primeira Dinastia do Egito (c. 3100-2900 a.C.). Foi utilizada como necrópole real e nobre desde os primeiros tempos do Egito Antigo. As tumbas mais antigas em Saqqara são mastabas, estruturas retangulares feitas de tijolos de barro que serviam como sepulturas para a elite.


            A importância de Saqqara aumentou significativamente durante a Terceira Dinastia (c. 2686-2613 a.C.), quando o faraó Djoser encomendou a construção de sua pirâmide escalonada. Projetada pelo arquiteto e vizir Imhotep, a pirâmide de Djoser é considerada a primeira estrutura monumental de pedra do mundo e um precursor das pirâmides posteriores de Gizé. Esta pirâmide marcou uma inovação na arquitetura funerária egípcia e simbolizou o poder e a divindade do faraó.

            <p class="mb-2 text-l">
                Saqqara era um centro religioso significativo devido à sua proximidade com Mênfis, a antiga capital do Egito. A cidade era considerada sagrada, e muitos templos e capelas dedicadas aos deuses egípcios foram construídos ao longo dos séculos. A deusa Bastet, o deus Ptah e o deus Sokar eram particularmente venerados em Saqqara.


                A pirâmide de Djoser, com suas seis mastabas empilhadas umas sobre as outras, é o marco mais icônico de Saqqara. Este complexo funerário inclui várias estruturas, como templos, pátios, e uma série de galerias subterrâneas, que foram usadas para armazenar os restos mortais do faraó e seus tesouros.


                Além da pirâmide de Djoser, Saqqara abriga várias outras pirâmides menores, mastabas e tumbas de oficiais importantes. As mastabas de Mereruka, Kagemni e Ti são famosas por suas intrincadas decorações em relevo, que retratam cenas da vida cotidiana, atividades agrícolas, cerimônias religiosas e a vida após a morte.


                Os Textos das Pirâmides, encontrados nas pirâmides de Unas e Teti em Saqqara, são algumas das mais antigas coleções de textos religiosos do mundo. Esses textos, inscritos nas paredes das câmaras funerárias, eram fórmulas mágicas destinadas a proteger e guiar o faraó na vida após a morte.
            </p>
            <p class="mb-2 text-l">
                Saqqara não apenas serviu como um local de sepultamento, mas também como um centro de inovação arquitetônica e artística. A transição da construção com tijolos de barro para a construção com pedra, exemplificada pela pirâmide de Djoser, marcou um avanço significativo na engenharia e na arquitetura.


                As escavações em Saqqara começaram no século XIX e continuam até hoje. Arqueólogos de todo o mundo têm trabalhado para descobrir, preservar e estudar as inúmeras tumbas, artefatos e textos antigos encontrados no sítio. Essas descobertas têm fornecido insights valiosos sobre a sociedade, a religião e a cultura do Egito Antigo.


                Hoje, Saqqara é reconhecida como um Patrimônio Mundial da UNESCO e é um dos sítios arqueológicos mais importantes do Egito. As ruínas de Saqqara atraem milhares de turistas, pesquisadores e historiadores, todos interessados em explorar e entender a rica história e herança do Egito Antigo.
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