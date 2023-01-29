<template>
    <div id="footer">
        <p id="Contact">Contact Me!</p>
        <a  href="https://www.linkedin.com/in/robert-pendergrast-6b731420a" target="_blank"><img class="picture" src="linkedin.jpg"></a><a  href="https://www.instagram.com/robbiependergrast/" target="_blank"><img class="picture" src="instagram.jpg"></a><a  href="https://www.facebook.com/robbie.pendergrast.98" target="_blank"><img class="picture" src="facebook.jpg"></a>
    </div>
</template>

<style>

    @import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');
    
    #Contact{
        padding-top: 50px;
        padding-bottom: 30px;
        transition: 0.5s;
        font-family: 'Ubuntu' Arial, sans-serif;
    }

    
    #footer{
        text-align: center;
        font-family: Ubuntu;
        color: white;
        font-size: 28px;
        background-color: #2BAEFF;
        padding-bottom: 50px;
        transition: 0.5s;
        
    }
    
    #footer:hover{
        font-size: 32px;
        height: 120%;
        transition: 0.5s;
        
    }

    .picture{
        height: 2.5%;
        padding-left: 20px;
        padding-right: 20px;
        width: 2.5%;
        transition: 0.5s;
    }

    .picture:hover{
        height:4%;
        width:4%;
        transition: 0.5s;
    }
</style>