<template>
    <div class="container-fluid">
        <div class="row">
            <div class="col-lg-2 col-sm-0"></div>
            <div class="col-lg-8  col-sm-12">
                <section>
                    <div class="container">
                        <div class="row py-4">
                            <div class="d-flex justify-content-between">
                                <a name="" id="" class="btn fw-medium fs-6" style="color: #1e70a8;" href="#"
                                    role="button">Back to Meals</a>
                                <button type="button" class="btn btn-primary fw-medium px-4 fs-6">Recipe</button>
                            </div>
                        </div>
                    </div>
                </section>
                <section>
                    <div class="container">
                        <div class="row py-5">
                            <h1 class="fw-bold fs-2 text-center"> Scrambled Eggs with Wholemeal Toast </h1>
                        </div>
                        <div class="row py-4 p-2">
                            <div class="col-lg-5 col-sm-12">
                                <h5 class="fw-bolder pb-3 text-dark">
                                    Ingredients
                                </h5>
                                <ul class=" fs-6 ">
                                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> 2 Large Eggs
                                        (110g)</p>
                                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> 2 Slices of
                                        Wholemeal Toast</p>
                                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> 100g Butter</p>
                                </ul>
                            </div>
                            <div class=" col-md-7 text-end mt-5 col-sm-12 align-item-end "><img class=" w-100"
                                    src="/Assets/Tuna Salad Recipe.jpg" style="margin-top:-65px!important;" alt=""></div>
                        </div>
                    </div>
                </section>
                <section>
                    <div class="container">
                        <div class="row">
                            <h4 class="fw-semibold text-dark pb-4">Recipe</h4>
                        </div>
                        <div class="col-8">
                            <ul class=" fs-6">
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Crack the Eggs into
                                    bowl and Whisk them until well beaten.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Heat a non-stick pan
                                    on medium heat and add the butter.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Once the butter has
                                    melted, pour the beaten eggs into pan.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Lets the eggs sit for
                                    a few seconds to start cooking, the gently stir them with a spatula.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Continue stirring the
                                    eggs occasionally untill they are mostly cooked but still slightly runny.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Remove the pan from
                                    heat and let the residual heat finish cookung the eggs to your desired consistency.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> While the eggs are
                                    cooking. toast the wholemeal slices of bread.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Once the eggs and
                                    toast are ready,serve the scrambled eggs on top of the wholemeal bread slices.</p>
                                <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Enjoy your delicious
                                    Scrambled Eggs with Wholemeal Toast!</p>
                            </ul>
                        </div>
                        <div class="col-12 d-flex m-auto d-block justify-content-evenly py-5">
                            <div class="">
                                <h3 class=" text-center fw-bolder">580</h3>
                                <span class="text-dark fw-medium ms-2"> Calories </span>
                            </div>
                            <div style="height: 52px;" class="border border-1 border-danger mt-1"></div>
                            <div class="">
                                <h3 class=" text-center fw-bolder">40g</h3>
                                <span class="text-dark fw-medium ms-2"> Protein </span>
                            </div>
                            <div style="height: 52px;" class="border border-1 border-danger mt-1"></div>
                            <div class="">
                                <h3 class=" text-center fw-bolder">80g</h3>
                                <span class="text-dark fw-medium ms-3"> Carbs </span>
                            </div>
                            <div style="height: 52px;" class="border border-1 border-danger mt-1"></div>
                            <div class="">
                                <h3 class=" text-center fw-bolder">10g</h3>
                                <span class="text-dark fw-medium ms-2"> Fat </span>
                            </div>
                        </div>
                    </div>
                </section>
        </div>
    </div>
</div></template>
<script>
export default {
    name: 'ScrambledRecipe'
}
</script>
<style>
 @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');
.container-fluid {
    font-family: 'Poppins', sans-serif !important;
    background-color: #fcf8f9;
} 
.border-danger {
            border-color: #1e70a8 !important;
        }
        .btn-primary{
           background-color: #1e70a8!important;
        }
        h1,h2,h3{
           color: #1e70a8;
        }
        a{
           text-decoration: none;
        }
        .container-fluid{
            background-color: #fcf8f9;
        }
</style>