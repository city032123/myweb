<template>
  <div CLASS="header">
    <h1 class="logo">111111</h1>

    <NuxtLink to="/about">
    <h1 class="link">about</h1>
    </NuxtLink>

    <NuxtLink to="/about">
    <h1 class="link">about</h1>
    </NuxtLink>

    <NuxtLink to="/about">
    <h1 class="link">about</h1>
    </NuxtLink>

    <NuxtLink to="/about">
    <h1 class="link">about</h1>
    </NuxtLink>
  </div>
</template>

<style scoped>
.header{
  border: solid 1px black;
  padding: 0px 80px 0px 80px;
  display: flex;
}
.logo{
  flex: 4;
  background-color: var(--maincolor);
}
.link{
  padding: 0px 20px 0px 20px;
  flex:.5;
}
</style>
