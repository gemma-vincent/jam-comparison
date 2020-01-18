<template>
  <main class="h-full main-bg">
    <div class="container mx-auto lg:py-12 px-5 md:px-8 lg:px-12 py-10 md:py-12 relative z-1">
      <slot />
    </div>
  </main>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<style>
body {
  background: url("../assets/images/icons/background.svg") repeat;
}
</style>
