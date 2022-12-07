<script>

import NavContent from './NavContent.vue';

export default {

    name: "AppHeader",

    data() {
        return {

            currentLink: 0,

            linksInfo: [
                {
                    linkName: "HOME",
                    linkRef: "#",
                    id: 0
                },
                {
                    linkName: "ABOUT",
                    linkRef: "#",
                    id: 1
                },
                {
                    linkName: "SERVICES",
                    linkRef: "#",
                    id: 2
                },
                {
                    linkName: "WORK",
                    linkRef: "#",
                    id: 3
                },
                {
                    linkName: "ARTICLES",
                    linkRef: "#",
                    id: 4
                },

            ]
        }
    },
    components: {
        NavContent,
    }, 
    methods:{
        onLinkClick(i){
            this.currentLink = i;
        }
    }
}
</script>

<template>
  
    <div class="container">
        <a href="#">
            <img class="logo" src="../../assets/img/construction_logo.png" alt="Header Logo">
        </a>
        <nav>
            <NavContent
            v-for="(linkInfo, index) in this.linksInfo" 
            :info="linkInfo" 
            :currentLink="this.currentLink"
            @onLinkClick="onLinkClick(index)" />

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

</style>