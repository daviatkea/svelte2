<script>
  export let type = "default";
  export let inversed = false;
</script>

<button class:inversed class={type}><slot /></button>

<style>
  button {
    border: none;
    color: var(--primary-font-color);
    background: var(--default-color);
    padding: 1rem;
    border-radius: 12px;
    transition: all 0.2s;
    cursor: pointer;
    max-width: -moz-fit-content;
    max-width: fit-content;
  }
  .primary {
    background: var(--primary-color);
  }
  .primary:hover {
    color: var(--primary-color);
    background: var(--primary-font-color);
  }
  .secondary {
    background: var(--secondary-color);
  }
  .primary.inversed {
    color: var(--primary-color);
    background: var(--primary-font-color);
  }
  .secondary.inversed {
    color: var(--secondary-color);
    background: var(--primary-font-color);
  }
</style>
