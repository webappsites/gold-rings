<template>

        <!--bej-polosa-container-->
         <div class="bej-polosa-container">
              <div class="bej-polosa">
             
               </div>
         </div> <!--bej-polosa-container-->
   
  </template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>


.bej-polosa-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  /*flex-wrap: wrap;*/
  width: 1200px;
  max-width: 100%;
  min-width: 0;
  height: 46px;
  max-height: 100%;
  margin: 40px 0 20px 0;
  /*padding: 10px 0 10 px 0;*/
  /*border: 2px solid rgb(32, 29, 228);*/
}

.bej-polosa {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
  height: 100%;
  /*background-color: #f5ebe9;*/
  /*background: #f5ebe9;*/
  background: #F3F1ED;
  /*border: 3px solid rgb(134, 199, 31); */
}


</style>
