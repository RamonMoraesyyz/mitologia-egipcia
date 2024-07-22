<template>
  <div id="app">

    <header class="main-header" style="background-color: black; color: white;">
      <nav class="nav-links">
        
        <div class="dropdown" @mouseenter="dropdownOpenTitans = true" @mouseleave="dropdownOpenTitans = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenTitans">
            <b>Deuses</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenTitans" aria-labelledby="dropdownMenuTitans">
            <router-link class="dropdown-item" to="/deuses/amon">Amon</router-link>
            <router-link class="dropdown-item" to="/deuses/anubis">Anúbis</router-link>
            <router-link class="dropdown-item" to="/deuses/atum">Atum</router-link>
            <router-link class="dropdown-item" to="/deuses/bastet">Bastet</router-link>
            <router-link class="dropdown-item" to="/deuses/hathor">Hathor</router-link>
            <router-link class="dropdown-item" to="/deuses/horus">Hórus</router-link>
            <router-link class="dropdown-item" to="/deuses/isis">Ísis</router-link>
            <router-link class="dropdown-item" to="/deuses/maat">Ma'at</router-link> 
            <router-link class="dropdown-item" to="/deuses/Nephthys">Nephthys</router-link>
            <router-link class="dropdown-item" to="/deuses/nut">Nut</router-link>
            <router-link class="dropdown-item" to="/deuses/osiris">Osíris</router-link>
            <router-link class="dropdown-item" to="/deuses/ptah">Ptah</router-link>
            <router-link class="dropdown-item" to="/deuses/ra">Rá</router-link>
            <router-link class="dropdown-item" to="/deuses/sekhmet">Sekhmet</router-link>
            <router-link class="dropdown-item" to="/deuses/set">Set</router-link>
            <router-link class="dropdown-item" to="/deuses/sobek">Sobek</router-link>
            <router-link class="dropdown-item" to="/deuses/thoth">Thoth</router-link>
            <router-link class="dropdown-item" to="/deuses/geb">Geb</router-link>

            <!-- Adicione outros links dos Titãs aqui -->
          </div>
        </div>
        <div class="dropdown" @mouseenter="dropdownOpenGods = true" @mouseleave="dropdownOpenGods = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenGods">
            <b>Faraós</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenGods" aria-labelledby="dropdownMenuGods">
            <router-link class="dropdown-item" to="/faraos/narmer">Narmer</router-link>
            <router-link class="dropdown-item" to="/faraos/djoser">Djoser</router-link>
            <router-link class="dropdown-item" to="/faraos/sneferu">Sneferu</router-link>
            <router-link class="dropdown-item" to="/faraos/khufu">Khufu</router-link>
        
            
          </div>
        </div>
        <b><router-link to="/herois"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenHeroes = true" @mouseleave="dropdownOpenHeroes = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenHeroes">
            <b>Gigantes</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenHeroes" aria-labelledby="dropdownMenuHeroes">
            

            
            <!-- Adicione outros links dos Heróis aqui -->
          </div>
        </div>

        <div class="dropdown" @mouseenter="dropdownOpenHeros = true" @mouseleave="dropdownOpenHeros = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenHeros">
            <b>Heróis</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenHeros" aria-labelledby="dropdownMenuTitans">
           


            <!-- Adicione outros links dos Titãs aqui -->
          </div>
        </div>






        <b><router-link to="/monstros"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenMonsters = true" @mouseleave="dropdownOpenMonsters = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenMonsters">
            <b>Anões</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenMonsters" aria-labelledby="dropdownMenuMonsters">
            
            <!-- Adicione outros links dos Monstros aqui -->
          </div>
        </div>


        <b><router-link to="/locais"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenLocals = true" @mouseleave="dropdownOpenLocals = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenLocals">
            <b>Criaturas</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenLocals" aria-labelledby="dropdownMenuLocals">
            
            

          
          </div>
        </div>



        <b><router-link to="/aventuras"></router-link></b>
        <div class="dropdown" @mouseenter="dropdownOpenAdventures = true" @mouseleave="dropdownOpenAdventures = false">
          <button class="dropdown-toggle" type="button" aria-haspopup="true" :aria-expanded="dropdownOpenAdventures">
            <b>Locais</b>
          </button>
          <div class="dropdown-menu" v-show="dropdownOpenAdventures" aria-labelledby="dropdownMenuAdventures">
            

            <!-- Adicione outros links das Aventuras aqui -->
          </div>
        </div>
      </nav>
    </header>
    <!-- Renderiza o conteúdo da página atual -->
    <NuxtPage />
  </div>
</template>

<script>
export default {
  data() {
    return {
      dropdownOpenTitans: false,
      dropdownOpenGods: false,
      dropdownOpenHeroes: false,
      dropdownOpenHeros: false,
      dropdownOpenMonsters: false,
      dropdownOpenLocals: false,
      dropdownOpenAdventures: false,
    };
  },
};
</script>

<style scoped>
.main-header {
  padding: 10px;
 
}

.nav-links {
  display: flex;
  justify-content: space-between; /* Espaçamento entre os elementos */
  align-items: center; /* Centraliza verticalmente os elementos */
}

.dropdown-toggle {
  cursor: pointer;
  padding: 5px 10px;
  font-size: larger;
}

.dropdown-item {
  padding: 5px 10px;
  display: block;
  text-decoration: none;
  color: inherit;
}

.dropdown-menu {
  position: absolute;
  background-color: black; /* Define o fundo branco para o dropdown */
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1); /* Adiciona uma sombra suave */
  z-index: 1; /* Garante que o dropdown esteja acima dos demais elementos */
}

.dropdown-divider {
  margin: 5px 0;
  border-bottom: 1px solid #ccc;
}

/* Adicionado estilo para tornar o header responsivo */
@media screen and (max-width: 768px) {
  .nav-links {
    flex-direction: column; /* Altera a direção dos elementos para coluna */
  }

  .dropdown {
    margin-bottom: 10px; /* Adiciona espaçamento abaixo do dropdown */
  }
}

/* Espaçamento igual entre todos os botões */
.nav-links .left-buttons > * {
  margin-right: 5px; /* Espaçamento de 5px entre os botões do canto esquerdo */
}

</style>