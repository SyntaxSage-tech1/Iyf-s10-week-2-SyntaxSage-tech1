<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">    
    <tittle>My Portifolio</tittle>
    <link rel="stylesheet" href="style.css"> 
  
</head>

<body>
    <!--NAVIGATION BAR-->
    <nav>
        <div>
            <h1>MR.BONI</h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <!--HERO/IMAGE* BIO SECTION-->
    <section id="about">
        <div>
            <img
                class="fit picture"
                src="IMG-20260210-WA0004.jpg"
                alt="Profile Photo of Boni"
                >
        </div>
        <!--Bio-->
        <div>
            <h2>Boni's Bio</h2>
            <p>Junior Web🌎 Developer</p>
            <p>Hi, I'm Boni! I'm a passionate web developer with a love for creating beautiful and functional websites.<br> With over 5 years of experience in the industry, I have a strong background in HTML, CSS, JavaScript, and various web development frameworks.<br> I enjoy working on both front-end and back-end projects, and I'm always eager to learn new technologies and improve my skills.
            </p>
        </div>
    </section>
    <!--SKILLS SECTION-->
    <section id="skills">
        <div>
            <h2>Skills</h2>
            <!--Skills Grid-->
            <div>
                <!--Skill 1-->
                <div>
                    <div>🌐</div>
                    <h3>Web Development</h3>
                    <p>Proficient in HTML, CSS, JavaScript, and various web development frameworks.</p>
                </div>
                <!--Skill 2-->
                <div>
                    <div>🎨</div>
                    <h3>css</h3>
                    <p>Skilled in creating responsive and visually appealing layouts using CSS.</p>
                </div>
                <!--Skill 3-->
                <div>
                    <div>⚡</div>
                    <h3>JavaScript</h3>
                    <p>Experienced in building interactive and dynamic web applications using JavaScript.</p>
                </div>
                <!--Skill 4-->
                <div>
                    <div>💻</div>
                    <h3>Frameworks</h3>
                    <p>Familiar with popular web development frameworks such as React, Angular, and Vue.js.</p>
                </div>
            </div>
        </div>
    </section>    
    <!--CONTACT SECTION-->
    <section id="contact">
        <h2>Contact Me</h2>
        <form>
            <!--Name field-->
            <div>
                <label>Name:</label>
                <input
                    type="text"
                    placeholder="Enter your name"
                >
            </div>
            <!--Email field-->
            <div>
                <label>Email:</label>
                <input
                    type="email"
                    placeholder="Enter your email"
                >
            </div>
            <!--Message field-->
            <div>
                <label>Message:</label>
                <textarea
                    rows="4"
                    placeholder="Enter your message"
                ></textarea>
            </div>
            <!--submit Button-->
            <button
                type="submit"
            >
                Send Message
            </button>
        </form>
    </section>  
    <!--FOOTER-->
    <footer>
        <p>&copy; 2026 Boni.Built with ❤️for 💻programing.</p>
    </footer>

</body>
</html>
