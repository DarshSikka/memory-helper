<template>
  <div>
    <h1 class="text-4xl mt-4 text-blue-900">Your Subjects</h1>
    <div
      v-for="subject in subjects"
      class="bg-blue-900 rounded-2xl text-white w-96 mx-auto mt-4 p-6 text-2xl"
      :key="subject"
    >
      {{ subject }}
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      subjects: ["History", "Geography", "Economics", "Civics", "Biology"],
    };
  },
};
</script>
