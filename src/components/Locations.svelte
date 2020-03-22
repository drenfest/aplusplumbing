<script>
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



    function compare(a, b) {
        // Use toUpperCase() to ignore character casing
        const bandA = a.city.toUpperCase();
        const bandB = b.city.toUpperCase();

        let comparison = 0;
        if (bandA > bandB) {
            comparison = 1;
        } else if (bandA < bandB) {
            comparison = -1;
        }
        return comparison;
    }
    locations.sort(compare);
</script>
<style>
    h2 {
        padding:1rem;
    }
    .location-container{
        width:100%;
    }
    .locations{
        padding:4rem;
    }
    .location-list{
        overflow-y:scroll;
        list-style:none;
        max-height:600px;
    }
    .location-list > li{
        padding:.5rem 2rem;
        text-align:center;
        margin:2rem 0;
    }
</style>
<section class="locations">
    <div class="location-container">
<!--                <h2>Sewer &amp; Drain Repair</h2>-->
<!--                <ul class="location-list">-->

<!--                    {#each locations as location}-->
<!--                            <li><a href="sewer-drain-repair-{location.city.replace(' ','-').toLowerCase()}-{location.state.toLowerCase()}" title="Sewer & Drain Repair In {location.city} {location.state}">{location.city}, {location.state}</a></li>-->
<!--                    {/each}-->
<!--                </ul>-->
                <h2>Hydro Jetting</h2>
                <ul class="location-list">
                    {#each locations as location}
                            <li><a href="hydro-jetting-{location.city.replace(' ','-').toLowerCase()}-{location.state.toLowerCase()}" title="Sewer & Drain Repair In {location.city} {location.state}">{location.city}, {location.state}</a></li>
                    {/each}
                </ul>
    </div>
</section>
