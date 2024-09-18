<script setup>

</script>

<template>
  <nav class="navbar">
    <div class="navbar-container">
      <h3>BankAdminPanel</h3>
      <ul class="navbar-menu">
        <li>
          <router-link to="/">Requests</router-link>
        </li>
        <li>
          <router-link to="/">Help</router-link>
        </li>
        <li>
          <a href="#">Messages</a>
        </li>
        <li>
          <a href="#">Logout</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped>
.navbar{
  background-color: #f2f2f2;
  font-size: 14px;
  color: #222222;
}
.navbar-container{
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1200px;
  height: 60px;
  margin: 0 auto;
}
.navbar-menu{
  list-style: none;
  display: flex;
  justify-content: flex-start;
}
.navbar-menu li a,
.navbar-menu li router-link{
  text-decoration: none;
  margin-left: 15px;
  color: #222222;
}


</style>