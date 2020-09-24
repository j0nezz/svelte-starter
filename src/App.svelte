<script lang="ts">
  export let name: string;
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <h1 class="title">Bulma</h1>

  <p class="subtitle">
    Modern CSS framework based on <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox">Flexbox</a>
  </p>

  <div class="field">
    <div class="control">
      <input class="input" type="text" placeholder="Input" />
    </div>
  </div>

  <div class="field">
    <p class="control">
      <span class="select">
        <select>
          <option>Select dropdown</option>
        </select>
      </span>
    </p>
  </div>

  <div class="buttons">
    <a class="button is-danger">Primary</a>
    <a class="button is-link">Link</a>
  </div>
</main>
<svelte:head>
  <style src="styles.scss">
  </style>
</svelte:head>
