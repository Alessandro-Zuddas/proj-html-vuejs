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
        <h2 class="main-title">Titolo main top</h2>
        <hr>
        <p class="desc-text">
            Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eum saepe ab quis accusantium repellendus aspernatur repudiandae, <br> maxime perspiciatis deserunt impedit ipsam magni quae placeat dolor.
        </p>

        <div class="row row-bt-circle">
            <div class="column">
                <p class="card-icon">Icon</p>
                <h3 class="card-title">Titolo</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident?
                </p>
            </div>
            <div class="column">
                <p class="card-icon">Icon</p>
                <h3 class="card-title">Titolo</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident?
                </p>
            </div>
            <div class="column">
                <p class="card-icon">Icon</p>
                <h3 class="card-title">Titolo</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident?
                </p>
            </div>
            <div class="column">
                <p class="card-icon">Icon</p>
                <h3 class="card-title">Titolo</h3>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Libero optio quos tenetur labore id, expedita quibusdam ipsum provident?
                </p>
            </div>
        </div>
    </div>

    
    <div class="row bg-variant">   
        <div class="container-sm">
            <div class="company-infos">
                <div>Icon</div>
                <h2>0000</h2>
                <p>Info Text</p>
            </div>
            <div class="company-infos">
                <div>Icon</div>
                <h2>0000</h2>
                <p>Info Text</p>
            </div>
            <div class="company-infos">
                <div>Icon</div>
                <h2>0000</h2>
                <p>Info Text</p>
            </div>
            <div class="company-infos">
                <div>Icon</div>
                <h2>0000</h2>
                <p>Info Text</p>
            </div>
        </div>
    </div>

</template>

<style scoped>

.container{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 4.6875rem 0;
}

.main-title{
    padding-bottom: .625rem;
}

hr{
    width: 5%;
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
    width: calc(100% / 4 - 1.25rem);
    margin: 0 .625rem;
    padding: 1.25rem .625rem;
    background-color: lightgray;
    border-radius: .625rem;
}

.card-icon,.card-title{
    margin-bottom: .625rem;
}

.bg-variant{
    padding: 1.5625rem 0;
    position: relative;
    overflow: hidden;
    /* DEBUG */
    background-color: aqua;
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
}

</style>