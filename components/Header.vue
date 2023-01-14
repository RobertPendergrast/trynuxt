<template>
    
    
    <div id="head" class="links">
        <div class="column">
            <a href="#head"><img src="logo2.jpg" class="headder"></a>
        </div>
        <div class="column">
            <p class="header"> <a id="About" href="#AboutMe">About</a> <a id="projects" href="#experience">Projects</a> <a id="contact" href="#footer">Contact</a> </p>
        </div>
    </div>
</template>

<style>

    #logo{
        padding-left:60px;
        text-align: left;
    }

    #head{
        height: 40px; 
    }

    #About{
        transition: 0.5s;
    }

    #projects{
        transition: 0.5s;
    }
    
    #About:hover{
        color: #134a97;
        transition: 0.5s;
    }

    #projects:hover{
        color: #134a97;
        transition: 0.5s;    
    }

    #contact{
        padding-right: 60px;
        transition: 0.5s;
    }
    #contact:hover {
        color: #134a97;
        transition: 0.5s;
    
        
      }

    .links a{
        text-decoration: none;
        color: #2BAEFF;
    }

    .header{
        text-align: right;
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        font-size: 18px;
        font-weight: 500;
        color: #2BAEFF;
        word-spacing: 20px;
        padding-top: 20px;
    }

    .headder{
        font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
        font-size: 18px;
        font-weight: 500;
        color: #2BAEFF;
        word-spacing: 20px;
        padding-top: 20px;
        height: 6%;
        width: 6%;
        padding-left: 60px;
    }

    .column{
        float: left;
        width: 50%;
    }

</style>