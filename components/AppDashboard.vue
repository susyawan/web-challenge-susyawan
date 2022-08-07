<template>
    <div>
        <div class="row p-0 m-0">
            <AppSidebar />
            <div class="col-sm-10 col-md-10 col-lg-10 col-xl-10 col-12 p-0">
                <AppHeader />
                <AppCard />
                <AppTask />
                <AppTransaction />
            </div>
        </div>
    </div>
</template>

<script>
import AppSidebar from '../components/AppSidebar'
import AppCard from '../components/AppCard'
import AppHeader from '../components/AppHeader.vue'
import AppTask from '../components/AppTask.vue'
import AppTransaction from '../components/AppTransaction.vue'
import Vue from 'vue'
import { BootstrapVue, IconsPlugin } from 'bootstrap-vue'

// Import Bootstrap and BootstrapVue CSS files (order is important)
import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'

// Make BootstrapVue available throughout your project
Vue.use(BootstrapVue)
// Optionally install the BootstrapVue icon components plugin
Vue.use(IconsPlugin)

export default {
    name: 'AppDashboard',
    components: {
        AppSidebar,
        AppCard,
        AppHeader,
        AppTask,
        AppTransaction
    }
}
</script>

<style>
</style>