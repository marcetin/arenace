<script>
  // export let post
  import Member from '@components/member.svelte'
  import Title from '@components/title.svelte'
  import Panel from '@components/panel.svelte'
</script>
<div class="divider"></div> 

<div class="grid grid-cols-2 gap-4">
  <Title title="ARENACE TEAM" >Main Team Members</Title>
  <Panel title="People behind Arenace startup project">The main Team members behind the Arenace project development have a lenghty years of expereince in the crypto industry, marketing, web development and grphics design. Beside the main team, we will be hiring more experienced and talented people to boost up Arenace platform on a whole new level of interactivity.</Panel>
</div>




 <div class="w-full grid grid-cols-4 gap-8">
  <Member 
avatar="rzi"
name="Rod Zisso"
role="Head of Blockchain Development and Project Management"
location="USA / Burkina Faso"
twitter="rodzisso"
github="muroko"
 ></Member>
 <Member 
avatar="carlos"
name="Carlos Contreras"
role="Head of Marketing Strategy and Social Medias Management"
location="USA / Mexico Europe"
twitter="carlos"
github="carlos"
 ></Member>
 <Member 
avatar="marcetin"
name="Djordje Marcetin"
role="Head of Web Development and Servers Node Management"
location="Europe / Serbia"
twitter="marcetin"
github="marcetin"
 ></Member>
 <Member 
avatar="peter"
name="Peter Eu"
role="Head of Ui/UX Design and Arts Management"
location="Asia / Malaysia"
twitter="motleysquad"
github="inkiya"
 ></Member>
</div>