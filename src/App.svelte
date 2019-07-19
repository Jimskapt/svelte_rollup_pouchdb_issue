<script>
	import PouchDB from 'pouchdb-browser';

	export let name;

	let db = new PouchDB('test');
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello {name}!</h1>
