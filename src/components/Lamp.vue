<script setup>
// defineProps({
//   lightsOn: {
//     type: Boolean,
//     required: true
//   }
// })
</script>

<template>
  <div class="text" id="cord">
  </div>

  <div id="lamp">

    <div class="text" id="socket">
    </div>
    
    <br>
    
    <div class="text"  id="bulb">
      <span id="coil">
        w
      </span>
    </div>

  </div>

  <div id="light">

  </div>
      
</template>
<style>
  #coil {
    font-size:0.75rem;
  }
  #light {
    z-index:3;
    height:350px;
    aspect-ratio: 1;
    position:absolute;
    margin:0px!important;
    top: 50%;
    left:50%;
    background:none;
    border-radius:50%;
    filter: blur(800px);
  }
  #lamp {
    display:flex; 
    justify-content: center; 
    align-items:center; 
    flex-direction:column; 
    margin-bottom:1rem;
  }
  #cord {
    height:10vh; 
    width:50%; 
    border-right:2px solid black; 
    display:flex; 
  }
  #socket {
    height:2vh; 
    width:1.5vh; 
    border:2px solid black; 
  }
  #bulb {
    height:5vh;
    width:5vh; 
    border-radius: 50%; 
    border:2px solid black;
    margin-top:-2px;
  }
</style>