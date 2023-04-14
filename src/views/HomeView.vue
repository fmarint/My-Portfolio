<template>
  <div id="wrapper">
    <!-- begin Header -->
    <Header />
    <!-- begin Header -->

    <!-- content begin -->
    <main class="no-bottom no-top" id="content">
      <div id="top"></div>

      <!-- page preloader begin -->
      <div id="preloader">
        <div class="preloader1"></div>
      </div>
      <!-- page preloader close -->

      <!-- float text begin -->
      <FloatSocialIcons />
      <!-- float text end -->

      <!-- load external content begin -->
      <div id="de_modal">
        <button class="button-close"></button>
        <div class="d-modal-loader">HOLAAA</div>
      </div>
      <!-- load external content close -->

      <Iam />

      <AboutMe />

      <MyQuote />

      <Services />

      <Portfolio />

      <Resume />

      <Counter />

      <Blog />

      <Contact />
    </main>
    <!-- content close -->

    <a href="#" id="back-to-top"></a>
    <!-- footer begin -->
    <footer>
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <a href="/">
              <span class="copy"
                >©Copyright ECONOMIC Todos los derechos reservados.</span
              >
            </a>
          </div>
          <div class="col-md-6">
            <div class="social-icons">
              <a href="#"><i class="fa fa-facebook fa-lg"></i></a>
              <a href="#"><i class="fa fa-twitter fa-lg"></i></a>
              <a href="#"><i class="fa fa-linkedin fa-lg"></i></a>
              <a href="#"><i class="fa fa-pinterest fa-lg"></i></a>
              <a href="#"><i class="fa fa-rss fa-lg"></i></a>
            </div>
          </div>
        </div>
      </div>
    </footer>
    <!-- footer close -->
  </div>
</template>

<script>
import AboutMe from "../components/AboutMe.vue";
import Blog from "../components/Blog.vue";
import Contact from "../components/Contact.vue";
import Counter from "../components/Counter.vue";
import FloatSocialIcons from "../components/FloatSocialIcons.vue";
import Header from "../components/Header.vue";
import Iam from "../components/Iam.vue";
import MyQuote from "../components/MyQuote.vue";
import Portfolio from "../components/Portfolio.vue";
import Resume from "../components/Resume.vue";
import Services from "../components/Services.vue";

export default {
  components: {
    Header,
    FloatSocialIcons,
    Iam,
    AboutMe,
    Services,
    MyQuote,
    Portfolio,
    Resume,
    Counter,
    Blog,
    Contact,
  },
};
</script>
<style>
</style>