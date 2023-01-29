

<template>
    <header id="banner" class="banner">
        <h1 id="h1">Web Development</h1>
        <h4>HTML, CSS, JavaScript</h4>
    </header>
</template>

<script>
    
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');

.banner, h1{
    transition: 0.6s;
}

.banner{
    font-size:  48px;
    text-align: center;
    padding-top: 300px;
    padding-bottom: 300px;
    font-family: Ubuntu;
    background-image: url("../static/JSJS.jpg");
    background-attachment: fixed;
    color: white;
    border-radius: 5%;
}

.banner.active{

}

</style>
