<script>
import { RouterLink } from 'vue-router'
import VueLogo from './VueLogo.vue'
import Search from './Search.vue'

export default {
    name: 'NavBar',
    components: {
        VueLogo,
        Search
    }
}

</script>

<template>
    <nav>
        <div>
            <div class="nav-left-container">
                <RouterLink to="/" class="nav-left">
                    <VueLogo />
                </RouterLink>
                <Search />
            </div>

            <div class="nav-right-container">
                <button class="nav-dropdown">
                    <span>Docs</span>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-chevron-down" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M6 9l6 6l6 -6" /></svg>
                </button>
                <RouterLink to="/api" class="nav-right">
                    API
                </RouterLink>
                <RouterLink to="/playground" class="nav-right">
                    Playground
                </RouterLink>
                <button class="nav-dropdown">
                    <span>Ecosystem</span>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-chevron-down" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M6 9l6 6l6 -6" /></svg>
                </button>
                <button class="nav-dropdown">
                    <span>About</span>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-chevron-down" width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M6 9l6 6l6 -6" /></svg>
                </button>
                <RouterLink to="/sponsor" class="nav-right">
                    Sponsor
                </RouterLink>
                <RouterLink to="/partners" class="nav-right">
                    Partners
                </RouterLink>
                <picture>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-language" width="18"
                        height="18" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                        stroke-linecap="round" stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M4 5h7" />
                        <path d="M9 3v2c0 4.418 -2.239 8 -5 8" />
                        <path d="M5 9c0 2.144 2.952 3.908 6.7 4" />
                        <path d="M12 20l4 -9l4 9" />
                        <path d="M19.1 18h-6.2" />
                    </svg>
                </picture>
                <button class="toggle-theme">
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-sun" width="16" height="16"
                        viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"
                        stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M12 12m-4 0a4 4 0 1 0 8 0a4 4 0 1 0 -8 0" />
                        <path
                            d="M3 12h1m8 -9v1m8 8h1m-9 8v1m-6.4 -15.4l.7 .7m12.1 -.7l-.7 .7m0 11.4l.7 .7m-12.1 -.7l-.7 .7" />
                    </svg>
                    <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-moon" width="16" height="16"
                        viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"
                        stroke-linejoin="round">
                        <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                        <path d="M12 3c.132 0 .263 0 .393 0a7.5 7.5 0 0 0 7.92 12.446a9 9 0 1 1 -8.313 -12.454z" />
                    </svg>
                </button>
                <div class="social">
                    <a href="https://github.com/vuejs/">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-github" width="24"
                            height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path
                                d="M9 19c-4.3 1.4 -4.3 -2.5 -6 -3m12 5v-3.5c0 -1 .1 -1.4 -.5 -2c2.8 -.3 5.5 -1.4 5.5 -6a4.6 4.6 0 0 0 -1.3 -3.2a4.2 4.2 0 0 0 -.1 -3.2s-1.1 -.3 -3.5 1.3a12.3 12.3 0 0 0 -6.2 0c-2.4 -1.6 -3.5 -1.3 -3.5 -1.3a4.2 4.2 0 0 0 -.1 3.2a4.6 4.6 0 0 0 -1.3 3.2c0 4.6 2.7 5.7 5.5 6c-.6 .6 -.6 1.2 -.5 2v3.5" />
                        </svg>
                    </a>
                    <a href="https://twitter.com/vuejs">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-x" width="24"
                            height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path d="M4 4l11.733 16h4.267l-11.733 -16z" />
                            <path d="M4 20l6.768 -6.768m2.46 -2.46l6.772 -6.772" />
                        </svg>
                    </a>
                    <a href="https://discord.com/invite/HBherRA">
                        <svg xmlns="http://www.w3.org/2000/svg" class="icon icon-tabler icon-tabler-brand-discord"
                            width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path stroke="none" d="M0 0h24v24H0z" fill="none" />
                            <path d="M8 12a1 1 0 1 0 2 0a1 1 0 0 0 -2 0" />
                            <path d="M14 12a1 1 0 1 0 2 0a1 1 0 0 0 -2 0" />
                            <path
                                d="M15.5 17c0 1 1.5 3 2 3c1.5 0 2.833 -1.667 3.5 -3c.667 -1.667 .5 -5.833 -1.5 -11.5c-1.457 -1.015 -3 -1.34 -4.5 -1.5l-.972 1.923a11.913 11.913 0 0 0 -4.053 0l-.975 -1.923c-1.5 .16 -3.043 .485 -4.5 1.5c-2 5.667 -2.167 9.833 -1.5 11.5c.667 1.333 2 3 3.5 3c.5 0 2 -2 2 -3" />
                            <path d="M7 16.5c3.5 1 6.5 1 10 0" />
                        </svg>
                    </a>
                </div>
            </div>
        </div>
    </nav>
</template>

<style>
nav {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 13px 0;
    border-bottom: 1px solid #363636;
    position: fixed;
    top: 0;
    width: 100%;
    z-index: 1000;
    background-color: #1A1A1A;
}

nav > div {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 73%;
}

.nav-dropdown {
    display: flex;
    background-color: transparent;
    justify-content: center;
    align-items: center;
    border: none;
    color: #E1E1E1;
    gap: 5px;
}

.nav-dropdown > svg {
    width: 14px;
}

.nav-left-container, .nav-right-container  {
    display: flex;
    justify-content: center;
    align-content: center;
    align-items: center;
    gap: 20px;
}

.nav-left-container {
    margin-right: auto;
}

.nav-right-container>picture {
    border-left: 1px solid #363636;
    border-right: 1px solid #363636;
    display: block;
    margin: auto;
    justify-content: center;
    align-items: center;
    padding: 0 10px;
}

.nav-right-container>picture>svg {
    color: #E1E1E1;
    margin: auto;
    display: block;
}

.toggle-theme {
    background-color: transparent;
    border: 1px solid #363636;
    border-radius: 25px;
}

.toggle-theme > svg {
    color: #E1E1E1;
}

.nav-left {
    text-decoration: none;
    color: #E1E1E1;
    font-family: 'Inter', sans-serif;
    font-weight: 500;
    margin-right: auto;
}

.nav-right {
    text-decoration: none;
    color: #E1E1E1;
    font-size: 13px;
    font-family: 'Inter', sans-serif;
    font-weight: 500;
}

.nav-right:hover {
    color: #42b883;
    transition: all .2s ease;
}

.social {
    display: flex;
    gap: 20px;
    align-items: center;
}

.social > a > svg {
    display: block;
    color: #979797;
    width: 20px;
}

.social > a > svg:hover {
    color: #E1E1E1;
    transition: all .2s ease;
}

</style>