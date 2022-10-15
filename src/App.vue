<template>
  <NavBar />
  <router-view/>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.css';
import 'bootstrap/dist/js/bootstrap';//当界面缩小时能将折叠的菜单打开
import NavBar from './components/NavBar';


export default{
  name:"App",
  components:{
    NavBar,

}
}

</script>

<style>

</style>
