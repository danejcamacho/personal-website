<script>
	import Header from '../Header.svelte';
</script>

<main>
    <Header/>

    <body>
        <h1> Portfolio </h1>
        <ul>
            <li>
                <a target="_blank" href="https://github.com/danejcamacho/monkey-dating">
                    <h2>Monkey Dating Website</h2>
                    <h3>A website built using svelte for acmCSUF's Mini-hackathon</h3>
                </a>
            </li>

            <li>
                <h2>Monkey Dating Website</h2>
            </li>
        </ul>
    </body>
    


</main>




<style>

    main {
        max-width: 1000px;
        margin: 0 auto;
        font-family: Arial, Helvetica, sans-serif;
        color: #000000
    } 

    li {
        list-style-type: none;
    }

    a:link { text-decoration: none; }
    a:visited { 
        text-decoration: none;
        color: #000000
     }
    a:hover { text-decoration: none; }
    a:active { text-decoration: none; }
</style>