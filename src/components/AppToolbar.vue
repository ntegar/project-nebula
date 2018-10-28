<template>
    <div id="nav">
    <v-toolbar class="transparent elevation-0">
    <v-toolbar-title>Title</v-toolbar-title>
    <v-spacer></v-spacer>
    <v-toolbar-items class="hidden-sm-and-down">
      <v-btn flat style="border-radius: 15px;"><router-link to="/" style="text-decoration: none;">Home</router-link></v-btn>
      <v-btn flat style="border-radius: 15px;"><router-link to="/about" style="text-decoration: none;">About</router-link></v-btn>
    </v-toolbar-items>
  </v-toolbar>
    </div>
</template>

<style scoped>
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #ffffff;
}


#nav a.router-link-exact-active {
  color: #ff794a;
}
</style>
