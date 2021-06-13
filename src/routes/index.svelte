<svelte:head>
	<title>WYSIWYG</title>
</svelte:head>

<div class="w-full p-10 h-screen bg-green-200">
	<div class="rounded-3xl bg-white border shadow p-3">
		<div class="focus:outline-none border-red-500 border rounded p-2" contenteditable bind:innerHTML={isi}></div>
		<textarea name="" id="" cols="30" rows="10" bind:value={isi} class="focus:outline-none border-red-500 border rounded p-2"></textarea>
	</div>
</div>

<script>
	let isi
</script>