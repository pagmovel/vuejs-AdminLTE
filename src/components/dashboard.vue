<template>
  <div class="row">
    <div class="col-sm-12 col-md-12">
      <h3>Welcome !!!</h3>
      <p>
        Lorem ipsum Ad non ut aliquip Duis minim sit ex esse eiusmod anim minim 
        esse qui mollit elit do pariatur deserunt eu eiusmod tempor tempor sunt 
        fugiat ad dolore reprehenderit do labore ex.
      </p>
    </div>
  </div>
</template>

<script>
  module.exports = {
    name: "Dashboard",
    data: function(){
      return{
      }
    },
    route: {
      activate: function(t){
        this.$parent.$parent.$data.title = 'Dashboard';
        t.next();
      }
    }
  }
</script>

