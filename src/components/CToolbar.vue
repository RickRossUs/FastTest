<template>
    <div>
        <div class="nav-menu">
            <v-icon size="48" @click="showMobileMenu = !showMobileMenu">mdi-menu</v-icon>
            <div class="nav-content" :class="showMobileMenu ? 'open-menu' : 'closed-menu'">
                <div class="logo">Logo</div>
                <ul class="nav-items">
                    <li>Nuestra compania</li>
                    <li>Nuestros servicios</li>
                    <li>Bandera</li>
                    <li>Contactenos</li>
                </ul>
                <div class="login-button">Portal paciente</div>
            </div>
        </div>
    </div>
</template>

=============================================SCRIPT========================================================================
<script lang="ts" setup>
import { Ref, ref } from 'vue';

const showMobileMenu: Ref<Boolean> = ref(true)


</script>

=============================================STYLE=========================================================================
<style scoped lang="scss">
.nav-menu {
    position: fixed;
    width: 100vw;
    background: linear-gradient(to bottom, rgba(0, 0, 255, .7) 0%, rgba(0,0,0,0) 100%);
    z-index: 100;
}

.nav-content {
    display: flex;
    justify-content: space-between;
    padding: 10px 30px;
    align-items: center;
    color: rgb(255, 255, 255);
}

.nav-items {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style: none;
    margin: 0;
    padding: 0;

    li {
        padding: 0 10px;
    }
}

i {
    display: none;
}

@media screen and (max-width: 768px) {
    .nav-menu {
        padding-top: 10px;
        position: absolute;
        width: 100%;
    }

    .open-menu {
        opacity: 1;
        height: 150px;
    }

    .closed-menu {
        opacity: 0;
        height: 0;
        padding: 0;
    }

    .nav-content {
        flex-direction: column;
        z-index: 100;
        position: relative;
        transition: all 0.2s ease-out;
    }

    .nav-items {
        flex-direction: column;
    }

    i {
        display: block;
        text-align: right;
        padding: 0 10px 10px 0;
    }
}
</style>