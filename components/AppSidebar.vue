<template>
    <nav class="col-2 p-0 offcanvas-lg offcanvas-end" tabIndex="-1" id="offcanvasRight"
        aria-labelledby="offcanvasRightLabel" style="border-right: 2px solid #DCDCDC">
        <div class="d-flex flex-column gap-5 p-3 bg-custom sidebar">
            <div class="offcanvas-header d-flex align-items-center self-place-center">
                <a href="/"
                    class="d-flex flex-row flex-md-row flex-lg-column flex-xl-row align-items-center gap-2 md-3 me-md-auto link-dark text-decoration-none">
                    <BsTriangleHalf size="40px" />
                    <h4 class="offcanvas-title text-nowrap" id="offcanvasResponsiveLabel">
                        Super Finti
                    </h4>
                </a>
            </div>

            <div class="offcanvas-body d-flex flex-column gap-4">
                <div class="d-flex align-items-center d-block d-lg-none d-xl-none">
                    <div class="d-flex flex-row">
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

                    <div class="d-flex flex-row">
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
                </div>

                <div>
                    <h5>Main Navigation</h5>
                    <ul class="nav nav-pills flex-column mb-auto mt-2">
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsFillGridFill />
                                    Dashboard
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsFullscreen />
                                    Transactions
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsFillXDiamondFill />
                                    Contacts
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsToggles />
                                    Features
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsStack />
                                    Library
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <h5>Settings &amp; Schedule</h5>
                    <ul class="nav nav-pills flex-column mb-auto mt-2">
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsBox />
                                    Base Wallet
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsFillFolderFill />
                                    My Contacts
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsMicFill />
                                    Invoices
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                        <li class="nav-item">
                            <a href="/" class="nav-link d-flex justify-content-between align-items-center">
                                <div class="d-flex align-items-center gap-2">
                                    <BsBatteryCharging />
                                    Schedules
                                </div>
                                <BsChevronRight />
                            </a>
                        </li>
                    </ul>
                </div>

                <div>
                    <div class="shadow position-relative d-flex flex-column align-items-center text-center py-3 pt-5 mt-4 bg-gradienting"
                        style="border-radius: 10px">
                        <div class="shadow-lg position-absolute d-flex bg-light justify-content-center align-items-center"
                            style="place-self: center; top: -30px; height: 60px; width: 60px; border-radius: 50%">
                            <div class="d-flex justify-content-center align-items-center text-white"
                                style="width: 30px; height: 30px; border-radius: 50%; background-color: tomato">
                                <span>?</span>
                            </div>
                        </div>
                        <div class="my-3">
                            <h5>Help Center</h5>
                            <p class="m-0">Having Trouble in Finti.</p>
                            <p>Please contact us for more question.</p>
                        </div>
                        <div class="shadow">
                            <button class="btn btn-secondary">Go To Help Center</button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </nav>
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
    name: "AppSidebar"
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