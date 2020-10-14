<template>
  <div class="home">
    <div class="container-fluid intro">
      <div class="row">
        <div class="col-12">
          <h1>Regular Expressions</h1>
          <p>This is just for my own practice, just the expression, expected output and the actual output will be displayed.</p>
          <p>See code for notes and explanations.</p>
        </div>
      </div>
    </div>
    <div class="examples">
      <h3>What are Regular Expressions?</h3>
      <ul class="descriptionList">
        <li>Patterns used to match character combinations in strings.</li>
        <li>In JavaScript, they are also objects.</li>
        <li>There are multiple methods that you can use.</li>
      </ul>
      <p>  </p>
    </div>
  </div>
</template>

<script>
import Example from '@/components/Example.vue'
export default {
  name: 'Home',
  components: {
    Example
  },
  data() {

  },
  methods: {

  }
}
</script>

<style>
.intro {
  border-bottom: 3pt solid black;
}
.examples {
  display: flex;
  flex-direction: column;
}
.descriptionList {
  text-align: start;
}
</style>
