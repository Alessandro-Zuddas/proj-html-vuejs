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

        <div class="row">
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

</style>