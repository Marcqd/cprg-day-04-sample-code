<template>
  <header>
    <div>
      <NuxtLink to="/">Logo: User Name</NuxtLink>
    </div>
    <nav>
      <NuxtLink to="signup">Sign Up Page</NuxtLink>
    </nav>
  </header>
</template>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
  gap: 2rem;
  padding: 2rem;
  color: white;
  background-color: black;
}
a {
  color: white;
}
a:hover {
  color: blue;
}
</style>
