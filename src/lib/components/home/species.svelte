<script>
  // export let post
  import Title from '@components/title.svelte'
  import Panel from '@components/panel.svelte'
  import Specie from '@components/specie.svelte'
</script>
<div class="grid grid-flow-row-dense grid-cols-3">
  <div>
    <Title title="ARENACE SPECIES">NFT Staking Platform</Title>

<Panel title="How Does it Work?">
<h4 class="font-bold">Arenace Species NFT Staking Platform</h4>
<p>The Specie NFTs are set in 5 categories:</p>
<p>Human, Mutant, Cyborg, Alien and Dragon species.</p>
<p>The cost of each NFT staking is between 20 to 100
ARN. The total amount of the Species NFTs is 50000
and half is set as a initial sale and the other half is
reserved to be pursached on the platform.</p>
<p>There is no limit on how many species you can stake.
Each specie is a game character and will unlock
special and more powerful abilities in our games.</p>
</Panel>
  </div>
  <div class="col-span-2">

    <Specie title="HUMANS SPECIE" image="" number="10000" cost="20">More details on the character combats, strengths, unique abilities and rarities will be set in our upcoming initial white paper.</Specie>
    <Specie title="MUTANTS SPECIE" image="" number="10000" cost="40">More details on the character combats, strengths, unique abilities and rarities will be set in our upcoming initial white paper.</Specie>
    <Specie title="CYBORGS SPECIE" image="" number="10000" cost="60">More details on the character combats, strengths, unique abilities and rarities will be set in our upcoming initial white paper.</Specie>
    <Specie title="ALIENS SPECIE" image="" number="10000" cost="80">More details on the character combats, strengths, unique abilities and rarities will be set in our upcoming initial white paper.</Specie>
    <Specie title="DRAGONS SPECIE" image="" number="10000" cost="100">More details on the character combats, strengths, unique abilities and rarities will be set in our upcoming initial white paper.</Specie>


  </div>
</div>