<script lang="ts">
	import '../app.css';
	const { children } = $props();
	export const prerender = true;
</script>

{@render children()}
