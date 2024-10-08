# Mike Teaches Tech Website

Welcome to the GitHub repository for the [Mike Teaches Tech website](https://www.miketeachestech.com). This site is built using [Hugo](https://gohugo.io/) with the [Tella theme](https://github.com/opera7133/tella). The site is hosted on [GitHub Pages](https://pages.github.com/) and utilizes a custom domain purchased from [GoDaddy](https://www.godaddy.com/).

## Getting Started

These instructions will get you a copy of this website up and running on your local machine for development and testing purposes, or perhaps to get you started in making your own website!

### Prerequisites

You need to have the following tools installed on your system:
- Git
- Hugo
- npm

### Installing

1. **Clone the repository:**
`git clone https://github.com/miketeachestech/miketeachestech.github.io.git` 

2. **Install Hugo:**
Follow the instructions on the [Hugo official site](https://gohugo.io/getting-started/installing/) to install Hugo on your system.

3. **Install npm:** 
Follow the instructions on the [npm official docs site](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) to install npm on your system.

4. **Install dependencies:**
Run `npm install` in the root folder of the project.

5. **Running the project locally:**
Run `hugo server` in the root folder of the project. This command will start the Hugo server locally, and you can view your website at `http://localhost:1313`.

### Using the Tella Theme

Ensure you have the Tella theme files in your themes directory. You might need to run `git submodule add https://github.com/opera7133/tella.git themes/tella` in the root folder of your project.

## Deployment

To deploy your Hugo website using GitHub Pages, follow [these instructions.](https://gohugo.io/hosting-and-deployment/hosting-on-github/)