<template>
  <q-page padding>
    <div class="text-h1 q-pt-lg q-pb-md text-primary">Learning Center</div>
    <div class="text-subtitle1 q-pb-lg text-blue-10">
      Where you can find everything you want to know in bite-sized chunks.
    </div>
    <hr />
    <ul>
      <li>Trailheads by topic: easy, medium, expert</li>
      <li>Searchable catalog of lessons</li>
      <li>
        <q-btn :to="{ name: 'lesson-sample' }">Basic Lesson</q-btn>
      </li>
      <li>
        <q-btn :to="{ name: 'lesson-prototype' }">Prototype Lesson</q-btn>
      </li>
      <li>
        <q-btn :to="{ name: 'lesson-scratch' }"
          >Alternate Prototype Lesson</q-btn
        >
      </li>
      <li>
        <q-btn :to="{ name: 'lesson-planner' }">Build Lessons</q-btn>
      </li>
    </ul>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped></style>
