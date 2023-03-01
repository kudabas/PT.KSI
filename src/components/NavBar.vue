<template>
  <div>
    <v-navigation-drawer
    class="deep-purple accent-4"
      v-model="drawer"
      app
      temporary
      dark
      src="@/assets/ksiputih.png"
    >
      <v-list>
        <v-list-item>
          <v-list-item>
            <img src="LogoB.png" alt="Logo" />
          </v-list-item>
          <v-list-item-content>
            <v-list-item-title class="title">PT.KSI</v-list-item-title>
            <v-list-item-subtitle>WEB</v-list-item-subtitle>
          </v-list-item-content>
        </v-list-item>
      </v-list>

      <v-divider />

      <v-list dense>
        <v-list-item>
          <router-link to="/" custom v-slot="{ navigate }">
          <v-btn class="text-black" @click="navigate" role="link"> Home </v-btn>
        </router-link>
        <br />
        <br />
          <v-btn class="text-black" text @click="scroll('how')">Service</v-btn>
          <br />
          <br />
          <router-link to="/about" custom v-slot="{ navigate }">
          <v-btn class="text-black" @click="navigate" role="link"> About Us </v-btn>
        </router-link>
          <br />
          <br />
          <router-link to="/stories" custom v-slot="{ navigate }">
          <v-btn class="text-black" @click="navigate" role="link"> Stories and Visit </v-btn>
        </router-link>
          <br />
          <br />
          <v-btn class="text-black" text @click="scroll('footer')">Contact</v-btn>
          <v-list-item-content>
            <v-list-item-title class="subtitile-1">{{
              text
            }}</v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-app-bar  dark flat class="px 12">
      <v-img
        class="mx-10"
        src="../assets/ksiputih.png"
        max-height="100"
        max-width="100"
      ></v-img>
      <v-app-bar-nav-icon
        @click.stop="drawer = !drawer"
        class="mr-4 text-white"
        v-if="isXs"
      />

      <div v-else>
        <router-link to="/" custom v-slot="{ navigate }">
          <v-btn  @click="navigate" role="link"> Home </v-btn>
        </router-link>
        <!-- <v-btn text @click="scroll('#HomeView')" class="text-white">Home</v-btn> -->
        <v-btn  @click="scroll('how')" >Service</v-btn>
        <router-link to="/about" custom v-slot="{ navigate }">
          <v-btn  @click="navigate" role="link"> About Us </v-btn>
        </router-link>
        <router-link to="/stories" custom v-slot="{ navigate }">
          <v-btn  @click="navigate" role="link"> Stories and Visit </v-btn>
        </router-link>
        <!-- <v-btn text @click="scroll('home')" class="text-white">About Us</v-btn> -->
        <v-btn  @click="scroll('footer')" >Contact</v-btn>
      </div>
      <v-spacer></v-spacer>

      <v-btn  @click="scroll('home')" >English</v-btn>
    </v-app-bar>

    <!-- <v-app-bar
      app
      color=""
      elevation=""
      hide-on-scroll
      prominent
      scroll-target="#scrolling-techniques-4"
      dark
      class="px-15"
      flat
    >
      <v-toolbar-title>
        <v-img src="@/assets/ksiputih.png" max-width="100px" />
      </v-toolbar-title>
      <v-app-bar-nav-icon
        @click.stop="drawer = !drawer"
        class="mr-4 text-white"
        v-if="isXs"
      />
      <div v-else>
        <router-link to="/" custom v-slot="{ navigate }">
          <v-btn class="text-white" @click="navigate" role="link"> Home </v-btn>
        </router-link>
        <v-btn text @click="scroll('how')" class="text-white">Service</v-btn>
        <v-btn text @click="scroll('home')" class="text-white">About Us</v-btn>
        <v-btn text @click="scroll('home')" class="text-white">Contact</v-btn>
        
      </div>
    </v-app-bar> -->
  </div>

  <!-- <v-btn class="text-white" text @click="$vuetify.goTo('home')">
          <span class="mr-2">Home</span>
        </v-btn>
        <v-btn class="text-white" text @click="$vuetify.goTo('#features')">
          <span class="mr-2">About</span>
        </v-btn>
        <v-btn class="text-white" text @click="$vuetify.goTo('#download')">
          <span class="mr-2">Service</span>
        </v-btn>
        <v-btn class="text-white" text @click="$vuetify.goTo('#pricing')">
          <span class="mr-2">Contact Us</span>
        </v-btn> -->

  <!-- <div id="navbar">
    <div class="nav-brand">
      <h2>W3hubs</h2>
      <i class="fa fa-navicon" v-on:click="display"></i>
    </div>

    <div class="bar-items" :class="{ hide: !show }">
      <div id="menu">



        <RouterLink to="/home">
          Home
        </RouterLink>


        <RouterLink to="/about">
          About
        </RouterLink>


        <RouterLink to="/servie">
          Service
        </RouterLink>


        <RouterLink to="/contact">
          Contact Us
        </RouterLink>
      </div>
    </div>

  </div> -->
  <!-- <body>
  <nav class="navbar">
    <div class="logo">MUO</div>


    <ul class="nav-links">

      <input type="checkbox" id="checkbox_toggle" />

      <label for="checkbox_toggle" class="hamburger">&#9776;</label>

      <div class="menu">
        <li><a href="/">Home</a></li>

        <li><a href="/">About</a></li>

        <li class="services">
          <a href="/">Services</a>


          <ul class="dropdown">
            <li><a href="/">Dropdown 1 </a></li>

            <li><a href="/">Dropdown 2</a></li>

            <li><a href="/">Dropdown 2</a></li>

            <li><a href="/">Dropdown 3</a></li>

            <li><a href="/">Dropdown 4</a></li>
          </ul>
        </li>

        <li><a href="/">Pricing</a></li>

        <li><a href="/">Contact</a></li>
      </div>
    </ul>
  </nav>
</body> -->

  <!-- <v-app-bar color="#1C6758" dark flat class="px 12">
        <v-img
        
    class="mx-10"
    src="../assets/ksiputih.png"
    max-height="100"
    max-width="100"
  ></v-img>
  <v-btn text @click="scroll('#HomeView')" class="text-white">Home</v-btn>
  <v-btn text @click="scroll('how')" class="text-white">Service</v-btn>
  <v-btn text @click="scroll('home')" class="text-white">About Us</v-btn>
  <v-btn text @click="scroll('home')" class="text-white">Contact</v-btn>
  <v-spacer></v-spacer>
  <v-btn text @click="scroll('home')" class="text-white">English</v-btn>
    </v-app-bar> -->
</template>

<script>
export default {
  data: () => ({
    drawer: null,
    isXs: false,
    // items: [
    //   ["Home", "home"],
    //   ["Service", "home"],
    //   ["About Us", "#download"],
    //   ["Contact", "#pricing"],
    // ],
  }),
  props: {
    color: String,
    flat: Boolean,
  },
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
    onResize() {
      this.isXs = window.innerWidth < 850;
    },
  },

  watch: {
    isXs(value) {
      if (!value) {
        if (this.drawer) {
          this.drawer = false;
        }
      }
    },
  },
  mounted() {
    this.onResize();
    window.addEventListener("resize", this.onResize, { passive: true });
  },
};

// data() {
//   return { show: false }
// },
// methods: {
//   display() {
//     console.log("clicked")
//     this.show = !this.show
//   }
// }

// methods: {
//   scroll(refName) {
//     const element = document.getElementById(refName);
//     element.scrollIntoView({behavior: "smooth"});
//   }
// }
</script>

<style scoped>
.v-app-bar {
  background: linear-gradient(500deg, #1c6758 15%, #3d8361 50%);
}
.v-toolbar {
  transition: 0.6s;
}

.expand {
  height: 80px !important;
  padding-top: 10px;
}

.span {
  color: green;
}

.v-btn:hover {
  background-color: #D6CDA4;
  color:#3D8361;
}

.v-btn:focus {
  background-color: #D6CDA4;
  color:#3D8361;
}

.v-btn:active {
  background-color: #D6CDA4;
  color:#3D8361;
}
.v-btn {
  text-transform:none !important;
  color:floralwhite;
}
</style>
<!-- <style>
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&display=swap');

body {
  margin: 0;
  font-family: 'Lato', sans-serif;
}
h1{
  text-align: center;
  font-size: 36px;
  text-transform: capitalize;
}
h2 {
  padding-left: 15px;
  color: #fff;
  margin: 0;
}

#navbar {
  display: flex;
  align-items: center;
  background-color: #42b883;
  width: 100%;

}

#menu {
  list-style-type: none;
  display: flex;
  align-items: center;
  justify-content: end;
  width: 100%;
  margin: 0;
  padding: 0;
}

.bar-items {
  width: 100%;
}

a {
  padding: 20px;
  
}

li:hover {
  background-color: #42d392;
}

a {
  text-decoration: none;
  font-size: 18px;
  color: #fff;
}

.fa {
  display: none;
}

@media(max-width:675px) {
  #navbar {
    flex-direction: column;
  }

  .fa {
    display: block;
    padding: 0 25px;
    position: absolute;
    right: 0;
    color: #fff;
    font-size: 30px;
    cursor: pointer;

  }

  #menu {
    flex-direction: column;
    padding: 5px 0;
  }

  a {
    text-align: center;
    width: 100%;
    box-sizing: border-box;
    padding: 15px;
  }

  .hide {
    display: none;
  }

  .nav-brand {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 15px 0px;
    background-color: #15935a;
  }
}
</style> -->

<!-- <style>
* {
  margin: 0;

  padding: 0;

  box-sizing: border-box;
}

body {
  font-family: cursive;
}

a {
  text-decoration: none;
}

li {
  list-style: none;
}

.navbar {
  display: flex;

  align-items: center;

  justify-content: space-between;

  padding: 20px;

  background-color: teal;

  color: #fff;
}

.nav-links a {
  color: #fff;
}

/* LOGO */

.logo {
  font-size: 32px;
}

/* NAVBAR MENU */

.menu {
  display: flex;

  gap: 1em;

  font-size: 18px;
}
.menu li:hover {
  background-color: #4c9e9e;

  border-radius: 5px;

  transition: 0.3s ease;
}

.menu li {
  padding: 5px 14px;
}

/* DROPDOWN MENU */

.services {
  position: relative;
}

.dropdown {
  background-color: rgb(1, 139, 139);

  padding: 1em 0;

  position: absolute; /*WITH RESPECT TO PARENT*/

  display: none;

  border-radius: 8px;

  top: 35px;
}

.dropdown li + li {
  margin-top: 10px;
}

.dropdown li {
  padding: 0.5em 1em;

  width: 8em;

  text-align: center;
}

.dropdown li:hover {
  background-color: #4c9e9e;
}

.services:hover .dropdown {
  display: block;
}
/* CHECKBOX HACK */

input[type="checkbox"] {
  display: none;
}

/*HAMBURGER MENU*/

.hamburger {
  display: none;

  font-size: 24px;

  user-select: none;
}
@media (max-width: 768px) {
  .menu {
    display: none;

    position: absolute;

    background-color: teal;

    right: 0;

    left: 0;

    text-align: center;

    padding: 16px 0;
  }
  .menu li:hover {
    display: inline-block;

    background-color: #4c9e9e;

    transition: 0.3s ease;
  }

  .menu li + li {
    margin-top: 12px;
  }

  input[type="checkbox"]:checked ~ .menu {
    display: block;
  }

  .hamburger {
    display: block;
  }

  .dropdown {
    left: 50%;

    top: 30px;

    transform: translateX(35%);
  }

  .dropdown li:hover {
    background-color: #4c9e9e;
  }
}
/* html {
  scroll-behavior: smooth;
} */
</style> -->