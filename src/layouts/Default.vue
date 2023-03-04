<template>
  <div class="layout">
    <header class="header">
      <section data-bs-version="5.1" class="menu menu1 boldm5 cid-ttRnktJ11Q" once="menu" id="menu1-0">



        <nav class="navbar navbar-dropdown navbar-expand-lg">
          <div class="menu_box container-fluid">
            <div class="navbar-brand d-flex d-lg-none">
              <span class="navbar-logo">
                <a href="../index.html">
                  <img src="../assets/images/logo.png" alt="">
                </a>
              </span>

            </div>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-bs-toggle="collapse"
              data-target="#navbarSupportedContent" data-bs-target="#navbarSupportedContent"
              aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
              <div class="hamburger">
                <span></span>
                <span></span>
                <span></span>
                <span></span>
              </div>
            </button>
            <div class="collapse navbar-collapse" id="navbarSupportedContent">
              <div class="navbar-brand d-none d-lg-flex">
                <span class="navbar-logo">
                  <a href="/">
                    <img src="../assets/images/oscarlogo-100x63.png" alt="Oscar Commerce">
                  </a>
                </span>

              </div>
              <ul class="navbar-nav nav-dropdown nav-right" data-app-modern-menu="true">
                <li class="nav-item"><a class="nav-link link text-primary display-4" href="../index.html">Home</a></li>

                <li class="nav-item"><a class="nav-link link text-primary display-4"
                    href="http://docs.oscarcommerce.com/en/latest/">Documentation</a></li>
                <li class="nav-item"><a class="nav-link link text-primary display-4" href="/cases">Cases</a></li>
                <li class="nav-item"><a class="nav-link link text-primary display-4" href="/contact">Contact Us</a></li>
              </ul>
              <div class="icons-menu-main">
                <a class="iconfont-wrapper" href="#" target="_blank">
                  <span class="p-2 mbr-iconfont socicon-facebook socicon"></span>
                </a>



              </div>


              <div class="offcanvas_box">
                <button class="btn_offcanvas" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight"
                  aria-controls="offcanvasRight">
                  <div class="hamburger">
                    <span></span>
                    <span></span>
                  </div>
                </button>
                <div class="offcanvas offcanvas-end" tabindex="-1" id="offcanvasRight"
                  aria-labelledby="offcanvasRightLabel">
                  <div class="offcanvas-header">
                    <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas"
                      aria-label="Close"></button>
                  </div>
                  <div class="offcanvas-body">

                    <p class="mbr-text mbr-fonts-style display-4">Oscar is an open-source ecommerce framework for
                      Django.&nbsp;<br></p>
                    <div class="offcanvas_contact">
                      <h3 class="mbr-section-subtitle mbr-fonts-style display-5">
                        <a href="https://twitter.com/django_oscar" class="text-primary"
                          target="_blank">OscarCommerce</a></h3>

                    </div>
                    <div class="icons-menu">
                      <a class="iconfont-wrapper" href="https://twitter.com/django_oscar" target="_blank">
                        <span class="p-2 mbr-iconfont socicon-twitter socicon"></span>
                      </a>



                    </div>

                  </div>
                </div>
              </div>
            </div>
          </div>
        </nav>
      </section>
    </header>
    <slot />
  </div>
</template>

<static-query>
  query {
  metadata {
  siteName
  }
  }
</static-query>

<style>

</style>