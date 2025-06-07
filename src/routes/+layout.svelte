<script lang="ts">
	import '../app.css';
	import { onMount } from 'svelte';
	
	let { children } = $props();
	onMount(() => console.log(`\nHey there! 👋\n
Since your looking at the code, you might be interested in joining the Syntax Cafe development team!
if you are, please reach out to us on Discord: https://discord.gg/rFyuV5ycHJ.\n
Also, there is a CTF challenge active on this domain (syntaxcafe.app) that you can try to solve,
here is your first hint https://syntaxcafe.app/ctf, good luck! 🕵️‍♂️\n\n`))
</script>

{@render children()}
