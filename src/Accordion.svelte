<script>
	import Body from "./body.svelte";
	
	import Item from "./item.svelte";
	
	let active = null;
</script>

<svelte:head>
<link href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css" rel="stylesheet"></svelte:head>

<div class="space-y-4">

	
	<Body bind:active>
		<Item id="0" title="Accordion Item #1" subTitle="First One">
			<h1>
				This is the first item's accordion body.
			</h1>
		</Item> 

		<Item id="1" title="Accordion Item #2" subTitle="Second One">
			<h1>
				This is the second item's accordion body.
			</h1>
		</Item> 

		<Item id="2" title="Accordion Item #3" subTitle="Third One">
			<h1>
				This is the third item's accordion body.
			</h1>
		</Item> 
	</Body>
</div>