<template>
  <!--  <button-->
  <!--      class="bg-gray-900 hover:bg-gray-800 text-white transition-all duration-150 ease-in-out font-semibold px-5 py-2 rounded"-->
  <!--      v-bind:class="btnClass"-->
  <!--  >-->
  <button class="" v-bind:class="btnClass">
    <slot name="default"></slot>

    <slot name="textbeforesvg"></slot>

    <slot name="svgbeforetext"></slot>

    <slot name="svg"></slot>

    <slot name="textbtn"></slot>

    <slot name="svgaftertext"></slot>

    <slot name="textaftersvg"></slot>
  </button>
</template>

<script>
export default {
  name: "Button1",
  props: {
    btnClass: {
      type: String
    },
    btnText: {
      type: String
    }
  },
  data() {
    return {};
  }
};
</script>

<style scoped lang="scss"></style>
