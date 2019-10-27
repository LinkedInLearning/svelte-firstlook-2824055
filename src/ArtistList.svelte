<script>
  export let artists;
</script>

<style>
  img {
    height: 80px;
  }

  h4 {
    font-size: 1rem;
  }

  p {
    font-size: 0.8em;
  }
</style>

{#each artists as { name, src, reknown }}
  <div
    class="list-group-item d-flex w-100 list-group-item-action
    align-items-center">
    <img class="rounded mr-3 d-block" {src} alt={`Photo of ${name}`} />
    <div>
      <h4 class="mb-0">{name}</h4>
      <p class="text-muted mb-0">{reknown}</p>
    </div>
  </div>
{/each}
