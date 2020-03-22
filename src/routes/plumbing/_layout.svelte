<script>
    import Hero from '../../components/Hero.svelte';

     import SidebarSubnav from '../../components/SidebarSubnav.svelte';
</script>
<style>

</style>
<Hero
        heroImage="/assets/images/heros/seepage-tile.jpg"
        heroTitle="Plumbing Services"
        heroBigText="A+ Rooter"
        heroText="Residential and Commercial Plumbing Services">
    <p>Whether your home or office is having trouble with its plumbing, the team at A+ Rooter Plumbing is here to help you. We can diagnose the issue with your plumbing and then take the proper steps to fixing it. If your toilet won’t flush or your sinks are clogged, contact us; we will be able to help you with affordable rates and fast turnaround times.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <SidebarSubnav />

        </aside>
    </div>
</div>
