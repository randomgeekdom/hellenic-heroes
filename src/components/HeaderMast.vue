<script setup lang="ts">
defineProps<{
  msg: string;
}>();
</script>

<template>
  <div class="greetings">
    <p>
      In a time of gods and myth, where monsters roam ancient Greece, heroes
      rise to fight the threats to humanity. They are the
    </p>
    <br />
    <h1>
      <router-link to="/"><img src="hh-logo.png" /></router-link>
    </h1>
    <p>
      Hellenic Heroes is a tabletop RPG intended for 3 or more players to take
      on the roles of mythical heroes in ancient Greece.
    </p>
  </div>
</template>

<style scoped>
h1 {
  font-weight: 500;
  font-size: 2.6rem;
  top: -10px;
}

h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
