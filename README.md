<div align="center">
  <br />
  <img src=".github/logo.svg" width="546" alt="Move.It" />
  <br />
  <p>
    <img src="https://img.shields.io/badge/made%20by-Thales%20Macena-2D325E?labelColor=F0DB4F&style=for-the-badge&logo=visual-studio-code&logoColor=2D325E" alt="Made by Thales Macena">
    <img alt="Top Language" src="https://img.shields.io/github/languages/top/thalesmacena/next-level-week-proffy?color=2D325E&labelColor=F0DB4F&style=for-the-badge&logo=javascript&logoColor=2D325E">
    <a href="https://github.com/thalesmacena/next-level-week-proffy/commits/master">
      <img alt="Last Commits" src="https://img.shields.io/github/last-commit/thalesmacena/next-level-week-proffy?color=2D325E&labelColor=F0DB4F&style=for-the-badge&logo=github&logoColor=2D325E">
    </a>
<a href="https://github.com/thalesmacena/next-level-week-proffy/issues"><img alt="Top Language" src="https://img.shields.io/github/issues-raw/thalesmacena/next-level-week-proffy?color=2D325E&labelColor=F0DB4F&style=for-the-badge&logo=github&logoColor=2D325E"></a>
  </p>
</div>

## 🗂 Table of contents
- [🗂 Table of contents](#-table-of-contents)
- [📑 About](#-about)
- [🚶 Static Project](#-static-project)
- [🏃 Dynamic Project](#-dynamic-project)
  - [💻 Modules](#-modules)
  - [🔥 Run the Project](#-run-the-project)


## 📑 About

Application developed during [Rocketseat](https://rocketseat.com.br/) Next Level Week. The classes were taught by the teacher [maik britto](https://github.com/maykbrito).

Proffy is a tutoring platform. Teachers register and tell the classes and times they want to teach. Students can search for teachers by selected subjects and schedules.

## 🚶 Static Project

You can find the static design of the pages, an example of what it would look like, in Master Branch without all its functionality. By accessing [Proffy website](https://thalesmacena.github.io/next-level-week-proffy/), its Github pages link. You can also find a [Error page](https://thalesmacena.github.io/next-level-week-proffy/not-found.html), if the server responded with a http 404 error. 

## 🏃 Dynamic Project

In the development branch you can find the updated project using [node.js](https://nodejs.org/en/). The reason for leaving the application finished in the dev branch, is to keep your dependencies as close as possible to the original and to be able to use the github pages tool to show the design of the application in the master branch.

### 💻 Modules
This project uses [Express.js](https://expressjs.com/) framework, the [nunjucks](https://mozilla.github.io/nunjucks/) template engine, the [asynchronous sqlite](https://www.npmjs.com/package/sqlite-async) database. And the [Nodemon](https://nodemon.io/) as a development dependency to reload the server whenever changes are made

### 🔥 Run the Project
to run the project first download or copy all the files from the dev branch to your chosen local directory. Then use your package manager's run command:

**With NPM:**
```Bash
npm run dev
```

**With Yarn:**
```Bash
yarn run dev
```

**The server is listening on port 5500, so to access, just go to 127.0.0.1:5500 or localhost:5500**
