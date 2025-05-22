<script lang="ts">
  import { Diamond } from "@lucide/svelte";
  import ToastSit from "$lib/assets/img/toastSit.png"
</script>


<div class="flex flex-col items-center justify-center h-96 w-full text-white font-bold shrink-0">
  <div class="flex flex-col items-center justify-center w-[500px] shrink-0">
    <img src={ToastSit} alt="toast sitting with a calender" class="h-28 shrink-0"/>
    <h1 class="w-full text-5xl text-center shrink-0">Hello, I'm Noah</h1>
    <div class="flex items-center justify-center text-xl shrink-0">
      <p>Software Engineer</p>
      &nbsp;&nbsp;&nbsp;<Diamond fill="white" size=8/>&nbsp;&nbsp;&nbsp;
      <p>Dallas Texas</p>
    </div>
    <div>
      
    </div>
  </div>
</div>