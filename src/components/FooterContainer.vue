<template>
     <div class="footer-container"><!--footer-container--> 
        <!--column-categories-->
        <div class="column-categories">
            <div class="column__nazvanie">
                <p>Категории</p>
            </div>
            <div class="column__punkty">

                <p><a href="#">Кольца</a></p>
                <p><a href="#">Часы</a></p>
                <p><a href="#">Браслеты</a></p>
                <p><a href="#">Брелки</a></p>
                <p><a href="#">Цепи</a></p>
                <p><a href="#">Серьги</a></p>
                <p><a href="#">Ожерелья</a></p>
   
            </div>
        </div><!--column-categories-->

         <!--column-information-->
         <div class="column-information">
            <div class="column__nazvanie">
                <p>Информация</p>
            </div>
            <div class="column__punkty">

                <p><a href="#">Обратная связь</a></p>
                <p><a href="#">Партнерская программа</a></p>
                <p><a href="#">Возврат товара</a></p>
                <p><a href="#">Блог</a></p>
                <p><a href="#">Карта сайта</a></p>
            
            </div>
        </div><!--column-information-->

        <!--column-contact-us-->
        <div class="column-contact-us">
            <div class="column__nazvanie">
                <p>Контакты</p>
            </div>
            <div class="column__punkty">

                <p><a href="#">Телефон :</a></p>
                <p><a href="#">+10-987-654-32-10</a></p>
                <p><a href="#">Эл. почта :</a></p>
                <p><a href="#">koltsa@yuvelir.com</a></p>
                <p>  </p>
            
            </div>
        </div><!--column-contact-us-->

        <!--column-subscribe-->
        <div class="column-subscribe">
            <div class="column__nazvanie">
                <p>Подписаться</p>
            </div>
            <div class="column__punkty">

                <p><a href="#"><i class="fa fa-facebook" aria-hidden="true"></i></a></p>
                <p><a href="#"><i class="fa fa-twitter" aria-hidden="true"></i></a></p>
                <p><a href="#"><i class="fa fa-linkedin" aria-hidden="true"></i></a></p>
                <p><a href="#"><i class="fa fa-google-plus" aria-hidden="true"></i></a></p>
                <p> </p>
            
            </div>
        </div><!--column-subscribe-->

    <div class="footer-copyrating">
        Интернет-бутик "КОРОНА - ЮВЕЛИР" © 2022
    </div>

    </div><!--footer-container-->

    <!--footer-container--> 
   
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
.footer-container {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  flex-wrap: wrap;
  /*width: 1200px;*/
  width: 100%;
  max-width: 1200px;
  /*min-width: 0;*/
  height: 500px;
  /*max-height: 100%;*/
  height: auto;
  margin: 60px 0 0 0;
  /*padding: 10px 0 10 px 0;*/
  padding-top: 50px;
  /*background: #f5ebe9;*/
  /*background: #F3F1ED;*/
  background-color: #faf8f8;
  /*border: 2px solid rgb(29, 228, 211);*/
}

.column-categories {
 padding-left: 10px;
  padding-top: 10px;
  width: 250px;
  max-height: 100%;
  /*border: 2px solid rgb(29, 228, 211);*/

}

.column__nazvanie {
  padding-top: 10px;
  text-transform: uppercase;
  font-size: 28px;
  font-stretch: condensed;
}

.column-information {
  /*margin-top: 10px;*/
  padding-left: 10px;
  padding-top: 10px;
  width: 250px;
  max-height: 100%;
  /*border: 2px solid rgb(29, 228, 211);*/
}

.column__punkty {
  margin-top: 10px;
  padding-bottom: 10px;
}

.column__punkty > p {
  margin-top: 10px;
  padding-bottom: 10px;
}

.column-contact-us {
  /*margin-top: 10px;*/
  padding-left: 10px;
  padding-top: 10px;
  width: 300px;
  max-height: 100%;
  /*border: 2px solid rgb(29, 228, 211);*/
}

.column-subscribe {
  /*margin-top: 10px;*/
  padding-left: 10px;
  padding-top: 10px;
  width: 300px;
  max-height: 100%;
  /*border: 2px solid rgb(29, 228, 211);*/
}

.footer-copyrating {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
  width: 1200px;
  /*width: 100%;*/
  /*max-width: 1200px;*/
  min-width: 0;
  height: 500px;
  /*max-height: 100%;*/
  height: auto;
  margin: 60px 0 60px 0;
  /*padding: 10px 0 10 px 0;*/
  padding-top: 50px;
  padding-bottom: 50px;
  /*background: #f5ebe9;*/
  /*background: #F3F1ED;*/
  background-color: #faf8f8;
  /*border: 2px solid rgb(29, 228, 211);*/
}


</style>
