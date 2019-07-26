<script>
  import { Router, Route } from 'svero'

  import Home from '@components/home/Home.svelte'
</script>

<Router>
  <Route path="/" component={Home} />
</Router>
