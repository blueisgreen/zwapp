<template>
  <q-page padding>
    <div class="q-pa-md q-gutter-md">
      <div class="text-h3">Course Laboratory</div>
      <div class="text-subtitle1">
        Where idealized knowledge sharing is discovered
      </div>
      <div class="row">
        <div class="col">
          <q-card>
            <q-card-section>Courses</q-card-section>
            <q-card-actions align="center">
              <q-btn
                :to="{ name: 'courseBuilder' }"
                no-caps
                color="primary"
                label="Work with Courses"
              />
            </q-card-actions>
          </q-card>
        </div>
        <div class="col">
          <q-card>
            <q-card-section>Lessons</q-card-section>
            <q-card-actions align="center">
              <q-btn
                :to="{ name: 'lessonPlanner' }"
                no-caps
                color="primary"
                label="Work with Lessons"
              />
            </q-card-actions>
          </q-card>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <q-card>
            <q-card-section>
              Wish list:
              <ul>
                <li>Manage images, videos</li>
                <li>Create quizzes</li>
              </ul>
            </q-card-section>
          </q-card>
        </div>
      </div>
    </div>
  </q-page>
</template>

<script setup></script>

<style lang="scss" scoped></style>
