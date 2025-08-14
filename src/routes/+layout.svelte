<script>
	import Nav from '$lib/components/Nav.svelte';
</script>

<svelte:head>
	<title>Cheltenham Democratic School Board Candidates</title>

	<!-- Social / SEO -->
	<meta property="og:title" content="Endorsed Cheltenham Democratic School Board Candidates" />
	<meta
		property="og:description"
		content="Learn about the endorsed Democratic candidates and their values."
	/>
	<meta property="og:image" content="http://csbdems.com/img/candidates/full.jpg" />
	<meta property="og:url" content="http://csbdems.com" />
	<meta name="twitter:title" content="Endorsed Cheltenham Democratic School Board Candidates" />
	<meta
		name="twitter:description"
		content="Learn about the endorsed Democratic candidates and their values."
	/>
	<meta name="twitter:image" content="http://csbdems.com/img/group_full.jpg" />
	<meta name="twitter:card" content="summary_large_image" />
</svelte:head>

<div class="container-fluid">
	<Nav />

	<slot />

	<!-- Footer -->
	<div class="row" id="footer">
		<div class="col-xs-12 text-center">
			<h3><a href="mailto:CSBDems@gmail.com">Contact Us</a></h3>
			<p>
				Visit us on <a
					href="https://www.facebook.com/cdsbc"
					target="_blank"
					rel="noopener noreferrer">Facebook</a
				>
			</p>
		</div>
	</div>
</div>
