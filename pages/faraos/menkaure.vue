<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos/menkaure.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Menkaure
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Menkaure nasceu no seio da poderosa Quarta Dinastia, uma família de construtores de pirâmides que dominou o Egito durante o período do Antigo Reino. Sua mãe é geralmente identificada como uma das esposas de Khafre. Menkaure sucedeu seu pai no trono, continuando a tradição de grandes projetos de construção que caracterizavam sua família.
            <p class="mb-2 text-l">
                O principal feito de Menkaure é a construção da terceira e menor das três grandes pirâmides de Gizé. Embora seja menor que as pirâmides de Khufu e Khafre, a pirâmide de Menkaure é notável por seu acabamento e pela qualidade de sua construção. A pirâmide foi originalmente revestida com granito vermelho na parte inferior e calcário branco na parte superior, o que a distinguia das demais.

            Além da pirâmide, Menkaure construiu um complexo funerário completo, incluindo um templo mortuário e um templo do vale, onde foram encontrados belos exemplos de escultura egípcia. Entre as esculturas mais notáveis está o grupo de estátuas de Menkaure com a deusa Hathor e várias divindades locais, que mostram o faraó de uma maneira majestosa e serena.
  
          
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Menkaure é a história associada à sua pirâmide. Segundo a tradição, a pirâmide de Menkaure foi deixada inacabada, com a parte superior sem o revestimento completo de granito que caracteriza a parte inferior. Existem várias teorias sobre o motivo disso, incluindo a possibilidade de que Menkaure tenha morrido antes da conclusão do trabalho ou que houve uma mudança nas prioridades de construção devido a fatores econômicos ou políticos.

                Além disso, Menkaure é frequentemente lembrado na literatura antiga como um governante justo e benevolente. O historiador grego Heródoto relatou que Menkaure era considerado mais humano e menos opressor em comparação com seus predecessores, embora esses relatos sejam baseados em tradições e histórias que surgiram muito depois de seu reinado.
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
  