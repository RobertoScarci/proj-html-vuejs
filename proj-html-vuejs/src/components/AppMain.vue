<template>
    <main>
        <div class="container first">
            <div class="row">
                <div class="col-8">
                    <h1>
                        Key Features
                    </h1>
                    <p>
                        Start working with <span>Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.
                    </p>
                </div>
            </div>
        </div>
        <div class="container first">
            <div class="row">
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Modular</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <a href="#" class="">Read More</a>
                    </div>
                </div>
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Responsive</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <a href="#" class="">Read More</a>
                    </div>
                </div>
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Customizable</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <a href="#" class="">Read More</a>
                    </div>
                </div>
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Scalable</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <a href="#" class="">Read More</a>
                    </div>
                </div>
            </div>
        </div>
    </main>
</template>

<script>
</script>

<style lang="scss" scoped>

@use "../styles/general.scss" as *;
@use "../styles/partials/mixins" as *;
@use "../styles/partials/variables" as *;

.first{
    width: 70%;
    padding-top: 4rem;
}

.first h1{
    font-size: 1.8rem;
}

.first p{
    padding-top: 2rem;
    color: $text-color;
}

.first span{
    color: $secondary-color;
    font-weight: bold;
}

.col-3{
    width: calc((100% / 4) - 1rem);
    margin: .5rem;
}

</style>