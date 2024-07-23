<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/seti.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Seti
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Seti I foi um faraó da XIX Dinastia do Egito, que reinou aproximadamente de 1290 a 1279 a.C. Ele é amplamente reconhecido por suas realizações militares, seus projetos de construção impressionantes e sua administração eficiente, estabelecendo as bases para o auge do poder egípcio durante o reinado de seu filho, Ramsés II.


            Seti I era filho do faraó Ramsés I e da rainha Sitre. Seu nome completo era Menmaatre Seti, e ele assumiu o trono após a curta duração do reinado de seu pai. Seti I veio de uma família militar, e sua própria carreira militar começou cedo, o que o preparou bem para as campanhas que ele lideraria como faraó.
            <p class="mb-2 text-l">
                Conquistas Militares: Seti I é conhecido por suas campanhas militares para restaurar a autoridade egípcia nos territórios perdidos. Ele liderou expedições contra os hititas na Síria, os líbios no oeste e os núbios no sul. Seus feitos militares são detalhadamente registrados nos relevos das paredes do Templo de Karnak.

                Projetos de Construção: Seti I foi um grande construtor. Ele iniciou a construção do Templo de Abydos, dedicado ao deus Osíris, que é famoso por seus relevos bem preservados e alta qualidade artística. Além disso, ele continuou a expansão do Templo de Karnak e começou a construção da grande sala hipostila.

                Administração: Seti I foi um administrador eficaz, restaurando templos e monumentos que haviam sido danificados durante o tumultuado período do final da XVIII Dinastia. Ele reforçou a administração central e garantiu a lealdade das províncias, fortalecendo a unidade do império egípcio.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Seti I é sua tumba no Vale dos Reis, KV17, conhecida como a Tumba de Belzoni, em homenagem ao explorador Giovanni Battista Belzoni que a descobriu em 1817. Esta tumba é uma das mais longas e profundas do Vale dos Reis e é famosa por seus relevos coloridos e bem preservados, que fornecem uma rica visão da arte e cultura funerária egípcia. A tumba de Seti I é considerada uma das mais belas e elaboradas, refletindo a importância e o poder de seu reinado.
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
  