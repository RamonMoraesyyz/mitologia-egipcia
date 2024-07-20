<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/faraos/djoser.jpg" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
          Djoser
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          O faraó Djoser, também conhecido como Zoser, foi um dos monarcas mais importantes da Terceira Dinastia do Egito, governando por volta de 2670 a.C. Ele é mais famoso por suas inovações arquitetônicas e pela construção da primeira pirâmide de pedra do Egito, a Pirâmide de Djoser, localizada em Saqqara.


        Djoser nasceu em uma família real egípcia durante a Terceira Dinastia. Ele foi filho do faraó Khasekhemwy e da rainha Nimaathap. Sua ascendência real garantiu que ele fosse educado e preparado para assumir o trono desde jovem.
          <p class="mb-2 text-l">
            O reinado de Djoser ocorreu por volta de 2670 a.C., durante a Terceira Dinastia do Egito Antigo. Ele governou por aproximadamente 19 anos, embora algumas fontes sugiram que seu reinado possa ter durado até 29 anos. Este período foi marcado por estabilidade e progresso, permitindo inovações culturais e tecnológicas significativas.


          Djoser é mais conhecido pela construção da Pirâmide de Djoser em Saqqara, a primeira pirâmide de pedra do Egito e a mais antiga estrutura de pedra em grande escala conhecida na história. Esta pirâmide escalonada, projetada por seu vizir e arquiteto Imhotep, marcou uma evolução significativa na arquitetura funerária egípcia, passando das mastabas tradicionais para uma estrutura mais complexa e grandiosa.

          Além de suas realizações arquitetônicas, Djoser também é lembrado por suas contribuições à administração e à centralização do poder. Ele reforçou a autoridade do faraó e implementou várias reformas que melhoraram a gestão do reino. Djoser é frequentemente associado a inovações na irrigação e agricultura, ajudando a garantir a prosperidade do Egito durante seu reinado.
          </p>
          <p class="mb-2 text-l">
            Uma curiosidade fascinante sobre Djoser é a lenda da fome de sete anos. De acordo com uma inscrição conhecida como Estela da Fome, encontrada na Ilha de Sehel, durante o reinado de Djoser, o Egito teria enfrentado uma severa fome que durou sete anos. A estela relata que Djoser consultou Imhotep, que por sua vez teria procurado respostas nos textos sagrados. A solução foi encontrada ao restaurar o culto ao deus do Nilo, Khnum, resultando no fim da fome e no retorno da abundância ao Egito. Embora a veracidade histórica desta lenda seja debatida, ela destaca a importância de Djoser e Imhotep na mitologia e na história egípcia.
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
