<script>
export let title
</script>

  <div class="">
    {#if title}
    <small class="uppercase text-base">{ title }</small>
    {/if}
    <h2 class="text-4xl font-medium text-accent"><slot /></h2>
  </div>
