<template>
<div class="body">
    <link rel="stylesheet" href="https://fonts.google.com/specimen/Erica+One?thickness=10">
      <div class="introduction">
        <div class="intro-text">
            <h1>JOSHUA LAROA</h1>
            <h5>Graphic Designer, Video Editor, Frontend Developer, Aspiring UI/UX Designer</h5>
            <br>
            <p>Hi! I'm Joshua Laroa, I am currently studying BSIT in University of San Carlos.
                I live in Talisay City, Cebu, Philippines. I have a passion about art and graphic. All my
                life I surround myself with artwork. When I was still an elementary student, my cousin installed
                Adobe Photoshop. Since then I sharpened my skills on digital art platforms. 
                <br><br> My parents discourage me on taking art related courses 
                like architecture and fine arts because they want me to be an engineering student. I found
                a course suited for me where I can mix art and technology. I am a frontend developer and 
                currently studying UI/UX Design.
            </p>
            </div>
         <div class="intro-pic"><img src="../assets/intro.png"></div>
      </div>

      
</div>
</template>

<script>

</script>

<style>


.intro-pic img{
    float: right;
    height: auto;
    width: 100%;
    margin-top: -265px;
}

.intro-text{
    margin-top: 80px;
    margin-left: 200px;
    float: left;
    
}
h1{
    
    font-family: "Intro";
    height: auto;
    width: 100%;
}

h5{
    font-family: "P";
    font-weight: bold;
}

p{
    margin-top: -20px;
    font-family: "P";
    height: 50px;
    width: 600px;
}

@font-face {
  font-family: "Intro";
  src: local("Intro"),
   url(../fonts/Intro.ttf) format("truetype");
}

@font-face {
  font-family: "P";
  src: local("P"),
   url(../fonts/P.ttf) format("truetype");
}
</style>
