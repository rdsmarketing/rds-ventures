<template>
  <Layout>
    <!-- Learn how to use images here: https://gridsome.org/docs/images -->
    <g-image alt="Example image" src="~/favicon.png" width="135" />

    <h1>Welcome To RDS-Ventures</h1>

    <p>We are a proffesional Technology Company with over 2 decades of Industry expierence among our C-Level executives.</p>
    <div>
      <h2>What We Do</h2>
      <p>Our organization provides high level consulting and engeineering for various technloogical projects specfically in web development.</p>
    </div>
    <div>
      <h2>Who We Serve</h2>
      <p>We work with organizations of all shapes and sizes however we specialize in providing effieicient and on-time results for goverment agencies at the federal and state level.</p>
    </div>
    <div>
      <h2>Why Choose Us?</h2>
      <p>We are experts in our field.</p>
    </div>

    <p class="home-links">
      <a href="https://gridsome.org/docs/" target="_blank" rel="noopener">Gridsome Docs</a>
      <a href="https://github.com/gridsome/gridsome" target="_blank" rel="noopener">GitHub</a>
    </p>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: "RDS Ventures Corporate Homepage",
    description:
      "We are a proffesional Technology Company with over 2 decades of Industry expierence among our C-Level executives."
  }
};
</script>

<style>
.home-links a {
  margin-right: 1rem;
}
</style>
