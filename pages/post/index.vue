<template>
  <div class="post-container">
    <header class="post-head">
      <h1>
        Немецкую компанию Siemens, которая в одностороннем порядке приостановила поставки скоростных поездов «Сапсан» в Россию
      </h1>
    </header>
    <div class="logo-wrapper">
      <img src="/images/econom_logo.jpeg" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: "index"
}
</script>

<style scoped lang="scss">
  .post-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    padding: 20px;

    .post-head {
      width: 85%;
    }

    .logo-wrapper {
      width: 100%;
      >img {
        width: 100%;
      }
    }
  }
</style>
