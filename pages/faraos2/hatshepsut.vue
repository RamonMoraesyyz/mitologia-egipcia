<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/hapshepsut.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Hatshepsut
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Hatshepsut foi uma das mais notáveis faraós do Antigo Egito e a segunda mulher a ocupar o trono faraônico. Ela nasceu por volta de 1507 a.C., filha do faraó Tutmés I e da rainha Ahmose. Após a morte de seu pai, seu meio-irmão Tutmés II subiu ao trono e Hatshepsut casou-se com ele, fortalecendo ainda mais sua posição na corte egípcia.
            <p class="mb-2 text-l">
                Regente e Faraó: Quando Tutmés II faleceu, seu filho Tutmés III, ainda criança, herdou o trono. Hatshepsut inicialmente atuou como regente, mas logo se declarou faraó, governando efetivamente como co-regente com Tutmés III. Durante seu reinado, ela assumiu títulos masculinos e se representava como um faraó homem em muitas representações artísticas.

                Expansão Comercial: Hatshepsut é conhecida por revitalizar o comércio egípcio. Uma de suas mais famosas expedições foi para a terra de Punt, uma região rica em ouro, mirra e outros bens preciosos. Essa expedição foi um grande sucesso e fortaleceu a economia egípcia.

                Projetos de Construção: Ela iniciou inúmeros projetos de construção, deixando um legado arquitetônico impressionante. Entre os mais notáveis está o Templo de Deir el-Bahari em Tebas, que é considerado uma obra-prima da arquitetura egípcia antiga. Ela também renovou muitos templos e construiu obeliscos no Templo de Karnak.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Hatshepsut é que, após sua morte, seu nome e suas imagens foram sistematicamente apagados dos registros históricos e monumentos por ordem de Tutmés III, seu sucessor. Os motivos exatos para isso ainda são debatidos pelos historiadores, mas acredita-se que pode ter sido uma tentativa de legitimar o poder de Tutmés III e reafirmar a tradição patriarcal no governo egípcio.
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
  