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
		background-color: white;

		position: fixed;
  		left: 0;
  		bottom: 0;
  		width: 100%;
  		text-align: center;
		padding-bottom: 8px;
		padding-top: 8px;

		display: flex;
		justify-content: center;
		gap: 20px;
	}

	a, a:visited {
		text-decoration: none;
		color: black;

	}

	#content-wrap {
		padding-bottom: 36px;
	}

</style>

<nav id="header">
	<a href="/">home</a>
	<a href="/about">about</a>
	<a href="/projects">projects</a>
</nav>

<div id="content-wrap">
	<slot/>
</div>

<nav id="footer">
	<a href="https://www.linkedin.com/in/cooperbocko">linkedin</a>
	<a href="https://github.com/cooperbocko">github</a>
	<a href="mailto:cooperbocko@gmail.com">email</a>
</nav>
