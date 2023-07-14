<style>
	#header {
		font-family: 'Courier New', Courier, monospace;
		font-size: 18px;
		font-weight: bold;

		margin-right: 15px;
		margin-top: 30px;

		display: flex;
		justify-content: flex-end;
		gap: 20px;
	}

	#footer {
		font-family: 'Courier New', Courier, monospace;
		font-size: 18px;
		font-weight: bold;

		position: fixed;
  		left: 0;
  		bottom: 0;
  		width: 100%;
  		text-align: center;
		margin-bottom: 15px;

		display: flex;
		justify-content: center;
		gap: 20px;
	}

	a, a:visited {
		text-decoration: none;
		color: black;

	}

</style>

<nav id="header">
	<a href="/">home</a>
	<a href="/about">about</a>
	<a href="/projects">projects</a>
</nav>

<slot />

<nav id="footer">
	<a href="https://www.linkedin.com/in/cooperbocko">linkedin</a>
	<a href="https://github.com/cooperbocko">github</a>
	<a href="mailto:cooperbocko@gmail.com">email</a>
</nav>
