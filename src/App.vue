<template>
  <div id="app">
    <!--<img alt="Vue logo" src="./assets/logo.png"> -->
    <!--<HelloWorld msg="Welcome to Your Vue.js App"/>-->
    <!--<HelloWorld> </HelloWorld>-->
   
   <HeaderContainer> </HeaderContainer> 
   <GoldContainer> </GoldContainer> 
   <AboutJewelryContainer> </AboutJewelryContainer> 
   <BejPolosaContainer> </BejPolosaContainer>
   <CollectionRowContainer> </CollectionRowContainer>
   <FooterContainer> </FooterContainer> 
   </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import HeaderContainer from './components/HeaderContainer.vue'
import GoldContainer from './components/GoldContainer.vue'
import AboutJewelryContainer from './components/AboutJewelryContainer.vue'
import BejPolosaContainer from './components/BejPolosaContainer.vue'
import CollectionRowContainer from './components/CollectionRowContainer.vue'
import FooterContainer from './components/FooterContainer.vue'

export default {
  name: 'App',
  components: {
    'HeaderContainer': HeaderContainer,
    'GoldContainer': GoldContainer,
    'AboutJewelryContainer': AboutJewelryContainer,
    'BejPolosaContainer': BejPolosaContainer,
    'CollectionRowContainer': CollectionRowContainer,
    'FooterContainer': FooterContainer,
    //'HelloWorld': HelloWorld   
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: #2c3e50;
  margin-top: 60px;
  margin-left: auto;
  margin-right: auto;
}

body {
  margin: 5px auto;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  width: auto;
  /*height: 100%;*/
  /*height: 100%;*/
  /*min-height: 100%;*/
  /*max-height: 100%;*/
  /*font: 400 13px/20px "Raleway",sans-serif;*/
  /*font-family: 'Times New Roman', Times, serif;*/
  /*font-family:Georgia, 'Times New Roman', Times, serif;*/
  font-family: Raleway, sans-serif;
  color: #898989;
    background: #fff;
  /*border: 2px solid rgb(186, 44, 221);*/
}

a {
    text-decoration: none;
    color: inherit;
  }

</style>
