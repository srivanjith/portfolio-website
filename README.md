<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sri Vanjith | Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, sans-serif;
}

body{
    line-height:1.6;
    background:#f9f9f9;
}


header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 10%;
    background:#222;
}

.logo{
    color:white;
    font-size:22px;
}

nav a{
    color:white;
    text-decoration:none;
    margin-left:20px;
}

nav a:hover{
    color:#00bcd4;
}

/* Hero */
.hero{
    text-align:center;
    padding:60px 10%;
    background:white;
}

.hero img{
    width:150px;
    border-radius:50%;
    margin-bottom:15px;
}

.hero span{
    color:#00bcd4;
}

.hero button{
    margin-top:20px;
    padding:10px 20px;
    border:none;
    background:#00bcd4;
    color:white;
    cursor:pointer;
}

/* Sections */
section{
    padding:50px 10%;
    text-align:center;
}

.gray{
    background:#f0f0f0;
}

/* Skills */
.skills{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:15px;
}

.skills span{
    background:#00bcd4;
    color:white;
    padding:10px 18px;
    border-radius:20px;
}

/* Projects */
.projects{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}

.card{
    background:white;
    padding:20px;
    width:260px;
    box-shadow:0 0 10px rgba(0,0,0,0.1);
}

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:15px;
}

@media(max-width:768px){
    header{
        flex-direction:column;
    }

    nav{
        margin-top:10px;
    }

    .projects{
        flex-direction:column;
        align-items:center;
    }
}
</style>
</head>

<body>

<header>
    <h1 class="logo">SRI !</h1>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section id="home" class="hero">
    <img src="https://via.placeholder.com/150" alt="Profile">
    <h2>Hi, I'm <span>Sri Vanjith</span></h2>
    <p>Software Developer | Frontend Learner</p>
    <button>Brief CV</button>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        Engineering undergraduate with strong technical knowledge and practical
        exposure through projects and labs.
    </p>
</section>

<section id="skills" class="gray">
    <h2>Skills</h2><br>
    <div class="skills">
        <span>HTML</span>
        <span>CSS</span>
        <span>JavaScript</span>
        <span>C</span>
        <span>Java</span>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2><br>
    <div class="projects">
        <div class="card">
            <h3>Music Player</h3>
            <p>HTML, CSS & JavaScript based music player.</p>
        </div>
        <div class="card">
            <h3>Portfolio Website</h3>
            <p>Responsive personal portfolio website.</p>
        </div>
    </div>
</section>

<section id="contact" class="gray">
    <h2>Contact</h2>
    <p>Email: srivanjiththangaraj48@gmail.com</p>
    <p>Phone: +91 9626669747</p>
</section>

<footer>
    <p>© 2025 Sri Vanjith</p>
</footer>

</body>
</html>
