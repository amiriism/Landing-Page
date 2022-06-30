<template>
    <div id="login">
    <div id="login-img">
        <h1>Login</h1>
        </div>
        <div id="login-txt">
            <input type="text" placeholder="Username" id="input-txt-box" >
            <input type="password" placeholder="Password" id="input-txt-box">
            <v-btn color="#0a216693" id="login-btn">Login</v-btn>
            <label style="font-weight:bold;margin:10px;color:white" >Remember me</label><input type="checkbox" >
           
        
        
    </div>
    
    </div>
</template>



<style>
body {
  font-family: "Montserrat", sans-serif;
}

#login{
    background-color:#0a183d ;
    height: auto;
    padding-bottom: 150PX;
    
}


#login-img{
    background-image: url('@/assets/16.jpg');
    height: 150px;
    width: 500px;
   margin: auto;
   border-radius: 20px 20px 0px 0px;
    position: relative;
    top: 20px;
    
}
#login-img h1{
   text-align: center;

}
#login-txt{
    height: 350px;
    width: 500px;
    background-color: #050d24;
    padding-top: 50px;
   margin: auto;
   border-radius: 0px 0px 20px 20px;
margin-top: 20px;
}



#input-txt-box{
    display: block;
    width: 400px;
    background-color: #0a216693;
    color: white;
    outline: none;
    padding: 15px 10px;
    margin-left: 55px;
    margin-bottom: 30px;
    border-radius: 20px; 
    transition: 0.5s;
}
#login-btn{
    width: 400px;
    height: 45px;
    border-radius: 20px;
    margin-left: 55px;
    display: block;
    color: #ffffff;
    margin-bottom: 50px;
}
#input-txt-box:hover{
    background-color:#26365f ;
    transition: 0.5;
}


</style>