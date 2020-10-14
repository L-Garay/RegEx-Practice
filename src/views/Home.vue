<template>
  <div class="home">
    <div class="container-fluid intro">
      <div class="row">
        <div class="col-5">
          <h1>Regular Expressions</h1>
          <p>
            This is just for my own practice, just the expression, expected
            output and the actual output will be displayed.
          </p>
          <p>See code for notes and explanations.</p>
        </div>
      </div>
    </div>
    <div class="container-fluid examples">
      <div class="row">
        <div class="col-6 offset-1">
          <h3>What are Regular Expressions?</h3>
          <ul class="descriptionList">
            <li>Patterns used to match character combinations in strings.</li>
            <li>In JavaScript, they are also objects.</li>
            <li>There are multiple methods that you can use:</li>
          </ul>
        </div>
        <div class="col-11">
          <ul class="methodList">
            <li>
              <h4>test()</h4>
              - executes a search for match between the regular expression and a
              specified string, returns true or false.
            </li>
            <li>
              <h4>exec()</h4>
              - executes a search for match in a specified string and returns
              matching results in an array, or null.
              <b>Can use iterators to iterate over multiple matches.</b>
            </li>
            <li>
              <h4>match()</h4>
              - executes a search for match in a specified string and returns
              matching results in an array, or null.
            </li>
            <li>
              <h4>matchAll()</h4>
              - executes a search for match in a specified string and returns
              matching results in an array, or null.
              <b>Can use iterators to iterate over multiple matches.</b>
            </li>
            <li>
              <h4>search()</h4>
              - tests for a match in a string, it returns the index of the match
              or -1 if the search fails.
            </li>
            <li>
              <h4>replace()</h4>
              - returns a new string with some or all matches of a pattern
              replaced by a replacement. The pattern can be a string or a
              regular expression, and the replacement can be a string or a
              function to be called for each match.
              <b
                >If pattern is a string, only the first occurrence will be
                replaced.</b
              >
              The original string is left unchanged.
            </li>
            <li>
              <h4>replaceAll()</h4>
              - returns a new string with some or all matches of a pattern
              replaced by a replacement. The pattern can be a string or a
              RegExp, and the replacement can be a string or a function to be
              called for each match. If pattern is a string, only the first
              occurrence will be replaced.
            </li>
            <li>
              <h4>split()</h4>
              - divides a string in a given pattern into an ordered list of
              substrings and puts the substrings into an array, and returns the
              array.
            </li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Example from '@/components/Example.vue';
export default {
  name: 'Home',
  components: {
    Example,
  },
  data() {},
  methods: {},
};
</script>

<style>
.intro {
  border-bottom: 3pt solid black;
}
.descriptionList {
  text-align: start;
}
.methodList {
  text-align: start;
  margin-left: 25pt;
}
</style>
