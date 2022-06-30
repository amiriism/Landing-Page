<template >
  <div
    class="mx-auto overflow-hidden"
    
    
  
 >
    <v-app-bar
      color="#0A183D"
      dark
      
    >
      <v-app-bar-nav-icon @click="drawer = true" v-show="$vuetify.breakpoint.smAndDown"></v-app-bar-nav-icon>

 <v-toolbar-title v-show="$vuetify.breakpoint.mdAndUp"><v-img src="@/assets/10.png" width="131px"></v-img></v-toolbar-title>
 <button id="btn-nav" v-show="$vuetify.breakpoint.mdAndUp"> <a href="/">Home</a></button>
 <button id="btn-nav" v-show="$vuetify.breakpoint.mdAndUp" >  <a href="/About">About</a></button>


 <button id="btn-nav" v-show="$vuetify.breakpoint.mdAndUp"> <a href="/Contact">Contact</a></button>
 <button id="btn-nav" style="margin-left:400px" v-show="$vuetify.breakpoint.mdAndUp"> <a href="/Help">Help</a></button>
 <p style="margin-left:10px" v-show="$vuetify.breakpoint.mdAndUp">|</p>
 <button id="btn-nav" style="margin-left:10px" v-show="$vuetify.breakpoint.mdAndUp">  <a href="/Login">Login</a></button>
 <button id="btn-nav" v-show="$vuetify.breakpoint.mdAndUp"> <a href="/Register">Create an account</a></button>


     
    </v-app-bar>
 

    <v-navigation-drawer
      v-model="drawer"
      absolute
      temporary
      
    >
      <v-list
        nav
        dense
      >
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
          
        >
          <v-list-item href="/">
            <v-list-item-icon >
              <v-icon>mdi-home</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Home</v-list-item-title>
          </v-list-item>

          <v-list-item href="/About">
            <v-list-item-icon>
              <v-icon>mdi-information-variant</v-icon>
            </v-list-item-icon>
            <v-list-item-title>About</v-list-item-title>
          </v-list-item>

         

        


           <v-list-item href="/Contact">
            <v-list-item-icon>
              <v-icon>mdi-contactless-payment</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Contact</v-list-item-title>
          </v-list-item>


           <v-list-item href="/Help">
            <v-list-item-icon>
              <v-icon>mdi-help-rhombus</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Help</v-list-item-title>
          </v-list-item>

           <v-list-item href="/Login">
            <v-list-item-icon>
              <v-icon>mdi-login-variant</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Login</v-list-item-title>
          </v-list-item>


           <v-list-item href="/Register">
            <v-list-item-icon>
              <v-icon>mdi-account-plus-outline</v-icon>
            </v-list-item-icon>
            <v-list-item-title>Create an account</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
  </div>
</template>


<script>
  export default {
    data: () => ({
      drawer: false,
      group: null,
    }),
  }
</script>

<style>
#btn-nav:hover{
  color:red;
} 

#btn-nav{
  margin-left: 50px;
  
} 

a{
  color: white;
  text-decoration: none;
} 
a:hover{
  color: red;
}


body{
  font-family: "Montserrat", sans-serif
}
</style>