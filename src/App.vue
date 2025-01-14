<script>
export default {
  name: "App",
  data() {
    return {
      name: "Ivan",
      status: "active",
    };
  },
};
</script>

<template>
  <h1>Hello {{ name }}</h1>
  <p v-if="status === 'active'">User is Active</p>
  <p v-else-if="status === 'pending'">User is Pending</p>
  <p v-else>User is inactive</p>
</template>
