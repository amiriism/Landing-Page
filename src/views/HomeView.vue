<template>
  <div>
    <div id="container">
      <v-container>
        <v-row id="section1">
          <v-col sm="12" md="6">
            <p id="p-1" style="color: red; display: inline">Listen</p>
            <p id="p-1">
              to <br />
              new music.
            </p>

            <p style="color: white; margin-top: 10px">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              <br />
              eiusmod tempor incididunt ut labore et dolore magna <br />
              aliqua. Quis ipsum suspendisse ultrices gravida.
            </p>
            <v-btn id="btn-section1-1" color="#FF0000">DOWNLOAD NOW</v-btn>
            <v-btn id="btn-section1-2" color="#" outlined
              >START FREE TRIAL</v-btn
            >
          </v-col>

          <v-col md="6" v-show="$vuetify.breakpoint.mdAndUp">
            <v-img src="@/assets/7.png"></v-img>
          </v-col>
        </v-row>
      </v-container>
    </div>

    <div id="section3">
      <v-row>
        <v-col md="6" sm="12">
          <h2>
            Unlimited Access <br />
            to 100K tracks
          </h2>
        </v-col>
        <v-col md="6" sm="12">
          <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod <br />
            incididunt ut labore et dolore magna aliqua. Quis ipsum sus-<br />
            pendisse ultrices gravida. Risus commodo viverra maecenas accumsan
            <br />
            lacus vel facilisis. Lorem ipsum dolor sit amet, consectetur
            adipiscing elit,<br />
            sed do eiusmod tempor incididunt ut labore et dolore magna
            aliqua.<br />
            Quis ipsum suspendisse ultrices gravida.
          </p>

          <v-btn id="btn-section3" color="#FF0000">TRY IT NOW</v-btn>
        </v-col>
      </v-row>
    </div>

    <div id="section4">
      <h2>How it works</h2>
      <v-row>
        <div class="media">
          <div id="section5">
            <v-col md="4" sm="12">
              <v-img
                src="@/assets/6.png"
                height="41"
                width="37"
                id="section5-img"
              ></v-img>

              <div id="section5-text">
                <h4 style="color: white">Create an account</h4>
                <p style="color: white">
                  Lorem ipsum dolor sit amet, consectetur adipi- <br />
                  elit, sed do eiusmod tempor incididunt ut<br />
                  et dolore magna aliqua. Quis ipsum sus-<br />pendisse ultrices
                  gravida.
                </p>
              </div>
            </v-col>
          </div>
        </div>
        <div class="media">
          <div id="section5">
            <v-col md="4" sm="12">
              <v-img
                src="@/assets/8.png"
                height="41"
                width="39"
                id="section5-img"
              ></v-img>
              <div id="section5-text">
                <h4 style="color: white">Choose a plan</h4>
                <p style="color: white">
                  Donec in sodales dui, a blandit nunc. Pellen-<br />tesque id
                  eros venenatis, sollicitudin neque<br />
                  sodales, vehicula nibh. Nam massa odio, portti-<br />tor vitae
                  efficitur non.
                </p>
              </div>
            </v-col>
          </div>
        </div>
        <div class="media">
          <div id="section5">
            <v-col md="4" sm="12">
              <v-img
                src="@/assets/9.png"
                height="41"
                width="25"
                id="section5-img"
              ></v-img>

              <div id="section5-text">
                <h4 style="color: white">Download Music</h4>
                <p style="color: white">
                  Ablandit nunc. Pellentesque id eros venenatis,<br />
                  sollicitudin neque sodales, vehicula nibh. Nam<br />
                  massa odio, porttitor vitae efficitur non, ultric-<br />ies
                  volutpat tellus.
                </p>
              </div>
            </v-col>
          </div>
        </div>
      </v-row>
    </div>
    <div id="section6">
      
      <v-row>
        <v-col md="6" sm="12">
          <h2>Our Concept &amp; artists</h2>
        </v-col>
      
        <v-col md="6" sm="12">
          <p>
            Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
            labore<br />
            et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida.
            Risus<br />
            commodo viverra maecenas accumsan lacus vel facilisis. Lorem
            ipsum<br />
            dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
            <br />incididunt ut labore et dolore magna aliqua.
          </p>
        </v-col>
      </v-row>
      
      
      <v-row>
        <v-col md="3" sm="6">
          <v-img src="@/assets/3.webp" id="section6-img"></v-img>
          <h5 id="section6-text">Soul Music</h5>
        </v-col>

        <v-col md="3" sm="6">
          <v-img src="@/assets/4.webp" id="section6-img"></v-img>
          <h5 id="section6-text">Live Concerts</h5>
        </v-col>

        <v-col md="3" sm="6">
          <v-img src="@/assets/1.webp" id="section6-img"></v-img>
          <h5 id="section6-text">Live Concerts</h5>
        </v-col>

        <v-col md="3" sm="6">
          <v-img src="@/assets/5.webp" id="section6-img"></v-img>
          <h5 id="section6-text">Live Concerts</h5>
        </v-col>
      </v-row>
     
    </div>

    <div id="section7">
      <v-row>
        <v-col md="6" sm="12">
          <h2>
            Subscription <br />
            from $15/month
          </h2>
          <h3>Start a free trial now</h3>
          <p>
            Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
            labore<br />
            et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida.
            Risus <br />commodo viverra maecenas accumsan lacus vel facilisis.
            Lorem ipsum<br />
            dolor sit amet, consectetur adipiscing elit, sed do eiusmod
            tempor<br />
            incididunt ut labore et dolore magna aliqua.
          </p>
          <v-btn id="btn-section3" color="#FF0000" style="margin-left: 70px"
            >TRY IT NOW</v-btn
          >
        </v-col>

        <v-col md="6" sm="12">
          <div id="section7-window">
            <ul>
              <li>
                <v-img
                  src="@/assets/11.webp"
                  width="20px"
                  height="20px"
                  style="display: inline-block"
                ></v-img
                >Play any track
              </li>
              <li>
                <v-img
                  src="@/assets/11.webp"
                  width="20px"
                  height="20px"
                  style="display: inline-block"
                ></v-img
                >Listen offline
              </li>
              <li>
                <v-img
                  src="@/assets/11.webp"
                  width="20px"
                  height="20px"
                  style="display: inline-block"
                ></v-img
                >No ad interruptions
              </li>
              <li>
                <v-img
                  src="@/assets/11.webp"
                  width="20px"
                  height="20px"
                  style="display: inline-block"
                ></v-img
                >Unlimited skips
              </li>
              <li>
                <v-img
                  src="@/assets/11.webp"
                  width="20px"
                  height="20px"
                  style="display: inline-block"
                ></v-img
                >High quality audio
              </li>
              <li>
                <v-img
                  src="@/assets/11.webp"
                  width="20px"
                  height="20px"
                  style="display: inline-block"
                ></v-img
                >Shuffle play
              </li>
            </ul>
          </div>
        </v-col>
      </v-row>
    </div>

    <div id="section8">
      <v-row>
        <v-col md="6" sm="12">
          <h2>Why go Premium</h2>
        </v-col>

        <v-col md="6" sm="12">
          <p style="margin-top: 90px; margin-left: 100px">
            Consectetur adipiscing elit, sed do eiusmod tempor incididunt ut
            labore <br />
            et dolore magna aliqua. Quis ipsum suspendisse ultrices gravida.
            Risus <br />
            commodo viverra maecenas accumsan lacus vel facilisis. Lorem
            ipsum<br />
            dolor sit amet, consectetur adipiscing elit, sed do eiusmod
            tempor<br />
            incididunt ut labore et dolore magna aliqua.
          </p>
        </v-col>
      </v-row>

      <v-row>
        <v-col md="3" sm="6">
          <v-img src="@/assets/12.png" id="section8-img"></v-img>
          <h4>No ad interruptions</h4>
          <p>Consectetur adipiscing elit</p>
        </v-col>
        <v-col md="3" sm="6">
          <v-img src="@/assets/13.png" id="section8-img"></v-img>
          <h4>High Quality</h4>
          <p>Ectetur adipiscing elit</p>
        </v-col>
        <v-col md="3" sm="6">
          <v-img src="@/assets/14.png" id="section8-img"></v-img>
          <h4>Listen Offline</h4>
          <p>Sed do eiusmod tempo</p>
        </v-col>
        <v-col md="3" sm="6">
          <v-img src="@/assets/15.png" id="section8-img"></v-img>
          <h4>Download Music</h4>
          <p>Adipiscing elit</p>
        </v-col>
      </v-row>
    </div>

    <div id="footer">
      <v-row>
        <v-col md="6" sm="12">
          <v-img src="@/assets/10.png" id="footer-img"></v-img>
          <v-icon color="#6A7080" id="footer-icon">mdi-instagram</v-icon>
          <v-icon color="#6A7080" id="footer-icon">mdi-facebook</v-icon>
          <v-icon color="#6A7080" id="footer-icon">mdi-twitter</v-icon>
          <v-icon color="#6A7080" id="footer-icon">mdi-youtube</v-icon>
        </v-col>

        <v-col md="2" sm="4">
          <h2>ABOUT US</h2>
          <a href="#">Our Story</a>
          <a href="#">Sol Music Blog</a>
          <a href="#">History</a>
        </v-col>

        <v-col md="2" sm="4">
          <h2>PRODUCTS</h2>
          <a href="#">Music</a>
          <a href="#">Subscription</a>
          <a href="#">Custom Music</a>
          <a href="#">Footage</a>
        </v-col>

        <v-col md="2" sm="4">
          <h2>PLAYLISTS</h2>
          <a href="#">Newsletter</a>
          <a href="#">Careers</a>
          <a href="#">Press</a>
          <a href="#">Contact</a>
        </v-col>
      </v-row>
    </div>
  </div>
</template>

<script>
export default {};
</script>



<style>
body {
  font-family: "Montserrat", sans-serif;
}
#container {
  background-color: #0a183d;
  height: 724px;
  width: 100%;
}

#p-1 {
  color: white;
  display: inline;
  font-size: 60px;
  font-weight: bold;
  line-height: 0.9;
}

#section1 {
  margin-left: 50px;
  margin-top: 100px;
}
#btn-section1-1 {
  margin-top: 50px;
  border-radius: 30px;
  height: 60px;
  color: white;
}
#btn-section1-2 {
  margin-top: 50px;
  margin-left: 20px;
  border-radius: 30px;
  height: 60px;
  border: 2px solid red;
  color: white;
}

#section3 {
  height: auto;
  background-color: white;
  padding-top: 105px;
  padding-bottom: 105px;
}

#section3 h2 {
  margin-left: 70px;
  font-size: 60px;
  display: inline-block;
}
#section3 p {
  display: inline-block;
  padding-left: 50px;
}

#btn-section3 {
  margin-left: 50px;
  margin-top: 20px;
  border-radius: 30px;
  height: 60px;
  color: white;
  width: 150px;
  
}

#section4 {
  background-image: url("@/assets/2.webp");
  height: auto;
  padding-bottom: 200px;
  background-color: #0a193d;
}
#section4 h2 {
  color: white;
  padding-top: 100px;
  padding-left: 100px;
  font-size: 60px;
}

@media only screen and (max-width: 960px) {
  .media {
    min-width: 100%;
    margin-top: 30px;
  }
}

.media {
  width: 33.3%;
}
#section5 {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  background-color: red;
  margin-left: 80px;
  margin-top: 100px;
  margin-bottom: 50px;
  position: relative;
}
#section5-img {
  position: absolute;
  top: 20px;
  left: 40px;
}
#section5-text {
  width: 380px;
  position: absolute;
  top: 80px;
  word-break: break-all;
}
#section5-text p {
  font-size: 15px;
  opacity: 0.6;
  line-height: 1.5;
}
#section5-text h4 {
  font-size: 24px;
  margin-bottom: 20px;
}
#section6 {
  background-color: white;
  width: 100%;
  height: auto;
  padding-bottom: 100px;
}
#section6 h2 {
  font-size: 60px;
  margin-left: 100px;
  margin-top: 100px;
}

#section6 p {
  margin-left: 100px;
  
  margin-top: 100px;
  
}

#section6-img {
  width: 250px;
  height: 250px;
  border-radius: 40px;
  margin: auto;
  margin-top: 50px;
}

#section6-text {
  font-size: 18px;
  text-align: center;
}

#section7 {
  background-color: #0a183d;
  height: auto;
  padding-bottom: 200px;
}
#section7 h2 {
  color: white;
  font-size: 60px;
  font-weight: 500;
  margin-top: 100px;
  margin-left: 70px;
}
#section7 h3 {
  color: red;
  font-weight: 500;
  font-size: 30px;
  margin-left: 70px;
  margin-top: 20px;
}
#section7 p {
  color: white;
  font-weight: 400;
  opacity: 0.6;
  margin-left: 70px;
  margin-top: 20px;
  line-height: 1.5;
}
#section7-window {
  width: 400px;
  height: 440px;
  background-color: #1c294a;
  margin-top: 100px;
  border-radius: 50px;
  padding: 60px 10px 40px 100px;
  margin-left: 70px;
}
#section7 ul {
  list-style: none;
}
#section7 li {
  color: white;
  font-size: 18px;
  margin-bottom: 25px;
}

#section8 {
  background-color: white;
  height: auto;
  padding-bottom: 200px;
}
#section8 h2 {
  margin-left: 100px;
  font-size: 60px;
  margin-top: 80px;
}

#section8-img {
  width: 190px;
  height: 190px;
  border-radius: 50%;
  margin: auto;
  margin-top: 80px;
}
#section8 h4 {
  font-size: 24px;
  text-align: center;
  margin-top: 30px;
}
#section8 p {
  text-align: center;
  margin-top: 10px;
}
#footer {
  background-color: #0a183d;
  height: auto;
  padding-bottom: 100px;
}
#footer-img {
  width: 150px;
  height: 20px;
  margin-top: 100px;
  margin-left: 100px;
}
#footer-icon {
  margin-left: 100px;
  margin-top: 50px;
}

#footer h2 {
  color: white;
  margin-top: 150px;
  text-align: center;
}

#footer a {
  display: block;
  text-align: center;
  margin-top: 20px;
  text-decoration: none;
  color: #6a7080;
}
</style>