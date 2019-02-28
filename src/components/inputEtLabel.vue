<template>
  <div class="input_et_label">
    <label for="textfield">{{message_label}}</label>
   
    <textarea v-if="typeInput==='textarea'" id="textfield" v-model="message_label"></textarea>      
    <input v-else id="textfield"  v-bind:type="typeInput" v-bind:value="message">
  </div>
</template>

<script>
export default {
  name: "input_et_label",
  props: {
    message: String,
    message_label: String,
    //add types + algo
    typeInput: String
  }
};
</script>

<style scoped>
.input_et_label {
  color: red;
}
label {
  display: block;
  
  width: 150px;
}

input {
  float: left;
}
</style>