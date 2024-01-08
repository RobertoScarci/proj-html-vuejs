<template>
    <header class="pt-3 pb-2">
        <div class="my_container">
            <div class="row">
                <div class="col-2">
                   <img src="../assets/logo-dark.png" alt="Land's logo">
                </div>
            <div class="col-5">
                <ul>
                    <li>HOME</li>
                    <li>LANDING</li>
                    <li>PAGES</li>
                    <li>DOCS</li>
                </ul>
            </div>
            <div class="settings col-5">
                Search
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
}

.my_container{
    width: 100%;
}

ul{
    list-style-type: none;
    display: flex;
    padding: 0 2rem;
    font-size: .9rem;
}

li{
    margin-left: 3.5rem;
}

img{
    width: calc(100% / 2);
    display: flex;
    justify-content: center;
}

.settings{
    padding-left: 3rem;
    justify-content: center;
}
</style>