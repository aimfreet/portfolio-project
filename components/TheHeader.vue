<template>
    <header class="header">
        <div class="header__logo-section">
            <div class="header__logo">
                <SiteLogo />
            </div>
        </div>
        <div class="header__nav-content">
            <div class="header__nav-social"></div>
            <nav class="header__nav-menu">
                <ul class="header__nav-links">
                    <li>Resume</li>
                    <li>About</li>
                    <li>Contact</li>
                </ul>
            </nav>
        </div>
    </header>
</template>

<script>
    import SiteLogo from './logos/SiteLogo.vue';
    export default {
      components: {
        SiteLogo,
      }
    }
    </script>

<style lang="scss">
    @import '../assets/style.scss';
    .header {
        height: 118px;
        background: var(--white);
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 1rem 2rem;
        &__nav {
            &-links {
                display: flex;
                list-style-type: none;
            }
        }
        &__logo {
            height: 100%;
            & svg {
                height: 100%;
            }
            &-section {
                width: 100%;
                height: 100%;
            }
        }
    }
</style>