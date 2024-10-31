<template>
    <div>
        <input type="text" v-model="city" placeholder="inserisci una Città" />
        <button @click="searchWeather">Cerca Meteo</button>
    </div>
</template>

<script>
export default{
    name:"SearchCity",
    data() {
        return {
            city:""
        };
    },
    methods: {
        searchWeather() {
            console.log(`Cercando il meteo per ${this.city}`);
        }
    }
};
</script>

<style scoped>
</style>