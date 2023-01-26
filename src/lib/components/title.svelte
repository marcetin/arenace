<script>
export let title
</script>

  <div class="card-body">
    {#if title}
    <small class="uppercase text-base">{ title }</small>
    {/if}
    <h2 class="text-4xl font-medium"><slot /></h2>
  </div>
