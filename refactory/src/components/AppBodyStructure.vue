<template>
  <div>
    <div class="container-fluid">
      <div class="row">
        <div class="col-xl-12">
          <navbar/>
        </div>
      </div>

      <div class="row">
        <div class="col-sm-3">
        <sidebar/>
          
        </div>
        <div class="col-sm-7">
          <Body />
        </div>
        <div class="col-sm-2">
          <button class="btn btn-danger">ggggg</button>
        </div>
      </div>
      <div class="row">
        <div class="col-xl-12">
          <Footer />
        </div>
      </div>
    </div>
  </div>
</template>

<script>

import sidebar from './sidebar.vue'
import navbar from './navbar.vue'
import Footer from './Footer.vue'
import Body from './Body.vue'

export default {
 name: 'AppBodyStructure',
 components: {
    sidebar, navbar,Footer,Body
  }
}
</script>

<style>
.btn {
  width: 100%;
}

.row {
  margin: 20px;
}
</style>
