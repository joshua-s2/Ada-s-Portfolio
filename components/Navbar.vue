<template>
  <nav class="flex justify-between items-center">
    <div>
      <img src="~/assets/images/Logo.svg" alt="" />
    </div>
    <div>
      <ol class="flex">
        <a href="/"> <li class="px-4">Home</li></a>
        <a href="/"> <li class="px-4">Home</li></a>
        <a href="./Portfolio">
          <li class="px-4">
            Portfolio
          </li></a
        >
        <a href="/"> <li class="px-4">Home</li></a>
        <a href="/"> <li class="px-4">Home</li></a>
        <a href="/"> <li class="px-4">Home</li></a>
      </ol>
    </div>
  </nav>
</template>

<script>
export default {
  name: "Navbar",
  data() {
    return {
      showMenu: false
    };
  },
  methods: {
    toggleNavbar: function() {
      this.showMenu = !this.showMenu;
    }
  }
};
</script>
