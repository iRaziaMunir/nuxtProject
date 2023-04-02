<template>
    <div>
     <AppHeader />  
     
    
      
      
    </div>
  </template>


  <script>
import AppHeader from '../components/inc/AppHeader.vue';
import AppFooter from '../components/inc/AppFooter.vue';
import index from '../pages/index.vue';
import About from '../pages/About.vue';
import contact from '../pages/contact.vue';
import services from '../pages/services.vue';
export default{
    name: 'default',
    components:{
    AppHeader,
    AppFooter,
    index,
    About,
    contact,
    services
    }
}
</script>