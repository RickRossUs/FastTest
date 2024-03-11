<template>
    <div class="center">

        <v-row class="" align="center" justify="center">
            <v-col cols="12" sm="4" class="py-5 img">
                <img src="../assets/Depositphotos_103747962_XL-scaled.jpg" alt="img">
            </v-col>
            <v-col cols="12" sm="8">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laboriosam, quia. Labore quae tenetur alias, inventore
                ex deleniti nam praesentium beatae consectetur ad accusantium vero, tempora, suscipit perspiciatis itaque totam
                error.
            </v-col>
        </v-row>
        <CBtn />
    </div>
</template>

=============================================SCRIPT========================================================================
<script lang="ts" setup>
import CBtn from './CBtn.vue';


</script>

=============================================STYLE=========================================================================
<style scoped lang="scss">
.center {
padding: 30px 10vw;

}
.img {
    display: flex;
    justify-content: flex-end;
    align-items: center;
}
img {
    height: 200px;
    max-width: 100%;
border-radius: 50% 0 50% 50%;
}
</style>