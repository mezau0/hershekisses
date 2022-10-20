<template>
  <div class="title">
        <h1>Her/She Kisses</h1>
    </div>

    <div class="titlepic">
        <img src="../assets/title.png" alt="title image; five characters. From right to left; Bax, wearing a 
        sweater rolled at the sleeves and long pants. Cam, wearing a cropped bell-sleeved shirt, a 
        miniskirt, heels, and a long jacket. Emery, who is in a wheelchair, wearing a turtleneck with 
        a heart detail and long gray pants. Archie, dressed in a tank top, a skirt, a fanny pack, leg 
        warmers, and using a cane. Last is Harper in a turtleneck, pants, boots, and a trench coat.">
    </div>

<div class="buttons" >
    <Button text="Start" link=""  margin-right="50px"/> 
    <Button text="Settings" link="" margin-right="50px"/> 
    <Button text="About" link="about" margin-right="50px"/> 
    <Button text="Credits" link=""  margin-right="50px"/> 
    
</div>

</template>

<script setup> 
import Button from "@/components/Button.vue"
</script>

<style scoped>

h1 {
   font-family: 'Press Start 2P', cursive;
   color: #402954;
   font-size: 60px;
   text-align: center;
}

h2 {
   font-family: 'Press Start 2P', cursive;
   color: #402954;
   font-size: 50px;
}

.title {
   display: flex;
   justify-content: center;
   align-items: flex-start;
   padding: 0;
}

.titlepic {
   display: flex;
   justify-content: center;
   align-items: center;
   padding: 10px;
}

.about {
   padding: 40px;
   font-size: 40px;
   display: flex;
   justify-content: center;
   align-items: center;
}
.buttons {
   display: flex;
   justify-content: center;
   align-items: center;
   padding: 20px;
}
.buttonabout {
   background-color: #F7C392;
   font-size: 35px;
   border: 3.5px dashed black;
   border-radius: 50%;
   padding: 16px;
   font-family: 'VT323', monospace;
   margin-right: 150px;
   margin-left: 150px;
   box-shadow: 0 7px #B8916C;
}

.buttonabout:hover {background-color: #FFD6B0}

.buttonabout:active {
 background-color: #F7C392;
 box-shadow: 0 5px #B8916C;
 transform: translateY(4px);
}

.aboutbus {
   display: flex;
   justify-content: center;
   align-items: flex-end;
}


.loading { 
   float: left;
   padding-left: 150px;
   padding-top: 100px;
   padding-bottom: 100px;
   }

.loadingtxt {
  float: right;
  padding-right: 230px;
  padding-top: 250px;
  
}






/* Dot typing animation, from:
https://codepen.io/nzbin/pen/GGrXbp

.dot-typing {
  position: relative;
  left: -9999px;
  width: 10px;
  height: 10px;
  border-radius: 5px;
  background-color: #9880ff;
  color: #9880ff;
  box-shadow: 9984px 0 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  animation: dotTyping 1.5s infinite linear;
}

@keyframes dotTyping {
  0% {
    box-shadow: 9984px 0 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  }
  16.667% {
    box-shadow: 9984px -10px 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  }
  33.333% {
    box-shadow: 9984px 0 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  }
  50% {
    box-shadow: 9984px 0 0 0 #9880ff, 9999px -10px 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  }
  66.667% {
    box-shadow: 9984px 0 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  }
  83.333% {
    box-shadow: 9984px 0 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px -10px 0 0 #9880ff;
  }
  100% {
    box-shadow: 9984px 0 0 0 #9880ff, 9999px 0 0 0 #9880ff, 10014px 0 0 0 #9880ff;
  }
}

*/
</style>