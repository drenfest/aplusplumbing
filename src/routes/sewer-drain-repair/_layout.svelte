<script>
    import Hero from '../../components/Hero.svelte';
    import SidebarSubnav from '../../components/SidebarSubnav.svelte';
    import CouponSidebar from '../../components/CouponSidebar.svelte';
</script>
<style>

</style>
<Hero heroImage="/assets/images/heros/storm-drain.jpg" heroTitle="Sewer & Drain Repair Services" heroBigText="A+ Rooter Inc." heroText="Make Sure Your Storm Drains Are Working Properly">
    <p>At A+ Rooter Inc. Plumbing, we use the latest sewer camera technology to find, repair, or clean your sewer problems. We can also diagnose and fix storm drain, floor drain, and outside floor drain problems for you. Contact us today and we will make sure you get affordable prices and fast turnaround times from a company with over 30 years in business.</p>
    <a class="btn btn-light" href="/contact" title="Schedule Sewer & Drain Repair Service">Schedule Service Now</a>
</Hero>
<div class="container">
    <div class="row">
        <section class="content col-xs-12 col-sm-8">
            <slot></slot>
        </section>
        <aside class="content col-xs-12 col-sm-4">
            <SidebarSubnav />
            <CouponSidebar/>
        </aside>
    </div>
</div>
