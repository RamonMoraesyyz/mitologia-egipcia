<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/tutankhamon.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Tutankhamon
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Tutancâmon, também conhecido como o "Rei Tut," é um dos faraós mais famosos do Antigo Egito, apesar de seu curto reinado. Ele pertenceu à XVIII Dinastia e reinou de aproximadamente 1332 a.C. a 1323 a.C. Sua notoriedade moderna é em grande parte devido à descoberta de sua tumba quase intacta em 1922 por Howard Carter.


            Tutancâmon nasceu por volta de 1341 a.C. Ele era filho do faraó Akhenaton (originalmente Amenhotep IV), conhecido por suas reformas religiosas monoteístas, e provavelmente de uma de suas esposas secundárias, Kiya. Tutancâmon subiu ao trono muito jovem, provavelmente com cerca de nove anos de idade, após a morte de Akhenaton e do breve reinado de Smenkhkare.
            <p class="mb-2 text-l">
                Restaurador das Tradições: Durante o reinado de Tutancâmon, houve um retorno às antigas tradições e deidades egípcias após o período de reformas religiosas de seu pai, Akhenaton. Ele restaurou o politeísmo e devolveu poder e status ao clero de Amon. Seu nome original, Tutankhaten, que significava "Imagem viva de Aton," foi mudado para Tutankhamon, "Imagem viva de Amon," refletindo essa mudança.

                Reformas e Construções: Tutancâmon começou a restaurar os templos e monumentos que haviam sido desfigurados ou negligenciados durante o reinado de seu pai. Embora não tenha iniciado grandes projetos de construção devido à curta duração de seu reinado e sua juventude, ele encomendou trabalhos significativos de restauração.

                Estabilidade Política: Sob a orientação de seus conselheiros, especialmente Ay e Horemheb, Tutancâmon tentou estabilizar o Egito após o tumultuado período de seu pai. Seu casamento com Anquesenamon, sua meia-irmã e filha de Akhenaton e Nefertiti, também ajudou a solidificar sua posição.
            </p>
            <p class="mb-2 text-l">
                A curiosidade mais notável sobre Tutancâmon é a descoberta de sua tumba quase intacta no Vale dos Reis por Howard Carter em 1922. Esta descoberta é considerada uma das mais significativas da arqueologia egípcia, pois forneceu uma riqueza de informações sobre o Egito Antigo e a vida real. A tumba de Tutancâmon continha tesouros fabulosos, incluindo sua famosa máscara mortuária de ouro, móveis, carruagens, armas e roupas, que estavam praticamente intactos devido ao fato de que a tumba não havia sido saqueada ao longo dos milênios.

            A morte de Tutancâmon aos 19 anos permanece um mistério. Existem várias teorias, incluindo uma possível infecção resultante de um ferimento, uma doença genética, ou até mesmo um assassinato, embora nenhuma delas tenha sido conclusivamente provada.
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
  