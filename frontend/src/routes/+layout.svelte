<script lang="ts">
	import '../app.css';
	
	let { children } = $props();
</script>

<div class="flex justify-between items-center px-8 w-full bg-taro-darkGray h-20">
	<div class="flex items-center justify-center text-taro-orange text-2xl">
		<p class="">
			P&#8239;O&#8239;P&#8239;T&#8239;A&#8239;R&#8239;O
		</p>
	</div>
	<div>
		:D
	</div>
</div>

{@render children()}
