<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/faraos/sneferu.jpg" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Sneferu
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          O faraó Sneferu foi o fundador da Quarta Dinastia do Egito, governando por volta de 2613 a.C. a 2589 a.C. Ele é conhecido por suas inovações arquitetônicas e pela construção de várias pirâmides, estabelecendo um legado de desenvolvimento monumental que influenciou significativamente a arquitetura egípcia subsequente.


        Sneferu nasceu em uma família real egípcia durante o final da Terceira Dinastia. Ele era filho do faraó Huni e de uma mulher chamada Meresankh I. Embora sua mãe não fosse de origem real, Sneferu ascendeu ao trono devido à sua linhagem paterna e aos seus casamentos estratégicos, incluindo sua união com Hetepheres I, que pode ter sido sua meia-irmã e filha de Huni.
          <p class="mb-2 text-l">
            O reinado de Sneferu ocorreu aproximadamente entre 2613 a.C. e 2589 a.C., cobrindo um período de cerca de 24 anos, embora algumas estimativas sugiram que ele possa ter reinado por até 48 anos. Este período foi caracterizado por um grande avanço na construção de monumentos e pelo desenvolvimento de técnicas arquitetônicas que seriam utilizadas por seus sucessores.


          Sneferu é mais famoso por suas contribuições à arquitetura egípcia, particularmente no que diz respeito à construção de pirâmides. Ele foi responsável por três grandes pirâmides, cada uma representando um estágio significativo no desenvolvimento das técnicas de construção:

          Pirâmide de Meidum: Originalmente uma pirâmide escalonada, foi posteriormente convertida em uma pirâmide verdadeira. No entanto, devido a problemas estruturais, parte dela desmoronou, e hoje é conhecida como a "Pirâmide Colapsada".

          Pirâmide Bent (ou Romboidal): Localizada em Dahshur, esta pirâmide é notável por sua forma incomum, com um ângulo de inclinação que muda aproximadamente na metade de sua altura. Este design único foi resultado de ajustes feitos durante a construção para evitar desmoronamentos.

          Pirâmide Vermelha: Também em Dahshur, esta é a primeira pirâmide verdadeira bem-sucedida, com lados suaves e uma base sólida. Foi chamada assim devido à cor avermelhada do calcário utilizado em sua construção.

          Além das pirâmides, Sneferu também implementou várias reformas administrativas e militares, consolidando o poder do estado egípcio e expandindo suas fronteiras através de campanhas militares no Sinai e na Núbia.
          </p>
          <p class="mb-2 text-l">
            Uma curiosidade interessante sobre Sneferu é sua reputação como um faraó benevolente e popular. Diferentemente de alguns de seus sucessores, Sneferu era frequentemente descrito como um "rei bom" em textos posteriores, indicando que ele era amado e respeitado por seu povo. Sua imagem positiva é refletida em vários textos antigos, onde ele é descrito como justo e gentil, uma raridade entre os monarcas do Egito Antigo.
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
