<template>
  <div class="col-12 justify-content-center py-4" id="transactions">
    <div class="container-fluid row row-cols-auto m-0">

      <div class="col-xl-7 col-lg-7 col-md-12 col-sm-12 col-12 p-3 bg-custom" style="border-radius: 5px">
        <div class="d-flex flex-column gap-4">
          <div class="d-flex justify-content-between align-items-center">
            <h4>Latest Transactions</h4>
            <ul class="list-group list-group-horizontal">
              <li class="list-group-item">
                <a href="/" class="text-black">
                  <BsSearch />
                </a>
              </li>
              <li class="list-group-item">
                <a href="/" class="text-black">
                  <BsToggles />
                </a>
              </li>
            </ul>
          </div>

          <div class="d-flex flex-column gap-3">
            <h6 class="text-muted">Mon, Mar 1</h6>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-greyde rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsBoxArrowRight />
                </div>
                <h6>Payment Sent to Shakir</h6>
              </div>
              <div>
                <h6 style="color: red">$560.00</h6>
              </div>
            </div>


            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-greyde rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsBoxArrowInLeft />
                </div>
                <h6>Salary from Redwhale</h6>
              </div>
              <div>
                <h6>$12,200.00</h6>
              </div>
            </div>


            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-greyde rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsForwardFill />
                </div>
                <h6>Money Sent to Wise.com</h6>
              </div>
              <div>
                <h6 style="color: red">$3,000.00</h6>
              </div>
            </div>
          </div>

          <div class="d-flex flex-column gap-3">
            <h6 class="text-muted">Mon, Mar 1</h6>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-greyde rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsBoxArrowRight />
                </div>
                <h6>Purchased Macbook Pro</h6>
              </div>
              <div>
                <h6 style="color: red">$560.00</h6>
              </div>
            </div>
          </div>
        </div>
      </div>


      <div class="col-xl-5 col-lg-5 col-md-12 col-sm-12 col-12 p-3">
        <div class="d-flex flex-column gap-4">
          <div class="d-flex justify-content-between align-items-center">
            <h4>Upcoming Transactions</h4>
            <ul class="list-group list-group-horizontal">
              <li class="list-group-item">
                <a href="/" class="text-black text-decoration-none">
                  View All
                </a>
              </li>
            </ul>
          </div>
          <div class="d-flex flex-column gap-3">
            <h6>Today</h6>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-primary rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsFillDropletFill />
                </div>
                <div>
                  <h6>Water Bill</h6>
                  <span class="text-muted" style="font-size: 14px">
                    Unsuccessfully
                  </span>
                </div>
              </div>
              <div>
                <h6 style="color: red">- $280.00</h6>
              </div>
            </div>
          </div>

          <div class="d-flex flex-column gap-3">
            <h6>Tomorrow</h6>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-danger rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsCurrencyDollar />
                </div>
                <div>
                  <h6>Income : Salary Oct</h6>
                  <span class="text-muted" style="font-size: 14px;">
                    Successfully
                  </span>
                </div>
              </div>
              <div>
                <h6>+ $1200.00</h6>
              </div>
            </div>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-info rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsPlugFill />
                </div>
                <div>
                  <h6>Electric Bill</h6>
                  <span class="text-muted" style="font-size: 14px">
                    Successfully
                  </span>
                </div>
              </div>
              <div>
                <h6 style="color: red">- $480.00</h6>
              </div>
            </div>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-warning rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsReceipt />
                </div>
                <div>
                  <h6>Income : Jane transfers</h6>
                  <span class="text-muted" style="font-size: 14px">
                    Successfully
                  </span>
                </div>
              </div>
              <div>
                <h6>+ $500.00</h6>
              </div>
            </div>

            <div class="d-flex justify-content-between align-items-center">
              <div class="d-flex justify-content-between align-items-center gap-2">
                <div class="bg-warning rounded d-flex justify-content-center align-items-center"
                  style="width: 35px; height: 35px">
                  <BsReceipt />
                </div>
                <div>
                  <h6>Income : Jane transfers</h6>
                  <span class="text-muted" style="font-size: 14px">
                    Successfully
                  </span>
                </div>
              </div>
              <div>
                <h6>+ $500.00</h6>
              </div>
            </div>
          </div>
        </div>
      </div>
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
  name: "AppTransaction",

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