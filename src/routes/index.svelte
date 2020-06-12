<script>
	import Hero from '../components/Hero.svelte';
	import Divider from '../components/Divider.svelte';
	import Coupon from '../components/Coupon.svelte';
	import ServicesGrid from '../components/ServicesGrid.svelte';

</script>
<style>

	.homeintro {
	padding-bottom:5vh;
	}
	.homeintro h2{
		font-size:3rem;
				color:var(--primary);

	}

	.about-section{
    position: relative;
    padding-top:8vh;
    	}
	.about-section > .container > h2{
		margin-bottom:1.75rem;
		font-weight:700;
		font-size:2.5rem;
	}
	.aboutsub {
	font-size:60%;
	font-weight:300;
	display:block;
	text-transform:uppercase;
	}
	.red{
		color:var(--danger);
	}
	.blue{
		color:var(--primary);
	}
	.about-support {
	font-family: 'Oswald', sans-serif;
	text-transform:uppercase;
	font-size:18px;
	font-weight:400;
	line-height:1.4em;
	display:block;
	margin-bottom:.15rem;
	}
	.abouthmtx {
	padding:0px ;
	}

	.service-btns-bg{
	background: rgb(61,84,103);
background: linear-gradient(90deg, rgba(61,84,103,1) 9%, rgba(96,115,130,1) 90%);
	}
	.service-buttons{
		display:grid;
		grid-template-rows:1fr 1fr 1fr;
	}
	.coupon-section{
		background-image: url(/assets/images/homeaboutbk.jpg);
		background-size:cover;
		background-repeat:no-repeat;
		background-attachment:fixed;
		padding:0;
		position:relative;
	}
	.coupon-section > .container > .row{
		margin: 2rem 0;
	}
	.specials-button{
		margin-top:2rem;
	}
	.specials-button>a{
		background-color:var(--primary-color);
		border:none;
		border-radius:0;
	}
	.specials-button>a:hover{
		background-color:#711D1D;
	}
	.background-wave{
		margin-top:-50px;
	}
	@media screen and (min-width:768px){

	.about-section{
	}
	.abouthmtx {
	padding:0px 75px;
	}


		.service-btns-bg{
			background: rgb(61,84,103);
background: linear-gradient(90deg, rgba(61,84,103,1) 9%, rgba(96,115,130,1) 90%);
		}
		.service-buttons{
			grid-template-rows:1fr;
			grid-template-columns: 1fr 1fr 1fr;
			max-width: 1140px;
			margin:auto;
		}
	}


 @media screen and (max-width: 768px){

 .homeintro{
 padding-left:3vw;
 padding-right:3vw;
	 padding-left: 30px;
 }
}

</style>
<svelte:head>
	<title>A+ Rooter Inc., Plumber, Sewer, & Drain Repair Company</title>
	<meta name="description" content="Customers rely on A+ Rooter Inc. to get the job done in a high-degree of professionalism and workmanship.">
</svelte:head>
<Hero
		heroImage="/assets/images/heros/truck.jpg"
		heroTitle="Plumbing Company | Sewer & Drain Experts"
		heroBigText="A+ Rooter Inc."
		heroText="90 Minute Emergency Service Available">
	<p>A+ Rooter Inc., is Antioch Illinois’s preferred  Plumbing Company. We offer 24/7 Plumbing Emergency Service and promise to be at your door step in 90 minutes or less.  We are family owned and operated plumbing company licensed, bonded and Insured covering Lake and McHenry Counties</p>
	<a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>


</Hero>
<!--Service Buttons Are In Hero Component-->
<section class="about-section">

	<div class="container">
	<div class="homeintro">
		<h2 class="text-center">A+ Rooter Inc.<span class="aboutsub">Sewer &amp; Drain Experts</span></h2>

		<div class="row justify-content-center" style="padding:15px 0 0px;">
			<div class="row">
				<div class="col-xs-12 col-sm-6">
					<h3 class="blue">Award Winning Plumber - Sewer and Drain Repair Since 1989</h3>
					<h4>We Serve- Antioch, McHenry, Mundelein, Vernon Hills, Waukegan, Crystal Lake and Beyond
					</h4>
					<p>A+ Rooter Inc.,  is here to help.  From common problems like leaky faucets and toilets to sewer repair and installation or maybe you have a clogged drain?  A+ Rooter Inc. will quickly diagnose your problem and have you on your way.  We Service residential and commercial, are fully equipped to solve any of your draining problems, big or small, at a price you can afford with the least amount of inconvenience to you.</p>
					<ul>
						<li>Sewer Repairs And Clean-Out Installations</li>
						<li>Emergency Issues 24/7</li>
						<li>Repairs On All Makes & Models</li>
						<li>Maintenance</li>
					</ul>
				</div>
					<div class="col-xs-12 col-sm-6">
						<h3 class="blue">Why Choose A+ Rooter Inc.,  Plumbing Sewer and Drain</h3>
						<p>With over 8 trucks on the road at any given time our plumbers can respond to your emergency fast.  Whether it’s holiday, weekend or 2am our friendly plumbers will be at your doorstep within 90 minutes or less because we realize that’s when you need us most.</p>
						<p>For years, our goal has been to ensure the complete satisfaction of every customer while offering knowledge and friendly service at affordable rates. We hope that you’ll feel confident in our ability to exceed all of your expectations and know that our customers are always our number one focus.</p>
						<a class="btn btn-danger text-center" style="display:block;" href="tel:+1847-838-0406" title="Click Here To Call Now ">Call Now! 1-847-838-0406</a>
					</div>
			</div>
		</div>
		</div>
	</div>
</section>
<section class="coupon-section">
<div class="wavedown2"><svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="100%" height="auto" viewBox="0 0 1200 43.057" enable-background="new 0 0 1200 43.057" xml:space="preserve">
<path fill="#FFFFFF" d="M1200-1v25.353c0,0-113.453,14.887-293.734,14.183S590.773,17.312,447.112,16.606S108.522,34.31,0,34.31
	V-0.295L1200-1z"/>
</svg> </div>
	<Divider>
		<h2>Specials</h2>
	</Divider>
	<div class="container">
		<div class="row">
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$50" couponTitle="Off Sump Pumps &amp; Battery Backups" couponSubtitle="" couponText="Not to be combined with any other discount or offer"/>
			</div>
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$30" couponTitle="Off Drain Cleaning" couponSubtitle="" couponText="Not to be combined with any other discount or offer"/>
			</div>
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$50" couponTitle="Off Hydro Jetting" couponSubtitle="" couponText="Not to be combined with any other discount or offer"/>
			</div>
		</div>
		<div class="row">
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$100" couponTitle="Off Water Heaters" couponSubtitle="" couponText="Not to be combined with any other discount or offer"/>
			</div>
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$100" couponTitle="Off Any Repair Over $1000" couponSubtitle="" couponText="Not to be combined with any other discount or offer"/>
			</div>
			<div class="col-xs-12 col-sm-4">
				<Coupon couponPrice="$10%" couponTitle="Off Seniors, Military &amp; First Responders" couponSubtitle="" couponText="Not to be combined with any other discount or offer"/>
			</div>
		</div>
<!--		<div class="text-center specials-button">-->
<!--			<a class="btn btn-primary btn-lg text-center" href="special" title="See Our Specials">See All Of Our Current Specials</a>-->
<!--		</div>-->
	</div>
	 <div class="waveup2"><svg style="margin-bottom:-2px" version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
     width="100%" height="auto" viewBox="0 0 1200 43.057" enable-background="new 0 0 1200 43.057" xml:space="preserve">
<path fill="#FFFFFF" d="M0,43.057V17.704c0,0,113.453-14.887,293.734-14.183S609.227,24.745,752.888,25.45
    S1091.478,7.747,1200,7.747v34.604L0,43.057z"/>
</svg> </div>
</section>

<Divider>
	<h2>Sewer &amp; Drain Services</h2>
</Divider>
<ServicesGrid/>
