<!-- Routes.svelte -->
<script>
    import { Route, Router } from 'svelte-routing';
    import Home from './pages/Home.svelte';
    import Workshops from './pages/Workshops.svelte';
    import Events from './pages/Events.svelte';
    import Sponsors from './pages/Sponsors.svelte';
    import Accommodation from './pages/Accommodation.svelte';
    import Account from './pages/Account.svelte';
    import Team from './pages/Team.svelte';
    import Contact from './pages/Contact.svelte';
</script>

<Router>
    <Route path="/" component={Home} />
    <Route path="/workshops" component={Workshops} />
    <Route path="/events" component={Events} />
    <Route path="/sponsors" component={Sponsors} />
    <Route path="/accommodation" component={Accommodation} />
    <Route path="/account" component={Account} />
    <Route path="/team" component={Team} />
    <Route path="/contact" component={Contact} />
</Router>
