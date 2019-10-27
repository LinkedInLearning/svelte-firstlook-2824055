<script>
  import ArtistList from "./ArtistList.svelte";
  import ArtistSearch from "./ArtistSearch.svelte";
  let searchTerm = "Barot Bellingham";
</script>

<style global lang="scss">
  $primary: purple;
  @import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>

<div class="container">
  <ArtistSearch {searchTerm} />
  <ArtistList />
</div>
