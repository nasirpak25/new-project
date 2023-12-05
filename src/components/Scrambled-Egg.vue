<template>
 <div class="container-fluid">
        <div class="row">
            <div class="col-lg-2 .col-sm-0"></div>
            <div class="col-lg-8 col-sm-12">
                <section>
                    <div class="container ">
                        <div class="row pt-4 pb-4">
                            <div class="d-flex justify-content-between">
                                <a name="" id="" class="btn fw-medium fs-5  " style="color: #1e70a8;" href="#"
                                    role="button">Back to Meals</a>
                                <button
                                    class="border-0 text-white btn-primary fw-medium py-2 fs-6 px-5">Recipe</button>
                            </div>
                        </div>
                    </div>
                </section>
                <section>
                    <div class="container">
                        <div class="row py-3 p-2 justify-content-center p-5">
                            <div class=" col-12 text-center"><img class="w-75" src="/Assets/Scrambled Egg.jpg" alt="">
                            </div>
                        </div>
                        <div class="row text-center">
                            <h1 class="fw-bold f1">Scrambled Eggs <span class="mx-2 fs-4"> with Wholemeal Toast</span></h1>
                        </div>
                    </div>
                </section>
                <section>
                    <div class="container">
                        <div class="row">
                            <div class="col-lg-1 col-sm-0"></div>
                            <div class="col-lg-10 col-sm-12 py-2">
                                <div class="bg-white text-center p-3 mt-3">
                                    <h5 class="fs-6">Whipping up your recipe, this'll just take a few seconds.....</h5>
                                </div>
                            </div>
                            <div id="heading" class="col-lg-1 col-sm-0"></div>
                        </div>
                        <div class="col-8 d-flex m-auto d-block justify-content-evenly mt-4">
                            <div class="">
                                <h2 class=" text-center fw-bolder">2095</h2>
                                <p class="text-dark fw-normal fs-6 ms-2"> Calories </p>
                            </div>
                            <div style="height: 70px;" class="border-1 border"></div>
                            <div class="">
                                <h2 class=" text-center fw-bolder">150g</h2>
                                <p class="text-dark fw-normal fs-6 ms-2"> Protein </p>
                            </div>
                            <div style="height: 70px;" class="border-1 border"></div>
                            <div class="">
                                <h2 class=" text-center fw-bolder">235g</h2>
                                <p class="text-dark fw-normal fs-6 ms-2"> Carbs </p>
                            </div>
                            <div style="height: 70px;" class="border-1 border"></div>
                            <div class="">
                                <h2 class=" text-center fw-bolder">55g</h2>
                                <p class="text-dark fw-normal fs-6 ms-3"> Fat </p>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
            <div class="col-lg-2 col-sm-0"></div>
        </div>
    </div>
</template>

<script>
export default{
    name:'ScrambledEgg'
}
</script>
<style>

 @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');
.container-fluid {
    font-family: 'Poppins', sans-serif !important;
    background-color: #fcf8f9;
}
.container-fluid {
    background-color: #fcf8f9;
}
.btn-primary {
    background-color: #1e70a8 !important;
}
h1,
h2 {
    color: #1e70a8;
}
a {
    text-decoration: none;
}
</style>