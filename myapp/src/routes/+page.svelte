<script>
    import Header from './Header.svelte';
</script>

<Header/>
<main>
    
    
    <h1 class = animate_text> Hi! My name is Dane... </h1>


    
    <ul class = "card">
        <li class= "card">
            <h1>Links</h1>
            <a target=_blank href="https://github.com/danejcamacho" >Click Here for my Github</a> <br> <br>
            <a target=_blank href="https://github.com/danejcamacho" >Click Here for my LinkedIn</a> <br> <br>
            
        </li>
        <li class = "card">
            <h1>Education</h1>
            <h2><i>California State University, Fullerton</i></h2>
            <h2><i>GPA: 3.64</i></h2>
            <ul>
                <li><h3>Selected for University Honors Program</h3></li>
                <li><h3>Selected for Dean's List</h3></li>
            </ul>
            <h2>Relevant Coursework</h2>
            <p>C++ Object Oriented Programming and Data Structures, Discrete Mathematics, Linear Algebra, Calculus I & II,  x86_64 Assembly, Python Programming</p>
        </li>
        
    </ul>

</main>

<style>
    main .card{
        
        max-width: 1000px;
        margin: 0 auto;
        font-family: Arial, Helvetica, sans-serif;
        color: #000000
        
    }   
    main{
        max-width: 1000px;
        margin: 0 auto;
        font-family: Arial, Helvetica, sans-serif;
        color: #000000
    }
    ul .card{
        list-style-type:none;
        flex-direction: column;
        align-items: center;
        margin: 10px;
        padding: 30px;
        background-color: #fff;
        border-radius: 10px;
        box-shadow: 0 3px 10px rgba(0, 0, 0, 0.1);
    }

    li {
        list-style-type:disc;
    }
    
    p {
        font-size: 20px;
        
    }
    a {

        font-style:italic;
        font-size: 30px;
        box-shadow: inset 0 0 0 0 #54b3d6;
        color: #3db1db;
        margin: 30px;
        padding: 20px;
        transition: color .3s ease-in-out, box-shadow .3s ease-in-out;
        
        text-decoration: none;

}
    a:hover {
        box-shadow: inset 1000px 0 0 0 #2ec0f5;
        color: white;
    }

    .animate_text {
    text-transform: uppercase;
    background-image: linear-gradient(
        -225deg,
        #231557 0%,
        #44107a 29%,
        #ff1361 67%,
        #fff800 100%
    );
    background-size: auto auto;
    background-clip: border-box;
    background-size: 200% auto;
    color: #fff;
    background-clip: text;
    text-fill-color: transparent;
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    animation: textclip 2s linear infinite;
    display: inline-block;
        font-size: 190px;
    }

    @keyframes textclip {
    to {
        background-position: 200% center;
    }
    }

</style>
