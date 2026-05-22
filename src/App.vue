<template>
  <div class="container">
    <h1 class="title">Aniversário do Wesley</h1>
    <img src="./banco.gif" alt="GIF animado" class="gif" />
    <div
      style="margin-left: 20px; margin-right: 20px; margin-top: -50px"
      class="description"
    >
      <p>
        Meu aniversário é no dia <strong>22 de maio</strong>, mas a comemoração
        será em:
      </p>
      <br />
      <p style="margin-bottom: 10px">
        📅 Data: 23 de maio de 2026 <br />
        (sábado)
      </p>

      <p style="margin-bottom: 10px">
        📍 Local:
        <a
          href="https://maps.app.goo.gl/H3HimKr8EpdnXUMK9"
          target="_blank"
          class="location-link"
          >Imua Ceará Vaa - Canoe Club</a
        >
      </p>

      <p style="margin-bottom: 10px">⏰ Horário: 5h00</p>
    </div>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style scoped>
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  height: 100vh;
  text-align: center;
}

.title {
  font-size: 2rem;
  margin-bottom: -50px;
  color: #ffffff;
  z-index: 999999;
}

.gif {
  max-width: 510px;
}

.description {
  font-size: 1.2rem;
  color: #ffffff;
}

.location-link {
  color: #ffffff;
  text-decoration: none;
}
</style>
