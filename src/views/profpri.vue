<template>
<div class="container">
    <h1> <span class="badge badge-secondary"></span></h1>
    <div class="btn-group-vertical btn-group-lg" role="group" aria-label="Basic example">
  <button  type="button" class="btn btn-secondary">Ante Antic</button>
  <button  type="button" class="btn btn-secondary">Ivo Ivic</button>
  <button  type="button" class="btn btn-secondary">David Davidov</button>
  <button  type="button" class="btn btn-secondary">Borna Boban</button>
  <button  type="button" class="btn btn-secondary">Olaf Olafic</button>
  <!-- Svaki ucenik ce biti u bazi podataka -->
</div>
</div>
</template>

<style scoped>
 
 .btn {
     margin-top: 100px;
 }
</style>

<script>
import Swal from 'sweetalert2'

export default {

    methods: {
        Alert() {
      // Use sweetalert2
      Swal.fire({
  title: 'Uspjesno pohranjeno!',
  
  
})
    },
    }
}
</script>
