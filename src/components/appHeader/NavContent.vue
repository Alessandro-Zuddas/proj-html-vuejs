<script>
export default {

    name: "NavContent",

    data() {
        return {
            
        }
    },
    props:{
        info: Object,
        currentLink: Number,
    }, 
    methods:{

    }
}
</script>

<template>

    <a class="nav-link" :class="{active : currentLink === info.id}" :href="info.linkRef" @click="$emit(`onLinkClick`)">
        {{ info.linkName }}
    </a>

</template>

<style scoped>

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
    right: 16px;
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

a{
    font-size: .8125rem;
}

</style>