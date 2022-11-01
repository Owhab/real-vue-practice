<template>
  <div class="event-card">
    <h1>Hello World</h1>
  </div>
  
</template>

<script>
export default {
  name: 'EventCard',
 /*  props: {
    msg: String
  } */

  data(){
    return{
      event: {
        id: 5928101,
        category: "animal welfare",
        title: "Cat Adoptation Day",
        description: "FInd your new feline friend at this event",
        location: "Meow Town",
        data: "January 28, 2022",
        time: "12:00",
        petsAllowed: true,
        organizer: "Kal Laydee"
      }
    }
  }
}
</script>

<style scoped>

.event-card{
  padding: 20px;
  width: 250px;
  cursor: pointer;
  border: 1px solid #;
}

</style>
