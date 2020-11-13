<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated container style="height: 100px">
      <q-toolbar>
        <div class="avatar1">
          <q-avatar rounded size="58px" font-size="35px" color="teal" text-color="white" icon="N" class="absolute-center"/>
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {}
</script>

<style scoped>
</style>
