<template>
  <div>
    <h1>Họ và tên: {{ name }}</h1>
  </div>
</template>

<script setup>
const user = {
  firstName: "Nguyễn Văn",
  lastName: "Đoan",
};

function forMatName(user) {
  const name = user.firstName + " " + user.lastName;
  return name;
}

const name = forMatName(user);
</script>

<style scoped></style>
