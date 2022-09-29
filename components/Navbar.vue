<template>
  <nav class="navbar navbar-expand-lg navbar-light">
    <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
      <NuxtLink class="navbar-brand" to="/">
        <img
          src="@/assets/images/logo.png"
          width="30"
          height="30"
          class="d-inline-block align-top"
          alt=""
        />
        Yonce-Ce
      </NuxtLink>
      <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
        <li class="nav-item active">
          <NuxtLink class="nav-link" to="/registro">
            Registro <span class="sr-only">(current)</span>
          </NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="#">API</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink class="nav-link" to="/about">Acerca de...</NuxtLink>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {};
</script>

<style scoped></style>
