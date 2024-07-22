<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos/khafre.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Khafre
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Khafre, também conhecido como Quéfren, foi um faraó da Quarta Dinastia do Antigo Egito, que governou aproximadamente entre 2570 e 2544 a.C. Ele era filho do faraó Khufu (ou Quéops) e, como seu pai, é mais famoso por suas contribuições monumentais no planalto de Gizé.


            Khafre nasceu durante o reinado de seu pai, Khufu, e era um dos muitos filhos deste poderoso faraó. Sua mãe era provavelmente uma das rainhas secundárias de Khufu. Khafre sucedeu seu irmão Djedefré, cujo reinado foi relativamente breve.
            <p class="mb-2 text-l">
                O principal feito de Khafre é a construção da segunda maior pirâmide de Gizé, frequentemente chamada de Pirâmide de Quéfren. Esta pirâmide é apenas ligeiramente menor que a Grande Pirâmide de seu pai, mas se destaca devido ao seu engenhoso sistema de construção e à sua localização elevada, que a faz parecer quase do mesmo tamanho.

                Além da pirâmide, Khafre também é amplamente associado à construção da Grande Esfinge de Gizé, uma das estátuas mais icônicas do mundo antigo. A esfinge, com corpo de leão e rosto humano, é geralmente considerada uma representação de Khafre, simbolizando seu poder e sabedoria. A esfinge e seu templo adjacente são algumas das maiores realizações arquitetônicas de seu reinado.

                Khafre também construiu um templo mortuário e um templo do vale, que são conhecidos por seus impressionantes colossos de diorito. Esses templos faziam parte do complexo funerário ligado à sua pirâmide e foram usados para rituais e cerimônias religiosas.
  
          Além da Grande Pirâmide, Khufu também é creditado com a construção de várias outras estruturas menores e templos. Seu reinado foi marcado por uma centralização do poder e uma administração eficiente, que ajudou a manter a estabilidade e a prosperidade do Egito.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Khafre é que sua pirâmide ainda conserva parte de seu revestimento original de calcário em seu topo. Isso oferece uma visão sobre como todas as pirâmides de Gizé poderiam ter aparecido em seu auge, brilhando com um revestimento branco que refletia o sol.

                Além disso, há um debate contínuo entre os egiptólogos sobre o verdadeiro propósito e significado da Grande Esfinge. Algumas teorias sugerem que a esfinge pode ter sido construída anteriormente e que Khafre apenas a modificou ou restaurou. No entanto, a opinião predominante é que a esfinge foi criada durante o reinado de Khafre e representa sua autoridade e poder divino.
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
  