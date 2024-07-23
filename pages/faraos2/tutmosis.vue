<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/tutmosis.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Tutmosis
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            O nome Tutmés refere-se a vários faraós da XVIII Dinastia do Egito, sendo os mais notáveis Tutmés I, Tutmés II, Tutmés III e Tutmés IV. Vou focar no mais destacado deles, Tutmés III, que é frequentemente chamado de "Napoleão do Egito" devido às suas conquistas militares.


            Tutmés III nasceu por volta de 1481 a.C. Ele era filho do faraó Tutmés II e de uma esposa secundária chamada Iset. Após a morte de seu pai, ele era jovem demais para governar, então sua madrasta e tia, a famosa Hatshepsut, assumiu o trono como regente e posteriormente como faraó. Tutmés III foi mantido à margem do poder durante o reinado de Hatshepsut, mas treinou como comandante militar.
            <p class="mb-2 text-l">
                Conquistas Militares: Após a morte de Hatshepsut, Tutmés III assumiu o trono e iniciou uma série de campanhas militares que expandiram significativamente o império egípcio. Ele realizou pelo menos 17 campanhas militares, conquistando territórios no Oriente Médio, incluindo partes da Síria e Canaã. Suas vitórias são frequentemente registradas em inscrições detalhadas no Templo de Karnak.

                Administração e Governança: Além de suas conquistas militares, Tutmés III foi um administrador eficiente. Ele consolidou o poder egípcio nas regiões conquistadas, estabelecendo governadores locais leais e impondo tributos que enriqueceram o Egito.

                Construções: Tutmés III também foi um grande construtor, continuando e expandindo muitos dos projetos iniciados por Hatshepsut. Ele acrescentou significativamente ao Templo de Karnak, incluindo a construção do santuário de Amon e de muitos outros monumentos e templos em todo o Egito.
            </p>
            <p class="mb-2 text-l">
                Uma curiosidade interessante sobre Tutmés III é que, apesar de seu longo reinado e grandes feitos, ele inicialmente teve que lutar para se estabelecer como o faraó legítimo após a morte de Hatshepsut. Muitos estudiosos acreditam que ele ordenou a remoção ou modificação de muitas referências a Hatshepsut em monumentos e registros históricos. Essa prática foi uma tentativa de reescrever a história de forma a minimizar o impacto do reinado de Hatshepsut e legitimar plenamente seu próprio governo.
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
  