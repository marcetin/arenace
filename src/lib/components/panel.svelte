<script>
export let title
</script>

<div class="w-full text-sm">
  <div class="prose lg:prose-xl">
    {#if title}
    <h2 class="bg-accent px-2 py-1 text-sm text-base-100">{ title }</h2>
    {/if }
    <div><slot /></div>
  </div>
</div>