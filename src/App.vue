<template>
  <div id="app">
    <Calendar></Calendar>
    <slider></slider>
    <dashboard
      Header="Cafe Badilico"
      Body="$ • Italian, Cafe"
      Footer=" Order Now"
      
    ></dashboard>
    <dashboard
      Header="Cafe Mariot"
      Body="$ • Bangladeshi, Cafe"
      Footer="Order now"
    ></dashboard>
    <dashboard
      Header="Indian Dhaba"
      Body="$ • Indian, Cafe"
      Footer="Order Now"
    ></dashboard>
    </div>
      
    
    
    
 
</template>

<script>
import Calendar from './components/Calendar.vue'
import slider from './components/slider.vue'
import dashboard from './components/dashboard.vue'
export default {
  name: 'App',
  components: {
 Calendar,slider,dashboard
  }
}

</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
@import '../node_modules/@syncfusion/ej2-base/styles/material.css';
@import '../node_modules/@syncfusion/ej2-buttons/styles/material.css';
@import '../node_modules/@syncfusion/ej2-inputs/styles/material.css';
@import '../node_modules/@syncfusion/ej2-popups/styles/material.css';
@import '../node_modules/@syncfusion/ej2-lists/styles/material.css';
@import "../node_modules/@syncfusion/ej2-vue-calendars/styles/material.css";
</style>


