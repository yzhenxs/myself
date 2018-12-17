<template>
 <div class="three" :style="{backgroundColor:beijing}">第三个路由
     <br>
   <button @click="bianse">点我变色</button>
   <Sun></Sun>
 </div>
</template>

<script>
import Sun from "./sun"
export default {
  name: 'three',
  components:{
    Sun
  },
  data () {
    return {
        beijing:"blue"
        // msg: 'Welcome to Your Vue.js App'
    }
  },
  methods:{
    bianse(){
     this.beijing='greenyelow'
    }

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

