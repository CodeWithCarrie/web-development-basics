<div align="center">
    <img src="public/images/cwc-logo-4-colors.svg" alt="Code with Carrie logo" width="50%" />
    <h1>Web Development Basics</h1>
    <p><em>Beginner demos and exercises on building web apps with HTML, CSS, and 'vanilla' JavaScript</em></p>
    <a href="http://www.codewithcarrie.com"><img src="https://img.shields.io/badge/by-CodeWithCarrie.com-b03454?style=for-the-badge" alt="badge linking to CodeWithCarrie's website" /></a>
    <img src="https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML" />
    <img src="https://img.shields.io/badge/CSS-rebeccapurple?style=for-the-badge&logo=css&logoColor=white" alt="CSS" />
    <img src="https://img.shields.io/badge/JavaScript-F0DB4F?style=for-the-badge&logo=javascript&logoColor=333333" alt="JavaScript" />
    <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=eslint&logoColor=white" alt="ESLint" />
    <img src="https://img.shields.io/badge/Prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=333333" alt="Prettier" />
</div>

---

<div align="center">
    <a href="https://github.com/CodeWithCarrie/web-development-basics/blob/main/README.md#setup">Setup</a> &bull;
    <a href="https://github.com/CodeWithCarrie/web-development-basics/tree/main#1---html-basics">HTML Basics</a> &bull;
    <!-- TODO: Add links to sections below -->
</div>

---

### Welcome!

In a field increasingly dominated by AI code generation, it is essential to have a firm grasp on the fundamentals in order to plan ahead, compose crystal-clear prompts, and recognize errors and poorly-formed code. The only way to build muscle is to exercise it, and learning programming is no different!

> [!IMPORTANT]
> You need to deepen your problem-solving skills and core understanding of syntax and code composition independently _before_ you can integrate AI tools in your workflow and become a more efficient developer. My learning resources are designed to do just that!

---

### HOW TO FORK AND CLONE

#### CREATE YOUR OWN COPY

1. FORK it to your own GitHub account
1. COPY the link from your new repo on GitHub
1. CLONE it to your local machine. Example:

`git clone https://github.com/YourUsername/web-development-basics`

#### PRACTICE IN YOUR OWN BRANCHES

If you want to update your forked repository from my parent repository when I add or change things to mine in the future, there are instructions below this section.
It will go much easier if you don't ever change the code in `main`. Instead, do the following:

1. From `main`, use the command `git checkout -b new-branch-name` to create your own branch for practicing (example: `html-practice`).
1. Practice as much as you'd like in your new branch, making commits as you add code.
1. When you are ready to work on something different in another new branch, use the command `git checkout main` to return to `main` and then you can repeat the two steps above.

### HOW TO UPDATE YOUR REPO AFTER I'VE UPDATED MINE

> [!WARNING]
> I am still adding new content regularly, so you will likely have to sync your forked repo with mine in order to pull that content into your own.

**Set the upstream link:**

1. On your local machine, make sure you are in the correct directory in the terminal.
1. Use the command `git remote add upstream https://github.com/CodeWithCarrie/web-development-basics`

You now have a direct link to my original repo!

Use the command `git remote -v` to verify that you have linked to both `origin` (your forked repo) and `upstream` (my original repo)

**Update your repo anytime I make changes in the future:**

1. On your local machine, make sure you are in the correct directory in the terminal.
1. If you have any uncommitted changes, **stage** and **commit** them.
1. Make sure you are in the branch you wish to update (e.g. `main`)
1. Use the command `git fetch upstream` so your local repo has knowledge of changes I made in my repo
1. Use the command `git rebase upstream/main` to sync your repo

**Check to see which branches you already have:**

1. You can use the command `git branch` anytime to see what local branches you have
1. The command `git branch -r` will show you branches that exist on GitHub (after you've fetched that knowledge)

---

## DEMOS & PRACTICE EXERCISES

If you are unfamiliar with the basics of JavaScript, I recommend starting with my [JavaScript Fundamentals Series](https://github.com/CodeWithCarrie/javascript-fundamentals) and [Modular JavaScript Series](https://github.com/CodeWithCarrie/modular-javascript) before continuing with any tutorials below that involve JavaScript.

Each topic will have a corresponding video on the [@CodeWithCarrie](https://youtube.com/@CodeWithCarrie) YouTube channel, with some code left for the learner to complete in-between videos. Use the links in the sections below for quick peeks at the starter code or solution in different branches. You can fork your own copy of this repository for practice on your local machine. While individual links are available below for each video, you can also start with the [full playlist](https://www.youtube.com/playlist?list=PLvcPeTeqi37QwaJI-_Zy83NjgwyQ8DuAx).

> [!TIP]
> I recommend working through the demos and exercises in the sequence shown below.

Go forth and learn!

---

### SETUP

This collection of coding exercises focuses on HTML, CSS, JavaScript, and JSON. It is recommended to use the Live Server extension in VS Code and also be prepared to use Postman to test HTTP requests and responses.

---

### 1 - HTML Basics

Switch to the [01-html-basics-starter](https://github.com/CodeWithCarrie/web-development-basics/tree/01-html-basics-starter) branch or the [01-html-basics-solution](https://github.com/CodeWithCarrie/web-development-basics/tree/01-html-basics-solution) branch.

| Topics                           | Videos                               |    Length |
| -------------------------------- | ------------------------------------ | --------: |
| Structuring a Page with HTML     | [Demo](https://youtu.be/rHiaNZtMwfI) |     10:14 |
| Structuring Content with HTML    | [Demo](https://youtu.be/OIAeGlKc6ko) |      4:03 |
| Organizing Information with HTML | [Demo](https://youtu.be/Dr4cVDCIvKQ) |      2:43 |
| Adding Images & Links            | [Demo](https://youtu.be/m6z8H3sQSpE) |      4:41 |
|                                  | **TOTAL**                            | **21:41** |

---

### 2 - CSS

| Topics                                      | Code                                 |   Length |
| ------------------------------------------- | ------------------------------------ | -------: |
| Introduction to CSS                         | [Demo](https://youtu.be/wPiYZTE43Ko) |    17:49 |
| Dynamic Styling                             | _Coming soon!_                       |          |
| FlexBox Layout                              | _Coming soon!_                       |          |
| Responsive Design with Grid & Media Queries | _Coming soon!_                       |          |
|                                             | **TOTAL**                            | **0:00** |

---

### 3 - HTML Forms

_Coming soon!_

---

### 4 - The DOM

_Coming soon!_

---

_...and more!_

---

## ABOUT THE AUTHOR

### Caroline "Carrie" Jones

Front End Engineer and Lead Instructor at [LaunchCode](https://www.launchcode.org)

[@Carolista](https://github.com/Carolista) - [CodeWithCarrie.com](http://codewithcarrie.com) - [LinkedIn](https://www.linkedin.com/in/carolinerjones)
