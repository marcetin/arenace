<script>
export let title
</script>

<div class="card card-compact w-full bg-base-100">
  <div class="card-body prose lg:prose-xl">
    {#if title}
    <h2 class="card-title bg-accent px-2 py-1 text-sm text-base-100">{ title }</h2>
    {/if }
    <p><slot /></p>
  </div>
</div>