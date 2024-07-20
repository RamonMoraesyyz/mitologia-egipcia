<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/deuses/osiris.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Osíris
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Osíris é um dos deuses mais importantes e venerados da mitologia egípcia. Ele é o deus da ressurreição, do julgamento e do submundo, representando a vida após a morte e a renovação.


            Osíris é filho de Geb, o deus da Terra, e Nut, a deusa do Céu. Ele é irmão de Ísis, Nephthys e Set. Osíris é casado com sua irmã Ísis, e juntos, eles são pais de Hórus, o jovem deus do céu e da vingança.
            <p class="mb-2 text-l">
                Osíris e Ísis têm um filho, Hórus. Após a morte de Osíris, Ísis concebe Hórus através de meios mágicos, e ele se torna o vingador de seu pai, lutando contra Set para restaurar a ordem.


                Osíris é mais conhecido por sua morte e ressurreição, que são centrais para seu papel como deus da vida após a morte. O mito conta que Set, seu irmão ciumento, conspirou para matá-lo. Set enganou Osíris, fazendo-o entrar em um caixão que foi lacrado e jogado no rio Nilo. Ísis, devotada esposa e irmã, procurou e encontrou o corpo de Osíris, mas Set o desmembrou em 14 partes e espalhou-as pelo Egito.

                Ísis, com a ajuda de Nephthys, Anúbis e Thoth, reuniu os pedaços do corpo de Osíris e os embalsamou, realizando os primeiros rituais de mumificação. Osíris foi então revivido por meio de magia, mas não retornou ao mundo dos vivos. Em vez disso, ele se tornou o governante do submundo, onde julgava as almas dos mortos e oferecia a promessa de vida eterna para aqueles considerados justos.

                Osíris é associado à fertilidade e à agricultura. Ele é frequentemente representado como uma múmia com a pele verde, simbolizando a vegetação e a renovação da vida. Ele segura o cetro e o flagelo, símbolos de poder e soberania.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Osíris é sua ligação com as pirâmides e o alinhamento astronômico. Acredita-se que os complexos de pirâmides, especialmente o de Gizé, foram alinhados com as estrelas de Órion, que eram associadas a Osíris. As pirâmides, servindo como túmulos para os faraós, refletiam a crença de que esses reis mortos seriam unidos com Osíris na vida após a morte, garantindo sua ressurreição e imortalidade.
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
  