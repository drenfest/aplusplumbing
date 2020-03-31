<script>
    import Divider from "../components/Divider.svelte";
</script>
<style>
    .why-us-section{
        align-items:center;
        text-align:center;
    }
    .why-us-section > .container{
        padding:4rem 2rem 0rem 2rem;
    }
    .why-us-section h3{
        font-weight:normal;
    }
    h2 {
        padding:1rem;
    }
    h3{
        color: var(--primary-color);
    }
    .row img{
        margin:1rem 0;
        max-height:50px;
    }
    .row{
        margin:2rem;
    }
</style>

<section class="why-us-section">
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#202d41" fill-opacity="1" d="M0,288L40,277.3C80,267,160,245,240,213.3C320,181,400,139,480,144C560,149,640,203,720,240C800,277,880,299,960,293.3C1040,288,1120,256,1200,224C1280,192,1360,160,1400,144L1440,128L1440,0L1400,0C1360,0,1280,0,1200,0C1120,0,1040,0,960,0C880,0,800,0,720,0C640,0,560,0,480,0C400,0,320,0,240,0C160,0,80,0,40,0L0,0Z"></path></svg>
        <Divider>
            <h2>Why Choose A+ Rooter Inc.,  Plumbing Sewer and Drain</h2>
        </Divider>
    <div class="container">
        <div class="row">
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/licensed-logo.png" alt="Licensed Icon">
                <h3>Licensed</h3>
            </div>
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/bonded-logo.png" alt="Bonded Icon">
                <h3>Bonded</h3>
            </div>
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/rapid-response-times.svg" alt="Rapid response times Icon">
                <h3>Rapid response times</h3>
            </div>
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/24-badge.png" alt="24/7 Emergency Icon">
                <h3>24/7 Emergency</h3>
            </div>
        </div>
        <div class="row">
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/affordable-rates.svg" alt="Affordable rates Icon">
                <h3>Affordable rates</h3>
            </div>
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/satisfaction-guaranteed.svg" alt="Satisfaction Guranteed">
                <h3>Satisfaction Guranteed</h3>
            </div>
            <div class="col-xs-12 col-md">
                <img src="/assets/images/icons/free-estimates.svg" alt="Free Written Estimates and second opinions Icon">
                <h3>Free Written Estimates and second opinions</h3>
            </div>
        </div>
    </div>
    <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#202d41" fill-opacity="1" d="M0,288L40,277.3C80,267,160,245,240,213.3C320,181,400,139,480,144C560,149,640,203,720,240C800,277,880,299,960,293.3C1040,288,1120,256,1200,224C1280,192,1360,160,1400,144L1440,128L1440,320L1400,320C1360,320,1280,320,1200,320C1120,320,1040,320,960,320C880,320,800,320,720,320C640,320,560,320,480,320C400,320,320,320,240,320C160,320,80,320,40,320L0,320Z"></path>
    </svg>
</section>
