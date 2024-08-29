<script>
	import { onMount } from 'svelte';
  
	onMount(() => {
	  window.afdcStationsOptions = {
		"country":"all",
		"localeCountry":"US",
		"path":"/find/route",
		"query":{
		  "fuel":["ELEC"],
		  "ev_levels":["all"]
		}
	  };
  
	  const script = document.createElement('script');
	  script.src = "https://widgets.nrel.gov/afdc/station-locator/assets/embed.js";
	  script.async = true;
	  script.defer = true;
	  document.body.appendChild(script);
	});
  </script>
  
  <div id="afdc-stations">
	<div id="afdc-stations-loading">Loading alternative fueling station locator...</div>
  </div>
  
  <noscript>Please enable JavaScript to view the alternative fueling station locator.</noscript>
  