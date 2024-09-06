<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shreesh Chary</title>
    <style>
        body {
            font-family: Times, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 20px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .tab-content {
            padding: 20px;
            display: none;
        }
        #home {
            display: block;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
        }
    </style>
    <script>
        function showTab(tabId) {
            // Hide all content
            var contents = document.getElementsByClassName('tab-content');
            for (var i = 0; i < contents.length; i++) {
                contents[i].style.display = 'none';
            }
            // Show the selected tab content
            document.getElementById(tabId).style.display = 'block';
        }
    </script>
</head>
<body>
    <header>
     <img src="https://raw.githubusercontent.com/ShreeshChary/ShreeshChary.github.io/main/20240906_095925.jpg" alt="Shreesh Chary" class="profile-img">
        <h1>Shreesh Chary</h1>
        <p>I am an aspiring economist with a strong interest in international trade, economic growth, and the role of R&D in shaping productivity. My skills include econometric modeling, data analysis, and visualization using Stata, R, and Eviews. Currently, my research focuses on the impact of international knowledge spillovers on productivity across OECD countries, exploring the effects of human capital, economic size, and import intensity. I’m passionate about using data-driven research to understand complex economic dynamics and inform policy.</p>
        <p>
            <a href="https://raw.githubusercontent.com/<ShreeshChary>/<ShreeshChary.github.io>/CV.pdf" target="_blank">CV</a> |
            <a href="https://scholar.google.com/citations?user=zV1w51QAAAAJ&hl=en&oi=ao" target="_blank">Google Scholar</a> |
            <a href="https://www.linkedin.com/in/shreesh-chary-2765391b3/" target="_blank">LinkedIn</a>
        </p>
    </header>

    <nav>
        <a href="#" onclick="showTab('publications')">Publications</a>
        <a href="#" onclick="showTab('working-papers')">Working Papers</a>
        <a href="#" onclick="showTab('contact')">Contact</a>
    </nav>

<div id="publications" class="tab-content">
    <h2>Publications</h2>
    <ul>
        <li><a href="https://www.tandfonline.com/doi/full/10.1080/23311886.2024.2350837" target="_blank">On the role of military spending: an economic thought perspective</a> with Niharika Singh, June 2024</li>
        <li><a href="https://link.springer.com/article/10.1007/s11948-024-00475-3" target="_blank">Employee Grievance Redressal and Corporate Ethics: Lessons from the Boeing 737-MAX Crashes</a>, May 2024</li>
        <li><a href="https://doi.org/10.1080/14799855.2024.2326412" target="_blank">Political Regimes and Self-Reliance in the Indian Arms Industry</a> with Krishna Kanta Roy, April 2024</li>
        <li><a href="https://doi.org/10.1108/JES-05-2023-0265" target="_blank">The Nexus Between Arms Imports, Military Expenditures and Economic Growth of the Top Arms Importers in the World: a Pooled Mean Group Approach</a>, August 2023</li>
    </ul>
</div>

<div id="working-papers" class="tab-content">
    <h2>Working Papers & Unpublished Work</h2>
    <ul>
        <li><a href="https://www.researchgate.net/publication/383619716_Heterogeneity_and_Non-Linearities_in_International_RD_Spillovers_Evidence_Using_Novel_Panel_Estimators" target="_blank">Heterogeneity and Non-Linearities in International R&D Spillovers: Evidence from OECD Countries</a>, September 2024</li>
        <li><a href="https://www.researchsquare.com/article/rs-3789990/v1" target="_blank">An Empirical Investigation of Wagner's Law for Twelve Indian States: A Pooled Mean Group Approach Using Linear and Non-Linear Specifications</a>, with Prakash Choudhary and Namah Singh, December 2023</li>
    </ul>
</div>


    <div id="contact" class="tab-content">
        <h2>Contact Information</h2>
        <p>Email: shreesh.chary@gmail.com</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/shreesh-chary-2765391b3/" target="_blank">Shreesh Chary</a></p>
    </div>
</body>
</html>

