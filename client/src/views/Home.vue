<template>
    <div>
        <div class="navbar">
    <span class="navbar-menu">
      <ul class="navbar-header">
        <li>
          <a href="/login">Login</a>
        </li>
        <li>
          <a href="/register">Register</a>
        </li>
      </ul>
    </span>
  </div>
  <h1>This is my Test (Vue-Django) Web Site</h1>
    </div>
</template>

<script>
export default {
    name: "view-home"
}
</script>

<style scoped>

li a {
  text-decoration: none;
}

ul {
  list-style-type: none;
}

li {
  display: inline;
}

.navbar-header {
  display: flex;
}
</style>