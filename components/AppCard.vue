<template>
    <div>
        <div class="col-sm-12 col-md-12 col-lg-10 col-xl-10 col-12 position-absolute">
            <div class="bg-custom position-absolute"
                style="height: 100px; width: 100%; border-bottom: 2px solid #DCDCDC"></div>
        </div>
        <div class="col-12">
            <div class="container-fluid row row-cols-auto justify-content-center align-items-center mx-0">
                <div class="col-xl-4 py-3">
                    <div class="card shadow bg-gradienting" style="min-width: 330px; height: 200px">
                        <div class="card-body d-flex flex-column justify-content-between">
                            <div class="d-flex justify-content-between align-items-center">
                                <h6>Your Working Balance</h6>
                                <h6 class="text-muted text-decoration-underline">
                                    Saving Account
                                </h6>
                            </div>
                            <div class="d-flex justify-content-around align-items-baseline">
                                <h3>PKR 9,250,000</h3>
                                <span style="font-size: 14px; font-weight: bold">
                                    PKR
                                </span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-xl-4 py-3">
                    <div class="card shadow bg-pinkour" style="min-width: 330px; height: 200px">
                        <div class="card-body d-flex flex-column justify-content-between">
                            <div class="d-flex justify-content-between align-items-center">
                                <h6>Your Saving Status</h6>
                                <div class="d-flex justify-content-center align-items-center text-white"
                                    style="width: 30px; height: 30px; border-radius: 50%; background-color: grey">
                                    <h6>?</h6>
                                </div>
                            </div>
                            <div class="d-flex gap-3 align-items-center">
                                <div class="bg-redie d-flex justify-content-center align-items-center"
                                    style="width: 60px; height: 60px; border-radius: 50%">
                                    <BsBox size="1.5em" />
                                </div>
                                <div>
                                    <h4>4.28%</h4>
                                    <span style="font-size: 14px; font-weight: bold">
                                        Your spending increased
                                    </span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="col-xl-4 py-3">
                    <div class="card shadow bg-greenie" style="min-width: 330px; height: 200px">
                        <div class="card-body d-flex flex-column justify-content-between">
                            <div class="d-flex">
                                <div class="position-absolute bg-dark"
                                    style="width: 30px; height: 30px; border-radius: 50%"></div>
                                <div style="width: 30px; height: 30px; border-radius: 50%; background-color: grey; margin-left: 20px"></div>
                            </div>
                            <div class="d-flex flex-column align-items-baseline">
                                <h6 class="text-muted">Card Number</h6>
                                <h5>3829 4820 4629 5025</h5>
                            </div>
                            <div class="d-flex justify-content-between align-items-baseline">
                                <div>
                                    <span class="text-muted" style="font-size: 12px">CARD HOLDER NAME</span>
                                    <h5>Anita Rose</h5>
                                </div>
                                <div>
                                    <span class="text-muted" style="font-size: 12px">VALID THRU</span>
                                    <h5>09/17</h5>
                                </div>
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
    name: "AppCard",

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