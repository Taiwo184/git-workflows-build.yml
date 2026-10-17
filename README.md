# GitHub Pages Deployment Workflow

This project demonstrates how to automatically connect a javascript build tool to docker and then  automate the build with Github Actions. 
## How it works

Commit and push your project to GitHub. The workflow should run when you push to main or open a pull request targeting main. The workflow is triggered when changes are pushed to the `main` branch and the `index.html` file has been modified.

The workflow then:

1. Checks out the repository.
2. Configures GitHub Pages.
3. Uploads the website as an artifact.
4. Deploys the website to GitHub Pages.

## Technologies

- HTML
- Docker
- Git
- GitHub
- GitHub Actions
- GitHub Pages

## Deployment URL

https://Taiwo184.github.io/git-workflows-build.yml
