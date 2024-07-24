<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/nectanebo.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Nectanebo
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Nectanebo foi o nome de dois faraós da 30ª Dinastia do Egito, Nectanebo I e Nectanebo II, conhecidos por seus esforços para preservar a independência egípcia contra as incursões estrangeiras, especialmente dos persas.


            Nectanebo I, também conhecido como Nakhtnebef, reinou de 380 a.C. a 362 a.C. Ele foi o fundador da 30ª Dinastia, assumindo o trono após um golpe contra Neferites II.
            <p class="mb-2 text-l">
                Durante seu reinado, Nectanebo I enfrentou uma invasão persa em 373 a.C., liderada pelo general Farnabazo. Graças à sua habilidade militar e à estratégia defensiva, ele conseguiu repelir os invasores e manter a independência do Egito. Nectanebo I também foi um grande patrono das artes e da religião egípcia, patrocinando a construção de templos e a renovação de monumentos. Ele investiu significativamente em Karnak, construindo um quiosque para Amon e um santuário para Khonsu.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Nectanebo I é que ele é frequentemente mencionado na literatura esotérica e alquímica. Algumas lendas medievais o retratam como um grande mago e alquimista. Em uma dessas lendas, Nectanebo II fugiu para a Macedônia, onde se disfarçou como um mago e acabou se tornando o pai de Alexandre, o Grande, através de um artifício mágico que envolveu a mãe de Alexandre, Olímpia. Embora essa história seja mais mito do que realidade, ela ilustra o fascínio duradouro por Nectanebo II como uma figura misteriosa e poderosa.
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
  