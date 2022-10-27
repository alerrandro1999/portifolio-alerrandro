<script setup lang="ts">

</script>

<template>
    <section class="container">
      <h1>Alerrandro Borges</h1>
      <p>Desenvolvedor Web</p>
      <div class="icones">
        <img src="@/assets/php.svg" alt="">
        <img src="@/assets/laravel.svg" alt="">
        <img src="@/assets/html.svg" alt="">
        <img src="@/assets/css.svg" alt="">
        <img src="@/assets/github.svg" alt="">
        <img src="@/assets/git.svg" alt="">
      </div>
      <div class="contato">
        <a href="">&lt; contate-me /></a>
      </div>
    </section>
</template>

<style scoped>
  .container{
    background-color: rgba(0, 0, 0, 0.7);
    color: #fff;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    padding: 100px 200px;
    gap: 25px;
  }

  .container h1 {
    font-size: 70px;
  }

  .container p {
    font-size: 40px;
  }

  .container img {
    width: 60px;
    height: 60px;
    padding: 10px;
  }
  .container a {
    color: #fff;
    text-decoration: none;
    font-size: 25px;
  }

  a, p, h1{
    font-weight: 300;
  }

  @media (max-width: 1000px)
  {
    .container {
      padding: 70px 170px;
    }
    .container h1 {
      font-size: 40px;
    }
    .container p {
      font-size: 20px;
    }

    .container img {
      width: 40px;
      height: 40px;
    }

    .container a {
      font-size: 20px;
    }
  }

  

  @media (max-width: 700px)
  {
    .container {
      padding: 20px 20px;
    }
    .container h1 {
      font-size: 30px;
    }
    .container p {
      font-size: 20px;
    }

    .container img {
      width: 35px;
      height: 35px;
    }

    .container a {
      font-size: 15px;
    }
  }
</style>
