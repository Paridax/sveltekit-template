<script lang="ts">
	import { PUBLIC_MESSAGE } from '$env/static/public';
</script>

<head>
	<title>Paridax Svelte</title>
</head>

<div class="container h-full mx-auto flex flex-col py-20 justify-center items-center">
	<h1 class="h1">WELCOME!</h1>
	<p class="p">
		{PUBLIC_MESSAGE}
	</p>
</div>
