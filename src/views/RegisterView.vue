<template>
    <div id="regiser">
    <div id="register-img">
        <h1>Create an account</h1>
        </div>
        <div id="register-txt">
            <input type="text" placeholder="Enter your username" id="input-text-box" >
            <input type="email" placeholder="Enter your email" id="input-text-box" >
            <input type="password" placeholder="Enter your password" id="input-text-box">
            <v-btn color="#0a216693" id="register-btn">Create an account</v-btn>
            <p style="text-align:center;color:white">don't have an account? <a href="/Login" >Login now!</a></p>
    </div>
    
    </div>
</template>



<style>




body {
  font-family: "Montserrat", sans-serif;
}
#regiser{
    background-color:#0a183d ;
    height: auto;
    padding-bottom: 150px;
    
}


#register-img{
    background-image: url('@/assets/17.jpg');
    height: 150px;
    width: 500px;
   margin: auto;
   position: relative;
   top: 20px;
   border-radius: 20px 20px 0px 0px;
}
#register-img h1{
text-align: center;
position: relative;
top: 80px;
}



#register-txt{
    height: 380px;
    width: 500px;
    background-color: #050d24;
    padding-top: 50px;
    margin: auto;
   border-radius: 0px 0px 20px 20px;
   margin-top: 20px;
  

}





#input-text-box{
    display: block;
    width: 400px;
    background-color: #0a216693;
    outline: none;
    padding: 15px 10px;
    margin-left: 55px;
    margin-bottom: 30px;
    border-radius: 20px; 
    transition: 0.5s;
    
}
#register-btn{
    width: 400px;
    height: 45px;
    border-radius: 20px;
    margin-left: 55px;
    display: block;
    margin-bottom: 20px;
     color: #ffffff;
}
#input-text-box:hover{
    background-color:#26365f;
    transition: 0.5;
}
#register-txt a{
color:white;
text-decoration: underline;
}

</style>