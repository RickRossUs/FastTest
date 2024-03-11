<template>
    <v-carousel cycle height="200" white="100%" hide-delimiter-background hide-delimiters :show-arrows="false">
        <v-carousel-item>
            <img src="../assets/Depositphotos_103747962_XL-scaled.jpg" alt="img">
            <div class="center">
                <h2>Tu bienestar es nuestra prioridad</h2>
                <CBtn />
            </div>
        </v-carousel-item>
        <v-carousel-item>
            <img src="../assets/Depositphotos_103747962_XL-scaled.jpg" alt="img">
            <div class="center">
                <h2>Tu bienestar es nuestra prioridad</h2>
                <CBtn />
            </div>
        </v-carousel-item>
        <v-carousel-item>
            <img src="../assets/Depositphotos_103747962_XL-scaled.jpg" alt="img">
            <div class="center">
                <h2>Tu bienestar es nuestra prioridad</h2>
                <CBtn />
            </div>
        </v-carousel-item>
    </v-carousel>
</template>

=============================================SCRIPT========================================================================
<script lang="ts" setup>
import CBtn from './CBtn.vue';
</script>

=============================================STYLE=========================================================================
<style scoped lang="scss">
.v-carousel {
    width: 100vw;
    height: 110vh !important;
    border-radius: 0 0 20px 20px !important;

    .v-carousel-item {
        position: relative;
        display: flex;
        justify-content: center;
        align-items: center;
        min-width: 100%;
        min-height: 100%;
        border-radius: 0 0 20% 20% !important;

        img {
            width: 100%;
            height: 100%;
            border-radius: 0 0 20% 20% !important;

        }

        .center {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        }
        & h2 {
            
            font-size: 3rem;
            color: rgb(255, 255, 255);
            z-index: 100;
        }
    }
}

@media (max-width:959px) {
    .v-carousel-item h2 {
        font-size: 2rem !important;
    }
}
</style>