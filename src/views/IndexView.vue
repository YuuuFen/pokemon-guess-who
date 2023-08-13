<script setup>
</script>

<template>
  <div class="container">
    <main class="main-section">
      <div class="image-container"><img src="https://fakeimg.pl/350x350/37B0DB/000"></div>
      <div class="infomation-container">
        <div class="title-container">
          <div class="title-content">？？？</div>
          <div class="title-content">我是誰</div>
        </div>
        <div class="logo-container">
          <div class="logo-content">ポケモンモンスター</div>
          <div class="logo-description">Pocket Monster</div>
        </div>
      </div>
    </main>
  </div>
</template>

<style scoped lang="scss">
.container {
  height: 100vh;
  background-color: #152346;
}

.main-section {
  padding: 6rem 10rem;
  display: flex;
}

.image-container {
  img {
    border: 0.5rem solid #fff;
    object-fit: cover;
  }
}

.infomation-container{
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.title-container {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  font-weight: 700;
  font-size: 3rem;
  color: yellow
}

.title-content {
  display: flex;
  justify-content: center;
}

.logo-container{
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.logo-content {
  display: flex;
  justify-content: center;
  font-weight: 700;
  font-size: 3rem;
  color: #00AD52
}

.logo-description {
  display: flex;
  justify-content: center;
  font-weight: 700;
  font-size: 1.5rem;
  color: #ffffff
}
</style>