# landpage
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Portfolio Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="hero-section">
        <div class="hero-content">
            <h1>Welcome to My Student Portfolio</h1>
            <p>Discover my projects, skills, and experiences.</p>
            <a href="#" class="btn-primary">Explore Now</a>
        </div>
        <img src="images/hero_image.jpg" alt="Hero Image" class="hero-image">
    </header>
    <main>
        <section class="features">
            <h2>Features</h2>
            <div class="feature">
                <img src="images/feature1.jpg" alt="Projects">
                <h3>Projects</h3>
                <p>Explore a collection of my academic and personal projects.</p>
            </div>
            <div class="feature">
                <img src="images/feature2.jpg" alt="Skills">
                <h3>Skills</h3>
                <p>Discover the skills I've acquired throughout my learning journey.</p>
            </div>
            <div class="feature">
                <img src="images/feature3.jpg" alt="Achievements">
                <h3>Achievements</h3>
                <p>See the milestones and achievements I've accomplished.</p>
            </div>
        </section>
        <section class="testimonials">
            <h2>Student Testimonials</h2>
            <div class="testimonial">
                <img src="images/student1.jpg" alt="Student 1">
                <p>"This portfolio is a great way to showcase my work and skills. It's easy to use and looks amazing!"</p>
                <h4>- Student 1</h4>
            </div>
            <div class="testimonial">
                <img src="images/student2.jpg" alt="Student 2">
                <p>"I love how I can display my projects and achievements in one place. It's a fantastic tool for students."</p>
                <h4>- Student 2</h4>
            </div>
            <div class="testimonial">
                <img src="images/student3.jpg" alt="Student 3">
                <p>"The design is clean and professional, and it really helps me stand out to potential employers."</p>
                <h4>- Student 3</h4>
            </div>
        </section>
        <section class="cta">
            <h2>Ready to showcase your work?</h2>
            <p>Create your own student portfolio today and start sharing your achievements with the world!</p>
            <a href="#" class="btn-primary">Get Started</a>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Student Portfolio</p>
    </footer>
</body>
</html>

#css
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

.hero-section {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #4CAF50;
    color: white;
    padding: 2em;
}

.hero-content {
    max-width: 50%;
}

.hero-content h1 {
    font-size: 2.5em;
    margin: 0;
}

.hero-content p {
    font-size: 1.2em;
    margin: 1em 0;
}

.hero-image {
    max-width: 40%;
    border-radius: 10px;
}

.btn-primary {
    background-color: #ff5722;
    color: white;
    padding: 0.7em 1.5em;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

.features {
    text-align: center;
    padding: 3em 1em;
    background-color: #fff;
}

.features h2 {
    font-size: 2em;
    margin-bottom: 1em;
}

.feature {
    display: inline-block;
    margin: 1em;
    width: 30%;
    vertical-align: top;
}

.feature img {
    width: 100%;
    height: auto;
    border-radius: 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin: 0.5em 0;
}

.feature p {
    font-size: 1em;
}

.testimonials {
    text-align: center;
    padding: 3em 1em;
    background-color: #f4f4f4;
}

.testimonials h2 {
    font-size: 2em;
    margin-bottom: 1em;
}

.testimonial {
    display: inline-block;
    width: 30%;
    margin: 1em;
    vertical-align: top;
}

.testimonial img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    margin-bottom: 1em;
}

.testimonial p {
    font-size: 1em;
    font-style: italic;
}

.testimonial h4 {
    font-size: 1.2em;
    margin-top: 0.5em;
    font-weight: bold;
}

.cta {
    text-align: center;
    padding: 3em 1em;
    background-color: #4CAF50;
    color: white;
}

.cta h2 {
    font-size: 2em;
    margin-bottom: 1em;
}

.cta p {
    font-size: 1.2em;
    margin-bottom: 1.5em;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 1em 0;
}
