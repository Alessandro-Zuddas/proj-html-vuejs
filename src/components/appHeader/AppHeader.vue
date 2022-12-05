<script>
export default {

    name: "AppHeader",

    data() {
        return {

        }
    }
}
</script>

<template>
  
    <div class="container">
        <div>
            Logo
        </div>
        <nav>
            <a class="nav-link" href="#">Link</a>
            <a class="nav-link" href="#">Link</a>
            <a class="nav-link" href="#">Link</a>
            <a class="nav-link" href="#">Link</a>
            <a class="nav-link" href="#">Link</a>
            <button class="nav-btn">Button</button>
        </nav>
    </div>

</template>

<style scoped>

.container{
    display: flex;
    justify-content: space-between;
    padding: .9375rem 3.125rem;
    /* DEBUG */
    background-color: aquamarine;
}

.nav-link{
    color: grey;
    text-decoration: none;
    padding-right: .9375rem;
}

.nav-btn{
    padding: .3125rem .625rem;
}

</style>