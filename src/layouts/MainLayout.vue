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
        <q-space />

        <div class="row gt-md q-py-lg col justify-end">
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
        <!-- md -->

        <q-btn class="lt-md" color="primary" icon="menu">
          <q-menu>
            <q-list style="min-width: 100px">
              <q-item href="#notre" clickable v-close-popup>
                <q-item-section>Notre Solution En prévention</q-item-section>
              </q-item>
              <q-item href="#blanches" clickable v-close-popup>
                <q-item-section>Salles Blanches</q-item-section>
              </q-item>
              <q-item href="#contact" clickable v-close-popup>
                <q-item-section>Contact</q-item-section>
              </q-item>
              <q-item clickable v-close-popup>
                <q-item-section>Articles</q-item-section>
              </q-item>
              <q-item clickable v-close-popup>
                <q-item-section>Se Connecter</q-item-section>
              </q-item>
            </q-list>
          </q-menu>
        </q-btn>
        <!--  -->
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
