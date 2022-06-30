<template>
  <div id="Contact">
    <div style="text-align:center;padding-bottom:100px;padding-top:50px">
      <v-row>
        <v-col md="12" sm="12">
          <h1 id="h1" >Get in touch with us</h1>

          <input type="text" placeholder="Name" class="text-box" style="margin-top:30px" />
           </v-col>
          <v-col md="12" sm="12">
          <input type="email" class="text-box" placeholder="Email" />
           </v-col>
          <v-col md="12" sm="12">
          <input type="text" class="text-box" placeholder="Subject" />
           </v-col>
          <v-col md="12" sm="12">
          <input type="text" class="text-box" placeholder="message" />
        </v-col>
          <v-col md="12" sm="12">
              <v-btn id="btn">Send Message</v-btn>
        </v-col>
      </v-row>
    </div>


     <v-row>
      <v-col md="4" sm="12">
        <v-icon x-large color="#000000" id="icon"
          >mdi-map-marker-outline</v-icon
        >
        <h5>Address:</h5>
        <p>
          198 west 21th street <br />
          suite 721 NewYork NY <br />
          10016
        </p>
      </v-col>
      <v-col md="4" sm="12">
        <v-icon x-large color="#000000" id="icon" style="margin-left: 180px"
          >mdi-phone-outline</v-icon
        >
        <h5>Phone:</h5>
        <p>+ 1235 2355 98</p>
      </v-col>
      <v-col md="4" sm="12">
        <v-icon x-large color="#000000" id="icon" style="margin-left: 180px">
          mdi-at</v-icon
        >
        <h5>Email:</h5>
        <p>info@Email.com</p>
      </v-col>
    </v-row>
  </div>
</template>

<style>
#Contact {
  background-color: #0a183d;
  padding-bottom: 200px;
  font-family: "Montserrat", sans-serif;
}
#icon {
  border: 1px solid white;
  border-radius: 50%;
  padding: 10px;
  background-color: white;
  margin-top: 20px;
  margin-left: 187px;
}
#Contact h5 {
  color: white;
  margin-left: 187px;
  margin-top: 10px;
}
#Contact p {
  color: white;
  font-size: 14px;
  margin-left: 160px;
  margin-top: 10px;
  opacity: 0.5;
  margin-bottom: 30px;
}
.text-box {
  width: 400px;
  margin-top: 10px;
  background-color:#050d24;
  padding: 15px 10px;
  border-radius: 20px;
  outline: none;
  color: white;
  
}
#h1{
    color: white;
} 
#btn{
    color: black; 
    background-color: white; 
    padding: 20px 10px;
    width: 400px; 
    border-radius: 20px;
     margin-top: 10px;
     height: 50px;
}

</style>