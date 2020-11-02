<template>
    <div id="weather">
        <h1>Météo Actuelle à {{ nomVille }}</h1>
        <p>Température : {{ temperature }}°C</p>
        <p>Date : {{ DatLocale }}</p>
    </div>
</template>

<script>
import moment from 'moment'
export default {   
props:{
    nomVille: String,
    temperature: Number
},
computed:{
    DatLocale(){
        moment.locale('fr');
       return moment().format( 'Do MMMM  YYYY');
    }
}
}
</script>

<style>
    #weather{
        margin: auto;
        margin-top: 15px;
        width: 855px;
        padding: 2px;
        background-color: rgb(244, 242, 250);
    }
</style>