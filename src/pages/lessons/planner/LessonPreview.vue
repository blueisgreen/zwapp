<template>
  <div class="text-h6">Preview</div>
  <q-card>
    <q-card-section>
      <div class="text-h6">{{ planner.selectedLesson.title }}</div>
      <div class="text-caption text-secondary">
        {{ planner.selectedLesson.subtitle }}
      </div>
    </q-card-section>
    <q-card-section>
      <span class="preview-style" v-html="planner.activeContentDraft" />
    </q-card-section>
  </q-card>
</template>

<script setup>
import { useLessonPlannerStore } from 'src/stores/lesson-planner.js'

const planner = useLessonPlannerStore()
</script>

<style lang="scss" scoped>
.preview-style {
  padding: 3em;
}
</style>
