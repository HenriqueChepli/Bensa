<template>
  <section>
  <div class="marcas">
    <MarcasComponente />
  </div>
  <div class="lancamentos">
    <LancamentosComponente/>
  </div>
  <div class="acessorios">
    <AcessoriosComponente/>
  </div>
  </section>
</template>

<script setup>
import MarcasComponente from '../components/MarcasComponente.vue'
import LancamentosComponente from '../components/LancamentosComponente.vue'
import AcessoriosComponente from '../components/AcessoriosComponente.vue'
</script>

<style>

</style>
