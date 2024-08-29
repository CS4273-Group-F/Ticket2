<script>
	import { onMount } from 'svelte';
  
	onMount(() => {
	  // Ensure this script only runs once in the browser
	  if (typeof window !== 'undefined') {
		document.body.style.margin = '0';
		document.body.style.padding = '0';
	  }
	});
  </script>
  
  <header>
	<h1>Demo Svelt App</h1>
  </header>
  
  <main>
	<slot />
  </main>
  
  <style>
	header {
	  background-color: #ff3e00;
	  color: white;
	  padding: 1em;
	  text-align: center;
	}
  
	h1 {
	  margin: 0;
	  font-size: 1.5em;
	}
  
	main {
	  padding: 1em;
	}
  </style>
  