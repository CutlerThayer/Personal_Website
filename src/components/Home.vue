<template>
    <v-container>
        <h1
            class=" my-12 heading-title" 
        >
            <div class="pop-color">Cutler Thayer!</div> Developer, Innovator, Engineer.
        </h1>
    </v-container>
</template>
<script>
import { defineComponent } from '@vue/composition-api'

export default defineComponent({

})
</script>

<style scoped>
*{
    background-color: #f8f9fc;
}
.heading-title {
    color: #1f1f25;
    font-size: 75px;
    font-weight: 900;
    font-family: Montserrat,sans-serif;
    line-height: 90px;
    justify-content: left;
    max-width: 70%;
    margin-left: 70px;
}
.pop-color {
    color: green;
}
</style>
