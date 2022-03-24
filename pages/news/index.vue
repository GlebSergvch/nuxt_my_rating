<template>
  <div class="news-wrapper">
    <div class="blog-head">
      <h2>Новости</h2>
    </div>
    <div class="blog-content">
      <div class="blog-item">
        <div class="article-title">
          <h3 class="title">Новая новость</h3>
        </div>
        <div class="logo-content">
          <img src="/images/econom_logo.jpeg" alt="">
        </div>
        <div class="description-mini">
          Немецкую компанию Siemens, которая в одностороннем порядке приостановила поставки скоростных поездов «Сапсан» в Россию, могут заместить другие организации, заявила спикер Совета Федерации Валентина Матвиенко на встрече с главой РЖД в рамках «Открытого диалога» в верхней палате парламента, трансляция мероприятия шла на ее канале в Rutube.
        </div>
        <div class="article-info">
          <div class="info-item">
            <div class="info-date">
              20 марта 2022, 08:17
            </div>
          </div>
          <div class="info-item">
            <div class="info-views">
              10
            </div>
          </div>
          <div class="info-item">
            <div class="info-comment-count">
              10
            </div>
          </div>
        </div>
      </div>
      <div class="blog-item">
        <div class="article-title">
          <h3 class="title">Новая новость</h3>
        </div>
        <div class="logo-content">
          <img src="/images/econom_logo.jpeg" alt="">
        </div>
        <div class="description-mini">
          Немецкую компанию Siemens, которая в одностороннем порядке приостановила поставки скоростных поездов «Сапсан» в Россию, могут заместить другие организации, заявила спикер Совета Федерации Валентина Матвиенко на встрече с главой РЖД в рамках «Открытого диалога» в верхней палате парламента, трансляция мероприятия шла на ее канале в Rutube.
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
name: "index"
}
</script>

<style scoped lang="scss">
  .news-wrapper {
    display: flex;
    flex-wrap: wrap;
    flex-basis: 100%;
    width: calc(100vw - 8px);

    .blog-head, .logo-content {
      display: flex;
      justify-content: center;
      align-items: center;
      width: 100%;
    }

    .blog-content {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-wrap: wrap;
      width: 100%;
    }

    .blog-item {
      max-width: 800px;
      background: #676767;
      border-radius: 10px;
      padding: 25px;
      margin-bottom: 25px;
      cursor: pointer;

      .article-title {
        h3 {
          margin: 0;
          padding: 0.5rem;
        }
      }
    }

    .logo-content {
      img {
        width: 90%;
        border-radius: 5px;
      }
    }

    .description-mini {
      padding: 0.25rem;
      margin: 0 0 10px;
    }

    .article-info {
      display: inline-flex;
      justify-content: flex-start;

      .info-item {
        margin-right: 10px;
      }
    }
  }
</style>
