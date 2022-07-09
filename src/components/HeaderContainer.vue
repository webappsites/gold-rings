<template>
        <div class="header-container"><!--header-container-->
             <nav class="nav-left">           
                    <a href="#">главная</a>
                    <a href="#">категории</a>
                    <a href="#">о нас</a>
                    <a href="#">наши контакты</a>
            </nav>
             <div class="logo-center">
                <a href="#">
                <img src="../assets/img/logo-korona-1.png" title="Jewelry" alt="Jewelry">
                </a>
             </div>
             
             <div class="header-account">
                <a href="#">личный кабинет</a>
             </div>
             <nav class="nav-right">                  
                    <a href="#">
                    <i class="fa fa-shopping-bag" aria-hidden="true"></i>
                    </a>
                    <a href="#">
                    <i class="fa fa-search" aria-hidden="true"></i>    
                    </a>
             </nav>

         </div> <!--header-container-->  
<!--<div>privet</div>-->
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
.header-container {
  margin: 0px auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  flex-wrap: wrap;
  width: 1200px;
  max-width: 100%;
  min-width: 0;
  height: 108px;
  height: auto;
  /*min-height: 100%;*/
  margin: 20px 0 20px 0;
  padding: 10px 0 10 px 0;
  /*background: #f5ebe9;*/
  background: #faf8f8;
  /*border: 4px solid rgb(99, 29, 228);*/
}

nav {
  display: flex;  
  flex-wrap: wrap;
  text-transform: uppercase;
   /*width: 855px;*/
  height: auto;
  margin: 10px 0 10px 0;
  /*border: 4px solid rgb(138, 23, 28);*/
}

.nav-left {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  /*width: 1200px;*/
  height: auto;
  margin: 10px 0 10px 0;
  /*border: 2px solid rgb(29, 228, 211);*/
}

.nav-left > a {
  display: flex;
  margin: 10px 15px 5px 0;
  height: auto;
  font-size: 13px;
  line-height: 20px;
  font-weight: 600;
  letter-spacing: 1.1px;
  color: #7b6e6d;
  /*border: 1px solid red;*/
}

.logo-center {
 /* margin-left: -7px;*/
  max-width: 140px;
  width: 100%;
  max-height: 150px;
  height: auto;

  /*border: 3px solid red;*/
}

.logo-center > a > img {
  /*margin-left: -7px;*/
  /*max-width: 290px;*/
  width: 100%;
  /*max-height: 90px;*/
  height: auto;
  /*border: 1px solid red;*/
}

.header-account > a {
  display: flex;
  margin: 0 35px;
  height: auto;
  font-size: 13px;
  line-height: 20px;
  font-weight: 600;
  letter-spacing: 1.1px;
  text-transform: uppercase;
  color: #7b6e6d;
  /*border: 1px solid red;*/
}

.nav-right {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  /*width: 1200px;*/
  height: auto;
  margin: 10px 0 10px 0;
  /*border: 2px solid rgb(29, 228, 211);*/
}

.nav-right > a {
  display: flex;
  margin: 10px 35px 5px 35px;
  height: auto;
  font-size: 17px;
  line-height: 20px;
  font-weight: 400;
  letter-spacing: 1.1px;
  color: #7b6e6d;
  /*border: 1px solid red;*/
}

</style>
