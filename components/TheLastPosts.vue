<template>
  <section class="common-section">
    <header class="section-header">
      <div class="container">
        <span>Our Blog</span>
        <h2>Latest News</h2>
      </div>
    </header>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="post-item">
            <figure class="post-thumb">
              <img src="~/assets/images/posts/post-01.png" alt="post- 1" />
            </figure>
            <div class="post-details">
              <NuxtLink to="/single">
                <h4>Holiday Digital Marketing Trends for the 2022 Season</h4>
              </NuxtLink>
              <div class="post-time">
                <p>8 Min Read</p>
                <p class="divider-line"></p>

                <p>June 16, 2022</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="post-item">
            <figure class="post-thumb">
              <img src="~/assets/images/posts/post-02.png" alt="post-2" />
            </figure>
            <div class="post-details">
              <NuxtLink to="/single">
                <h4>How To Rock Your Content Management Process</h4></NuxtLink
              >
              <div class="post-time">
                <p>8 Min Read</p>
                <p class="divider-line"></p>

                <p>June 16, 2022</p>
              </div>
            </div>
          </div>
        </div>

        <div class="col-md-4">
          <div class="post-item">
            <figure class="post-thumb">
              <img src="~/assets/images/posts/post-03.png" alt="post-3" />
            </figure>
            <div class="post-details">
              <NuxtLink to="/single">
                <h4>
                  What the New Google Search Essentials Tell Us About SEO
                </h4></NuxtLink
              >
              <div class="post-time">
                <p>8 Min Read</p>
                <p class="divider-line"></p>

                <p>June 16, 2022</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default { name: "TheLastPosts", layout: "component" };
</script>

<style></style>
