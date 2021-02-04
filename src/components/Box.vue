<template>
  <div
    class="flex flex-col flex-grow items-center border border-grey-600 rounded-lg h-full text-center"
  >
    <div
      class="font-medium bg-green-200 flex items-center justify-center w-full rounded-t-md px-5 h-1/3"
    >
      {{ title }}
    </div>
    <div
      class="text-gray-500 flex items-center justify-center flex-grow w-full rounded-b-md px-5"
    >
      {{ description }}
    </div>
  </div>
</template>

<script>
export default {
  name: "Box",
  props: {
    title: {
      type: String,
      default: ""
    },
    description: {
      type: String,
      default: "12/02/20"
    }
  }
};
</script>

<style scoped lang="css">
.customized {
  background: #d9efd5;
  color: #3ead2c;
}
</style>
