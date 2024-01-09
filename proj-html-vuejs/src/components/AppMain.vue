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
                        <span href="" class="">Read More</span>
                    </div>
                </div>
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Responsive</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <span href="" class="">Read More</span>
                    </div>
                </div>
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Customizable</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <span href="" class="">Read More</span>
                    </div>
                </div>
                <div class="card col-3">
                    <div class="card-body">
                       <h5 class="card-title">Scalable</h5>
                        <p class="card-text">Composed in a pseudo-Latin language which more or less corresponds.</p>
                        <span href="" class="">Read More</span>
                    </div>
                </div>
            </div>
        </div>
        <div class="container text-center pt-9 first">
            <div class="row">
                <div class="col-12">
                    <span class="fs-6">
                        Quickstart
                    </span>
                    <h1 class="pt-4">
                        Awesome isn't it? Let's dive in!
                    </h1>
                    <p class="text-centered pb-5">
                        Start working with <span>Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.
                    </p>
                    <div class="nav-bg p-3 rounded">
                            <div class="row">
                                <div class="col-lg-12">
                                    <ul class="nav nav-pills nav-justified flex-column flex-sm-row rounded bg-soft-light" id="pills-tab" role="tablist">
                                        <li class="nav-item" role="presentation">
                                            <a class="nav-link nav-link-alt rounded active" id="pills-npm-tab" data-bs-toggle="pill" href="#pills-npm" role="tab" aria-controls="pills-npm" aria-selected="true">
                                                <div class="text-center">
                                                    <h5 class="title fw-normal mb-0 text-white">npm</h5>
                                                </div>
                                            </a>
                                        </li>
                                        
                                        <li class="nav-item" role="presentation">
                                            <a class="nav-link nav-link-alt rounded" id="pills-nuget-tab" data-bs-toggle="pill" href="#pills-nuget" role="tab" aria-controls="pills-nuget" aria-selected="false" tabindex="-1">
                                                <div class="text-center ">
                                                    <h5 class="title fw-normal mb-0 text-white">nuget</h5>
                                                </div>
                                            </a>
                                        </li>
                                        
                                        <li class="nav-item" role="presentation">
                                            <a class="nav-link nav-link-alt rounded" id="pills-spm-tab" data-bs-toggle="pill" href="#pills-spm" role="tab" aria-controls="pills-spm" aria-selected="false" tabindex="-1">
                                                <div class="text-center">
                                                    <h5 class="title fw-normal mb-0 text-white">spm</h5>
                                                </div>
                                            </a>
                                        </li>
                                        
                                        <li class="nav-item" role="presentation">
                                            <a class="nav-link nav-link-alt rounded" id="pills-github-tab" data-bs-toggle="pill" href="#pills-github" role="tab" aria-controls="pills-github" aria-selected="false" tabindex="-1">
                                                <div class="text-center">
                                                    <h5 class="title fw-normal mb-0 text-white">github</h5>
                                                </div>
                                            </a>
                                        </li>
                                    </ul>
                                </div>
                            </div>

                            <div class="row">
                                <div class="col-12 mt-2">
                                    <div class="tab-content" id="pills-tabContent">
                                        <div class="tab-pane fade show active" id="pills-npm" role="tabpanel" aria-labelledby="pills-npm-tab">
                                            <p class="fw-bold mb-0"><span class="text-success">$</span> npm install <span class="text-success">-g</span> claps.js</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
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

span{
    color: $secondary-color;
    font-weight: bold;
}

.col-3{
    width: calc((100% / 4) - 1rem);
    margin: .5rem;
}

.text-centered{
    padding: 0 8rem;
}

.tab-content p{
    color: $text-color;
    text-align: left;
}

.nav-bg{
    background-color: #3C4858;
    margin: 0 4rem;
    margin-bottom: 3rem;
}

li.nav-item{
    background-color: #575f69;
    margin-top: .5rem;
}

</style>