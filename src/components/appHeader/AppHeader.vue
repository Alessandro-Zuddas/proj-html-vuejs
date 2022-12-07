<script>
export default {

    name: "AppHeader",

    data() {
        return {
            
        }
    }, 
    methods:{

    }
}
</script>

<template>
  
    <div class="container">
        <a href="#">
            <img class="logo" src="../../assets/img/construction_logo.png" alt="Header Logo">
        </a>
        <nav>
            <a class="nav-link active" href="#">HOME</a>
            <a class="nav-link" href="#">ABOUT</a>
            <a class="nav-link" href="#">SERVICES</a>
            <a class="nav-link" href="#">WORK</a>
            <a class="nav-link" href="#">ARTICLES</a>
            <button class="nav-btn">GET QUOTE</button>
        </nav>
    </div>

</template>

<style scoped>

.container{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: .9375rem 3.125rem;
}

.logo{
    max-width: 9.375rem;
    max-height: 9.375rem;
}

.nav-link{
    color: grey;
    text-decoration: none;
    padding-right: .9375rem;
}

.active{
    position: relative;
    color: var(--first-color);
    border-bottom: 5px solid white;
}

.active:before{
    content:'';
    position: absolute;
    left: 0;
    right: 18px;
    bottom: -44px;
    margin: 0 auto;
    width: 0;
    height: 0;
    border-top: 10px solid white;
    border-left: 10px solid transparent;
    border-right: 10px solid transparent;
}

.nav-link:hover{
    color: var(--first-color);
}

.nav-btn{
    color: gray;
    background-color: var(--first-color);
    border: none;
    padding: .4375rem .9375rem;
    cursor: pointer;
}

.nav-btn:hover{
    color: white;
    background-color: var(--second-color);
}

a{
    font-size: .8125rem;
}

</style>