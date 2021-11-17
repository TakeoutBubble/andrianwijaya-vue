<template>
<div class="container">
      <div class='andrian'>
           <div class="image">
              <img src="@/assets/andrian2.png" alt="My Picture" class="picture1">
            </div>
                   <h1 class="title">
                    Andrian Wijaya
                    </h1>
       <p class='text1'><span class='text2'>Enthusiastic </span> Web Developer</p>
       <div class="links text-center">
        <a class='sosmed inline-block mr-4 duration-200 ease-in-out' href="https://github.com/TakeoutBubble">
          <img src="@/assets/github-circle.svg" alt="Github" class='w-8' target="_blank">
        </a>
        <a class='sosmed inline-block mr-4 duration-200 ease-in-out' href="https://www.linkedin.com/in/andrian-wijaya-056a981bb/">
          <img src="@/assets/linkedin-circle.svg" alt="Linkedin" class='w-8' target="_blank">
        </a>
        <a class='sosmed inline-block mr-4 duration-200 ease-in-out' href="https://web.facebook.com/wandrian404/">
          <img src="@/assets/facebook.svg" alt="Linkedin" class='w-8' target="_blank">
        </a>
        <a class='sosmed inline-block mr-4 duration-200 ease-in-out' href="https://www.instagram.com/andrianwijaya404/">
          <img src="@/assets/instagram.svg" alt="Linkedin" class='w-8' target="_blank">
        </a>
        </div>
    </div>
      </div>
</template>
<script>
export default {};
</script>
<style scoped>
.socmed:hover {
  transform: translateY(-10px);
}
.image img {
  filter: drop-shadow(0 10px 30px #ccc);
}
.title {
  display: block;
  font-weight: 300;
  font-size: 100px;
  color: #35495e;
  letter-spacing: 1px;
}
.links {
  padding-top: 15px;
}
.text2 {
  color: green;
  font-size: 30px;
}
</style>