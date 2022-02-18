<script>
  export let title;
  export let description;
</script>

<article class="card">
  <header class="title">
    {title}
  </header>
  <div>
    {description}
  <div>
</article>

<style>
.card {
  background-color: black;
  color: white;
  padding: 1rem;
  border-radius: 0.5rem;
}

.title {
  font-weight: 600;
  margin-bottom: 0.5rem
}
</style>