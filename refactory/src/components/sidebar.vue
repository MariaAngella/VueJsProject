<template>
  <div id="sidebar">
    <ul>
    <li> <a href="#" class="btn btn-md btn-outline-primary">menu1</a></li>
    <li> <a href="#" class="btn btn-md btn-outline-primary">menu2</a></li>
    <li> <a href="#" class="btn btn-md btn-outline-primary">menu3</a></li>
    </ul>
    
  </div>
</template>

<script>
export default {
  name: 'sidebar',
  
}
</script>


<style scoped>
.btn{
width:100%
}
.row{
margin-bottom:20px;
}

#sidebar ul li{
list-style: none;
margin-bottom: 5%
}


</style>
