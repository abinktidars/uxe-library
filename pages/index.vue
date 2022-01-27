<template>
  <div class="wrapper">
    <header>
      <Header />
    </header>
    <main class="flex h-full">
      <Sidebar />
      <Content />
    </main>
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style lang="scss">
html,
body,
#__nuxt,
#__layout {
  height: 100%;
}

.wrapper {
  height: 100%;
  // height: calc(100% - 80px);
}

main {
  padding-top: 80px;
}
</style>
