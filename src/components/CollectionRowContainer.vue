<template>

        <!--collection-row-container-->
        <div class="collection-row-container">
           <!--izdelie-1-row-->
           <div class="izdelie-1-row">
              <!--image-collection-1-->
              <div class="image-izdelie-1-row">
                <img src="../assets/img/golden-ring.png" alt="серьги">
              </div><!--image-izdelie-1-row-->
              <div class="nazvanie-izdeliya">
                <p>Кольцо Etincelle de Cartier</p>
            </div>
            <div class="material-izdeliya">
                <p>розовое золото 750/1000, <br />инкрустировано 17 бриллиантами классической огранки <br />общим весом 0,48 карата <br />(для размера 52)</p>
            </div>
            <div class="cena-izdeliya">
                <p>1'150'000 руб.</p>
            </div>
           </div><!--izdelie-1-row-->

           <!--izdelie-2-row-->
           <div class="izdelie-1-row">
            <!--image-collection-1-->
            <div class="image-izdelie-1-row">
              <img src="../assets/img/golden-ring-22.png" alt="серьги">
            </div><!--image-izdelie-1-row-->
            <div class="nazvanie-izdeliya">
                <p>Кольцо Etincelle de Cartier</p>
            </div>
            <div class="material-izdeliya">
                <p>розовое золото 750/1000, <br />инкрустировано 25 бриллиантами классической огранки <br />общим весом 0,48 карата. <br />Ширина: 1,52 мм. <br />Толщина: 1,35 мм. <br />Диаметр узора: 7,8 мм. <br />Толщина рисунка: 3,3 мм <br />(для размера 52)</p>
            </div>
            <div class="cena-izdeliya">
                <p>920'000 руб.</p>
            </div>
         </div><!--izdelie-2-row-->     
 
           <!--izdelie-3-row-->
          <div class="izdelie-1-row">
            <!--image-collection-1-->
            <div class="image-izdelie-1-row">
              <img src="../assets/img/golden-ring-2.png" alt="серьги">
            </div><!--image-izdelie-1-row-->
            <div class="nazvanie-izdeliya">
                <p>Кольцо Etincelle de Cartier</p>
            </div>
            <div class="material-izdeliya">
                <p>розовое золото 750/1000, <br />инкрустировано 18 бриллиантами классической огранки <br />общим весом 0,63 карата <br />(для размера 52)</p>
            </div>
            <div class="cena-izdeliya">
                <p>1'115'000 руб.</p>
            </div>
         </div><!--izdelie-3-row-->  

         <!--izdelie-4-row-->
         <div class="izdelie-1-row">
            <!--image-collection-1-->
            <div class="image-izdelie-1-row">
              <img src="../assets/img/golden-ring-3.png" alt="серьги">
            </div><!--image-izdelie-1-row-->
            <div class="nazvanie-izdeliya">
                <p>Кольцо Etincelle de Cartier, малая модель</p>
            </div>
            <div class="material-izdeliya">
                <p>розовое золото 750/1000, <br />инкрустировано 55 бриллиантами классической огранки <br />общим весом 1 карат. <br />Ширина: 5,10 мм <br />(для размера 52)</p>
            </div>
            <div class="cena-izdeliya">
                <p>1'200'000 руб.</p>
            </div>
         </div><!--izdelie-4-row-->     

        </div> <!--collection-row-container-->

   
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


.collection-row-container {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  width: 1200px;
  max-width: 100%;
  /*min-width: 0;*/
  /*height: 340px;*/
  max-height: 100%;
  height: auto;
  margin: 40px 0 20px 0;
  /*padding: 10px 0 10 px 0;*/
  /*border: 2px solid rgb(32, 29, 228);*/
}

.image-izdelie-1-row {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 270px;
  /*max-width: 100%;*/
  height: 270px;
  min-height: 100%;
  /*border: 3px solid rgb(134, 199, 31); */
}

.image-izdelie-1-row > img{
  width: 100%;
  max-width: 100%;
  height: 100%;
  /*border: 3px solid rgb(134, 199, 31); */
}

.nazvanie-izdeliya {
  margin-top: 10px;
  margin-bottom: 10px;
  padding-left: 10px;
  width: 270px;
  height: 270px;
  max-width: 100%;
  height: 100%;
  font-size: 17px;
  line-height: 20px;
  font-weight: 700;
}

.material-izdeliya {
  margin-bottom: 10px;
  padding-left: 10px;
  width: 270px;
  height: 270px;
  max-width: 100%;
  height: 100%;
  font-size: 15px;
  line-height: 20px;
  font-weight: 500;
}

.cena-izdeliya {
  margin-bottom: 10px;
  padding-left: 10px;
  width: 270px;
  height: 270px;
  max-width: 100%;
  height: 100%;
  font-size: 16px;
  line-height: 20px;
  font-weight: 600;
}


</style>
