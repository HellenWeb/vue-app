<template>
<footer class="footer">
  <div class="container">
    <div class="footer__inner">
      <a>Copyright By. Hellen</a>
    </div>
  </div>
</footer>
</template>

<script>
export default {
  name: "MainFooter"
}
</script>

<style scoped>
footer {
    background: whitesmoke;
    height: 70px;
    width: 100%;
    position: absolute;
    bottom: 0;
}
a {
    text-decoration: none;
}
.footer__inner {
    margin-top: 25px;
    display: flex;
    justify-content: center;
}
.footer__inner a {
    color: black;
    text-decoration: none;
}
.intro__inner {
    margin: 10% 0;
}
</style>