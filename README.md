# The Curriculum Vitae Project

Daniel Arruda Santos Anjos CV (resume) forked from [**The Curriculum Vitae Project**](https://github.com/sneas/cv-project)

## Installation

### One step way (if you don't mind forking)

1. Fork this repo

### Multi step way (for those who who doesn't want to fork)

1. Create and clone a new repo
1. `npm install -g git-cp`
1. `cd` into the repo's folder
1. `git-cp git@github.com:sneas/cv-project.git` 

## Usage

1. Install project dependencies with `npm install`
1. Start local development server with `npm start`.
1. Update contents of `src` folder to fit your needs. This item is explained [below](#update-contents).
1. Commit your changes.
1. Publish your updated CV on GitHub pages with `npm run gh`.
1. Open `http://your-username.github.io/your-cv-repo`
1. Have a cookie 🍪

### Update contents

* The project uses [HandlebarsJS](https://github.com/wycats/handlebars.js/) as a template engine.
* The main HTML template could be found in [src/templates/index.html](src/templates/index.html). 
* Metadata for the template could be found in [src/metadata/metadata.js](src/metadata/metadata.js).
* Don't forget to update [src/assets/favicon.ico](src/assets/favicon.ico). Generate a new one with [favicon.io](https://favicon.io/).
