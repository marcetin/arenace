<script>
export let avatar
export let name
export let role
export let location
export let twitter
export let github
</script>

<div class="card card-compact w-full bg-base-100 shadow-xl">
  <figure><img src="/team/{ avatar }.jpg" alt="{ name }" /></figure>
  <div class="card-body border-4 rounded-b-3xl border-accent">
    <h2 class="card-title bg-accent -m-4 px-2 py-1 pb-2 text-base-100">{ name }</h2>
    <p>{ role }</p>
    <p>{ location }</p>
    <div class="card-actions justify-end">
      <button class="btn btn-primary">{ twitter }</button>
      <button class="btn btn-primary">{ github }</button>
    </div>
  </div>
</div>