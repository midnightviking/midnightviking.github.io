<script>
	import AboutMe from '$lib/components/AboutMe.svelte';
	import Header from '../lib/components/Header.svelte';
	import WorkHistory from '../lib/components/WorkHistory.svelte';
	import Skills from '$lib/components/Skills.svelte';
	import Contact from '$lib/components/Contact.svelte';
	import '$lib/scss/styles.scss';

	const consoleMessage = () =>{
		const wave = String.fromCodePoint(0x1F44B);
		console.clear();
		console.log(` _   _      _ _       \n| | | |    | | |      \n| |_| | ___| | | ___  \n|  _  |/ _ \\ | |/ _ \\ \n| | | |  __/ | | (_) |\n\\_| |_/\\___|_|_|\\___/ `);
		console.log(
			`%c${wave} Looking around? This site was written in svelte.\nIf you are looking for a web developer, check out my resume in the header and shoot me an email!`,
			"color:#222; background:#d96c47; font-size:20px; padding:10px;"
		);
	};
	consoleMessage();
</script>
<div class="main_style2">
	<Header />
	<div class="mainContent">		
		<section>
			<p>My career goals are to create, inspire, and to enjoy what I do. As a result I study a broad range of subjects related to web development and design. Developing for the web satisfies my need to be both creative and cerebral in my day to day life and moves at a wonderfully rapid pace to prevent boredom and stagnation.</p></section>
		<WorkHistory />
		<Skills />
		<AboutMe />
		<Contact />
	</div>
</div>