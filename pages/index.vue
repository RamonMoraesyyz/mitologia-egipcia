<template>
  <head>
    <link rel="icon" type="image/png" href="/static/helmet.png">
  </head>
  <div class="relative flex items-center justify-center min-h-screen bg-cover bg-center" style="background-image: url('/welcome.jpg');">
    <div class="text-center p-8 text-white max-w-3xl mx-auto bg-black bg-opacity-70 rounded-lg">
      <h1 class="text-7xl mb-8 drop-shadow-lg">Mitologia Egípcia</h1>
      <p class="text-2xl drop-shadow-lg leading-relaxed">
        A mitologia egípcia é um conjunto fascinante de crenças e histórias desenvolvidas ao longo de milênios no antigo Egito. Ela envolve um complexo panteão de deuses e deusas, cada um responsável por diferentes aspectos da vida e do universo, como Ra (o deus do sol), Osíris (o deus do submundo e da ressurreição), Ísis (a deusa da fertilidade e da maternidade), e Anúbis (o deus da mumificação e dos mortos).
        <br/><br/>
        Os mitos egípcios eram frequentemente representados em textos sagrados, templos, túmulos e monumentos. Entre os textos mais famosos estão o "Livro dos Mortos", que detalha o julgamento das almas no além, e a "História de Ísis e Osíris", que conta sobre a morte e ressurreição de Osíris, simbolizando a promessa de vida após a morte.
      </p>
    </div>
  </div>
</template>

<style scoped>
.bg-cover {
  background-size: cover;
}

.bg-center {
  background-position: center;
}

.drop-shadow-lg {
  text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
}

.bg-opacity-50 {
  background-color: rgba(0, 0, 0, 0.5);
}

.leading-relaxed {
  line-height: 1.75;
}

.rounded-lg {
  border-radius: 0.5rem;
}
</style>
