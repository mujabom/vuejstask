<template>
  <!--
 implement the following tasks using Vue js :

  1- move each section to a separate Vue component.
  2- make sure the functionality is still present after splitting the sections into components.
  3- implement the Add random number button functionality.
  4- implement the Reset button functionality .

  note: you should Style/CSS the page to be more presentable.
  -->
  <div>
<h2>Section 1</h2>
  <p>Sum Value = {{displayNumber}}</p>


<h2>Section 2</h2>

<button @click="displayNumber++">Add 1</button>
<button @click="displayNumber +=10">Add 10</button>
    <br/>
<p>implement the the add random number between 1-10 and reset button</p>
<button>Add a random number between 1-10</button>
<button>Reset the value to 0</button>




  </div>
</template>

<script>
export default {
  name: "sumNumbers",
  data () {
    return{
      displayNumber:0
    }
  }
}
</script>

<style scoped>

</style>