<template>
  <q-layout view="lHh Lpr lFf">
    <q-header elevated>
      <q-toolbar class="text-primary bg-white">
        <q-avatar square size="100px" font-size="82px">
          <img alt="Quasar logo" src="~assets/logo.svg" />
        </q-avatar>
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

        <q-separator dark vertical />
        <q-btn
          stretch
          href="#notre"
          flat
          label="Notre Solution
En prévention
"
        />
        <q-separator dark vertical />
        <q-btn
          stretch
          flat
          href="#blanches"
          label="Salles Blanches
"
        />
        <q-separator dark vertical />
        <q-btn stretch href="#contact" flat label="Contact" />
        <q-separator dark vertical />
        <q-btn stretch flat label="Articles" />
        <q-separator dark vertical />
        <q-btn
          stretch
          flat
          label="Se Connecter
"
        />
      </q-toolbar>
    </q-header>

    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>

<script>
const linksList = [
  {
    title: "Docs",
    icon: "school",
    link: "#",
  },
  {
    title: "Github",
    icon: "code",
    link: "#",
  },
  {
    title: "Discord Chat Channel",
    icon: "chat",
    link: "#",
  },
  {
    title: "Forum",
    icon: "record_voice_over",
    link: "#",
  },
  {
    title: "Twitter",
    icon: "rss_feed",
    link: "#",
  },
];

export default {
  name: "MainLayout",
  data() {
    return {};
  },
};
</script>
