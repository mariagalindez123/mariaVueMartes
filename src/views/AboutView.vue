<template>
  <div clas="row">
<div class="d-flex align- items-start-bg-light mb-3" style="height:100px;">
  <div clas="col">
    <p>SEBASTIEN GOMEZ</p>
    <b-img src="https://picsum.photos/300/300/?image=44" fluid thumbnail></b-img>
    <div class="col">
      
      <p>DATOS PERSONALE </p>
      <p>MIS ARCHIVOS</p>
      <p>MAS OPCIONES</p>
    </div>
  </div>
  </div>

<div clas="row">>
  <label for="d-flex-center"></label>
  <div class="d-flex align- items-star bg-light mb-3" style="height: 300px;">
    <div class=" col">
      <p>SUBIR ARCHIVO</p>
  
      <b-form-file v-model="file2" class="mt-3" plain></b-form-file>
    
     
    <b-col sm="2">
      <label for="textarea-small">Small:</label>
    </b-col>
   
      
    </div>
  </div>
</div>
</div>
   
    

</template>
<script>
  export default {
    data() {
      return {
        file1: null,
        file2: null
      }
    }
  }
</script>



