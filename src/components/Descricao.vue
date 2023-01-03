<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Desenvolvedor Back-End |
      <a href="alerrandrokaton@gmail.com" target="_blank" rel="noopener">E-mail</a> |
      <a href="https://github.com/alerrandro1999" target="_blank" rel="noopener">GitHub</a> |
      <a href="https://api.whatsapp.com/send?phone=+559499267-8728&amp;text=Olá tudo bem?" target="_blank" rel="noopener">WhatsApp</a>
    </h3>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
  color: #fff;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
