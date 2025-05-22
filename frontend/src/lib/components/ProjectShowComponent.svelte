<script>
  import { Diamond } from "@lucide/svelte";
  const { frontRunner, bullet, title, image, flipped } = $props()


</script>

<div class={`${flipped ? "flex flex-row-reverse" : "flex"} gap-2 items-center justify-evenly w-full h-96 text-white p-4`}>
  <div class="flex items-center justify-center min-w-48 w-[450px]">
    <img src={image} alt="showcase of specific project"/>
  </div>
  <div class={`flex flex-col items-center justify-center min-w-48 w-84`}>
    <h1 class="text-3xl text-taro-orange">{title}</h1>
    <p class="text-center">{frontRunner}</p>
    <ul class="w-full">
      {#each bullet as line}
      <li class="flex items-center">
        <Diamond fill="white" size=8 class="shrink-0"/><p class="pl-2">{line}</p>
      </li>
      {/each}
    </ul>
  </div>
</div>