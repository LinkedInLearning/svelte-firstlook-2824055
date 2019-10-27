<script>
  import { onMount } from "svelte";
  import ArtistList from "./ArtistList.svelte";
  import ArtistSearch from "./ArtistSearch.svelte";
  let searchTerm = "Barot Bellingham";
  let artists = [];

  onMount(async () => {
    const res = await fetch(`data.json`);
    artists = await res.json();
  });
</script>

<style global lang="scss">
  $primary: purple;
  @import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>

<div class="container">
  <ArtistSearch {searchTerm} />
  <ArtistList {artists} />
</div>
