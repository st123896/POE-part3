# POE-part3

POE-part3 is a front-end web project built with HTML, CSS, and JavaScript. It features multiple pages (Home, About, Services, News, Contact) and is structured with tools for workflow automation (Gulp, Grunt, Bower).  

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Getting Started](#getting-started)  
  - [Prerequisites](#prerequisites)  
  - [Installation](#installation)  
  - [Usage](#usage)  
- [Project Structure](#project-structure)  
- [Development & Build Tools](#development-and-build-tools)  
- [Contributing](#contributing)  


-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Features

- Multi-page website: Home, About, Services, News, Contact.  
- Responsive design (basic) with CSS for layout and styling.  
- Automation with Gulp / Grunt for tasks like minification, compilation etc.  
- Dependency management via Bower.  

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Technologies Used

| Purpose | Technology |
|---|---|
| Markup / Structure | HTML |
| Styling | CSS |
| Interactivity / Client-side logic | JavaScript |
| Package & dependency management | Bower, npm |
| Task automation / build system | Gulp, Grunt |

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Getting Started

### Prerequisites

Before you begin, make sure you have installed:

- [Node.js & npm](https://nodejs.org/)  
- [Gulp CLI](https://gulpjs.com/) & [Grunt CLI](https://gruntjs.com/) (if globally needed)  
- [Bower](https://bower.io/)  

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/st123896/POE-part3.git
Change into the project directory:
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
bash
Copy code
cd POE-part3
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Install npm packages:

bash
Copy code
npm install
Install Bower dependencies:

bash
Copy code
bower install
(If needed) Install Gulp / Grunt globally:

bash
Copy code
npm install -g gulp grunt-cli
Usage
To run build tasks (minify, compile, etc.):

bash
Copy code
gulp
or

bash
Copy code
grunt
To view the website locally, open index.html in your browser or use a web server (e.g. http-server, live-server) for better testing of relative paths and assets.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Project Structure
pgsql
Copy code
POE-part3/
├── index.html
├── Home.html
├── About.html
├── Services.html
├── News.html
├── Contact.html
├── style.css
├── package.json
├── bower.json
├── .bowerrc
├── gulpfile.js
└── gruntfile.js
index.html & other .html files – the various pages of the site
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
style.css – main stylesheet

package.json – npm dependencies and scripts

bower.json & .bowerrc – front-end dependency settings

gulpfile.js, gruntfile.js – task configuration for build processes

Development & Build Tools
Gulp – used for tasks such as CSS preprocessing (if applicable), minification, live reload (if configured).

Grunt – similar build tasks; may co-exist depending on certain workflows.

Bower – helps with front-end dependency management (libraries, frameworks).
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Contributing
Contributions are welcome! To contribute:

Fork the repository

Create a new feature branch (git checkout -b feature/YourFeature)

Make changes, commit (git commit -m "Add YourFeature")

Push to your fork (git push origin feature/YourFeature)

Open a Pull Request describing your changes

Please follow existing code conventions and ensure anything added maintains consistency in style and formatting.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Author: Tshepiso Mokhine

GitHub: https://github.com/st123896

