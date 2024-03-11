<template>
    <div class="footer">
        <v-row class="" align="center" justify="center">
            <v-col cols="12" sm="4" md="2" align="center" justify="center" >
                NOVA MEDICAL
            </v-col>
            <v-col cols="12" sm="4" md="2" align="center" justify="center" >
                Nuestra compañia
            </v-col>
            <v-col cols="12" sm="4" md="2" align="center" justify="center" >
                Nuestros servicio
            </v-col>
            <v-col cols="12" sm="4" md="2" align="center" justify="center" >
                Bandera
            </v-col>
            <v-col cols="12" sm="4" md="2" align="center" justify="center" >
                Contáctenos
            </v-col>
            <v-col cols="12" align="center" justify="center" >
                Derechos de autor. Todos los derechos reservados
            </v-col>
        </v-row>
    </div>
</template>

=============================================SCRIPT========================================================================
<script lang="ts" setup>

</script>

=============================================STYLE=========================================================================
<style scoped lang="scss">
.footer {
    padding: 50px 10vw;
    background-color: rgb(59, 59, 59);
    border-radius: 50% 50% 0 0;
color: white;

.v-col {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
}
}
</style>