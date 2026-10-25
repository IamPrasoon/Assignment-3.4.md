Before (Div-Based HTML):


<div><h1>My Portfolio</h1></div>
<div><a href="#about">About</a></div>
<div><h2>About Me</h2><p>I am a student.</p></div>
<div>Copyright 2026</div>

After (Semantic HTML) — index.html


<!DOCTYPE html>
<html lang="en">
<head>
    <title>My Portfolio</title>
</head>
<body>
    <header>
        <h1>Prasoon Anand</h1>
        <nav><a href="#about">About</a></nav>
    </header>

    <main>
        <section id="about">
            <h2>About Me</h2>
            <article>
                <h3>Introduction</h3>
                <p>I am a B.Tech CSE student.</p>
                <img src="profile.jpg"
                     alt="Portrait of Prasoon Anand"
                     width="150">
            </article>
        </section>
        <aside>
            <h2>Skills</h2>
            <p>HTML, CSS, JavaScript</p>
        </aside>
    </main>

    <footer>
        <p>Copyright 2026 Prasoon Anand</p>
    </footer>
</body>
</html>

Submission: Submit index.html and two screenshots showing the webpage before and after the changes.