<template>
  <div class="col-lg-12 control-section" id="wrapper">
         <ejs-daterangepicker id="daterangepicker" :placeholder="waterMarkText" :min="minDate" :max="maxDate"></ejs-daterangepicker>
    </div>
    
</template>

<script>
import { DateRangePickerPlugin } from "@syncfusion/ej2-vue-calendars";
  export default {
      component: DateRangePickerPlugin,
   data: function() {
    return {
      waterMarkText: "Select a Range",
      minDate: new Date("1/15/2017"),
      maxDate: new Date("12/20/2017")
    };
  }
  };
</script>



<style>
#wrapper {
  max-width: 246px;
  margin: 30px auto;
  padding-top: 15px;
}
</style>








export default {
  
};