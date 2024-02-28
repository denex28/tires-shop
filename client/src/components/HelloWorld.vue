<template>
  <div>залупа</div>
  <h1>пупа</h1>
  <button type="button" name="НОВИНКА" class="NEW">НОВИНКА
  </button>
  <button type="button" name="хит" class="hit">ХИТ</button>
  <button type="button" name="РАСПРОДАЖА" class="sale but">РАСПРОДАЖА</button>
  <button type="button" name="-20" class="ss">-20%</button>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'HelloWorld',
  props: {
    msg: String
  }
})
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h3 {
  margin: 40px 0 0;
} 
button {
  font-size: 11px;
  color:white;
  text-align:center;
  font-weight: 500;
  padding: 10px 10px;
  margin:10px 10px;
  font-family:sans-serif;
  border-style: none;
}
.NEW { 
background-color:black ;
}
.hit {background-color:#3F71BC ; 

}
.sale {background-color:#9747FF ;
}
.ss {background-color:
#FF6915;
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
