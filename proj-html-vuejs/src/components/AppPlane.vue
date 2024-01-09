<template>
    <main>
        <div class="container text-center">
            <div class="row">
                <div class="col-12 pt-4">
                    <h1 class="pt-4 fs-3">
                        Our rates for developer from landrick team
                    </h1>
                    <p class="pt-4 pb-3 text-centered">
                        Start working with <span>Landrick</span> that can provide everything you need to generate awareness, drive traffic, connect.
                    </p>
                </div>
            </div>

            <!-- Plane offer -->
            <div class="row plane">
                <div class="col-4 mt-4 pt-2">
                        <div class="card pricing pricing-primary business-rate border-0 p-4 rounded-md shadow">
                            <div class="card-body p-0">
                                <span class="py-2 px-4 d-inline-block bg-soft-primary h6 mb-0 text-primary rounded-lg">Basic</span>
                                <h2 class="fw-bold mb-0 mt-3">$9.00</h2>
                                <p class="pb-2 pt-3">Per Month</p>

                                <p class="pb-2">All the basics for businesses that are just getting started.</p>

                                <ul class="list-unstyled pt-3 border-top">
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Full Access</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Enhanced Security</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Source Files</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>1 Domain Free</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Enhanced Security</li>
                                </ul>

                                <div class="mt-4">
                                    <div class="d-grid">
                                        <button class="btn btn-primary">Buy Now</button>
                                    </div>
                                    <p class=" mt-3 mb-0">*No credit card required</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4 mt-4 pt-2">
                        <div class="card pricing pricing-primary business-rate border-0 p-4 rounded-md shadow">
                            <div class="card-body p-0">
                                <span class=" px-4 d-inline-block bg-soft-primary h6 mb-0 text-primary rounded-lg">Business</span>
                                <h2 class="fw-bold mb-0 pt-4">$39.00</h2>
                                <p class="pb-2 pt-3">Per Month</p>

                                <p class="pb-2 pt-1">Better for growing businesses that want more customers.</p>

                                <ul class="list-unstyled pt-3 border-top">
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Full Access</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Enhanced Security</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Source Files</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>1 Domain Free</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Enhanced Security</li>
                                </ul>

                                <div class="mt-4">
                                    <div class="d-grid">
                                        <button class="btn btn-primary">Buy Now</button>
                                    </div>
                                    <p class="mt-3 mb-0">*No credit card required</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="col-4 mt-4 pt-2">
                        <div class="card pricing pricing-primary business-rate border-0 p-4 rounded-md shadow">
                            <div class="card-body p-0">
                                <span class="py-2 px-4 d-inline-block bg-soft-primary h6 mb-0 text-primary rounded-lg">Enterprise</span>
                                <h2 class="fw-bold mb-0 mt-3">$79.00</h2>
                                <p class="pb-2 pt-3">Per Month</p>

                                <p class="pb-2">Advanced features for pros who need more customization.</p>

                                <ul class="list-unstyled pt-3 border-top">
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Full Access</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Enhanced Security</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Source Files</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>1 Domain Free</li>
                                    <li class="h6 mb-0"><span class="icon h5 me-2"><i class="uil uil-check-circle align-middle"></i></span>Enhanced Security</li>
                                </ul>

                                <div class="mt-4">
                                    <div class="d-grid">
                                        <button class="btn btn-primary">Buy Now</button>
                                    </div>
                                    <p class="mt-3 mb-0">*No credit card required</p>
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

p,
li{
    font-size: 1rem;
    color: $text-color;
}

span{
    color: $secondary-color;
    font-weight: bold;
}

.plane{
    text-align: left;
    padding-bottom: 5rem;
}


</style>