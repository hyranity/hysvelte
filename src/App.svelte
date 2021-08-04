<script>
	import { Router, Route, Link } from "svelte-navigator";
	import Landing from "./pages/Landing.svelte";
	
</script>

<Router primary={false}>
	<div class="main">
	  <Route path='/'>
		<Landing/>
	  </Route>
	</div>
  </Router>