<script setup>
import {reactive} from "vue";

const props = defineProps({
  text: {
    type: String,
    required: true
  }, 
  link: {
    type: String,
    required: true
  },
  marginLeft: {
    type: String,
    default: "0"
  },
  marginRight: {
    type: String,
    default: "0"
  },
})

const style = reactive({
  marginLeft: props.marginLeft, 
  marginRight: props.marginRight,
})

</script>

<template>
    <router-link :to="link" class="button" :style="style"> {{text}} </router-link>
</template>

<style scoped>
.button {
   background-color: #F7C392;
   font-size: 35px;
   border: 3.5px dashed black;
   border-radius: 50%;
   padding: 16px;
   font-family: 'VT323', monospace;
   box-shadow: 0 7px #B8916C;
}

.button:hover {background-color: #FFD6B0}

.button:active {
 background-color: #F7C392;
 box-shadow: 0 5px #B8916C;
 transform: translateY(4px);
}
</style>
