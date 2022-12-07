<script>
export default {

    name: "MainTop",

    data() {
        return {
        
        }
    }
}
</script>

<template>
  
    <div class="container">
        <h2 class="main-title">Specialists in Modern Construction</h2>
        <hr>
        <p class="desc-text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
        </p>

        <!-- Company benefits -->
        <div class="row row-bt-circle">
            <!-- Company benefit One -->
            <div class="column">
                <i class="fa-regular fa-building card-icon"></i>
                <h3 class="card-title">Buildings</h3>
                <p class="card-text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident? Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id.
                </p>
                <!-- On Hover Panel -->
                <div class="hover-panel">
                    <h4 class="hover-panel-title">ARTFULLY CRAFTED</h4>
                    <p class="hover-panel-text">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iusto, perspiciatis itaque voluptatum eius eum ex vero nulla optio ratione debitis pariatur repellendus.
                    </p>
                    <button class="hover-panel-btn">GET A QUOTE</button>
                </div>
                <!-- /On Hover Panel -->
            </div>
            <!-- /Company benefit One -->
            <!-- Company benefit two -->
            <div class="column">
                <i class="fa-solid fa-arrows-rotate card-icon"></i>
                <h3 class="card-title">Renovate</h3>
                <p class="card-text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident? Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id.     
                </p>
                <!-- On Hover Panel -->
                <div class="hover-panel">
                    <h4 class="hover-panel-title">ARTFULLY CRAFTED</h4>
                    <p class="hover-panel-text">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iusto, perspiciatis itaque voluptatum eius eum ex vero nulla optio ratione debitis pariatur repellendus.
                    </p>
                    <button class="hover-panel-btn">GET A QUOTE</button>
                </div>
                <!-- /On Hover Panel -->
            </div>
            <!-- /Company benefit two -->
            <!-- Company benefit three -->
            <div class="column">
                <i class="fa-sharp fa-solid fa-house card-icon"></i>
                <h3 class="card-title">Construct</h3>
                <p class="card-text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident? Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id.   
                </p>
                <!-- On Hover Panel -->
                <div class="hover-panel">
                    <h4 class="hover-panel-title">ARTFULLY CRAFTED</h4>
                    <p class="hover-panel-text">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iusto, perspiciatis itaque voluptatum eius eum ex vero nulla optio ratione debitis pariatur repellendus.
                    </p>
                    <button class="hover-panel-btn">GET A QUOTE</button>
                </div>
                <!-- /On Hover Panel -->
            </div>
            <!-- /Company benefit three -->
            <!-- Company benefit four -->
            <div class="column">
                <i class="fa-solid fa-truck card-icon"></i>
                <h3 class="card-title">Exclusive</h3>
                <p class="card-text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident? Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id.
                </p>
                <!-- On Hover Panel -->
                <div class="hover-panel">
                    <h4 class="hover-panel-title">ARTFULLY CRAFTED</h4>
                    <p class="hover-panel-text">
                        Lorem ipsum dolor, sit amet consectetur adipisicing elit. Iusto, perspiciatis itaque voluptatum eius eum ex vero nulla optio ratione debitis pariatur repellendus.
                    </p>
                    <button class="hover-panel-btn">GET A QUOTE</button>
                </div>
                <!-- /On Hover Panel -->
            </div>
            <!-- /Company benefit four -->
        </div>
    </div>
    <!-- /Company benefits -->
    
    <!-- Company Infos -->
    <div class="row bg-variant">   
        <div class="container-sm">
            <!-- Company Info One -->
            <div class="company-infos">
                <i class="fa-solid fa-suitcase info-icon"></i>
                <h2 class="info-number">3534</h2>
                <p class="info-text">PLANNING APPLICATIONS</p>
            </div>
            <!-- /Company Info One -->
            <!-- Company Info Two -->
            <div class="company-infos">
                <i class="fa-solid fa-building info-icon"></i>
                <h2 class="info-number">896</h2>
                <p class="info-text">COMPLETED PROJECTS</p>
            </div>
            <!-- /Company Info Two -->
            <!-- Company Info Three -->
            <div class="company-infos">
                <i class="fa-solid fa-users info-icon"></i>
                <h2 class="info-number">176</h2>
                <p class="info-text">TRAINED PROFESSIONALS</p>
            </div>
            <!-- /Company Info Three -->
            <!-- Company Info Four -->
            <div class="company-infos">
                <i class="fa-sharp fa-solid fa-globe info-icon"></i>
                <h2 class="info-number">19</h2>
                <p class="info-text">INTERNATIONAL OFFICES</p>
            </div>
            <!-- /Company Info Four -->
        </div>
    </div>
    <!-- /Company Infos -->

</template>

<style lang="scss" scoped>

/* Company benefits */

.container{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 4.6875rem 0;
}

.main-title{
    color: var(--titles-color);
    padding-bottom: .625rem;
}

hr{
    width: 8%;
    height: .125rem;
    background-color: #fed03d;
    border: none;
}

.desc-text{
    text-align: center;
    margin-top: 1.5625rem;
    margin-bottom: 2.5rem;
}

.row{
    display: flex;
    justify-content: space-between;
    text-align: center;
    width: 100%;
    padding: 0 3.125rem;
}

.column{
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: calc(100% / 4 - 1.25rem);
    margin: 0 .625rem;
    padding: 1.25rem .625rem;
    background-color: #f5f5f5;
    border-radius: .625rem;
}

.hover-panel{
    position: absolute; 
    top: 0;
    left: 0;
    display: none;
    flex-direction: column;
    align-items: center;
    width: 100%;
    height: 100%;
    padding: .9375rem .9375rem;
    color: var(--titles-color);
    background-color: var(--first-color);
    border-radius: .625rem;
}

.hover-panel-title{
    margin: 1.5625rem 0;
}

.hover-panel-btn{
    margin-top: 2.1875rem;
    padding: .625rem 1.25rem;
    color: var(--titles-color);
    background-color: #ffe07b;
    border: none;
    cursor: pointer;
}

.hover-panel-btn:hover{
    background-color: var(--second-color);
    color: white;
}

.column:hover{

    .hover-panel{
        display: flex;
    }

}

.card-icon{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: auto;
    width: 3.75rem;
    border-radius: 50%;
    aspect-ratio: 1;
    border: .0313rem solid var(--titles-color);
    color: var(--titles-color);
    font-size: 1.5625rem;
}

.card-title{
    color: var(--titles-color);
    font-size: 1.75rem;
}

.card-text{
    margin-top: .625rem;
}

.card-icon,.card-title{
    margin-bottom: .625rem;
}

/* /Company benefits */

/* Company infos */

.bg-variant{
    padding: 1.5625rem 0;
    position: relative;
    overflow: hidden;
    background-image: url("../../assets/img/home-244125289.jpg");
    background-size: cover;
    background-repeat: no-repeat;
}

.bg-variant:before{
    content: "";
    position: absolute;
    top: -30%;
    width: 100%;
    height: 50%;
    background-color: white;
    border-bottom-left-radius: 50%;
    border-bottom-right-radius: 50%; 
}

.bg-variant:after{
    content: "";
    position: absolute;
    width: 100%;
    bottom: -30%;
    height: 50%;
    background-color: white;
    border-top-left-radius: 50%;
    border-top-right-radius: 50%;
}

.container-sm{
    display: flex;
    padding: 6.25rem 0;
}

.company-infos{
    width: calc(100% / 4);
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 3.125rem 0;
    color: var(--first-color);
}

.company-infos:hover{
    transform: scale(1.1);
}

.info-text{
    color: white;
    font-size: .875rem;
}

.info-icon{
    font-size: 3.125rem;
    margin-bottom: .3125rem;
}

.info-number{
    font-size: 2.5rem;
}

/* /Company infos */

</style>