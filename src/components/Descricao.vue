<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Desenvolvedor Full Stack |
      <a href="mailto:alerrandrokaton@gmail.com" target="_blank" rel="noopener">E-mail</a> |
      <a href="https://github.com/alerrandro1999" target="_blank" rel="noopener">GitHub</a> |
      <a href="https://api.whatsapp.com/send?phone=+559499267-8728&amp;text=Olá tudo bem?" target="_blank" rel="noopener">WhatsApp</a>
    </h3>
  </div>
</template>

<style scoped>
.green {
  font-weight: 500;
  font-size: 30px;
  top: -10px;
}

h3 {
  font-size: 1rem;
  color: #fff;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1{
    text-align: left;
    font-size: 3rem;
  }
  .greetings h3 {
    text-align: left;
    font-size: 1.3rem;
  }
}
</style>
