<template>

    <nav class="navbar navbar-expand-lg p-0 m-0" id="navbar" >
        <div class="container p-0 m-0">
            <button class="navbar-toggler" @click="toggleNavbar" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon" :style="{ backgroundImage: 'url(' + navbarIcon + ')' }"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav" :class="{ 'show': isNavbarOpen }">
                <ul class="navbar-nav ml-auto">
                <li class="nav-item">
                    <router-link class="nav-link px-4" to="/" @click="closeNavbar">
                    Home
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link px-4" to="/about" @click="closeNavbar">
                    About
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link px-4" to="/skills" @click="closeNavbar">
                    Skills
                    </router-link>
                </li>
                <li class="nav-item">
                    <router-link class="nav-link px-4" to="/portfolio" @click="closeNavbar">
                    Portfolio
                    </router-link>
                </li>
                </ul>
            </div>
        </div>
    </nav>

</template>

<script>

export default {
    name: "NavBar",
    data() {
        return {
            isNavbarOpen: false,
            navbarIcon: require('@/assets/images/menu.svg')
        };
    },
    methods: {
        toggleNavbar() {
            this.isNavbarOpen = !this.isNavbarOpen;
            this.navbarIcon = this.isNavbarOpen ? require('@/assets/images/close.svg') : require('@/assets/images/menu.svg');
        },
        closeNavbar() {
            this.isNavbarOpen = false;
            this.navbarIcon = require('@/assets/images/menu.svg');
        }
    }
};
</script>

<style>

</style>