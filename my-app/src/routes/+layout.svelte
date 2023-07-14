<style>
	nav {
		font-family: 'Courier New', Courier, monospace;

		margin-right: 10px;

		display: flex;
		justify-content: flex-end;
		gap: 15px;
	}

	a, a:visited {
		text-decoration: none;
		color: red;
	}

</style>

<nav>
	<a href="/">home</a>
	<a href="/about">about</a>
	<a href="/projects">projects</a>
	<a href="/contact">contact</a>
</nav>

<slot />
