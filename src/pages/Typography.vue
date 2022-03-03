<template>
  <q-page class="flex column q-pa-md">
    <span class="text-h1">Typography</span>
    <span class="text-h2">Typography</span>
    <span class="text-h3">Typography</span>
    <span class="text-h4">Typography</span>
    <span class="text-h5">Typography</span>
    <q-separator />

    <span class="text-subtitle1">Subtitle 1</span>
    <span class="text-subtitle2">Subtitle 2</span>
    <q-separator />

    <p class="text-body1">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro, illum
      quasi placeat aut rem, similique, sint eligendi sequi odit culpa earum
      quam quis! Similique beatae perspiciatis et eveniet! Maiores,
      exercitationem?
    </p>
    <p class="text-body2">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro, illum
      quasi placeat aut rem, similique, sint eligendi sequi odit culpa earum
      quam quis! Similique beatae perspiciatis et eveniet! Maiores,
      exercitationem?
    </p>

    <q-btn color="primary" label="Abrir menú lateral" class="q-mt-md" @click="toggleSideMenu"></q-btn>
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import useUI from "../composables/useUI";

export default defineComponent({
  name: "Typography",
  setup(){
    const { toggleSideMenu } = useUI();
    return{
      toggleSideMenu
    }
  }
});
</script>
