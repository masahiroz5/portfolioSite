<template>
  <div>
    <nav>
      <ul class="nav__menu">
        <li class="nav__item">
          <NuxtLink to="/" class="nav__link">Home</NuxtLink>
        </li>
        <li class="nav__item">
          <NuxtLink to="/profile" class="nav__link">Profile</NuxtLink>
        </li>
        <li class="nav__item">
          <NuxtLink to="/career" class="nav__link">Career</NuxtLink>
        </li>
        <li class="nav__item">
          <NuxtLink to="/skill" class="nav__link">Skill</NuxtLink>
        </li>
        <li class="nav__item">
          <NuxtLink to="/works" class="nav__link">Works</NuxtLink>
        </li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  components: {},
};
</script>

<style scoped>
.nav__menu {
  display: flex;
  justify-content: flex-end;
}
.nav__item {
  list-style-type: none;
  margin-left: 20px;
}
.nav__item:hover {
  text-decoration: underline;
}
.nav__link {
  text-decoration: none;
  color: gray;
  font-size: 30px;
}
@media screen and (max-width: 400px) {
  .nav__link {
    font-size: 15px;
  }
}
</style>