<template>
<div class="container-fluid">
        <div class="row">
            <div class="col-lg-2 col-sm-0"></div>
            <div class="col-lg-8  col-sm-12">
    <section>
        <div class="container"> 
            <div class="row py-4">
                <div class="d-flex justify-content-between">
                    <a name="" id="" class="btn fw-medium fs-6" style="color: #1e70a8;" href="#" role="button">Back to Meals</a>
                    <button type="button" class="btn btn-primary fw-medium  px-4 fs-6">Recipe</button>
                </div>
            </div>
        </div>
    </section>
    <section>
        <div class="container">
            <div class="row pt-5">
                <h1 class="fw-bold fs-2">Tuna Salad with Quinao</h1>
            </div>
            <div class="row">
                <div class="col-lg-5 col-sm-12 mb-sm-2">
                    <h6 class="fw-medium  mt-5 text-dark">
                        Ingredients
                    </h6>
                    <ul class=" fs-6 fw-normal">
                        <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> 1 can of Tuna (80g)</p>
                        <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> 100g Quinoa</p>
                        <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Mixed Salad (200g)</p>
                        <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> 20g Olive oil</p>
                    </ul>
                </div>
                <div class=" col-md-7 text-end mt-5 col-sm-12 align-item-end "><img class=" w-100" src="/Assets/Tuna Salad Recipe.jpg" style="margin-top:-45px!important;" alt=""></div>
            </div>
        </div>  
    </section>
    <section>
        <div class="container">
            <div class="row">
                <h3 class="fw-medium text-dark py-4">Recipe</h3>
            </div>
            <div class="col-9 ">
                <ul  class=" fs-6 fw-normal">
                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span>  Crack the Eggs into bowl and Whisk them until well beaten.</p>
                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Heat a non-stick pan on medium heat and add the butter.</p>
                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Once the butter has melted, pour the beaten eggs into pan.</p>
                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Lets the eggs sit for a few seconds to start cooking, the gently stir them with a spatula.</p>
                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Continue stirring the eggs occasionally untill they are mostly cooked but still slightly runny.</p>
                    <p><span class="me-2"><img src="/Assets/right-icon.jpg" alt=""></span> Remove the pan from heat and let the residual heat finish cookung the eggs to your desired consistency.</p>    
                </ul>
            </div>
            <div class="col-8 d-flex m-auto d-block justify-content-evenly py-5 mt-5">
                <div class="">
                    <h3 class=" text-center fw-bolder">660</h3>
                    <p class="text-dark fw-medium text-center" style="font-size: 12px; margin-top: -10px;"> Calories </p>
                </div>
                <div style="height: 52px;" class="border border-1 border-danger mt-1"></div>                  
                <div class="">
                    <h3 class=" text-center fw-bolder">35g</h3>
                    <p class="text-dark fw-medium text-center" style="font-size: 12px; margin-top: -10px;"> Protein  </p>
                </div>
                <div style="height: 52px;" class="border border-1 border-danger mt-1"></div>
                <div class="">
                    <h3 class=" text-center fw-bolder" >75g</h3>
                    <p class="text-dark fw-medium text-center" style="font-size: 12px; margin-top: -10px;"> Carbs  </p>
                </div>
                <div style="height: 52px;" class="border border-1 border-danger mt-1"></div>
                    <div class="">
                    <h3 class=" text-center fw-bolder" >20g</h3>
                    <p class="text-dark fw-medium text-center" style="font-size: 12px ; margin-top: -10px;"> Fat  </p>
                </div>
            </div>
        </div>
    </section>
</div>
</div>
</div>
</template>
<script>
export default{
    name:'TunaSalad'
}
</script>

<style>

@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');
.container-fluid {
    font-family: 'Poppins', sans-serif !important;
    background-color: #fcf8f9;
}
        .container-fluid{
            background-color: #fcf8f9;
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
        .border-danger {
            border-color: #1e70a8 !important;
        }
</style>