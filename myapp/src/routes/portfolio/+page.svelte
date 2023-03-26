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
                    Monkey Dating Website
                </a>
                    <h3>A website built using svelte for acmCSUF's Mini-hackathon</h3>
                
            </li>

            <li>
                <a target="_blank" href="https://github.com/danejcamacho/breast-cancer-AI-models">
                    Breast Cancer Machine Learning Models
                </a>
                    <h3>An assortment of different ML models as applied to a dataset of breast cancer cells to predict whether a cell is malignant or benign</h3>
                
            </li>
            <li>
                <a target="_blank" href="https://github.com/hellokev/Sandwich-Project">
                    Random Sandwich Generator
                </a>
                    <h3>A Website built with Sveltekit that generates a random pixel art sandwich</h3>
                
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
    a {

        font-style:italic;
        font-size: 30px;
        box-shadow: inset 0 0 0 0 #54b3d6;
        color: #3db1db;
        margin: 0px;
        padding: 10px;
        transition: color .3s ease-in-out, box-shadow .3s ease-in-out;
        
        text-decoration: none;

    }
    a:hover {
        box-shadow: inset 1000px 0 0 0 #2ec0f5;
        color: white;
    }
</style>