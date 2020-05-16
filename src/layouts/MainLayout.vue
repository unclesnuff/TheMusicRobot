<template>
  <q-layout view="hHh lpR fFf">

    <q-header reveal bordered class="bg-dark text-white" height-hint="98vh" >
      <q-toolbar>
        <q-toolbar-title class="title text-weight-thin">
          <q-avatar>
            <img src="https://cdn.quasar.dev/logo/svg/quasar-logo.svg">
          </q-avatar>
          snuff's stuff
        </q-toolbar-title>

        <q-btn dense flat round icon="menu" @click="right = !right" />
      </q-toolbar>
    </q-header>

    <q-drawer v-model="right" content-class="bg-accent" side="right" overlay elevated>
<q-btn class="bg-secondary" to="Drumkit">Ye</q-btn>
      </q-drawer>

    <q-page-container class="bg-light-blue1">
      <router-view />
    </q-page-container>

  </q-layout>
</template>

<script>
export default {
  data () {
    return {
      right: false
    }
  }
}
</script>
