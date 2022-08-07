<template>
  <header class="col-12 p-3 bg-custom body-header">
    <div class="container-fluid d-flex justify-content-between flex-row">
      <div class="d-flex flex-row flex-nowrap align-items-center justify-content-center gap-2">
        <button data-bs-toggle="offcanvas" data-bs-target="#offcanvasRight" aria-controls="offcanvasRight"
          class="d-xl-none d-lg-none d-md-block d-block navbar-toggle">
          <BsList size="1.5em" />
        </button>
        <form action="">
          <input type="search" name="" id="" class="form-control form-control-dark" placeholder="Search" />
        </form>
      </div>

      <div class="d-flex flex-row d-none d-lg-block d-xl-block">
        <ul class="list-group list-group-horizontal">
          <li class="list-group-item">
            <a href="/" class="text-black">
              <BsFileEarmark size="1.2em" />
            </a>
          </li>
          <li class="list-group-item">
            <a href="/" class="text-black">
              <BsArchive size="1.2em" />
            </a>
          </li>
          <li class="list-group-item">
            <a href="/" class="text-black">
              <BsThreeDotsVertical size="1.2em" />
            </a>
          </li>
        </ul>
      </div>

      <div class="d-flex flex-row d-none d-lg-block d-xl-block">
        <ul class="list-group list-group-horizontal">
          <li class="list-group-item">
            <a href="/" class="text-decoration-none text-muted">
              <span>Wallet</span>
            </a>
          </li>
          <li class="list-group-item">
            <a href="/" class="text-decoration-none text-muted">
              <span>Invoice</span>
            </a>
          </li>
        </ul>
      </div>

      <div class="d-flex flex-row justify-content-center align-items-center">
        <h6 class="m-0 mx-2 text-nowrap">Hi, Sakhir</h6>
        <div class="shadow bg-dark" style="width: 30px; height: 30px; border-radius: 5px"></div>
      </div>
    </div>
  </header>
</template>

<script>
import Vue from "vue"
import { BootstrapVue, IconsPlugin } from "bootstrap-vue"

// Import Bootstrap and BootstrapVue CSS files (order is important)
import "bootstrap/dist/css/bootstrap.css"
import "bootstrap-vue/dist/bootstrap-vue.css"

// Make BootstrapVue available throughout your project
Vue.use(BootstrapVue)
// Optionally install the BootstrapVue icon components plugin
Vue.use(IconsPlugin)
export default {
  name: "AppHeader",

}
</script>

<style>
.sidebar {
  height: 100%;
}

h1,
h2,
h3,
h4,
h5,
h6,
p {
  margin: 0 !important;
  padding: 0 !important;
}

.bg-custom {
  background-color: #f8f8ff;
}

.bg-greyde {
  background: rgb(203, 203, 203);
  background: linear-gradient(90deg,
      rgba(203, 203, 203, 1) 0%,
      rgba(203, 203, 203, 1) 51%,
      rgba(203, 203, 203, 1) 100%);
}

.bg-gradienting {
  background: rgb(255, 225, 255);
  background: linear-gradient(90deg,
      rgba(255, 225, 255, 1) 0%,
      rgba(255, 230, 254, 1) 33%,
      rgba(230, 225, 255, 1) 100%);
}

.bg-pinkour {
  background: rgb(255, 251, 225);
  background: linear-gradient(90deg,
      rgba(255, 251, 225, 1) 0%,
      rgba(255, 230, 254, 1) 51%,
      rgba(255, 225, 255, 1) 100%);
}

.bg-greenie {
  background: rgb(225, 255, 225);
  background: linear-gradient(90deg,
      rgba(225, 255, 225, 1) 0%,
      rgba(230, 255, 231, 1) 51%,
      rgba(225, 255, 226, 1) 100%);
}

.bg-redie {
  background: rgb(255, 225, 225);
  background: linear-gradient(90deg,
      rgba(255, 225, 225, 1) 0%,
      rgba(255, 230, 230, 1) 51%,
      rgba(255, 225, 225, 1) 100%);
}

.list-group-item {
  background-color: transparent !important;
  border: none !important;
}

.navbar-toggle {
  background: rgb(203, 203, 203);
  background: linear-gradient(90deg,
      rgba(203, 203, 203, 1) 0%,
      rgba(203, 203, 203, 1) 51%,
      rgba(203, 203, 203, 1) 100%);
  border: none !important;
}

.self-place-center {
  place-self: center;
}
</style>