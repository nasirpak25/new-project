<template>
<div class=" container py-5">
        <div class="row">
            <div class="col-lg-2 col-sm-0"></div>
            <div class="col-lg-8 col-sm-12">
                <section class="d-md-block d-lg-block d-none">
                    <div class="container">
                        <div class="row py-4 px-4 ">
                            <div class="col-5 d-flex">
                                <div class="">
                                    <span class="px-2 py-1 text-white fw-semibold mx-2"
                                        style="background-color: #1e70a8;border-radius: 50%; ">1</span>
                                    <span class="" style="color: #1e70a8;font-weight: 600;">Details</span>
                                </div>
                                <div class=""
                                    style="border: solid 1px; width: 54%; height: 0%; margin-left: 20px; margin-top: 13px;">
                                </div>
                            </div>
                            <div class="col-5 d-flex">
                                <div> <span class="px-2 py-1 fw-semibold mx-2"
                                        style="color: #1e70a8; background-color: white;border-radius: 50%; ">2</span>
                                    <span class="" style="color: #1e70a8;font-weight: 600;">AI Magic</span>
                                </div>
                                <div
                                    style="border: solid 1px; width: 45%; height: 0%; margin-left:20px; margin-top: 13px;">
                                </div>
                            </div>
                            <div class="col-2">
                                <span class=" fw-semibold"
                                    style="color: #1e70a8; background-color:white;border-radius: 50%; ">3</span>
                                <span class="" style="color: #1e70a8;font-weight: 600;">plan</span>
                            </div>  
                        </div>
                    </div>
                </section>
                <section>
                    <div class="container">
                        <div class="row py-4">
                            <div class=" mx-3">
                                <h1 class="fw-bold display-4 d-md-block d-none">Create your meal plan</h1>
                                <h1 class="fw-bold display-6 d-md-none d-block">Create your meal plan</h1>
                                <p class="fw-medium py-3 fs-5 paragraph">We just need some vital information about
                                    yourself and your dietary goals and need to tailor a specific mealplan for you </p>
                            </div>
                        </div>
                    </div>
                </section>
                <section>
                    <div class="container py-lg-">
                        <div class="row g-5" style="color: #1e70a8; font-weight: 500;">
                            <div class="col-lg-4 col-sm-6 col-md-4 col-12">
                                <div class="mb-3">
                                    <label for="" class="form-label">Age</label>
                                    <input type="text" class="form-control border-white" name="" id=""
                                        aria-describedby="helpId" placeholder="">
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6 col-md-4 col-12">
                                <div class="mb-3">
                                    <label for="" class="form-label">Height (Centimeters)</label>
                                    <input type="text" class="form-control border-white" name="" id=""
                                        aria-describedby="helpId" placeholder="">
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6 col-md-4 col-12">
                                <div class="mb-3">
                                    <label for="" class="form-label">Weight (KG)</label>
                                    <input type="text" class="form-control  border-white" name="" id=""
                                        aria-describedby="helpId" placeholder="">
                                </div>
                            </div>
                        </div>
                        <div class="row g-5 py-2" style="color: #1e70a8; font-weight: 500;">
                            <div class="col-lg-4 col-sm-6 col-md-4 col-12">
                                <div class="mb-3">
                                    <label for="" class="form-label">Sex</label>
                                    <select class="form-select form-select-lg fs-6 border-white"
                                        style="color: #1e70a8; font-weight: 400;" name="" id="">
                                        <option selected>Male</option>
                                        <option value="">Femail</option>
                                        <option value="">Others</option>
                                    </select>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6 col-md-4 col-12">
                                <div class="mb-3">
                                    <label for="" class="form-label">Goal and aspiration</label>
                                    <select class="form-select form-select-lg  fs-6  border-white"
                                        style="color: #1e70a8; font-weight: 400;" name="" id="">
                                        <option selected>Build Muscle</option>
                                        <option value="">Energetic</option>
                                        <option value="">Build body</option>
                                    </select>
                                </div>
                            </div>
                            <div class="col-lg-4 col-sm-6 col-md-4 col-12">
                                <div class="mb-3">
                                    <label for="" class="form-label ">Meal count per day</label>
                                    <select class="form-select form-select-lg border fs-6  border-white"
                                        style="color: #1e70a8; font-weight: 400;" name="" id="">
                                        <option selected>3</option>
                                        <option value="">4</option>
                                        <option value="">5</option>
                                    </select>
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="row" style="color: #1e70a8; font-weight: 500;">
                        <div class="">
                            <div class="mb-3">
                                <label for="" class="form-label fs-6">Diet</label>
                                <select class="form-select form-select-lg fs-6 border  border-white"
                                    style="color: #1e70a8; font-weight: 400;" name="" id="">
                                    <option selected>Anything</option>
                                    <option value="">Anything</option>
                                    <option value="">Anything</option>
                                </select>
                            </div>
                        </div>
                        <div class="">
                            <div class="mb-3  py-4">
                                <label for="" class="form-label fs-6">Any allergies or ingredients you don't want to
                                    see in your meals?</label>
                                <select class="form-select form-select-lg border  border-white"
                                    style="color: #1e70a8; font-weight: 400;" name="" id="">
                                    <option selected></option>
                                    <option value="">---</option>
                                    <option value="">---</option>
                                </select>
                            </div>
                        </div>
                    </div>
                    <div class="row">
                        <div class="col-6">
                            <button type="button"
                                class="btn btn-primary mt-lg-5 mt-sm-3 mt-3 mx-lg-2 mx-md-2 px-4 py-2"> Generate
                                meal plan</button>
                        </div>
                        <div class="col-6">
                            <img class="m-auto d-block w-lg-75 w-100 " src="/Assets/meal-plan.jpg" alt="">
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
    name:'MealPlan'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');

.btn-primary {
    background-color: #1e70a8 !important;
}
.container {
    font-family: 'Poppins', sans-serif !important;
    background-color: #fcf8f9;
}
h1,
h2 {
    color: #1e70a8!important;
    font-family: 'Poppins', sans-serif !important;
}
a {
    text-decoration: none;
}
</style>