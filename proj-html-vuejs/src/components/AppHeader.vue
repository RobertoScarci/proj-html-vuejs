<template>
    <header class="pt-3 pb-2">
        <div class="container">
            <div class="row">
                <div class="col-4 pt-2">
                   <img src="../assets/logo-dark.png" alt="Land's logo">
                </div>
            <div class="col-4 pt-2">
                <ul class="navigation">
                    <li class="">HOME</li><i class="fa-solid"></i>
                    <li>LANDING</li><i class="fa-solid fa-chevron-down"></i>
                    <li>PAGES</li><i class="fa-solid fa-chevron-down"></i>
                    <li>DOCS</li><i class="fa-solid fa-chevron-down"></i>
                </ul>
            </div>
            <div class="settings col-4">
                <i class="fa-solid fa-magnifying-glass"></i>
                <i class="fa-brands fa-github plan"></i>
                <i class="fa-regular fa-chart-bar plan"></i>
                <i class="fa-solid fa-user-large plan"></i>
            </div>
            </div>
        </div>
        <div class="container jumbo">
            <div class="row">
                <div class="col-6 pt-5">
                <span class=" px-2 d-inline-block bg-soft-primary mb-0 text-primary rounded-lg plan">
                    Develoment
                </span>
                <h1 class="">
                    A Complete Developer Toolset
                </h1>
                <p class="pt-3 pb-3">
                    Launch your campaign and benefit from our expertise on designing and managing conversion centered bootstrap4 html page.
                </p>
                <button class="btn btn-primary">
                    Get Started
                </button>
                <button class="btn btn-outline-primary">
                    Documentation
                </button>
                <p class="pt-3">
                    Current Version: v2.6.0
                </p>
                </div>
                <div class="col-6">
                    <img src="../assets/about.png" alt="about's img">
                </div>
            </div>
        </div>
        <hr>
        <div class="container logos">
            <div class="row">
                <div class="col-12">
                    <ul>
                        <li>
                            <img src="../assets/amazon.svg" alt="Amazon logo">
                        </li>
                        <li>
                            <img src="../assets/google.svg" alt="google logo">
                        </li>
                        <li>
                            <img src="../assets/lenovo.svg" alt="lenovo logo">
                        </li>
                        <li>
                            <img src="../assets/paypal.svg" alt="paypal logo">
                        </li>
                        <li>
                            <img src="../assets/shopify.svg" alt="shopify logo">
                        </li>
                        <li>
                            <img src="../assets/spotify.svg" alt="spotify logo">
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </header>
</template>

<script>
</script>

<style lang="scss" scoped>

@use "../styles/general.scss" as *;
@use "../styles/partials/mixins" as *;
@use "../styles/partials/variables" as *;

header{
    background-color: #F8F9FC;
    text-align: center;
}

ul{
    list-style-type: none;
    display: flex;
    font-size: .9rem;
}

.col-4 li{
    margin-left: 1.8rem;
}

.col-4 li:hover{
    color: $secondary-color;
}

img{
    width: calc(100% / 4);
    text-align: left;
    vertical-align: top;
}

.settings{
    padding-right: 0;
    justify-content: center;
}

.jumbo{
    width: 70%;
    padding-top: 8rem;
    padding-bottom: 5rem;
    text-align: left;
}

.jumbo .row{
    display: flex;
    justify-content: center;
}

.jumbo img{
    width: 100%;
}

.btn-outline-primary{
    margin-left: .8rem;
}

button{
    font-size: .9rem;
    padding: .5rem;
    width: 8.5rem;
}

.btn-primary{
    background-color: $secondary-color;
}

.col-12 ul{
    padding-top: 2rem;
}

.logos{
    width: 75%;
    padding-bottom: 2rem;
}

p{
    color: $text-color;
    font-size: .8rem;
}

h1{
    font-size: 2.5rem;
    font-weight: bold;
    line-height: 1.5;
}

span.plan{
    background-color: #2F55D41A;
    border-radius: 50px;
    border: .1px solid rgb(200, 198, 198);
    font-size: .7rem;
    color: $secondary-color;
}

i{
    margin: 0 .8rem;
    font-size: 1.2rem;
}

i.plan{
    margin: 0 .2rem;
    padding: .6rem;
    color: $text-color;
    background-color: #2F55D41A;
    border-radius: 10px;
    border: .1px solid rgb(200, 198, 198);
    color: $secondary-color;
    box-shadow: rgba(0, 0, 0, 0.24) 0px 3px 8px;
}

i.plan:hover{
    background-color: $secondary-color;
    color: white;
}


.fa-chevron-down{
    font-size: .8rem;
    padding-top: .2rem;
    margin-right: 1rem;
}

li img{
    width: 50%;
}

</style>