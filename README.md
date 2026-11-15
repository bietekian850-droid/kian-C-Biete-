
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Personal Portfolio</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: #edf3ff;
    color: #24344f;
}

/* HEADER */
header {
    background: linear-gradient(120deg, #071c55, #1769dc);
    color: white;
    text-align: center;
    padding: 45px 15px;
}

header h1 {
    font-size: 27px;
    letter-spacing: 2px;
}

header p {
    margin-top: 12px;
    color: #dceaff;
}

/* NAVIGATION */
nav {
    background: white;
    padding: 14px 5px;
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 8px;
    position: sticky;
    top: 0;
    z-index: 10;
    box-shadow: 0 3px 10px #0001;
}

nav a {
    color: #1556c0;
    text-decoration: none;
    font-size: 12px;
    font-weight: bold;
    padding: 9px;
    border-radius: 20px;
}

nav a:hover {
    background: #1769dc;
    color: white;
}

/* SECTIONS */
section {
    background: white;
    max-width: 850px;
    margin: 25px auto;
    padding: 25px;
    border-radius: 15px;
    box-shadow: 0 5px 15px #193d7515;
}

section h2 {
    color: #1556c0;
    margin-bottom: 20px;
    padding-bottom: 10px;
    border-bottom: 3px solid #1769dc;
}

section h3 {
    color: #16478e;
    margin: 15px 0 8px;
}

section p {
    line-height: 1.7;
    margin: 9px 0;
    font-size: 14px;
}

/* HOME */
#home {
    text-align: center;
    padding: 35px 20px;
}

.profile-placeholder {
    width: 140px;
    height: 140px;
    border-radius: 50%;
    background: linear-gradient(120deg, #1769dc, #071c55);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 45px;
    font-weight: bold;
    margin: 0 auto 20px;
    border: 5px solid #dceaff;
}

.welcome {
    color: #1769dc;
    font-weight: bold;
    margin: 12px;
}

/* CARDS */
.info-card {
    background: #edf4ff;
    padding: 15px;
    margin: 12px 0;
    border-radius: 9px;
    border-left: 4px solid #1769dc;
    font-size: 14px;
}

.info-card strong {
    color: #16478e;
}

/* SKILLS */
.skill {
    background: #edf4ff;
    padding: 13px;
    margin: 9px 0;
    border-radius: 8px;
    font-size: 14px;
}

/* JAVA */
.game-box {
    background: #edf4ff;
    padding: 18px;
    border-radius: 10px;
}

.code {
    background: #101b32;
    color: #a8e6ff;
    padding: 18px;
    border-radius: 10px;
    overflow-x: auto;
    font-size: 12px;
    line-height: 1.6;
    white-space: pre;
    margin-top: 15px;
}

/* FOOTER */
footer {
    background: #071c55;
    color: white;
    text-align: center;
    padding: 28px 15px;
    line-height: 2;
    font-size: 13px;
}

/* MOBILE */
@media(max-width:600px) {
    header h1 {
        font-size: 21px;
    }

    section {
        margin: 15px 12px;
        padding: 20px;
    }

    nav a {
        font-size: 11px;
        padding: 8px;
    }
}
</style>
</head>

<body>

<header>
    <h1>YOUR FULL NAME</h1>
    <p>BS Information Technology | Student Portfolio</p>
</header>

<nav>
    <a href="#home">HOME</a>
    <a href="#personal">PERSONAL INFO</a>
    <a href="#education">EDUCATION</a>
    <a href="#skills">SKILLS</a>
    <a href="#java">JAVA CODE</a>
</nav>

<!-- HOME -->
<section id="home">

    <div class="profile-placeholder">
        ME
    </div>

    <h2>HELLO! I'M YOUR NAME</h2>

    <div class="welcome">
        Welcome to My Personal Portfolio!
    </div>

    <p>
        I am an Information Technology student
        passionate about computers, programming,
        and modern technology.

        My goal is to develop my programming
        skills and become a successful IT professional.
    </p>

</section>

<!-- PERSONAL INFORMATION -->
<section id="personal">

    <h2>Personal Information</h2>

    <div class="info-card">
        <strong>Full Name:</strong> YOUR FULL NAME
    </div>

    <div class="info-card">
        <strong>Course:</strong> BS Information Technology
    </div>

    <div class="info-card">
        <strong>Year Level:</strong> First Year
    </div>

    <div class="info-card">
        <strong>School:</strong> YOUR SCHOOL NAME
    </div>

    <div class="info-card">
        <strong>Email:</strong> YOUR EMAIL
    </div>

    <div class="info-card">
        <strong>Address:</strong> YOUR ADDRESS
    </div>

    <h3>About Me</h3>

    <p>
        I am a dedicated student who enjoys learning
        new things, exploring technology, and solving
        problems. I believe that education and
        continuous learning are important for success.
    </p>

</section>

<!-- EDUCATION -->
<section id="education">

    <h2>Educational Background</h2>

    <div class="info-card">
        <h3>College</h3>
        <p>School: YOUR COLLEGE</p>
        <p>Course: BS Information Technology</p>
        <p>Level: First Year College</p>
    </div>

    <div class="info-card">
        <h3>Senior High School</h3>
        <p>School: YOUR SENIOR HIGH SCHOOL</p>
        <p>Strand: YOUR STRAND</p>
    </div>

    <div class="info-card">
        <h3>Junior High School</h3>
        <p>School: YOUR JUNIOR HIGH SCHOOL</p>
    </div>

</section>

<!-- SKILLS -->
<section id="skills">

    <h2>My Skills</h2>

    <h3>Technical Skills</h3>

    <div class="skill">HTML – Basic Web Development</div>
    <div class="skill">CSS – Website Designing</div>
    <div class="skill">Java – Basic Programming</div>
    <div class="skill">Computer Troubleshooting</div>

    <h3>Personal Skills</h3>

    <div class="skill">Communication</div>
    <div class="skill">Teamwork</div>
    <div class="skill">Problem Solving</div>
    <div class="skill">Time Management</div>

</section>

<!-- JAVA PROJECT -->
<section id="java">

    <h2>My Java Programming Project</h2>

    <div class="game-box">

        <h3>Guess The Number Game</h3>

        <p>
            This is a simple Java console game.
            The player must guess a secret number
            between 1 and 100.
        </p>

        <p><strong>Programming Language:</strong> Java</p>

        <p><strong>Concepts Used:</strong>
        Scanner, Random, Variables, Loops,
        and If-Else Statements.</p>

    </div>

    <h3>Java Source Code</h3>

<pre class="code">import java.util.Scanner;
import java.util.Random;

public class GuessTheNumber {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);
        Random random = new Random();

        int secret = random.nextInt(100) + 1;
        int guess = 0;
        int attempts = 0;

        System.out.println("GUESS THE NUMBER");

        while (guess != secret) {

            System.out.print("Enter your guess: ");
            guess = input.nextInt();
            attempts++;

            if (guess < secret) {
                System.out.println("Too Low!");
            }
            else if (guess > secret) {
                System.out.println("Too High!");
            }
            else {
                System.out.println("You Win!");
                System.out.println("Attempts: " + attempts);
            }
        }

        input.close();
    }
}</pre>

</section>

<footer>
    <p>YOUR FULL NAME</p>
    <p>BS INFORMATION TECHNOLOGY</p>
    <p>BUILD DREAMS. CODE FUTURES.</p>
    <p>© 2026 MY PERSONAL PORTFOLIO</p>
</footer>

<script>
console.log("Portfolio Website Loaded!");

document.querySelectorAll("nav a").forEach(link => {
    link.addEventListener("click", function() {
        console.log("Opening " + this.textContent);
    });
});
</script>

</body>
</html>

