<template>
  <footer>
    <h2>Drop me a message.</h2>
    <p>
      If you want to hire me for a project, chat with me about music, art or
      else, or get a coffee, feel free to send me a message via
      <a href="https://twitter.com/yannickvdthoren">twitter</a> or by
      <a href="mailto:yannickvdthoren@gmail.com">email</a>.
    </p>
    <ul class="social">
      <li>
        <a href=""><Twitter /></a>
      </li>
      <li>
        <a href=""><Linkedin /></a>
      </li>
      <li>
        <a href=""><Dribbble /></a>
      </li>
      <li>
        <a href=""><Pinterest /></a>
      </li>
      <li>
        <a href=""><Instagram /></a>
      </li>
    </ul>
  </footer>
</template>
<script>
export default {
  name: 'Footer',
}
</script>
<style scoped>
.social {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 16px;
  margin-top: 48px;
}
.social svg {
  width: 16px;
}
</style>