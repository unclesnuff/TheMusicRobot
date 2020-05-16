<template>
  <q-page content-class="bg-dark">
<div class="row">
  <div class="text-h5 text-bold q-pa-md q-pt-md">Recent Content</div>
</div>

<div class="row">
  <div class="q-px-md">
    <q-card class="q-card--dark" style="width: '505px'">

            <q-banner dark dense>Very difficult, took 20 minutes</q-banner>
      <q-separator/>
      <q-card-section>
      <div class=" q-card--bordered text-light q-px-sm">
          5/9/2020 - Stuck but not forgotten
      </div>
      </q-card-section>
    </q-card>
  </div>
</div>
  </q-page>

</template>

<script>
export default {
  data () {
    return {
      cardData: [
        {
          id: 1,
          title: '"Robots on Acid" Preview"',
          content: 'My most recent collection of funky tunes.'
        },
        {
          title: 'test',
          content: 'idk',
          id: 2
        }
      ]
    }
  }
}
</script>
