<template>
  <b-container>
    <b-row aliggn-v="center">
      <card></card>
      <card></card>
      <card></card>
      
    </b-row>
  </b-container>
</template>

<script>
// @ is an alias to /src
import Card from '@/components/Card.vue';

export default {
  name: 'Home',
  components: {
   Card
  }
}
</script>
