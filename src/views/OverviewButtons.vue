<template>
  <div class="w-full max-w-8xl mx-auto">
    <div class="grid grid-cols-1">
      <div style="background-color: #667eea">
        <div class="container mx-auto px-6 text-center py-20">
          <h2 class="mb-6 text-4xl font-bold text-center text-white">
            ButtonsBlock1
          </h2>
        </div>
      </div>

      <Buttons1></Buttons1>

      <div></div>
    </div>
  </div>
</template>

<script>
import Buttons1 from "@/components/Buttons1";
export default {
  name: "OverviewButtons",
  components: { Buttons1 }
};
</script>

<style scoped lang="scss"></style>
