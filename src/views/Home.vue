<template>
    <EventCard v-for="event in events" :key="event.id" :event="event" />

</template>
<script>

import EventCard from '@/components/EventCard.vue';
export default {
    // eslint-disable-next-line
  name: 'Home',
  components: {
    EventCard
  },
  data(){
    return{
        events: [
            { id: 5928101,
                category: "animal welfare",
                title: "Cat Adoptation Day",
                description: "FInd your new feline friend at this event",
                location: "Meow Town",
                date: "January 28, 2022",
                time: "12:00",
                petsAllowed: true,
                organizer: "Kal Laydee"
            },
            { id: 59281001,
                category: "Vue Js Conf",
                title: "Vue JS Conference",
                description: "FInd your new feline friend at this event",
                location: "Town Hall, Dhaka",
                date: "January 30, 2022",
                time: "03:00",
                petsAllowed: true,
                organizer: "Abdul Owhab"
            },
            { id: 592801001,
                category: "React Conf",
                title: "React JS Conference",
                description: "FInd your new feline friend at this event",
                location: "Town Hall, Dhaka",
                date: "January 30, 2022",
                time: "03:00",
                petsAllowed: true,
                organizer: "Abdul Owhab"
            },
            { id: 592801001,
                category: "Laravel Conf",
                title: "Laravel Conference",
                description: "FInd your new feline friend at this event",
                location: "Town Hall, Dhaka",
                date: "January 30, 2022",
                time: "03:00",
                petsAllowed: true,
                organizer: "Abdul Owhab"
            },
        ]
    }
  }
}
</script>

<style>

</style>
