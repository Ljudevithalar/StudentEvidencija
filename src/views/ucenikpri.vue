<template>
<div class="container">
    <h1>[Ime studenta povuceno sa baze] <span class="badge badge-secondary">OIKT</span></h1>
    <div class="btn-group-vertical btn-group-lg" role="group" aria-label="Basic example">
  <button @click="Alert" type="button" class="btn btn-secondary">Prisutan</button>
  <button @click="Alert" type="button" class="btn btn-secondary">Zakasnio</button>
  <button @click="Alert" type="button" class="btn btn-secondary">Nije prisutan</button>
  <button @click="Alert" type="button" class="btn btn-secondary">Osloboden</button>
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
