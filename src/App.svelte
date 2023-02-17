<script lang="ts">
	import { Route, Router } from 'svelte-routing'

	import Index from './routes/index.svelte'
</script>

<Router>
	<Route path="/" component={Index} />
</Router>
