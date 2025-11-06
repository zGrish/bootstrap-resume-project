# Bootstrap Resume Project

A clean, modern, and responsive personal portfolio template built with Bootstrap 4 and SCSS. This project helps you showcase your skills, experience, projects, interests, and awards with an elegant coffee-inspired color palette.

---

## Table of Contents

- [About The Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Customization](#customization)
- [Contributing](#contributing)

---

## About The Project

This is a Bootstrap 4-based resume/portfolio template that is fully responsive and easy to customize. It features:

- Elegant coffee tone color scheme 
- Bootstrap cards for projects with smooth hover animations
- Skill icons using Devicons font
- Clear sections for experience, education, volunteering, skills, languages, interests, and awards
- SCSS source code for easy theming and styling

---

## Built With

- [Bootstrap 4](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
- [Devicons](https://vorillaz.github.io/devicons/)
- [Font Awesome](https://fontawesome.com/)
- [Sass/SCSS](https://sass-lang.com/)
- [jQuery](https://jquery.com/)

---

## Getting Started

### Prerequisites

- Node.js and npm installed
- Sass compiler (`sass`) installed globally or via npm
- Git (optional, for cloning repo)

### Installation

1. Clone the repository:
```
git clone https://github.com/yourusername/bootstrap-resume-project.git
cd bootstrap-resume-project
```

2. Install dependencies (if applicable):
This project uses `gulp` or `sass` for compiling SCSS. You can install Gulp CLI globally if using Gulp:
```
npm install -g gulp-cli
npm install
```

3. Compile SCSS to CSS:

**Using Sass CLI**
```
sass --watch scss:css
```


**Using Gulp**
```
gulp
```

This will generate `css/resume.css` and `css/resume.min.css`.

---

## Usage

- Open `index.html` in your browser to view the portfolio.
- Modify content sections inside `index.html` to add your personal info, projects, experience, etc.
- Update SCSS files inside the `scss/` folder to customize styles and color scheme.

---

## Customization

### Updating Colors

Modify the color variables in `scss/_variables.scss` as you like:
```
$espresso: #351904;
$gold: #E08E00;
```
Recompile SCSS to see changes.

### Adding Tech Icons

Use Devicons classes like:
```
<i class="devicons devicons-html5"></i>
<i class="devicons devicons-css3"></i>
```

### Adding Projects

Add cards inside `<section id="projects">` with structure:
```
<div class="card project-card mb-4">
  <div class="card-body"> <h5 class="card-title">Project Name</h5>
    <p class="card-text">Description, tools used, achievements.</p>
  </div>
</div> 
```
You can add or remove cards as needed.

---

### Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve this project.
