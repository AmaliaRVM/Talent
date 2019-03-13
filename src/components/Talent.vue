<template>
    <talent>
        <ul>
            <li v-for="talent in talents" v-bind:value="talent.value" :key="talent.value">
                {{talent}}
            </li>
        </ul>
    </talent>
</template>

<script>
export default {
    data(){
        return{
            talents: [
                "Being On Time",
                "Making An Effort",
                "Being High Energy",
                "Having A Positive Attitude",
                "Being Passionate",
                "Using Good Body Language",
                "Being Coachable",
                "Doing A Little Extra",
                "Being Prepared",
                "Having A Strong Work Ethic"
            ]
        }
    }

}
</script>

<style scoped>
li {
    list-style-type: none;
    color: white;
}


</style>
