<template>
    <div id="footer">
        <p id="Contact">Contact Me!</p>
        <a  href="https://www.linkedin.com/in/robert-pendergrast-6b731420a" target="_blank"><img class="image" src="linkedin.jpg"></a><a  href="https://www.instagram.com/robbiependergrast/" target="_blank"><img class="image" src="instagram.jpg"></a><a  href="https://www.facebook.com/robbie.pendergrast.98" target="_blank"><img class="image" src="facebook.jpg"></a>
    </div>
</template>

<style>

    @import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');
    
    #Contact{
        padding-top: 30px;
        padding-bottom: 30px;
        transition: 0.5s;
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
        border-radius: 5%;
        
    }

    .image{
        height: 2.5%;
        padding-left: 20px;
        padding-right: 20px;
        width: 2.5%;
        transition: 0.5s;
    }

    .image:hover{
        height:4%;
        width:4%;
        transition: 0.5s;
    }
</style>