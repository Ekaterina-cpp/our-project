<template>
  <q-layout view="hHh lpR fFf">

    <div class="fit row wrap justify-start items-start content-start">
      <div class="col-3 bg-green">
        <div class="row">
          <div class="ava1">
            <q-avatar rounded size="65px" font-size="42px" color="red" icon="F" text-color="white"/>
          </div>
          <div class="text-subtitle2 text-weight-bold margine">{{name}} <br> {{sorname}} </div>
        </div>
        <div class="row">
          <div class="col">
            <div class="full-width text-subtitle2 text-weight-bold text-center">
              Ваша доставка
            </div>
            <div class="q-pa-md">
              <q-linear-progress rounded size="15px" :value="progress" color="warning" class="q-mt-20" />
            </div>
          </div>
        </div>
      </div>
      <div class="col bg-blue">
        <div class="full-width text-subtitle2 text-weight-bold text-center">Ваша доставка</div>
        <div class="q-pa-md">
          <q-linear-progress rounded size="15px" :value="progress" color="warning" class="q-mt-20" />
        </div>
      </div>
    </div>
    <!-- <div class="leftMenu">
      <q-drawer show-if-above v-model="left" side="left" bordered>
        <div class="profile">
          <div id="avatar">
            <q-avatar rounded size="65px" font-size="42px" color="red" icon="F" text-color="white"/>
          </div>
        </div>
        <div class="text-subtitle2 text-weight-bold text-center">Ваша доставка</div>
          <div class="q-pa-md">
            <q-linear-progress rounded size="15px" :value="progress" color="warning" class="q-mt-20" />
          </div>
      </q-drawer>
    </div>
 -->

    <!-- Таня - пишешет дизайн основного меню
    Катя - ищещь во всех файлах упомнание Quasar (То что выводится) -->

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
      progress: 0.84,
      left: false,
      name: 'Ник',
      sorname: 'Уайлд'
    }
  }
}
</script>

<style scoped>
  .progressBar1 {
    size: 5 px;
  }
  .ava1 {
    margin: 9px;
  }
  .leftMenu {
    size: 150px;
  }
  .margine {
    margin: 21px;
  }
</style>
