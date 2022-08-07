<template>
  <div class="col-12">
    <div class="container-fluid py-4">
      <hr />
      <div class="row row-cols-auto">
        <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12 col-12 d-flex justify-content-between align-items-center my-4">
          <div class="mx-3">
            <h6>Task In Progress</h6>
            <div class="d-flex gap-3 align-items-center">
              <h5 class="m-0 text-danger">210</h5>
              <a href="/" class="bg-info d-flex align-items-center text-decoration-none" style="border-radius: 20px">
                <span class="px-2 text-dark" style="font-size: 14px">
                  23&#x2197;
                </span>
              </a>
            </div>
            <span class="text-muted" style="font-size: 14px">
              Current Month
            </span>
          </div>
          <div class="d-flex mx-3 align-items-center gap-2">
            <div class="d-flex align-items-baseline gap-2">
              <div class="bg-greyde" style="width: 20px;height: 40px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 10px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 25px;border-radius: 4px;"></div>
              <div class="shadow bg-danger" style="width: 20px;height: 60px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 38px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 45px;border-radius: 4px;"></div>
            </div>
          </div>
        </div>


        <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12 col-12 d-flex justify-content-between align-items-center my-4">
          <div class="mx-3">
            <h6>Task Completed</h6>
            <div class="d-flex gap-3 align-items-center">
              <h5 class="m-0 text-primary">185</h5>
              <a href="/" class="bg-info d-flex align-items-center text-decoration-none" style="border-radius: 20px">
                <span class="px-2 text-dark" style="font-size: 14px">
                  45&#x2197;
                </span>
              </a>
            </div>
            <span class="text-muted" style="font-size: 14px">
              Current Month
            </span>
          </div>
          <div class="d-flex mx-3 align-items-center gap-2">
            <div class="d-flex align-items-baseline gap-2">
              <div class="bg-greyde" style="width: 20px;height: 22px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 38px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 30px;border-radius: 4px;"></div>
              <div class="shadow bg-primary" style="width: 20px;height: 60px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 38px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 20px;border-radius: 4px;"></div>
            </div>
          </div>
        </div>


        <div class="col-xl-4 col-lg-6 col-md-6 col-sm-12 col-12 d-flex justify-content-between align-items-center my-4">
          <div class="mx-3">
            <h6>Monthly Tasks Summary</h6>
            <div class="d-flex gap-3 align-items-center">
              <h5 class="m-0 text-success">1240</h5>
              <a href="/" class="bg-info d-flex align-items-center text-decoration-none" style="border-radius: 20px">
                <span class="px-2 text-dark" style="font-size: 14px">
                  145&#x2197;
                </span>
              </a>
            </div>
            <span class="text-muted" style="font-size: 14px">
              Current Month
            </span>
          </div>
          <div class="d-flex mx-3 align-items-center gap-2">
            <div class="d-flex align-items-baseline gap-2">
              <div class="bg-greyde" style="width: 20px;height: 45px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px;height: 22px;border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px; height: 40px; border-radius: 4px;"></div>
              <div class="shadow bg-success" style="width: 20px; height: 60px; border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px; height: 55px; border-radius: 4px;"></div>
              <div class="bg-greyde" style="width: 20px; height: 25px; border-radius: 4px;"></div>
            </div>
          </div>
        </div>
      </div>
      <hr />
    </div>
  </div>
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
  name: "AppTask",

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