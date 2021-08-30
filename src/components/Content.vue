<template>
<div class="content">
    <div class="schools">
        <h4>My Institutions</h4>
        <div class="img-container">
            <img src="../assets/schools.png">
        </div>
    </div>

      <div class="projects">
        <h2>Achievements</h2><br><br>
        <h6>
        <tr>
            <th>Mang Tinapay Bakeshop - Freelance Motion Graphic Editor</th>
            <th>Free Flow Clothing - Graphic Designer</th>
        </tr>
        <tr>
            <th>Mancao Aesthetic Clinic - Poster Artist</th>
            <th>Developer Student Club (University of San Carlos)
            - Design Lead</th>
        </tr>
        <tr>
            <th>Indak Productions - Graphic Designer</th>
            <th>Code Fresh Apparel - CEO and Graphic Designer</th>
        </tr>
        
        </h6>
      </div>

      <div class="design">
        <h3>My Design Portfolio</h3>
        <div class="container-design">
            <a href="https://www.behance.net/joshualaroa"><img src="../assets/dp.png"></a>
        </div>
      </div>

      <div class="contact">
        <h5>Contact Me!</h5>

           <img src="../assets/fb.png" class="fb">
            <img src="../assets/phone.png" class="phone">
            <img src="../assets/email.png" class="email">

      </div>
</div>
</template>

<script>

</script>

<style>
    .content{
        margin-top: 200px;
        width: auto;
        height: auto;
    }

    .img-container{
       
       padding: 50px;   
       margin-right: auto;
       margin-left: auto;
    }

    .schools img{
        margin-top: -50px;
         display: block;
         margin-left: auto;
        margin-right: auto;
        width: 40%;   
    }

    h4{
        margin-top: 550px;
        text-align: center;
        font-family: "Nav";
        color: #9f73b7;
    }

    .projects{
        height: 260px;
        width: auto;
        background-image: linear-gradient(to right, #9f73b7 , #54b0e9);
    }

    h2{
        padding-top: 15px;
        font-family: "Intro";
        color: white;
        text-align: center;
    }
    th {
        height: 60px;
        }
    h6{
        margin-top: -50px;
        margin-left: auto;
        margin-right: auto;
        width: 840px;
        padding-top: 20px;
        font-family: "P";
        color: white;
        text-align: center;
    } 


    h3{
        padding-top: 15px;
        font-family: "Intro";
        color: #9f73b7;
        text-align: center;
    }

    .design img{
        margin-top: 10px;
         display: block;
         margin-left: auto;
        margin-right: auto;
        width: 60%;   
    }


    .contact{
        margin-top: 50px;
        height: 200px;
        background-image: linear-gradient(to right, #9f73b7 , #54b0e9);
    }

    .contact img{
        margin-top: 20px;
    }
    
    .contact button{
        background: none;
        border: none;
        padding: 0;
        cursor: pointer;

    }

    .fb {
        margin-top: 10px;
         display: block;
         margin-left: auto;
        margin-right: auto;
        width: 10%;   
    }

    .phone{
        margin-top: 10px;
         display: block;
         margin-left: auto;
        margin-right: auto;
        width: 12%;   
    }

    .email{
        margin-top: 10px;
         display: block;
         margin-left: auto;
        margin-right: auto;
        width: 20%;   
    }

    h5{
        padding-top: 15px;
        font-family: "Intro";
        color: white;
        text-align: center;
    }
</style>