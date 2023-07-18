<script>
    import Project from "../../components/Project.svelte";
</script>

<style>
    div {
        font-family: 'Courier New', Courier, monospace;

        width: 100%;
        max-width: 960px;
        object-fit: fill;
        align-self: flex-start;
        margin-left: auto;
        margin-right: auto;
        display: block;
        position: relative;


    }

    h1 {
        margin-bottom: 0;

        font-size: 50px;
    }

    p {
        max-width: 740px;

        font-size: 20px;
    }

    a, a:visited {
		text-decoration: none;
		color: red;
	}

</style>


<div>
  <h1>projects</h1>
  <p>unordered list with project title, description, and a picture</p>

    <ul>
        <li>
            <Project title="test" description="test" image="test"/>
        </li>
    </ul>  
</div>




