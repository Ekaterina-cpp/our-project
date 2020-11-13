<template>
  <q-layout view="hHh lpR fFf">

    <q-drawer show-if-above v-model="left" side="left" bordered>
      <div class="text-subtitle2 text-weight-bold text-center">Ваша доставка</div>
        <div class="q-pa-md">
          <q-linear-progress rounded size="15px" :value="progress" color="warning" class="q-mt-20" />
        </div>
    </q-drawer>

    <q-page-container>
      <router-view />
    </q-page-container>

    <!-- Катя - пишешет дизайн основного меню
    Таня - ищещь во всех файлах упомнание Quasar (То что выводится) -->

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
      progress: 0.84,
      left: false
    }
  }
}
</script>

<style scoped>
  .progressBar1 {
    size: 5 px;
  }
</style>
