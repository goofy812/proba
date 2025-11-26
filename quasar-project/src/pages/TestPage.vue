<template>
  <q-page padding>
    <q-card class="my-card bg-accent text-black">
      <q-card-section>
        <div v-text="Naslov"></div>
        <div v-text="Autor"></div>
        <p><a :href="link" target="_blank"></a>VeleRi</p>
        <q-btn
  flat
  label="Otvori"
  type="a"
  :href="link"
  target="_blank"
/>

      </q-card-section>
      <q-card-section>
        {{ poziv }}
      </q-card-section>
      <q-card-actions>
        <q-btn flat>Open</q-btn>
        <q-btn flat>Delete</q-btn>
      </q-card-actions>
    </q-card> 
  </q-page>
</template>

<script setup>
const Naslov = 'Studij Informatike'
const Autor = 'Tomislav Bijelic-Curkic'
const poziv = 'VeleRi'
const link = 'https://www.veleri.hr'


</script>
