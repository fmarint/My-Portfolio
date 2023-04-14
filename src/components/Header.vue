<template>
  <header class="transparent">
    <div class="container">
      <div class="row">
        <div class="col-md-12">
          <div class="de-flex sm-pt10">
            <div class="de-flex-col">
              <div class="de-flex-col">
                <!-- logo begin -->
                <div id="logo">
                  <a href="index.html">
                    <img alt="" class="logo" src="../assets/images/logo.png" />
                    <img
                      alt=""
                      class="logo-2"
                      src="../assets/images/logo.png"
                    />
                  </a>
                </div>
                <!-- logo close -->
              </div>
            </div>
            <div class="de-flex-col header-col-right">
              <ul id="mainmenu">
                <LinkItem :isActive="true" text="Homee" href="#top" />
                <LinkItem href="#section-about" text="About me" />
                <LinkItem href="#section-services" text="What I Do" />
                <LinkItem href="#section-portfolio" text="Portfolio" />
                <LinkItem href="#section-resume" text="My Resume" />
                <LinkItem href="#section-blog" text="Blog" />
                <LinkItem href="#section-contact" text="Contact Me" />
              </ul>

              <div class="menu_side_area">
                <span id="menu-btn"></span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </header>
</template>

<script>

import LinkItem from './LinkItem.vue'

export default {
  components: {
      LinkItem,
    //   LinkItem: defineAsyncComponent(() => import("./LinkItem.vue")),
      },
};
</script>

<style>
</style>