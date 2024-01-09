<template>
    <header class="pt-3 pb-2">
        <div class="container">
            <div class="row">
                <div class="col-4">
                   <img src="../assets/logo-dark.png" alt="Land's logo">
                </div>
            <div class="col-4 pr-2">
                <ul>
                    <li>HOME</li>
                    <li>LANDING</li>
                    <li>PAGES</li>
                    <li>DOCS</li>
                </ul>
            </div>
            <div class="settings col-4">
                Search
            </div>
            </div>
        </div>
        <div class="container jumbo">
            <div class="row">
                <div class="col-6 pt-5">
                <p class="pb-3">
                    Develoment
                </p>
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
                            <img src="../assets/google.svg" alt="Amazon logo">
                        </li>
                        <li>
                            <img src="../assets/lenovo.svg" alt="Amazon logo">
                        </li>
                        <li>
                            <img src="../assets/paypal.svg" alt="Amazon logo">
                        </li>
                        <li>
                            <img src="../assets/shopify.svg" alt="Amazon logo">
                        </li>
                        <li>
                            <img src="../assets/spotify.svg" alt="Amazon logo">
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
    margin-left: 3.5rem;
}

img{
    width: calc(100% / 4);
    text-align: center;
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
    width: 90%;
}

.btn-outline-primary{
    margin-left: .8rem;
}

button{
    font-size: .9rem;
    padding: .5rem;
    width: 8.5rem;
}

.col-12 ul{
    padding-top: 2rem;
    width: 100%;
}

.logos{
    width: 80%;
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

</style>