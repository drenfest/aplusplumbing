<script>
	import Hero from '../components/Hero.svelte';
	import Divider from '../components/Divider.svelte';
	import Coupon from '../components/Coupon.svelte';
	import ServicesGrid from '../components/ServicesGrid.svelte';

</script>
<style>
	.about-section{
		padding:4rem 2rem 24rem;
		background-size: cover;
		background-position: bottom center;
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
		padding:3rem 0;
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
	@media screen and (min-width:768px){

	.about-section{
		padding:6rem 2rem 6rem;
		background-size: cover;
		background-position: bottom center;
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
</style>
<svelte:head>
	<title>A+ Rooter, Sewer & Drain Repair Company</title>
	<meta name="description" content="Customers rely on A+ Rooter to get the job done in a high-degree of professionalism and workmanship.">
</svelte:head>
<Hero
		heroImage="/assets/images/heros/truck.jpg"
		heroTitle="Plumbing Company | Sewer & Drain Experts"
		heroBigText="A+ Rooter"
		heroText="90 Minute Emergency Service Available">
	<p>A+ Rooter Inc., is Antioch Illinois’s preferred  Plumbing Company. We offer 24/7 Plumbing Emergency Service and promise to be at your door step in 90 minutes or less.  We are family owned and operated plumbing company licensed, bonded and Insured covering Lake and McHenry Counties</p>
	<a class="btn btn-light" href="/contact" title="Schedule Hvac Repair Or Hvac Installation Service">Schedule Service Now</a>
</Hero>
<!--Service Buttons Are In Hero Component-->
<section class="about-section">
	<div class="container">
		<h2 class="text-center">A+ Rooter<span class="aboutsub">Sewer &amp; Drain Experts</span></h2>

		<div class="row justify-content-center" style="padding:15px 0 0px;">
			<div class="row">
				<div class="col-xs-12 col-sm-6">
					<h3>Award Winning Plumber - Sewer and Drain Repair Since 1989</h3>
					<h4>We Serve- Antioch, McHenry, Mundelein, Vernon Hills, Waukegan, Crystal Lake and Beyond
					</h4>
					<p>A+ Rooter Inc.,  is here to help.  From common problems like leaky faucets and toilets to sewer repair and installation or maybe you have a clogged drain?  A+ Rooter will quickly diagnose your problem and have you on your way.  We Service residential and commercial, are fully equipped to solve any of your draining problems, big or small, at a price you can afford with the least amount of inconvenience to you.</p>
					<ul>
						<li>Sewer Repairs And Clean-Out Installations</li>
						<li>Emergency Issues 24/7</li>
						<li>Repairs On All Makes & Models</li>
						<li>Maintenance</li>
					</ul>
				</div>
					<div class="col-xs-12 col-sm-6">
						<h3>Why Choose A+ Rooter Inc.,  Plumbing Sewer and Drain</h3>
						<p>With over 8 trucks on the road at any given time our plumbers can respond to your emergency fast.  Whether it’s holiday, weekend or 2am our friendly plumbers will be at your doorstep within 90 minutes or less because we realize that’s when you need us most.</p>
						<p>For years, our goal has been to ensure the complete satisfaction of every customer while offering knowledge and friendly service at affordable rates. We hope that you’ll feel confident in our ability to exceed all of your expectations and know that our customers are always our number one focus.</p>
						<a class="btn btn-primary text-center" style="display:block;" href="tel:+1847-838-0406" title="Click Here To Call Now ">Call Now! 1-847-838-0406</a>
					</div>
			</div>




	</div>
</section>
<Divider>
	<h2>Specials</h2>
</Divider>
<section class="coupon-section">
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
</section>
<Divider>
	<h2>Sewer &amp; Drain Services</h2>
</Divider>
<ServicesGrid/>
