<script>
    import Hero from '../../components/Hero.svelte';
    import SidebarSubnav from '../../components/SidebarSubnav.svelte';
    export let segment;
</script>
<style>
    .address{
        padding:2rem;
    }
</style>
<Hero
        heroImage="/assets/images/heros/leaking-house.jpg"
        heroTitle="Contact A+ Rooter Inc."
        heroBigText="Free Estimates"
        heroText=" Fill Out The Form Below Or Call To Contact A+ Rooter Inc.">
    <p>Contact A+ Rooter Inc. at <a href="tel:+1-847-838-0406" title="click here to call now">1-847-838-0406</a>.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Plumbing Repair Or Plumbing Installation Service">Order Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <SidebarSubnav {segment}/>
        </aside>
    </div>
</div>
