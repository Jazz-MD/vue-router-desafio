<template>
<section class="container" id="productos">
  <h1 class=" text-center">Contacto</h1>
  
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
