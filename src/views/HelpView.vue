<template >
  <div id="Help">
    <v-row  >
      <v-col md="12" sm="12" >
        <div id="help2" v-show="$vuetify.breakpoint.mdAndUp" >
            <h1>Help Center</h1>
              <v-text-field
            label="How can we help?"
            outlined 
            class="txt-box "
            
          > </v-text-field>
        </div>
      </v-col>
    </v-row>


    <v-row>
      <v-col sm="12">
        <div v-show="$vuetify.breakpoint.smAndDown" id="help3">
           <h1>Help Center</h1>
              <v-text-field
            label="How can we help?"
            outlined 
            class="txt-box2"
         
          > </v-text-field>
          </div>
      </v-col>
    </v-row>

    <h1 style="text-align:center;margin:20px;color:white">Answers to your questions</h1>
    <v-row >
      <v-col sm="12" md="12">
    <v-list >
      <v-list-group no-action id="list" >
        <template v-slot:activator >
          <v-list-item-content >
            <v-list-item-title > I forgot my login details</v-list-item-title>
          </v-list-item-content>
        </template>

        <v-list-item >
          <v-list-item-content>
            <v-list-item-title>
              <h3>
                I forgot the email address associated with my SoloMusic account
              </h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaelabore, tempora corporis, sint excepturi quas<br/>
                quam perspiciatis quod optio eum ratione, odit est accusantium delectus nostrum. Reiciendis dignissimos <br/>
                beatae consectetur, sed repudiandae magni ipsum. Cupiditate sednulla natus hic enim deserunt molestias autem <br/>
                facere voluptatum totam consequatur cum perferendis repellatvelit earum eum, rem obcaecati quaerat et illum provident.<br/>
                Adipisci, facilis odio suscipit aspernatur ex facere minus maxime culpa labore libero assumenda recusandae consectetur<br/>
                ipsam sunt porro dolore deserunt quisquam architecto est sed iusto? Iusto laborum tenetur suscipit voluptatibus <br/>
                aut necessitatibus non quo adipisci ratione natus, assumenda enim, vero distinctio at, repudiandae eum magnam nulla rerum<br/>
                aperiam nam? Doloribus nulla libero tempore, quia obcaecati  alias sint debitis vero modi nobis eos magni porro ad cum<br/>
                distinctio, eius dignissimos nihil labore maxime omnis. Impeditasperiores doloremque iusto. Voluptate rem sint rerum voluptas<br/>
                iure!
              </p>

              <h3>I forgot my password</h3>
              <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nostrum rem quo dolor sequi ad impedit omnis excepturi labore minus<br/> 
                  soluta perferendis nulla nam natus odio doloremque odit, aperiam magnam at facilis. Culpa a unde modi dolore, iure aspernatur vel <br/>
                  deleniti. Debitis, aspernatur. Delectus reiciendis suscipit placeat voluptatum quia commodi aliquid.<br/>
                  </p>
              
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-group>

      <v-list-group no-action id="list">
        <template v-slot:activator>
          <v-list-item-content>
            <v-list-item-title>What is SoloMusic?</v-list-item-title>
          </v-list-item-content>
        </template>

        <v-list-item>
          <v-list-item-content>
            <v-list-item-title>
              <p>
                Founded in 2007, SoundCloud is an artist-first platform powered by a global community of artists and listeners on the pulse of <br/>
                what’s new, now and next in music culture. We empower independent artists with the tools, services and resources they <br/>
                need to help them build and grow their careers. With over 250 million tracks from 30 million artists from 190 countries<br/>
                 on SoundCloud,we are the largest audio discovery platform in the world. 
                 </p>
              
              <h3>How can you use SoloMusic?</h3>
              <p><br/>
                     Lorem ipsum dolor sit amet consectetur adipisicing elit. Provident reiciendis beatae quas<br/>
                     Perferendis, tenetur facilis tempore doloremque repudiandae suscipit dolore labore deserunt fugiat consequatur<br/> 
                     Esse magni, quo cumque architecto deserunt officiis dolorum autem, molestias fugiat omnis dolorem qui error atqu<br/>
                     quod distinctio dolores sequi maiores at eos facere quasi. Tenetur facilis impedit debitis delectus sed numquam,<br/>
                     perferendis officiis sunt temporibus iure sequi?
                 </p>
              
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-group>

      <v-list-group no-action id="list">
        <template v-slot:activator>
          <v-list-item-content>
            <v-list-item-title
              >How do I get started on SoloMusic?</v-list-item-title
            >
          </v-list-item-content>
        </template>

        <v-list-item>
          <v-list-item-content>
            <v-list-item-title>
              <h3>Setting up your profile</h3>
              <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quos provident nesciunt optio nihil voluptas, molestias<br/> laudantium neque? natus asperiores
                    fuga numquam minus ullam quis voluptas dolorum facilis culpa adipisci labore voluptate quos unde dicta aut sint, dolores<br/>
                     repellendus.
                </p>
              
              <h3>Building your community</h3>
              <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit. Tempore explicabo mollitia dolor cupiditate vero eaque, sequi<br/> repudiandae esse sunt ipsum, accusantium fugit 
                    provident? Excepturi, rerum natus. Totam nostrum eos quia et odit ullam ipsa natus cumque <br/>quibusdam tempora, minus
                     unde illo ipsam sunt iure adipisci obcaecati.Sed tempora aliquid commodi!
                </p>
              
              <h3>Uploading your first track</h3>
              <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Perspiciatis voluptates quasi possimus
                    animi illum, neque minima eius omnis cumque nihil.
                </p>
              
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-group>

      <v-list-group no-action id="list">
        <template v-slot:activator>
          <v-list-item-content>
            <v-list-item-title
              >Getting started with mastering</v-list-item-title
            >
          </v-list-item-content>
        </template>

        <v-list-item>
          <v-list-item-content>
            <v-list-item-title>
              <h3>What is Mastering?</h3>
              <p>>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Officia nostrum sed ea unde possimus nemo<br/>
                     quaerat expedita eum, consectetur,modi delectus totam, dolorum quia eos veniam corrupti. Nulla, minus vero!
                </p>
              
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-group>

      <v-list-group no-action id="list">
        <template v-slot:activator>
          <v-list-item-content>
            <v-list-item-title>SoloMusic Go General FAQs</v-list-item-title>
          </v-list-item-content>
        </template>

        <v-list-item>
          <v-list-item-content>
            <v-list-item-title>
              <h3>
                Can I access the full SoloMusic catalogue with SoloMusic Go?
              </h3>
              <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Harum voluptatibus sit error quos neque amet minima <br/>
                    eveniet veritatis iste tempore repellendus explicabo provident, dicta quod eos obcaecati incidunt.<br/> Alias, necessitatibus 
                     dolorum sint quam sunt aliquid explicabo, laborum architecto illum doloremque a nesciunt <br/>dolore non voluptate  
                    Architecto fugit aliquid natus minus repellendus ipsum enim facere, fuga nemo dolor quae<br/> dolores inventore soluta! 
                     quia soluta recusandae quis! Blanditiis dicta magni beatae esse ab ipsa vel sapiente quibusdam<br/> temporibus  
                     consequatur eum iste quasi commodi perspiciatis obcaecati laborum? Minima repellat consequatur<br/> voluptatum error commodi 
                     dolor officiis vel illum numquam repellendus earum ipsa reprehenderit sed nesciunt sequi laboriosam<br/> ducimus quis!  
                     corrupti magnam ad nobis, perferendis sequi nisi quibusdam fugiat error repellendus libero quis velit,<br/> dolorem adipisci magni
                     repellat ipsam optio rem architecto atque cupiditate! Molestias pariatur accusantium enim, minima <br/>laudantium laboriosam 
                     quod illo necessitatibus doloribus eos ut itaque, nisi facilis odio excepturi  et! Vero labore <br/>odio dolorem est corrupti 
                     Eaque deleniti at impedit delectus non.<br/>
                </p>
              
              <h4>How many devices can I use with my Go subscription?</h4>
              <p>
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Exercitationem adipisci commodi  unde totam <br/>laboriosam nisi provident
                    ut quo ullam ab voluptatem, error, temporibus aperiam maiores fuga quisquam assumenda magni quis! <br/>Doloremque ,
                    nobis architecto earum libero nostrum a ipsa numquam sit eos! Modi perspiciatis alias doloribus voluptatibus. <br/> veniam recusandae 
                    esse atque facilis ab. Ullam quisquam aut perspiciatis incidunt a ab sunt velit, excepturi iste cumque natus, <br/>tempore vel
                    quaerat enim recusandae. Possimus, libero ea? Odit aliquid magnam consectetur praesentium quidem distinctio officia quae cum.<br/>
                </p>
              
              <h4>What does ad-free mean?</h4>
              <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Dolorum quae odit neque repellat eaque odio ad commodi rerum amet<br/>
                     itaque ex nulla. Alias quae ullam nostrum corrupti eos officiis fuga, quidem cupiditate maxime? Repellat et <br/>
                     neque ullam optio ab laboriosam. Voluptatibus dignissimos commodi placeat, ea corporis ex id, ullam<br/>
                    reprehenderit officiis modi numquam sapiente similique. Consectetur alias nobis voluptate quas at suscipit quod<br/>
                    Fugiat ratione ducimus corporis obcaecati! Iusto provident dolorem magnam assumenda ex omnis, molestias repellendus<br/>  
                    alias perspiciatis reprehenderit!
                </p>
              
            </v-list-item-title>
          </v-list-item-content>
        </v-list-item>
      </v-list-group>
      
    </v-list>
    </v-col>
    </v-row>
  </div>
</template>



<style>
#list {
  border: 1px solid white;
  border-left: none;
  border-right: none;
  background-color: #0a183d ;
}

#Help{
  background-color: #0a183d ;
  font-family: "Montserrat", sans-serif;
}



#help2 {
  background-image: url("@/assets/23.jpg");
  height: 500px;
  padding-left: 280px;
 margin-left:260px ;
 margin-top: 20px;
}
#help2 h1{
  font-size:60px;
  margin-right: 200px;
  color: white;
}

.txt-box{
  width: 300px;
  position: relative;
  left: 40px;
  top: 80px;
  
}


#help3 h1{
  font-size:60px;
  text-align: center;
  
}


.txt-box2{
  width: 200px;
position: relative;
top: 20px;
left: 30%;

}

.theme--light.v-list{
  background-color: #0a183d; 
  color: #ffffff;
}
down::before{
  color: #ffffff;
}
#Help *{
  color: #ffffff;
  
}


::after{
  color: #ffffff;
}

</style>

        


