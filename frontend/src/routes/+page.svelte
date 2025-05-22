<script>
  import IntroComponent from "@/lib/components/IntroComponent.svelte";
  import ProjectShowComponent from "@/lib/components/ProjectShowComponent.svelte";
  // import FooterComponent from "@/lib/components/FooterComponent.svelte";
  import CityScopeLanding from "@/lib/assets/img/cityScopeLanding.png";
  import SummonMeLanding from "@/lib/assets/img/summonMeLanding.png"

  const cityArray = [
    "Itineraries for future trips allow user to see what they plan on doing each day",
    "Full user capability utilizing Django Rest Framework Tokens",
    "Explore nearby attractions utilizing Google Maps",
  ]

  const summonArray = [
    "Build `Glance-Over` snippets of builds",
    "",
  ]

</script>

<div class="flex flex-col items-center justify-center w-full bg-taro-lightGray">
  <IntroComponent />
  <ProjectShowComponent title="City Scope"  frontRunner="Upcoming vacation? Plan ahead by creating day-by-day itineraries" bullet={cityArray} image={CityScopeLanding} flipped={false}/>
  <ProjectShowComponent title="SummonMe" frontRunner="An app for veteran league players which allows users to create brief snippets of builds" bullet={summonArray} image={SummonMeLanding} flipped={true}/>
  <!-- <ProjectShowComponent title="blank" frontRunner="need an app? heres my solution/description" bullet="blank" image="ligma" flipped={false}/> -->
</div>
