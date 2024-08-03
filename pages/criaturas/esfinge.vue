<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/criaturas/esfinge.jfif" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Esfinge
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            A Esfinge egípcia é uma criatura com o corpo de um leão e a cabeça de um humano, geralmente um faraó. Sua origem está profundamente enraizada na cultura egípcia antiga, onde representava poder, sabedoria e proteção. A mais famosa Esfinge é a Grande Esfinge de Gizé, situada na necrópole de Gizé, próximo às pirâmides. Acredita-se que tenha sido esculpida durante o reinado do faraó Quéfren (Khafre) por volta de 2500 a.C.

            <p class="mb-2 text-l">
                A Esfinge servia como guardiã dos templos e túmulos sagrados, simbolizando a proteção dos locais sagrados e do faraó. Era vista como uma figura poderosa e benevolente, possuindo a força do leão e a inteligência e autoridade do ser humano.

                Além de sua função protetora, a Esfinge também desempenhava um papel significativo na mitologia e religião egípcia:

                Guardião das Pirâmides: A Grande Esfinge de Gizé é vista como o guardião das pirâmides, protegendo os segredos e as riquezas dos faraós enterrados ali.
                Simbolismo Solar: Em algumas interpretações, a Esfinge é associada ao deus solar Rá, simbolizando o sol nascente e a renovação da vida.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre a Esfinge é a ausência do seu nariz. Existem várias teorias sobre o que aconteceu, mas a explicação mais amplamente aceita é que o nariz foi deliberadamente destruído. O historiador árabe do século XV, al-Maqrizi, sugeriu que um sufi chamado Muhammad Sa'im al-Dahr vandalizou a Esfinge em 1378 d.C., irritado com os camponeses locais que faziam oferendas à Esfinge na esperança de aumentar suas colheitas.

Além disso, outra curiosidade é a existência de esfinges femininas, embora menos comuns, representando rainhas ou deusas, como a Esfinge de Hatshepsut, que foi uma das poucas faraós mulheres do Egito Antigo.
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
  