<script lang="ts">
  import logo from './assets/svelte.png'
  import Counter from './components/Counter.svelte'
</script>

<main>
  <Counter />
</main>

<style>
  :root {
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen,
      Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  }

  main {
    text-align: center;
    padding: 1em;
    margin: 0 auto;
  }
</style>

<style>
  body {
    background-color: #4f5c7a;
  }

  .appdark {
    border: 10px solid #6277de;
    padding: 0px;
    margin: 0px;
    width: 250px;
    height: 450px;
    border-radius: 25px;
  }
</style>