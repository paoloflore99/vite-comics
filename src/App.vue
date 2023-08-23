<script>
import TheFooter from './components/TheFooter.vue';
import TheHeader from './components/TheHeader.vue';
import BonusVue from './components/Bonus.vue';
import cardlist  from '../public/card/card';
import card from '../public/card/card';

export default {
    components: {
        TheFooter,
        TheHeader,
        BonusVue,
        cardlist
    },
    data () {
        return{
            cardlist
        }
    }
}

</script>



<!------------------------------------------->


<template>
    <ul>
        <li v-for="card in cardlist">{{ card.type }}</li>
        <li v-for="card in cardlist">{{ card.thumb }}</li>
    </ul>
    <TheHeader></TheHeader>
    <THENav></THENav>
    <main></main>
    <BonusVue></BonusVue>
    <TheFooter></TheFooter>

</template>



<!------------------------------------------->
<style>
</style>
