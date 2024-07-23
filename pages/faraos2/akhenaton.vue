<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/akhenaton.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Akhenaton
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Akhenaton, originalmente conhecido como Amenhotep IV, foi um faraó da XVIII dinastia do Egito que reinou de aproximadamente 1353 a.C. a 1336 a.C. Ele é famoso por ter introduzido grandes mudanças religiosas e culturais no Egito, promovendo o culto exclusivo ao deus Aton, o disco solar.


          Akhenaton era filho do faraó Amenhotep III e da rainha Tiye. Ele nasceu como Amenhotep IV, mas mudou seu nome para Akhenaton, que significa "Servo de Aton", para refletir sua devoção ao novo deus.
            <p class="mb-2 text-l">
              Revolução Religiosa: Akhenaton é mais conhecido por sua tentativa de transformar a religião egípcia. Ele estabeleceu o culto monoteísta a Aton, o deus solar, e tentou suprimir o culto aos outros deuses tradicionais do Egito, particularmente Amon. Essa mudança foi radical em uma sociedade profundamente enraizada no politeísmo.

              Nova Capital: Ele fundou uma nova capital chamada Akhetaton (hoje conhecida como Amarna) dedicada ao deus Aton. A cidade foi construída rapidamente e se tornou o centro do novo culto religioso, com templos grandiosos dedicados ao deus solar.

            Arte e Cultura: Sob Akhenaton, a arte egípcia passou por uma transformação significativa. As representações tornaram-se mais realistas e menos idealizadas, muitas vezes mostrando o faraó e sua família com características físicas distintas. Essa mudança é conhecida como o "Estilo Amarniano" e é notável por seu realismo e expressividade.
            </p>
            <p class="mb-2 text-l">
              Uma curiosidade interessante sobre Akhenaton é que, após sua morte, seu sucessor Tutancâmon (originalmente Tutankhaton) restaurou os antigos cultos e tradições religiosas. O culto a Aton foi abandonado, e Akhetaton foi deixada em ruínas. Akhenaton foi inicialmente considerado um herege, e muitos dos registros de seu reinado foram destruídos ou modificados para remover referências ao seu governo e suas reformas religiosas. Apenas séculos depois, arqueólogos redescobriram sua história e reconheceram a importância de suas reformas e do período Amarniano na história egípcia.
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
  