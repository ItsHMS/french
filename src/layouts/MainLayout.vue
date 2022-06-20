<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar class="text-primary bg-white">
        <div class="row">
          <q-avatar square size="100px" font-size="82px">
            <img alt="Quasar logo" src="~assets/logo.svg" />
          </q-avatar>
        </div>
        <div class="row">
          <q-toolbar-title
            class="text-h1"
            style="
              font-weight: bold;
              text-shadow: rgb(0 0 0 / 37%) 1px 4px 4px;
              font-family: Century Gothic;
            "
          >
            Aziri
          </q-toolbar-title>
        </div>

        <div style="background: cornsilk" class="row q-py-lg col justify-end">
          <q-btn
            class="col-12 col-md-auto"
            href="#notre"
            flat
            label="Notre Solution
En prévention
"
          />

          <q-btn
            class="col-12 col-md-auto"
            flat
            href="#blanches"
            label="Salles Blanches
"
          />

          <q-btn
            class="col-12 col-md-auto"
            href="#contact"
            flat
            label="Contact"
          />

          <q-btn class="col-12 col-md-auto" stretch flat label="Articles" />

          <q-btn
            flat
            class="col-12 col-md-auto"
            label="Se Connecter
"
          />
        </div>
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
export default {
  name: "MainLayout",
  data() {
    return {};
  },
};
</script>
