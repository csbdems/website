<script lang="ts">
	export let href: string;
	export let imgSrc: string;
	export let name: string;
</script>

<a {href}>
	<div class="headshot"><img src={imgSrc} alt={name} /></div>
	<div class="name">{name}</div>
</a>
