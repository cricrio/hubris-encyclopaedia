<script>
  import Header from "./components/Header.svelte";
  import Card from "./components/Card.svelte";
  import Grid from "./components/Grid.svelte";
</script>

<main>
  <Header />
  <Grid>
    <Card
      title="Ferrari"
      description="Odit inventore est laborum sunt velit voluptates. Non porro voluptatibus quidem nisi illo non molestiae. Iste et tenetur excepturi omnis ut velit inventore vel.
"
    />
    <Card
      title="Ferrari"
      description="Odit inventore est laborum sunt velit voluptates. Non porro voluptatibus quidem nisi illo non molestiae. Iste et tenetur excepturi omnis ut velit inventore vel.
"
    />
    <Card
      title="Ferrari"
      description="Odit inventore est laborum sunt velit voluptates. Non porro voluptatibus quidem nisi illo non molestiae. Iste et tenetur excepturi omnis ut velit inventore vel.
"
    />
  </Grid>
</main>

<style>
  main {
    margin: auto;
    max-width: 780px;
  }
</style>
