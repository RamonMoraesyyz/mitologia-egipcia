<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/ramsess.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Ramsés 2
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Ramsés II, também conhecido como Ramsés, o Grande, foi um dos mais famosos e poderosos faraós do Antigo Egito. Ele reinou durante a XIX Dinastia, de aproximadamente 1279 a 1213 a.C., e é frequentemente lembrado como um dos maiores faraós da história egípcia devido à sua longa duração no trono e suas numerosas realizações.


            Ramsés II nasceu em 1303 a.C., filho do faraó Seti I e da rainha Tuya. Desde jovem, Ramsés foi preparado para governar e acompanhou seu pai em várias campanhas militares. Ele ascendeu ao trono após a morte de Seti I e continuou as políticas expansionistas e os projetos de construção de seu pai.
            <p class="mb-2 text-l">
                Conquistas Militares: Ramsés II é famoso por suas campanhas militares, especialmente a Batalha de Cades contra os hititas em 1274 a.C. Embora a batalha tenha sido inconclusiva, Ramsés se apresentou como um grande guerreiro e negociador. O tratado de paz subsequente com os hititas é um dos primeiros acordos de paz registrados na história.

                    Projetos de Construção: Ramsés II foi um dos faraós que mais construiu no Egito. Entre suas obras mais notáveis estão os templos de Abu Simbel, esculpidos na rocha e dedicados a ele e à sua esposa Nefertari. Ele também completou a grande sala hipostila no Templo de Karnak e construiu o Ramesseum, seu templo mortuário em Tebas.

                Administração e Diplomacia: Ramsés II estabeleceu uma administração eficiente e manteve a estabilidade e a prosperidade do Egito durante seu longo reinado. Ele também foi um diplomata habilidoso, estabelecendo tratados e casamentos diplomáticos com outras potências, como os hititas.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade fascinante sobre Ramsés II é a longevidade de seu reinado, que durou 66 anos, um dos mais longos da história egípcia. Ramsés II teve muitas esposas e concubinas, e é conhecido por ter tido mais de 100 filhos. Seu legado foi tão duradouro que nove faraós subsequentes adotaram o nome Ramsés em sua homenagem.

                Ramsés II é frequentemente associado ao faraó mencionado na Bíblia durante o Êxodo, embora essa identificação não seja confirmada. Sua múmia foi descoberta em 1881 no esconderijo de Deir el-Bahari e está atualmente em exibição no Museu Egípcio do Cairo.
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
  