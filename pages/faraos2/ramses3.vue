<template>
    <div class="relative bg-white text-black flex flex-col md:flex-row min-h-screen overflow-hidden">
  
      <!-- Conteúdo esquerdo (imagem) -->
      <div class="w-full h-screen md:w-1/2 md:h-auto overflow-hidden">
        <img src="/public/faraos2/ramses3.jpg" class="w-full h-full object-cover" />
      </div>
           
      <div class="w-full md:w-1/2 p-4 md:p-8 flex flex-col justify-center bg-yellow-100">
        <h1 class="text-2xl md:text-4xl font-bold mb-8 md:mb-10 mt-1 text-center">
            Ramsés III
        </h1>
  
        <div class="mb-4 text-center">
          <label class="mb-2 text-l">
            Ramsés III, um dos faraós mais notáveis do Egito Antigo, governou durante o período do Novo Império, especificamente na 20ª Dinastia, de 1186 a 1155 a.C. Ele é frequentemente considerado o último grande faraó do Egito, conhecido por suas batalhas defensivas e projetos de construção.


            Ramsés III era filho de Setnakhte, o fundador da 20ª Dinastia. Ele subiu ao trono após a morte de seu pai e herdou um Egito que enfrentava desafios internos e externos significativos. Ramsés III adotou o nome de seu famoso antecessor, Ramsés II, na esperança de restaurar a glória do Egito.
            <p class="mb-2 text-l">
                Liderança Militar: Ramsés III foi um líder militar formidável. Ele liderou campanhas contra os líbios e os Povos do Mar, que representavam uma séria ameaça ao Egito. Suas vitórias militares garantiram a segurança das fronteiras egípcias e fortaleceram o prestígio do faraó.
                Construções Monumentais: Durante seu reinado, foram construídos diversos monumentos grandiosos, como o templo funerário de Medinet Habu, um dos mais bem preservados do Egito. Esse templo contém inúmeras cenas detalhadas de suas campanhas militares e da vida cotidiana no Egito.
                Administração: Ramsés III implementou uma administração eficiente, garantindo a distribuição de alimentos e a manutenção de grandes projetos de construção.
            </p>
            <p class="mb-2 text-l">
                Uma das curiosidades mais fascinantes sobre Ramsés III é a maneira como ele morreu. Análises recentes da múmia do faraó revelaram que ele foi vítima de um complô, possivelmente envolvendo membros de sua própria família. A descoberta de cortes profundos em seu pescoço indica que ele foi assassinado.

                Essa descoberta trouxe à tona uma história dramática sobre a vida na corte egípcia e os perigos da política. A morte violenta de Ramsés III, um dos governantes mais poderosos de seu tempo, mostra que mesmo os faraós não estavam imunes às intrigas e conspirações.
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
  