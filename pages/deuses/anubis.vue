<template>
  <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">

    <!-- Conteúdo esquerdo (imagem) -->
    <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
      <img src="/public/deuses/anubis.jfif" class="w-full h-full object-cover" />
    </div>
         
    <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
      <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
        Anúbis
      </h1>

      <div class="mb-4 text-center">
        <label class="mb-2 text-l">
          Anúbis, também conhecido como Anpu ou Inpu, é uma divindade importante na mitologia egípcia, especialmente associada à morte e aos rituais funerários. Ele é frequentemente representado como um homem com cabeça de chacal ou como um chacal inteiro.


          Anúbis era originalmente uma divindade do deserto e dos cemitérios, onde os chacais eram frequentemente vistos. Seu papel principal era como protetor das tumbas e guia das almas no pós-vida. Com o tempo, ele se tornou uma figura central nos rituais de mumificação e julgamento dos mortos.

          <p class="mb-2 text-l">
            Anúbis teve vários filhos, mas o mais conhecido é Qebehsenuef, um dos quatro filhos de Hórus que protegia os vasos canópicos usados na mumificação. Esses filhos eram responsáveis por proteger os órgãos internos do falecido.


            Anúbis desempenhou vários papéis importantes na mitologia egípcia:

            Mumificação: Ele era considerado o patrono da mumificação. Anúbis supervisionava o processo de embalsamamento, garantindo que os corpos fossem preparados adequadamente para a vida após a morte.

            Guia das Almas: Anúbis guiava as almas dos mortos ao submundo (Duat) e estava presente no julgamento das almas, onde o coração do falecido era pesado contra a pena de Maat (a deusa da verdade e justiça) para determinar sua pureza.

            Protetor dos Cemitérios: Como guardião das tumbas, Anúbis protegia os mortos de saqueadores e espíritos malignos.
          </p>
          <p class="mb-2 text-l">
            Uma curiosidade interessante sobre Anúbis é que, embora ele seja amplamente associado ao mundo dos mortos, ele nunca foi considerado um deus do mal. Em vez disso, ele era visto como um guia benevolente que ajudava as almas a alcançarem seu destino final.

          Anúbis também aparece em várias histórias mitológicas, incluindo a famosa história do "Pesagem do Coração". Nesta cerimônia, Anúbis conduzia o falecido até a balança, onde o coração era pesado contra a pena de Maat. Se o coração fosse mais leve ou igual à pena, a alma poderia entrar no paraíso. Caso contrário, ela seria devorada por Ammit, um demônio com cabeça de crocodilo, corpo de leão e traseira de hipopótamo.
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
