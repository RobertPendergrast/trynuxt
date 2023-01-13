<template>
    <div id="page1">   
        <h1 id="title" class="main">Hi! I'm Robbie</h1>
        <p id="bio" class="back">Student, Designer & Developer</p>
        <img id="photo1" src="redpanda.jpg" alr="to be changed">
        <div id="AboutMe" class="fadeIn">
            <h1 id="Big">About Me</h1>
            <p class="whitetext">I'm currently a bachelors student at Columbia University in the City of New York studying computer science and applied mathematics.I have a great interest in software development, and intend on pursing studies in artificial intelligence!</p>
            
            <div id="experience">
                <h1 id="ex">My Experience</h1>
                <p class="pad">Click on the boxes below to check out some of the things I've made!</p>
                <div class="column">
                        <p id="ad" class="box">Affinity Designer</p>
                        <p id="Cs" class="box">CSS</p>
                        <p id="j" class="box">Java</p>
                </div>
                <div class="column">
                        <p id="ht" class="box">HTML</p>
                        <p id="gd" class="box">Game Design</p>
                        <p id="JS" class="box">JavaScript</p>
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
        transition: 0.5s;
        size: fixed;
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
        padding-bottom: 1300px;
    }


    #experience:hover{
        border-radius: 10%;
        font-size: 32px;
    }

    #Big{
        text-align: center;
        color: white;
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
        height: 25%
        
    }

    #title{
        padding-top: 120px;
        text-align: center;
        color: #041020;
        font-size: 64px;
    }

    #page1{
        font-family:'Ubuntu', sans-serif;
        background-color: white;
        width: 100%;
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
        text-align: center;
        color: white;
        padding: 80px 80px;
        font-size: 24px;
        padding-right:200px;
        padding-left:200px;
        padding-bottom: 180px;
        
    }

    .column{
        background-color: white;
        float: left;
        width: 50%;
    }

    
        

    

</style>