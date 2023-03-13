<script lang="ts">
  let noteCount = 0;
  let octave = 0;
  
</script>

<main>
  <div>  
    Note range
    <input type="text">
  </div>
  <div>
    Note count
    <input type="text">
  </div>  
</main>

<style>
  main {
    display: flex;
    flex-flow: row wrap;
    justify-content: center;
    gap: 1rem;
    margin: 1rem;
  }
</style>