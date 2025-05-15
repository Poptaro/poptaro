<script lang="ts">
	import '../app.css';
	
	let { children } = $props();
</script>

<div class="flex justify-between items-center px-8 w-full bg-gray-800 h-12">
	<div class="text-orange-500">
		Poptaro
	</div>
	<div>
		:D
	</div>
</div>

{@render children()}
