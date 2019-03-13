<template>
    <header>
        <h1 class="header">{{headerOne}}</h1>
        <hr>
        <hr>
        <h2 class="header">{{headerTwo}}</h2>
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
.header {
    color: white;
}
hr {
    width: 400px;
}
</style>
