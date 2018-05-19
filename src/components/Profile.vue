<template>
  <div>
    <h1 id="title">daremocorn.si</h1>
    <img src="@/assets/logo.jpg" id="avatar">
    <bio></bio>
    <contact-list></contact-list>
  </div>
</template>

<script>
import ContactList from '@/components/ContactList.vue'
import Bio from '@/components/Bio.vue'

export default {
  name: "profile",
  components: {
      ContactList,
      Bio
  }
}
</script>

<style>
#title {
    font-family: Dosis,Open Sans,sans-serif;
}
#avatar {
    border-radius: 50%;
}
</style>
