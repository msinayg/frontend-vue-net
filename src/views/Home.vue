<template>
  <div class="home">
    <ListarEmpleados />
  </div>
</template>

<script>
import ListarEmpleados from '@/components/empleados/ListarEmpleados.vue'

export default {
  name: 'Empleados',
  components: {
    ListarEmpleados
  }
}
</script>
