<script>
  import ArtistList from "./ArtistList.svelte";
  import ArtistSearch from "./ArtistSearch.svelte";
  let searchTerm = "Barot Bellingham";
  let artists = [
    {
      name: "Barot Bellingham",
      src: "https://lil-cdn.com/2824055/Barot_Bellingham_tn.jpg",
      reknown: "Royal Academy of Painting and Sculpture"
    },
    {
      name: "Jonathan G. Ferrar II",
      src: "https://lil-cdn.com/2824055/Jonathan_Ferrar_tn.jpg",
      reknown: "Artist to Watch in 2012"
    }
  ];
</script>

<style global lang="scss">
  $primary: purple;
  @import "../node_modules/bootstrap/scss/bootstrap.scss";
</style>

<div class="container">
  <ArtistSearch {searchTerm} />
  <ArtistList {artists} />
</div>
