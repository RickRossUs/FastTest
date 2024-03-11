<template>
    <div>
        <CToolbar />
        <CCarousel />
        <v-row class="">
            <v-col cols="12" sm="6" md="3">
                <CCard />
            </v-col>
            <v-col cols="12" sm="6" md="3">
                <CCard />
            </v-col>
            <v-col cols="12" sm="6" md="3">
                <CCard />
            </v-col>
            <v-col cols="12" sm="6" md="3">
                <CCard />
            </v-col>
        </v-row>
        <div class="center">
            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Accusamus praesentium deleniti doloremque vitae
                est fuga quo labore quibusdam, quas earum corrupti voluptate minus pariatur explicabo officia dolore
                facere, facilis aliquid.</p>
            <CBtn />
        </div>
        <CService />
        <CFooter />
    </div>
</template>

=============================================SCRIPT========================================================================
<script lang="ts" setup>
import CCarousel from '../components/CCarousel.vue'
import CCard from '../components/CCard.vue'
import CBtn from '../components/CBtn.vue';
import CService from '../components/CService.vue';
import CFooter from '../components/CFooter.vue';
import CToolbar from '../components/CToolbar.vue';

</script>

=============================================STYLE=========================================================================
<style scoped lang="scss">
.v-row {
    margin: -70px 30px 0 30px;
}

.center {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    padding: 50px 10vW;
}
</style>