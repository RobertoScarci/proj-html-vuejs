<template>
    <header class="pt-3 pb-2">
        <div class="my_container">
            <div class="row">
                <div class="col-4">
                   <img src="../assets/logo-dark.png" alt="Land's logo">
                </div>
            <div class="col-4">
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
        <div class="my_container jumbo">
            <div class="row">
                <div class="col-6">
                <p>
                    Develoment
                </p>
                <h3>
                    A Complete Developer Toolset
                </h3>
                <p class="p-3">
                    Launch your campaign and benefit from our expertise on designing and managing conversion centered bootstrap4 html page.
                </p>
                <button class="m-2">
                    Get Started
                </button>
                <button>
                    Documentation
                </button>
            </div>
            <div class="col-6">
                <img src="../assets/about.png" alt="about's img">
            </div>
            </div>
        </div>
    </header>
</template>

<script>
</script>

<style lang="scss" scoped>
@use "../styles/general.scss" as *;
header{
    background-color: #F8F9FC;
    text-align: center;
}

ul{
    list-style-type: none;
    display: flex;
    font-size: .9rem;
}

li{
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
    width: 80%;
    padding-top: 8rem;
}

.jumbo .row{
    display: flex;
    justify-content: center;
}

.jumbo img{
    width: 80%;
}
</style>