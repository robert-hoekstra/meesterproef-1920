<template>
  <nav class="nav">
    <nuxt-link to="/#">Home</nuxt-link>
    <nuxt-link to="/upload">Upload</nuxt-link>
    <nuxt-link to="/vocabulary">Vocabulary</nuxt-link>
    <nuxt-link to="/about">About</nuxt-link>
  </nav>
</template>

<script>
export default {

}
</script>

<style>
.nav{
    background-color:rgba(0, 197, 141, 0.651);
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    justify-content: center;
    align-items: flex-start;
    align-content: stretch;
    padding: 1em;
    border-bottom: solid gray 0.5em;
    margin-bottom: 2em;
}

.nav a{
    transition: 0.5s;
     color: gray;
     padding-left: 1em;
     padding-right: 1em;
     font-size: 2em;
}

.nav a:hover{
    transition: 0.5s;
    color: white;
}

</style>