<script>
</script>

<div class="me" />
<div class="social">
	<a href="https://github.com/y330"><i id="github" class="icon-github" /></a>
	<a href="https://linkedin.com/in/y330"><i id="linkedin" class="icon-linkedin-sign" /></a>
	<a href="https://github.com/y330/sveltekit-cms---yonahs-blog" title="Go to this site's source code"
		><i id="code" class="icon-code" /></a
	>
</div>

<style>
	.me {
		display: block;
		margin: 2em auto;
		margin-bottom: 3em;
		width: 150px;
		height: 150px;
		border-radius: 50%;
		position: relative;
		z-index: 2;
	}

	.social {
		text-align: center;
		font-size: 2.5em;
		color: #555;
		display: flex;
	}
	.social a {
		color: inherit;
		text-decoration: none;
	}
	.social i {
		margin: 0.3em;
		cursor: pointer;
		transition: color 300ms ease, margin-top 300ms ease;
		transform: translateZ(0);
	}
	.social i:hover {
		margin-top: -1px;
	}

	.social i#github:hover {
		color: black;
	}
	.social i#linkedin:hover {
		color: #0177b5;
	}
	.social i#code:hover {
		color: #29a329;
	}
</style>
