<template>

         <!--gold-container-->
         <div class="gold-container">
            <div class="gold-text">
                <p>Золотые кольца Картье</p>
            </div>
         </div> <!--gold-container-->
   
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
.gold-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  width: 1200px;
  max-width: 100%;
  min-width: 100%;
  height: auto;
  height: 108px;
  max-height: 100%;
  margin: 40px 0 20px 0;
  /*padding: 10px 0 10 px 0;*/
  /*border: 2px solid rgb(32, 29, 228);*/
}

.gold-text {
 /* font-family:Georgia, 'Times New Roman', Times, serif;*/
  font-size: 20px;
  line-height: 20px;
  font-weight: 700;
  /*font-stretch: condensed;*/
  /*letter-spacing: 1.1px;*/
  color: #7b6e6d;
}

</style>
