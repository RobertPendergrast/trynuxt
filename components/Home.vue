<template>
    <div id="page1">   
        <h1 id="title" class="main">Hi! I'm Robbie</h1>
        <p id="bio" class="back">Student, Designer & Developer</p>
        <img id="photo1" src="profil.jpg" alr="to be changed">
        <div id="AboutMe" class="fadeIn">
            <h1 id="Big">About Me</h1>
            <p class="whitetext">I'm currently a bachelors student at Columbia University in the City of New York studying computer science and applied mathematics.I have a great interest in software development, and intend on pursing studies in artificial intelligence!</p>
            
            <p class="whitetext"></p>
            <p class="whitetext">One of the things I enjoy outside of school and work is music. I have been playing the trumpet for over 10 years! I also enjoy running, and ran the hurdles for my high school track team. Other than that, I spend a lot of my time outside hiking - one of my life goals is to visit every national park!</p>
            <p class="whitetext"></p>
           
            
            <div id="experience">
                <h1 id="ex">My Experience</h1>
                <p class="pad">Here are some of the things that I have experience with!</p>
                <div class="column">
                    
                        
                        <div id="ad" class="box">
                            <p>Graphic Design</p>
                            <!--<NuxtLink class="links" to="/WebDev">Graphic Design</NuxtLink> -->
                        </div> 
                        <div id="Cs" class="box">
                            <p>CSS</p>
                            <!--<NuxtLink class="links" to="/WebDev">Graphic Design</NuxtLink> -->
                        </div>
                        <div id="j" class="box">
                            <p>Java</p>
                            <!--<NuxtLink class="links" to="/WebDev">Graphic Design</NuxtLink> -->
                        </div>
                        
                        
                        
                </div>
                <div class="column">
            
                        
                        <div id="ht" class="box">
                            <p>HMTL</p>
                            <!--<NuxtLink class="links" to="/WebDev">Graphic Design</NuxtLink> -->
                        </div>
                        <div id="gd" class="box">
                            <p>Game Design</p>
                            <!--<NuxtLink class="links" to="/WebDev">Graphic Design</NuxtLink> -->
                        </div>
                        <div id="JS" class="box">
                            <p>JavaScript</p>
                            <!--<NuxtLink class="links" to="/WebDev">Graphic Design</NuxtLink> -->
                        </div>
                        
                </div>
            </div>
            <div>
                
                
            </div>
        </div>
    </div>
    
</template>

<style>

    @import url('https://fonts.googleapis.com/css2?family=Ubuntu&display=swap');
    /* ID */

    
    

    

    .links{
        text-decoration: none;
        color: white;
    }
    
    .pad{
        padding-bottom: 50px;
    }

    #ex{
        padding-bottom: 120px;
        
    }

    #gd{
        background-image: url("../static/gamepost.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        color: white;
        margin: 0;
    }

    #JS{
        background-image: url("../static/JSJS.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        color: white;
        margin: 0;
    }

    #j{
        background-image: url("../static/Java.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        color: white;
        margin: 0;
    }

    #Cs{
        background-image: url("../static/css.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        color: white;
        margin: 0;
    }

    #ht{
        background-image: url("../static/HTMLL.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        color: white;
        margin: 0;
    }

    #ad{
        background-image: url("../static/BlackHole.jpg");
        background-repeat: no-repeat;
        background-size: 100% 100%;
        color: white;
        margin: 0;
    }


    .box{
        padding: 30% 20%;
        font-size: 32px;
        transition: 0.1s;
        size: fixed;
        position: relative;
        text-decoration: none;
    }

    .box:hover{
        box-shadow: inset 0 0 0 250px rgba(4,16,32,0.4);
        transition: 0.5s;
        /*font-size: 36px;*/
    }

    #experience{
        background-color: white;
        text-align: center;
        font-size: 24px;
        padding-top: 100px;
        transition: 0.5s;
        padding-bottom: 1450px;
    }


    #experience:hover{
        border-radius: 10%;
        font-size: 32px;
    }

    #Big{
        text-align: center;
        color: white;
        padding-bottom: 50px;
    }

    #AboutMe{
        background-color: #2BAEFF;
        padding-top: 180px;
        transition: 0.5s;
        font-size: 36px;
    }

    #AboutMe:hover{
        border-radius: 10%;
        transition: 0.5s;
        font-size: 42px;
    }

     #photo1{
        padding-bottom: 180px;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 25%;
        transition: 0.5s;
        height: 25%;
    }

    #photo1:hover{
        padding-bottom: 180px;
        display: block;
        margin-left: auto;
        margin-right: auto;
        width: 27%;
        height: 27%;
        transition: 0.5s;
        
    }

    #title{
        padding-top: 120px;
        text-align: center;
        color: #041020;
        font-size: 64px;
    }

    #page1{
        font-family:'Ubuntu', Arial, sans-serif;
        background-color: white;
        width: 100%;
        scroll-behavior: smooth;
        padding-bottom: 50px;
    }

    #intro{
        
        color: 0a264d;
        font-size: 24px;
        text-align: center;
    }

    #bio{
        text-align: center;
        color: #134a97;
        font-size: 32px;
        font-weight: 700;
    }

    #page{
       font-family: Arial, Helvetica, sans-serif;
    }

    /* Classes */

    .whitetext{
        text-align: justify;
        color: white;
        font-size: 24px;
        padding-right:200px;
        padding-left:200px;
        padding-bottom: 30px;
        text-justify: newspaper;
        
    }

    .column{
        background-color: white;
        float: left;
        width: 50%;
       
        
    }

    
        

    

</style>