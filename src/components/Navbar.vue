<template>
    <div class="navbar">
        <div class="logo" href="#">
            <a href=""><img src="../assets/logo.png"></a>
        </div>
        <div class="navbar-list">
          <a href="" class="link">About Me</a>
          <a href="" class="link">Achievements</a>
          <a href="" class="link">Projects</a>
          <a href="" class="link">Services</a>
          <a href="" class="link">Contact Me</a>
        </div>

    </div>
</template>

<script>

</script>

<style>
a:link {
  text-decoration: none;
}

a:hover{
    color: #54b0e9;
}

.navbar{
  font-family: "Nav";
  list-style-type: none;
  width: auto;
  height: auto;
  background-color: none;
}

.link{
  margin-right: 60px;
  color: #9f73b7;
}

.logo img{
    margin-top: 10px;
  margin-left: 10px;
  width: auto;
  height: 60px;
}

@font-face {
  font-family: "Nav";
  src: local("Nav"),
   url(../fonts/Nav.ttf) format("truetype");
}

</style>