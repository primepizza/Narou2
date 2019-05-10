<template>
  <div>
     <h1>{{msg}}</h1>
     <counter/>
     <Itemlist/>
  </div>
</template>

<script>
import Counter from "./Counter.vue";
import Itemlist from "./Itemlist.vue"
export default {
  name: "HelloWorld",
  props: {
    msg: String
  },
  components:{
    Counter,
    Itemlist
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
