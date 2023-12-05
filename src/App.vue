<script setup>

// import mondayplan from './components/monday-meal-plan.vue'
// import card from './components/card.vue'
import mealplan from './components/meal-plan.vue'
// import Tunasalad from './components/Tuna-Salad.vue'
// import scrambledEgg from './components/Scrambled-Egg.vue'
// import scrambledrecipe from './components/Scrambled-resipe.vue'

</script>

<template>
   <div>
      <div class="header">
        <!-- <div class="container"> -->
          <div class="row justify-content-center my-4">
            <div class="col-9 d-flex text-center justify-content-between">
              <span> <a href="#">Meal Plan</a> </span>
              <span> <a href="#">Monday Plan</a> </span>
              <span> <a href="#">Scrambled Egg</a> </span>
              <span> <a href="#">Scrambled Recipe</a> </span>
              <span> <a href="#">Tuna Salad</a> </span>
              <span> <a href="#">Card</a> </span>
            </div>
          </div>
        <!-- </div> -->
      </div>
    </div>
  <main>

     <!-- <mondayplan /> -->
     <!-- <card /> -->
     <mealplan />
     <!-- <Tunasalad /> -->
     <!-- <scrambledEgg /> -->
     <!-- <scrambledrecipe /> -->
  </main>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;700&display=swap');

template {
    font-family: 'Poppins', sans-serif !important;
    background-color: #fcf8f9;
}
a {
  text-decoration: none;

  color: black;
  font-weight: 700;

}
span{

  padding: 5px;
}
</style>
