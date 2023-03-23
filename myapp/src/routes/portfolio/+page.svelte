<script>
	import Header from '../Header.svelte';
</script>

<main>
    <Header/>

    <body>
        <h1> Portfolio </h1>
        <h2 class = "subtitle"> //click the project to go to the Github Repository</h2>
        <ul>
            <li>
                <a target="_blank" href="https://github.com/danejcamacho/monkey-dating">
                    <h2>Monkey Dating Website</h2>
                    <h3>A website built using svelte for acmCSUF's Mini-hackathon</h3>
                </a>
            </li>

            <li>
                <a target="_blank" href="https://github.com/danejcamacho/breast-cancer-AI-models">
                    <h2>Breast Cancer Machine Learning Models</h2>
                    <h3>An assortment of different ML models as applied to a dataset of breast cancer cells to predict whether a cell is malignant or benign</h3>
                </a>
                </li>
        </ul>
    </body>
    


</main>




<style>
    

    main {
        max-width: 1000px;
        margin: 0 auto;
        font-family: Arial, Helvetica, sans-serif;
        color: #000000;
        
    } 
    ul {
        list-style-type: none;
    }

    li {
        flex-direction: column;
        align-items: center;
        margin: 10px;
        padding: 20px;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
    }

    .subtitle {
        color: rgb(51, 174, 51);
    }
    a:link { text-decoration: none; }
    a:visited { 
        text-decoration: none;
        color: #000000
     }
    a:hover { text-decoration: none; }
    a:active { text-decoration: none; }
</style>