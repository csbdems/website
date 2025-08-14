<script lang="ts">
	import HeadshotCard from '$lib/components/HeadshotCard.svelte';
</script>

<!-- Opening tagline -->
<div class="row">
	<div class="col-xs-12 text-center">
		<div id="opening-tagline">
			<h1>The Endorsed 2025 Cheltenham Democratic School Board Candidates</h1>
		</div>
	</div>
</div>

<!-- Headshots -->
<div class="row" id="headshots">
	<div class="col-xs-6 col-sm-6 col-lg-2 col-lg-offset-2 text-center">
		<HeadshotCard
			href="/candidates#zachary"
			imgSrc="/img/candidates/zachary.jpg"
			name="Zachary J. Epps"
		/>
	</div>
	<div class="col-xs-6 col-sm-6 col-lg-2 text-center">
		<HeadshotCard href="/candidates#leah" imgSrc="/img/candidates/leah.jpg" name="Leah Mulhearn" />
	</div>
	<div class="col-xs-6 col-sm-6 col-lg-2 text-center">
		<HeadshotCard
			href="/candidates#caroline"
			imgSrc="/img/candidates/caroline.jpg"
			name="Caroline Watts"
		/>
	</div>
	<div class="col-xs-6 col-sm-6 col-lg-2 text-center">
		<HeadshotCard
			href="/candidates#dan"
			imgSrc="/img/candidates/daniel.jpg"
			name="Daniel Schultz"
		/>
	</div>
</div>

<!-- Next section link -->
<div class="row text-center">
	<div class="col-xs-12">
		<div class="next-section">
			<a href="#learnMore">
				<span class="next-section-text">Learn More about us</span>
				<div><i class="fas fa-chevron-down"></i></div>
			</a>
		</div>
	</div>
</div>

<a name="learnMore"></a>
<div class="row" id="front-page-message">
	<div class="section">
		<div class="col-xs-12">
			<h2>Collaboration - Transformation - Inclusion</h2>
			<p>
				Cheltenham schools thrive because of ongoing community <em>collaboration</em>. School
				Directors help establish a shared vision of the <em>transformation</em> happening within our
				schools. A shared vision keeps the focus on <em>inclusion</em>, ensuring that all voices are
				heard and all students are equipped to succeed.
			</p>
			<a href="/values">
				<div id="our-values-link">
					<span class="link-text">Our Values</span> <i class="fas fa-chevron-right"></i>
				</div>
			</a>
		</div>
	</div>
</div>

<div class="row" id="front-page-who-we-are">
	<div class="section">
		<div class="col-xs-12 col-lg-4">
			<h2>Who we are</h2>
			<p>We are parents, volunteers, residents, and believers in public education.</p>
			<p>Learn more about who we are and why we are running.</p>
		</div>
		<div class="col-xs-12 col-lg-8">
			<div class="group-photo">
				<img
					src="/img/candidates/full.jpg"
					alt="A group picture of the Democratic Candidates for Cheltenham School Board"
				/>
			</div>
		</div>
		<a href="/candidates">
			<div id="meet-the-candidates-link">
				<span class="link-text">Meet the candidates</span>
				<i class="fas fa-chevron-right"></i>
			</div>
		</a>
	</div>
</div>
