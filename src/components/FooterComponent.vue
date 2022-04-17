<template>
  <footer class="my-3 py-3">
    <div class="container">
      <div class="row">
        <div class="col-lg-12">
          <div class="wrapper border-bottom-3px">
            <div class="menu">
              <div class="d-block d-lg-flex align-items-lg-center pb-4 w-100">
                <router-link class="text-decoration-none d-block mx-5 ms-lg-0 me-5 text-uppercase" to="#">mail
                </router-link>
                <router-link class="text-decoration-none d-block mx-5 text-uppercase" to="#">twitter</router-link>
                <router-link class="text-decoration-none d-block mx-5 text-uppercase" to="#">linkedin</router-link>
              </div>
            </div>
          </div>
        </div>
        <div class="col-lg-12">
          <div class="wrapper position-relative w-110px mx-auto mx-lg-0">
            <svg version="1.1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px"
              y="0px" width="200px" height="200px" viewBox="0 0 300 300" enable-background="new 0 0 300 300"
              xml:space="preserve">
              <defs>
                <path id="circlePath" d=" M 80, 150 m -60, 0 a 60,60 0 0,1 120,0 a 60,60 0 0,1 -120,0 " />
              </defs>
              <circle cx="150" cy="100" r="75" fill="none" />
              <g>
                <use xlink:to="#circlePath" fill="none" />
                <text fill="#000">
                  <textPath class="fw-bold" xlink:to="#circlePath">Bullet with text - Bullet with text - Bullet with
                    text</textPath>
                </text>
              </g>
            </svg>
            <i class="fs-3 fab fa-app-store-ios position-absolute top-50 start-50 translate-middle"></i>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<script>
export default {
  name: "FooterComponent",
}
</script>