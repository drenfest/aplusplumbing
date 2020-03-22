<script context="module">
	export async function preload({params, query}){
		// return this.fetch(`/nn-filler.html/`)
		// 		.then((r) => {
		// 			r.text().then((nnText) =>{
		// 				return content = nnText;
		// 			});
		// 		})
		let cs = await params.city.split("-");
		let state = await cs[cs.length - 1].toUpperCase();
		let city = await params.city.replace("-"+state.toLowerCase(),'').replace('-',' ').replace(params.city.substr(0,1),params.city.substr(0,1).toUpperCase());
		return {nnCity:city,nnState:state};
	}
</script>
<script>
	export let nnCity;
	export let nnState;
	export let locations = [
		{city:"Algonquin", state:"IL"},
		{city:"Antioch", state:"IL"},
		{city:"Barrington", state:"IL"},
		{city:"Buffalo Grove", state:"IL"},
		{city:"Cary", state:"IL"},
		{city:"Crystal Lake", state:"IL"},
		{city:"Deerfield", state:"IL"},
		{city:"Fort Sheridan", state:"IL"},
		{city:"Fox Lake", state:"IL"},
		{city:"Fox River Grove", state:"IL"},
		{city:"Grayslake", state:"IL"},
		{city:"Great Lakes", state:"IL"},
		{city:"Gurnee", state:"IL"},
		{city:"Harvard", state:"IL"},
		{city:"Hebron", state:"IL"},
		{city:"Highland Park", state:"IL"},
		{city:"Highwood", state:"IL"},
		{city:"Huntley", state:"IL"},
		{city:"Ingleside", state:"IL"},
		{city:"Island Lake", state:"IL"},
		{city:"Lake Bluff", state:"IL"},
		{city:"Lake Forest", state:"IL"},
		{city:"Lake In The Hills", state:"IL"},
		{city:"Lake Villa", state:"IL"},
		{city:"Lake Zurich", state:"IL"},
		{city:"Libertyville", state:"IL"},
		{city:"Lincolnshire", state:"IL"},
		{city:"Marengo", state:"IL"},
		{city:"Mchenry", state:"IL"},
		{city:"Mundelein", state:"IL"},
		{city:"North Chicago", state:"IL"},
		{city:"Richmond", state:"IL"},
		{city:"Ringwood", state:"IL"},
		{city:"Round Lake", state:"IL"},
		{city:"Russell", state:"IL"},
		{city:"Spring Grove", state:"IL"},
		{city:"Union", state:"IL"},
		{city:"Vernon Hills", state:"IL"},
		{city:"Wadsworth", state:"IL"},
		{city:"Wauconda", state:"IL"},
		{city:"Waukegan", state:"IL"},
		{city:"Winthrop Harbor", state:"IL"},
		{city:"Wonder Lake", state:"IL"},
		{city:"Woodstock", state:"IL"},
		{city:"Zion", state:"IL"},
	];
</script>
<style>
</style>
<svelte:head>
	<title> Hydro Jetting {nnCity}, {nnState} | A+ Rooter Plumbing 847-838-0406</title>
	<meta name="description" content="We are a family owned and operated business licensed, bonded and insured since 1989 specializing in hydro jetting {nnCity}, {nnState}. 847-838-0406">
</svelte:head>
<h2>Hydro Jetting Service near {nnCity}, {nnState}</h2>
<p>A+ Rooter is a full-service Hydro Jetting business. We serve residents throughout the Northern Chicagoland area. We are a family owned and operated business that has been licensed, bonded and insured since 1989. Our highly trained plumbers have the knowledge and experience necessary to handle anything from a small toilet repair or clogged drain cleaning service, to a large plumbing and Hydro Jetting or repair emergencies.</p>
<p>Hydro Jetting or repair problems crop up at the most inconvenient of times, so it makes sense to deal with a Plumber and Hydro Jetting or repair company you can rely on and who will actually answer the phone when you need them the most. We are a family of plumbers with a passion for the industry. We can have your sewer back up and running again in no time. Our licensed and insured {nnCity}, {nnState} plumber and sewer cleaners are available anytime you need us, day or night, 24-hours a day. We will also schedule appointments based on your schedule-for the most convenient, timely service possible.</p>
<p>From sewer repair and installation to drain rodding of all kinds for your home or business, we are fully equipped to solve any of your draining problems, big or small, at a price you can afford with the least amount of inconvenience to you.</p>
<ul>
	<li>Sewer Repairs And Clean-Out Installations</li>
	<li>Emergency Issues 24/7</li>
	<li>Repairs On All Makes & Models</li>
	<li>Maintenance</li>
</ul>
<p>Our Hydro Jetting services not only serve the {nnCity}, {nnState} area but also all of Lake County, North Shore and McHenry County. Please call any of the numbers at the top of this page or <a href="/contact" title="Go to contact page">click here</a> to contact us by filling out a form.</p>
<h3>Residential And Commercial Hydro Jetting Services {nnCity}, {nnState} </h3>
<div class="row">
	<div class="col-xs-12 col-sm-6">
		<ul>
			<li>Sinks</li>
			<li>Faucets</li>
			<li>Toilets</li>
			<li>Sump Pumps</li>
			<li>Battery Backup Systems</li>
			<li>Ejector Pumps</li>
			<li>Sewer Line Repair and Clean Out Installation</li>
			<li>Drain Cleaning and Power Rodding</li>
		</ul>
	</div>
	<div class="col-xs-12 col-sm-6">
		<ul>
			<li>Hydro Jetting</li>
			<li>Video Televising and Inspection</li>
			<li>Leak Repairs</li>
			<li>Frozen and Burst Pipe Repair</li>
			<li>Water Heater Installation, Repair and Service</li>
			<li>Garbage Disposals</li>
			<li>Water Line Repair and Installation</li>
			<li>Basement Drainage and Seepage</li>
		</ul>
	</div>
</div>

