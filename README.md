# Mike Teaches Tech Website

Welcome to the GitHub repository for the [Mike Teaches Tech website](https://www.miketeachestech.com). This site is built using [Hugo](https://gohugo.io/) using the [Tella theme](https://github.com/opera7133/tella). The site is hosted on [GitHub Pages](https://pages.github.com/) and uses a custom domain purchased from [GoDaddy](https://www.godaddy.com/).

## Getting Started

These instructions will get you a copy of this website up and running on your local machine for development and testing purposes, or perhaps to make your own website based on mine! See deployment for notes on how to deploy the project as a live system.

### Prerequisites

You need to have the following tools installed on your system:
- Git
- Hugo
- npm

### Installing

1. **Clone the repository:**
`git clone https://github.com/miketeachestech/miketeachestech-website.git` 

2. **Install Hugo:**
Follow the instructions on the [Hugo official site](https://gohugo.io/getting-started/installing/) to install Hugo on your system.

3. **Install npm:** 
Follow the instructions on the [npm official docs site](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to install npm on your system.

4. **Install dependencies:**
Run `npm install` in the root folder of the project.

5. **Running the project locally:**
Run `hugo server` in the root folder of the project. This command will start the Hugo server locally, and you can view your website at `http://localhost:1313`.

### Using the Tella Theme

To integrate the Tella theme into your Hugo site:

1. Ensure you have the Tella theme files in your themes directory. You might need to run `git submodule add https://github.com/opera7133/tella.git themes/tella` in the root folder of your project.
2. Update the `config.toml` file in your Hugo site to set `theme = "tella"`.

## Deployment

To deploy your website using GitHub Pages:

1. Ensure your repository is set up to deploy from the `gh-pages` branch.
2. Push your changes to GitHub: `git push origin main` 
3. Your changes should now be live on GitHub Pages at `http://yourusername.github.io/miketeachestech-website`.