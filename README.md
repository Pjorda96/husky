# Husky

Husky project.
Documentation gide [here](https://typicode.github.io/husky/#/)

## Get started

Follow the gide instructions

- Install husky `npm install husky --save-dev`
- Enable git hooks `npx husky install`
- To automatically have Git hooks enabled after install `npm set-script prepare "husky install"`

#### To create a hook

`npx husky add .husky/pre-commit "npm test"`

## Clone the project

Just clone and install the project. The **prepare** script ensures you have git hooks installed.
