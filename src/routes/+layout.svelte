<script>
	import '../app.css';
</script>

<slot />

<style lang="postcss">
	:root {
		@apply w-screen min-h-screen;
		@apply bg-gradient-to-br from-white to-purple-200;
		@apply font-mono;
	}
</style>
