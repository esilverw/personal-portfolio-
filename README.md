[about.html](https://github.com/user-attachments/files/23972977/about.html)
[contact.html](https://github.com/user-attachments/files/23972978/contact.html)[styles.css](https://github.com/user-attachments/files/23972981/styles.css)
[portfolio.html](https://github.com/user-attachments/files/23972980/portfolio.html)
[index.html](https://github.com/user-attachments/files/23972979/index.html)
[styles.css](https://github.com/user-attachments/files/23972983/styles.css)
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
