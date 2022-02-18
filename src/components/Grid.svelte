<div class="grid">
  <slot/>
</div>

<style>

.grid {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  gap: 1rem;
}

</style>