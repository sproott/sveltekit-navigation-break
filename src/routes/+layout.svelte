<script lang="ts">
	let { children } = $props()
</script>

<div>
	<a href="/">Main</a>
	<a href="/second">Second</a>
	<a href="/break">Break</a>
</div>

{@render children()}
