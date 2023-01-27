<script>
  // export let post
  import Title from '@components/title.svelte'
  import Panel from '@components/panel.svelte'
</script>


<div class="grid grid-cols-3 grid-rows-2 gap-8 py-16 bg-base-200 ">
  <div class="flex flex-col py-16">
    <Panel title="ArnSwap">Arenace Decentralized Exchange
      Our own (DEX) which will feature
      buys and sells of crypto currencies
      and staking of LP tokens to earn a
      share of the trading fees.</Panel>
    <Panel title="ArnNft">Arenace NFTs Marketplace
      Where you can mint, buy and sell
      digital collectibles and game
      characters as NFTs to be used in the
      Play 2 Earn games</Panel>
    <Title class="row-span-2" title="ARENACE DAPPS ECOSYSTEM">Platform Ecosystem</Title>
    <Panel title="ArnVatars">Arenace Social Avatars
      Our users social Avatars that can be
      set as a profile avatar across
      Arenace Network and can also be
      used to unlock some perks.</Panel>
    <Panel title="ArnDeck">Arenace Play 2 Earn Platform
      Where users engage themselves in
      all sort of fun games from FPS, RPG,
      Platformer to Puzzle games. You
      earn ARN token on the platform.</Panel>
</div>

grid grid-cols-4 gap-4