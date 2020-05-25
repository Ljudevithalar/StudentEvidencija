<template>
 <div class="sidenav">
  <a href="/naslovnica">Naslovnica</a>
  <a href="/profesor">Profesor</a>
  <a href="/ucenik">Ucenik</a>
</div>




</template>

<script>


export default {
    data(){
    
    },
  name: "Navbar",
  props: {
    msg: String
  }
}

  </script>


  <style>

.sidenav a {
  padding: 6px 8px 6px 16px;
  text-decoration: none;
  font-size: 25px;
  color: #818181;
  display: list-item;
  font-family: 'Gill Sans', 'Gill Sans MT', 'Trebuchet MS', sans-serif;

}

.sidenav a:hover {
  color: #f1f1f1;
}



@media screen and (max-height: 450px) {
  .sidenav {padding-top: 15px;}
  .sidenav a {font-size: 18px;}
}


</style>