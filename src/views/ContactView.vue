<template>
<section class="container" id="productos">
  <h1 class=" text-center">Contacto</h1>
  <form action="">
    <div class="mb-3">
      <label for="exampleFormControlInput1" class="form-label">Email address</label>
      <input type="email" class="form-control" id="exampleFormControlInput1" placeholder="name@example.com">
    </div>
    <div class="mb-3">
     <label for="exampleFormControlTextarea1" class="form-label">Example textarea</label>
     <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
    </div>
  </form>
  <div class="row">
    <button @click="volverAlInicio" class="btn btn-primary" >Ir a Inicio</button>
  </div>
    <RouterView />
</section>
</template>
<script>
export default {
  methods: {
    volverAlInicio() {
      this.$router.push({ name: 'inicio' })
    }
  }
}
</script>
