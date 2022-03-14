<template>
  <div>
    <Header/>
    <p>{{loremText}}</p>
    <button @click="helloWorld">Hello World!</button>
  </div>
</template>

<script>
// @ is an alias to /src
import Header from '../components/Header.vue'

export default {
  components:{
    Header
  },
  data(){
    return{
      loremText:"This is a text written from the JavaScript."
    }
  },
  methods:{
    helloWorld(){
      console.log("Hello Word!");
    }
  }
}
</script>
