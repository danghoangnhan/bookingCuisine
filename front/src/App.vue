<template lang="pug">
  #app
    section#nav
      //- <font-awesome-icon :icon="['fas', 'coffee']" />
      b-navbar(toggleable="md")
        b-navbar-toggle.ml-auto(target="collapse")
        b-collapse(id="collapse" is-nav)
          b-navbar-nav.ml-auto
            b-nav-item Sign in
              font-awesome-icon(:icon="['far', 'user']")
            b-nav-item Sign up
              font-awesome-icon(:icon="['fas', 'user-plus']")
    .container
      .row
        .col-6

        .col-6
</template>

<script>
export default {
  name: 'App'
}
</script>
