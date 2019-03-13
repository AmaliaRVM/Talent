<template>
    <header>
        <h1>{{headerOne}}</h1>
        <hr>
        <hr>
        <h2>{{headerTwo}}</h2>
    </header>
</template>

<script>
export default {
    data() {
        return {
            headerOne: "10 THINGS THAT REQUIRE",
            headerTwo: "ZERO TALENT"
        }
    }

}
</script>

<style>
h1, h2{
    color: white;
    
}
hr {
    width: 400px;
    text-align: center;
}
</style>
