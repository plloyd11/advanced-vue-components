<template>
  <div class="min-h-screen bg-grey-darker p-8">
    <div class="max-w-md mx-auto">
      <user-settings-form></user-settings-form>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import UserSettingsForm from "@/components/UserSettingsForm.vue";

export default {
  name: "home",
  components: {
    UserSettingsForm
  }
};
</script>
