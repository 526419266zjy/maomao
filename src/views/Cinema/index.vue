<template>
    <div id="main" >
        <Header title="猫猫电影院" />
         hello Cinema
       <TabBar></TabBar>
    </div>
</template>

<script>
import Header from "@/components/Header";
import TabBar from "@/components/TabBar";
export default {
    name:"Cinema",
    components: {
        Header,
        TabBar
    }
}
</script>
 <style >
     
 </style>