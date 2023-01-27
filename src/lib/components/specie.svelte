<script>
 export let title
 export let image
 export let number
 export let cost
</script>

    <div class="card card-side bg-base-100">
      <figure><img src="/species/{ image }.jpg" class="h-16" alt="Movie"/></figure>
      <div class="card-body p-0 py-8 pl-4">
        <h3 class="card-title text-sm">{ title }</h3>
        <p class="font-bold text-xs">Total Number: { number } | Cost Per Specie: { cost } ARN</p>
        <p class="text-xs"><slot /></p>
      </div>
      <div class="card-actions flex-col justify-center">
        <button class="btn btn-primary p-1 h-min min-h-min">Get one!</button>
      </div>
    </div>
   