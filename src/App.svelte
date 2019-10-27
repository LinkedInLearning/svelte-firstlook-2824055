<script>
  export let name;
</script>

<style lang="scss">
  $primary: purple;

  @import "../node_modules/bootstrap/scss/bootstrap.scss";

  h1 {
    color: $primary;
  }
</style>

<div class="container">
  <h1>Hello {name}!</h1>
  <p class="text-primary">
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam deserunt eos
    quam reprehenderit porro, dolor nulla veritatis iure, voluptas repellendus
    consequuntur fugit illum similique? Ab obcaecati doloribus distinctio iure?
    Dolor.
  </p>
</div>
