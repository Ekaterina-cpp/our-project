<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar-title>
        Приложение тест
      </q-toolbar-title>
        <div>Тест {{ $q.version }}</div>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {}
</script>
