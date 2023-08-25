<script>
import TheFooter from './components/TheFooter.vue';
import TheHeader from './components/TheHader.vue';
import BonusVue from './components/bonus.vue';

import cardlist from '../src/card/card';

// import cardlist  from '../public/card/card';


export default {
    components: {
        TheFooter,
        TheHeader,
        BonusVue,
    },
    data() {
        return {
            cardlist
        }
    }
}

</script>



<!------------------------------------------->


<template>



    <TheHeader></TheHeader>
    
    <div class="card-mio bg-dark">
        <div class="container">
            <div class="row row-col-4">

                <div class="card bg-dark border-0 col-2 p-3 card-movi" v-for="card in cardlist">
                    <img class="quadrato" :src="card.thumb" alt="">
                    <a class="text-white" href="">{{ card.series }}</a>
                </div>
            </div>
        </div>

        <div class="button-container P-2">
            <button type="button" class="mio-btn btn btn-primary btn-lg rounded-0"><strong>LOARD MORE</strong></button>
        </div>
    </div>

    
    <main></main>
    <BonusVue></BonusVue>
    <TheFooter></TheFooter>

</template>



<!------------------------------------------->
<style lang="scss" scoped>

.quadrato {
    width: 150px;
    height: 150px; 
    object-fit: cover;
}

a {
    text-decoration: none;
}
.button-container {
    display: flex;
    justify-content: center;
    align-items: center;
    
} 
</style>
