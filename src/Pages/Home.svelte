<script>
	import CharityList from '../Components/CharityList.svelte' ;
	import Header from '../Components/Header.svelte';
	import Wellcome from '../Components/Wellcome.svelte';
	import Promo from '../Components/Promo.svelte';
	import Footer from '../Components/Footer.svelte';

    import { charities } from '../Data/charities.js';

	let title = "Charity";

	
</script>


<Header/>
<Wellcome/>
<CharityList {charities} />
<Promo/>
<Footer/>
