<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Learn more about Eden Sky Silverwolf, a Digital & Integrated Marketing Communications major with a Media Arts & Sciences minor at ASU.">
  <meta name="author" content="Eden Sky Silverwolf">
  <title>About | Eden Silverwolf</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>Eden Silverwolf</h1>
      <p>Digital & Integrated Marketing Communications · Media Arts & Sciences · ASU</p>
    </div>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html" class="active">About</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="page-intro">
      <h2>About Eden</h2>
      <p>
        I’m a Digital & Integrated Marketing Communications major with a Media Arts & Sciences minor at 
        Arizona State University. My work sits at the intersection of marketing, design, and technology. 
        I love building experiences that feel modern and fun, but also clear and easy to use.
      </p>
    </section>

    <section class="about-layout">
      <div class="about-text">
        <h3>How I Think About Marketing</h3>
        <p>
          To me, marketing isn’t just about pushing content—it’s about understanding people. In my classes and projects, 
          I focus on how audiences actually behave online, what they care about, and how brands can communicate in a way 
          that feels honest and human.
        </p>
        <p>
          My Media Arts & Sciences coursework adds a layer of critical thinking about technology, culture, and the media we use every day. 
          That influences how I write copy, design visuals, and choose platforms for different campaigns.
        </p>
        <h3>What I’ve Worked On</h3>
        <p>
          Some projects that represent my interests and skills include:
        </p>
        <ul>
          <li>Designing and coding this portfolio website from scratch using HTML5 and CSS3.</li>
          <li>Creating a metaverse-style fitness & wellness concept that blends virtual spaces with health goals.</li>
          <li>Experimenting with interactive media using Circuit Playground Express and creative coding tools.</li>
          <li>Supporting real-world marketing efforts during my internship, including event promotion and social storytelling.</li>
        </ul>
      </div>
      <div class="about-image">
        <img src="images/eden-working.jpg" alt="Eden working on a digital marketing and media project at a laptop">
      </div>
    </section>

    <section class="about-video">
      <h3>Quick Intro Video</h3>
      <p>
        This short video introduces who I am, what I study, and the kind of work I’m interested in within digital marketing and media.
      </p>

      <video controls width="640">
        <source src="videos/eden-intro.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Eden Sky Silverwolf. All rights reserved.</p>
    <p>
      <a href="contact.html#contact-form">Email Me Through the Form</a> | 
      <a href="https://www.asu.edu" target="_blank" rel="noopener">Visit ASU</a>
    </p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Contact Eden Sky Silverwolf for digital marketing, social media, and media arts projects.">
  <meta name="author" content="Eden Sky Silverwolf">
  <title>Contact | Eden Silverwolf</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>Eden Silverwolf</h1>
      <p>Digital & Integrated Marketing Communications · Media Arts & Sciences · ASU</p>
    </div>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="contact.html" class="active">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="page-intro">
      <h2>Contact Me</h2>
      <p>
        Want to collaborate on a digital marketing project, social media campaign, or creative media idea? 
        Use the form below to reach out. I’m especially interested in opportunities related to content creation, 
        branding, and digital storytelling.
      </p>
    </section>

    <section class="contact-section">
      <div class="contact-info">
        <h3>Let’s Connect</h3>
        <p>
          The best way to get in touch is through this contact form. I’m open to internships, freelance projects, 
          collaborations, and creative experiments.
        </p>
        <p><a class="btn-outline" href="#contact-form">Email Eden via Form</a></p>

        <ul>
          <li>
            <a href="https://www.linkedin.com/in/eden-silverwolf/" target="_blank" rel="noopener">
              Connect with me on LinkedIn
            </a>
          </li>
          <li>
            <a href="https://www.asu.edu" target="_blank" rel="noopener">
              Arizona State University
            </a>
          </li>
        </ul>
      </div>

      <div class="contact-form-wrapper">
        <h3>Send a Message</h3>
        <form id="contact-form" action="#" method="post">
          <div class="form-group">
            <label for="name">Full Name*</label>
            <input type="text" id="name" name="name" required>
          </div>

          <div class="form-group">
            <label for="email">Email Address*</label>
            <input type="email" id="email" name="email" required>
          </div>

          <div class="form-group">
            <label for="subject">Subject*</label>
            <input type="text" id="subject" name="subject" required>
          </div>

          <div class="form-group">
            <label for="project-type">Project Type</label>
            <select id="project-type" name="project-type">
              <option value="">Please select</option>
              <option value="social-media">Social Media Campaign</option>
              <option value="content-creation">Content Creation / Design</option>
              <option value="branding">Branding / Strategy</option>
              <option value="interactive">Interactive / Media Arts</option>
              <option value="other">Other</option>
            </select>
          </div>

          <div class="form-group">
            <label for="message">Message*</label>
            <textarea id="message" name="message" rows="5" required></textarea>
          </div>

          <div class="form-group">
            <button type="submit" class="btn">Submit</button>
          </div>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Eden Sky Silverwolf. All rights reserved.</p>
    <p>
      <a href="#contact-form">Back to Contact Form</a> | 
      <a href="https://www.google.com" target="_blank" rel="noopener">External Link: Google</a>
    </p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Digital marketing and media portfolio for Eden Sky Silverwolf, a Digital & Integrated Marketing Communications major with a Media Arts & Sciences minor at ASU.">
  <meta name="author" content="Eden Sky Silverwolf">
  <title>Eden Silverwolf | Digital Marketing & Media Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>Eden Silverwolf</h1>
      <p>Digital & Integrated Marketing Communications · Media Arts & Sciences · ASU</p>
    </div>
    <nav>
      <ul>
        <li><a href="index.html" class="active">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="portfolio.html">Portfolio</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <div class="hero-text">
        <h2>Turning Ideas into Scroll-Stopping Stories</h2>
        <p>
          Hi, I’m Eden, a Digital & Integrated Marketing Communications major with a Media Arts & Sciences minor at 
          Arizona State University. I combine strategy, visual design, and interactive media to help brands stand out 
          on social, connect with real people, and actually make an impact.
        </p>
        <p>
          From social campaigns and content calendars to web design and creative tech projects, I’m always thinking 
          about how to make experiences more engaging, inclusive, and human.
        </p>
        <a class="btn" href="portfolio.html">Explore My Work</a>
        <a class="btn-outline" href="contact.html#contact-form">Contact Eden</a>
      </div>
      <div class="hero-image">
        <img src="images/eden-profile.jpg" alt="Photo of Eden Sky Silverwolf, digital marketing and media student">
      </div>
    </section>

    <section class="highlights">
      <h2>What I Bring to the Table</h2>
      <div class="cards">
        <article class="card">
          <h3>Digital Marketing Strategy</h3>
          <p>
            Experience planning and scheduling social content across multiple platforms, aligning posts with campaigns, 
            seasonal events, and brand goals.
          </p>
        </article>
        <article class="card">
          <h3>Content & Media Creation</h3>
          <p>
            Creating graphics, short-form videos, photos, and event materials in tools like Canva and Adobe Express, 
            blending design with storytelling.
          </p>
        </article>
        <article class="card">
          <h3>Creative Tech & Web Design</h3>
          <p>
            Building responsive websites in HTML5/CSS3 and experimenting with interactive projects using tools like 
            Circuit Playground Express and media art concepts.
          </p>
        </article>
      </div>
    </section>

    <section class="featured">
      <h2>Featured Experience: Pediatric Clinic Social Media</h2>
      <p>
        As a marketing intern, I helped keep a pediatric clinic’s social presence active and relevant by 
        photographing campus and patients (ages 5–50), creating posts for all major platforms, and updating 
        their Google Business profile.
      </p>
      <p>
        I also designed posters and signs in Canva for family events and a fundraising basketball project in partnership 
        with the Phoenix Suns, where I helped come up with team names, mascots, and signed jerseys used in the event.
      </p>
      <img src="images/featured-campaign.jpg" alt="Mockup of a pediatric clinic digital campaign on multiple screens">
      <p>
        See more details and project snapshots on the <a href="portfolio.html">Portfolio page</a>.
      </p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Eden Sky Silverwolf. All rights reserved.</p>
    <p>
      <a href="contact.html#contact-form">Contact Me</a> | 
      <a href="https://www.asu.edu" target="_blank" rel="noopener">Arizona State University</a>
    </p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of digital marketing, design, and media projects by Eden Sky Silverwolf.">
  <meta name="author" content="Eden Sky Silverwolf">
  <title>Portfolio | Eden Silverwolf</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>Eden Silverwolf</h1>
      <p>Digital & Integrated Marketing Communications · Media Arts & Sciences · ASU</p>
    </div>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="portfolio.html" class="active">Portfolio</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="page-intro">
      <h2>Portfolio</h2>
      <p>
        This portfolio highlights a mix of coursework, internship experience, and creative projects. 
        Each piece shows how I think about audience, visuals, and storytelling across different digital platforms.
      </p>
    </section>

    <section class="projects-grid">
      <article class="card">
        <h3>Pediatric Clinic Social Campaign</h3>
        <p>
          Created and scheduled social media posts across platforms and refreshed the Google Business profile 
          for a pediatric clinic. Photographed the campus and patients (ages 5–50) to build a friendly, 
          community-focused look and feel.
        </p>
        <img src="images/social-campaign.jpg" alt="Social media mockup for a pediatric clinic campaign on mobile screens">
      </article>

      <article class="card">
        <h3>Fundraising Event with Phoenix Suns</h3>
        <p>
          Supported a basketball fundraiser partnered with the Phoenix Suns by brainstorming team names, mascots, 
          and signed jersey concepts. Designed promotional posters and signs in Canva for patients, families, 
          and event attendees.
        </p>
        <img src="images/event-poster.jpg" alt="Colorful event poster mockup for a basketball fundraiser">
      </article>

      <article class="card">
        <h3>CIS300 Portfolio Website</h3>
        <p>
          Designed and coded this portfolio website using HTML5 and CSS3. Focused on clean navigation, 
          responsive layout, and clear sections for my work, background, and contact information.
        </p>
        <img src="images/portfolio-site.jpg" alt="Laptop screen showing a personal portfolio website layout">
      </article>

      <article class="card">
        <h3>Interactive & Metaverse Concepts</h3>
        <p>
          Explored speculative design and metaverse concepts by imagining a fitness and wellness environment 
          in virtual spaces. Also experimented with interactive media using Circuit Playground Express 
          and creative coding tools.
        </p>
        <img src="images/metaverse-fitness.jpg" alt="Concept art mockup of a metaverse fitness and wellness environment">
      </article>
    </section>

    <section class="skills-table-section">
      <h3>Skills & Tools Overview</h3>
      <p>
        This table summarizes some of my main skills and tools across digital marketing, design, analytics, and interactive media.
      </p>

      <table>
        <thead>
          <tr>
            <th>Skill Area</th>
            <th>Tools / Platforms</th>
            <th>What I Do</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Social Media Marketing</td>
            <td>Instagram, TikTok, Facebook, X, Google Business</td>
            <td>Plan content calendars, write captions, post updates, and support brand consistency across platforms.</td>
          </tr>
          <tr>
            <td>Content Creation & Design</td>
            <td>Canva, Adobe Express, basic Photoshop</td>
            <td>Design flyers, social graphics, event materials, and simple animations for campaigns and events.</td>
          </tr>
          <tr>
            <td>Analytics & Optimization</td>
            <td>Platform Insights, basic Google Analytics</td>
            <td>Check performance (reach, clicks, engagement) and use results to adjust content and timing.</td>
          </tr>
          <tr>
            <td>Web & Interactive Media</td>
            <td>HTML5, CSS3, GitHub, Circuit Playground Express</td>
            <td>Build responsive pages, experiment with interactive projects, and connect visuals with user experience.</td>
          </tr>
        </tbody>
      </table>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Eden Sky Silverwolf. All rights reserved.</p>
    <p>
      <a href="contact.html#contact-form">Work With Me</a> | 
      <a href="https://marketing.asu.edu" target="_blank" rel="noopener">Learn about Marketing at ASU</a>
    </p>
  </footer>
</body>
</html>
/* Basic Page Styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: Arial, Helvetica, sans-serif;
  line-height: 1.6;
  color: #222222;
  background-color: #f9fafb;
}

/* Layout */
header {
  background-color: #111827; /* deep navy/charcoal */
  color: #ffffff;
  padding: 1rem 2rem;
}

.logo h1 {
  font-size: 1.8rem;
}

.logo p {
  font-size: 0.9rem;
  color: #d1d5db;
}

/* Navigation */
nav {
  margin-top: 0.5rem;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1rem;
  flex-wrap: wrap;
}

nav a {
  color: #e5e7eb;
  text-decoration: none;
  padding: 0.3rem 0.7rem;
  border-radius: 4px;
  font-size: 0.95rem;
}

/* warm accent color */
:root {
  --accent: #f97316; /* orange */
  --accent-dark: #ea580c;
  --accent-soft: #ffedd5;
}

nav a:hover,
nav a.active {
  background-color: var(--accent);
  color: #111827;
}

/* Main Content */
main {
  max-width: 1100px;
  margin: 0 auto;
  padding: 2rem 1rem 3rem;
}

.page-intro {
  margin-bottom: 2rem;
}

.page-intro h2 {
  font-size: 2rem;
  margin-bottom: 0.75rem;
}

.page-intro p {
  max-width: 750px;
}

/* Hero Section */
.hero {
  display: grid;
  grid-template-columns: 1.3fr 1fr;
  gap: 2rem;
  align-items: center;
  margin-bottom: 3rem;
}

.hero-text h2 {
  font-size: 2.3rem;
  margin-bottom: 1rem;
}

.hero-text p {
  margin-bottom: 1rem;
}

.hero-image img {
  width: 100%;
  border-radius: 10px;
  display: block;
}

/* Buttons */
.btn,
.btn-outline {
  display: inline-block;
  padding: 0.6rem 1.2rem;
  border-radius: 999px;
  text-decoration: none;
  font-size: 0.95rem;
  margin-right: 0.5rem;
  margin-bottom: 0.5rem;
}

.btn {
  background-color: var(--accent);
  color: #111827;
  border: none;
  font-weight: bold;
}

.btn:hover {
  background-color: var(--accent-dark);
  color: #ffffff;
}

.btn-outline {
  border: 1px solid var(--accent);
  color: var(--accent);
  background-color: transparent;
}

.btn-outline:hover {
  background-color: var(--accent-soft);
}

/* Cards / Highlights */
.highlights {
  margin-bottom: 3rem;
}

.highlights h2 {
  margin-bottom: 1.25rem;
}

.cards {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
  gap: 1.5rem;
}

.card {
  background-color: #ffffff;
  padding: 1.25rem;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(15, 23, 42, 0.08);
}

.card h3 {
  margin-bottom: 0.5rem;
}

/* Featured Section */
.featured {
  margin-top: 2rem;
}

.featured img {
  width: 100%;
  max-width: 700px;
  display: block;
  margin: 1rem 0;
  border-radius: 10px;
}

/* About Page Layout */
.about-layout {
  display: grid;
  grid-template-columns: minmax(0, 1.5fr) minmax(0, 1fr);
  gap: 2rem;
  margin-bottom: 2.5rem;
}

.about-layout ul {
  margin-top: 0.75rem;
  padding-left: 1.2rem;
}

.about-layout li {
  margin-bottom: 0.4rem;
}

.about-image img {
  width: 100%;
  border-radius: 10px;
}

/* Video Section */
.about-video video {
  width: 100%;
  max-width: 640px;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
  margin-top: 1rem;
}

/* Portfolio Grid */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 1.5rem;
  margin-bottom: 3rem;
}

.projects-grid .card img {
  width: 100%;
  border-radius: 8px;
  margin-top: 0.75rem;
}

/* Table Styles */
.skills-table-section table {
  width: 100%;
  border-collapse: collapse; /* removes cell spacing */
  margin-top: 1rem;
  background-color: #ffffff;
  border-radius: 10px;
  overflow: hidden;
}

.skills-table-section th,
.skills-table-section td {
  padding: 0.75rem 1rem;
  border-bottom: 1px solid #e5e7eb;
  vertical-align: top;
}

.skills-table-section th {
  background-color: #111827;
  color: #ffffff;
  text-align: left;
}

.skills-table-section tr:nth-child(even) td {
  background-color: #f3f4f6;
}

/* Contact Page */
.contact-section {
  display: grid;
  grid-template-columns: minmax(0, 1.1fr) minmax(0, 1.3fr);
  gap: 2rem;
}

.contact-info ul {
  list-style: none;
  margin-top: 0.75rem;
}

.contact-info li {
  margin-bottom: 0.5rem;
}

.contact-info a {
  color: var(--accent-dark);
}

.contact-form-wrapper {
  background-color: #ffffff;
  padding: 1.5rem;
  border-radius: 10px;
  box-shadow: 0 2px 6px rgba(15, 23, 42, 0.08);
}

/* Form Styles */
form .form-group {
  margin-bottom: 1rem;
}

form label {
  display: block;
  font-weight: bold;
  margin-bottom: 0.25rem;
}

form input[type="text"],
form input[type="email"],
form select,
form textarea {
  width: 100%;
  padding: 0.6rem;
  border-radius: 6px;
  border: 1px solid #d1d5db;
  font-size: 0.95rem;
}

form textarea {
  resize: vertical;
}

/* Footer */
footer {
  background-color: #111827;
  color: #e5e7eb;
  text-align: center;
  padding: 1rem;
}

footer a {
  color: #fed7aa;
  text-decoration: none;
}

footer a:hover {
  text-decoration: underline;
}

/* Responsive */
@media (max-width: 768px) {
  .hero,
  .about-layout,
  .contact-section {
    grid-template-columns: 1fr;
  }

  header {
    text-align: center;
  }

  nav ul {
    justify-content: center;
  }
}

