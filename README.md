* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
}

.container {
    width: 80%;
    margin: auto;
    padding: 2rem 0;
}

h1 span {
    color: #333;
}

.section {
    padding: 4rem 0;
    text-align: center;
}

.skills-grid, .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
    gap: 20px;
}

.skill i, .project i {
    font-size: 3rem;
    color: #333;
}

.skill p, .project h3 {
    font-size: 1.2rem;
    color: #333;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

footer .socials li {
    display: inline;
    margin-right: 10px;
}

footer .socials li a {
    color: #fff;
    font-size: 1.5rem;
}
