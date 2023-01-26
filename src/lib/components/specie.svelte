<script>
 export let title
 export let image
 export let number
 export let cost
</script>

    <div class="card card-side bg-base-100">
      <figure><img src="/species/{ image }.jpg" alt="Movie"/></figure>
      <div class="card-body p-0 pl-4">
        <h2 class="card-title">{ title }</h2>
        <p class="font-bold">Total Number: { number } | Cost Per Specie: { cost } ARN</p>
        <p><slot /></p>
        <div class="card-actions justify-end">
          <button class="btn btn-primary p-1 h-min min-h-min">Get one!</button>
        </div>
      </div>
    </div>
   