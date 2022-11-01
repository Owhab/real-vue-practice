<template>
  <div class="event-card">
    <span>@ {{event.time}} on {{event.date}} </span>
    <h1>{{event.title}}</h1>
  </div>
  
</template>

<script>
export default {
  name: 'EventCard',
  props: {
    event: Object
  },

  data(){
    return{
      /* eslint-disable */
      
    }
  }
}
</script>

<style scoped>

.event-card{
  padding: 20px;
  width: 40%;
  cursor: pointer;
  border: 1px solid black;
  margin: 10px auto;
}

.event-card:hover{
  transform: scale(1.01);
  box-shadow: 0 3px 1px 0 rgba(0, 0, 0, 0.2);
}

</style>
