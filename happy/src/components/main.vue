<template>
  <div class="hello">
    <h1>{{msg}}</h1>
    <button>Iniciar o Tutorial de uso</button>
  </div>
</template>

<script>
export default {
  name: 'msg',
  props: {
    msg: String
  }
}
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
button {
   border-top: 1px solid #98f59e;
   background: #064169;
   background: -webkit-gradient(linear, left top, left bottom, from(#088566), to(#064169));
   background: -webkit-linear-gradient(top, #088566, #064169);
   background: -moz-linear-gradient(top, #088566, #064169);
   background: -ms-linear-gradient(top, #088566, #064169);
   background: -o-linear-gradient(top, #088566, #064169);
   padding: 20px 40px;
   -webkit-border-radius: 28px;
   -moz-border-radius: 28px;
   border-radius: 28px;
   -webkit-box-shadow: rgba(0,0,0,1) 0 1px 0;
   -moz-box-shadow: rgba(0,0,0,1) 0 1px 0;
   box-shadow: rgba(0,0,0,1) 0 1px 0;
   text-shadow: rgba(0,0,0,.4) 0 1px 0;
   color: #ffffff;
   font-size: 15px;
   font-family: Georgia, serif;
   text-decoration: none;
   vertical-align: middle;
   }
.button:hover {
   border-top-color: #285978;
   background: #285978;
   color: #7680f0;
   }
.button:active {
   border-top-color: #f2faff;
   background: #f2faff;
   }
</style>
