<template>
      
    <nav class="fixed">
      <div class="fixedlogos" @click="toggleDropdown" >
        <img src="../assets/noun-quota-4750811.svg" alt="">
        <img src="../assets/2931155_add_attach_create_maximize_new_icon.png" alt="" class="open" v-if="!isDropdownOpen">
        <img src="../assets/2931151_close_delete_exit_remove_x_icon.png" alt="" class="close" v-else>
      </div>
      <div class="toggle" v-show="isDropdownOpen">
        <div class="fixedThings"  >
          <div class="fixedLinks">
            <ul>
              <h3>ATLAS</h3>
              <router-link to="/#supper-club" @click="closeDropdown" >DINING</router-link>
              <router-link to="/#travel"  @click="closeDropdown">TRAVEL</router-link>
              <router-link to="/#card"  @click="closeDropdown">CARD</router-link>
              <RouterLink to="/#appp"  @click="closeDropdown">APP</RouterLink>
              <router-link to="/#concierge"  @click="closeDropdown">CONCIERGE</router-link>
            </ul>
            <ul>
              <h3>BENEFITS</h3>
              <RouterLink to="/#benefits"  @click="closeDropdown">ATLAS BENEFITS</RouterLink>
              <RouterLink to=""  @click="closeDropdown">VISA INFINITE</RouterLink>
            </ul>
            <ul>
              <h3>CONTACT</h3>
              <a href="mailto:lawrenciaebube@gmail.com" target="_blank"  @click="closeDropdown">EMAIL</a>
              <a target="_blank" href="https://twitter.com/Lawrenebube"  @click="closeDropdown">TWITTER</a>
              <a href="https://instagram.com/lawrenijeomah" target="_blank" @click="closeDropdown">INSTAGRAM</a>
            </ul>
          </div>
          <button> BECOME A FOUNDING MEMBER </button>
        </div>
        <p class="copyright"> 2023 &copy; ATLAS EXPLORATION, INC</p>
      </div>
    </nav>
  </template>
  
  <script>
  export default {
    name: 'NavBar',
    data() {
      return {
        isDropdownOpen: false,
      };
    },
    methods: {
      toggleDropdown() {
        this.isDropdownOpen = !this.isDropdownOpen;
      },
      closeDropdown() {
        this.isDropdownOpen = false;
      },
    },
  };
  </script>
    
  