<script>
export let avatar
export let name
export let role
export let location
export let twitter
export let github
</script>

<div class="card card-compact w-full bg-base-100 shadow-xl">
  <figure><img src="https://placeimg.com/400/225/arch" alt="Shoes" /></figure>
  <div class="card-body">
    <h2 class="card-title">{ name }</h2>
    <p>{ role }</p>
    <p>{ location }</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">{ twitter }</button>
      <button class="btn btn-primary">{ github }</button>
    </div>
  </div>
</div>