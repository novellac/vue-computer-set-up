# Set Up Your Computer for VueJS

If you are new to VueJS, this is one place where you can start. Since I think that Windows can  be tricker to get started on, I've tried to pay special attention to Windows users throughout this guide.

_If you have questions, or would like to have something explained in more detail, please create an issue. if you want to make contributions, please create a Pull Request with a very clear description of the change you propose and why. This project functions under the [Geek Feminism Code of Conduct](https://geekfeminismdotorg.wordpress.com/about/code-of-conduct/)._

## Steps to Vue! (Follow them loosely, or in strict order, or not at all! :-))
- Node ([Node.JS](https://nodejs.org/en/download/))
    - What is Node? ([Wikipedia](https://en.wikipedia.org/wiki/Node.js))
    - Open terminal, check node -v
    - NPM should be installed when you install node. Check with npm -v
- NPM
    - What is NPM? ([Wikipedia](https://en.wikipedia.org/wiki/Npm_%28software%29))
    - [NVM](https://github.com/creationix/nvm) exists, and you might want to use it (but we won't do that now)
- VSCode ([Get VSCode](https://code.visualstudio.com/))
    - Extensions
        - [Sarah Drasner's Extension Pack](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-extensionpack)
        - [Extras: Gift's Recommendations](https://dev.to/lauragift21/a-collection-of-essential-vscode--extensions-26al) (goes beyond Vue)
- Vue [See the Docs](https://vuejs.org/v2/guide/installation.html)
    - npm install -g vue will install Vue everywhere
    - [Vue CLI](https://cli.vuejs.org/)
        - A command line interface (CLI) which can help you start new projects quickly, with some common preset options to choose from.
        - What do each of the options mean?
            - [Babel](https://babeljs.io/docs/en) - A JavaScript compiler that makes your newer JavaScript work with older versions of JavaScript.
            - [TypeScript](https://www.typescriptlang.org/index.html) - A compiled programming that includes JavaScript, but has extra features (most importantly [strong typing](https://en.wikipedia.org/wiki/Strong_and_weak_typing)). It is a "superset of Javascript," and compiles down to plain JavaScript.
            - [Progressive Web App support](https://en.wikipedia.org/wiki/Progressive_web_applications) - Helps your site act like a native app on the device, most notably it lets you use the app offline.
            - [Router](https://router.vuejs.org/) - Mostly we think of it as helping you to create multiple linked pages within your single page application ("routes"), but Vue Router does a bunch of other things too!
            - [Vuex](https://vuex.vuejs.org/) - Helps to manage "state" in your application. It stores some data that you may want to view and manipulate, and it makes sure you're manipulating that data in a safe way.
            - [CSS Preprocessors](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor) - These let you use CSS extension languages such as SASS, LESS, and Stylus (which are like CSS but with more features and different syntax).
            - [Linter](https://en.wikipedia.org/wiki/Lint_(software)) - Analyzes your code for errors, and alerts you to what and where, roughly, the errors are.
            - [Unit Testing](https://vuejs.org/v2/guide/unit-testing.html) - Lets you choose from [Jest](https://github.com/facebook/jest) or [Mocha](https://mochajs.org/) frameworks to test chunks of code in your app.
            - [E2E Testing](https://dev.to/lambdatesting/all-you-need-to-know-about-end-to-end-testing-4nbb) - Short for "[End to End Testing](https://vuejsdevelopers.com/2019/04/01/vue-testing-unit-vs-e2e/)," [Cypress](https://www.cypress.io/)/[Nightwatch](http://nightwatchjs.org/) are set up so you can test how your app works overall (e.g., What happens if you log in with an invalid email address?)
            - @TODO Use History Mode for Router?
            - @TODO Which CSS Preprocessor
            - @TODO Where do you prefer storing config?
            - @TODO Save as preset for future projects?
- Let's get hacking!
    - Add the project to VSCode. File > Add Folder (find the folder where your new project lives, click once on it, and click "Add Folder").
    - Have a look at the README file in the base of the project folder.
    - Open a terminal (ctrl + `)
    - Since this is the first time we've gotten into the project, we will use npm install
    - npm run serve
    - If asked whether node should be able to access networks (Windows) allow access.
    - Ctrl + click the "local" web address. This will start the browser and show us the starter template.
    - [Hands-on Vue, part 1](https://dev.to/vuevixens/hands-on-vuejs-for-beginners-part-1-2j2g), by Marina Mosti
    - Git!
        - Sign up/into [GitHub](https://github.com/) (we'll be using GitHub here, but GitLab and BitBucket are two other excellent choices)
        - (on your computer) Create ssh keys
            - [Windows](https://confluence.atlassian.com/bitbucketserver/creating-ssh-keys-776639788.html)
            - @TODO Add the SSH keys to GitHub
        - (on your computer)If it's not on there already, [install Git](https://www.atlassian.com/git/tutorials/install-git) on the computer. If you are on Windows, [cmder](https://cmder.net/) is recommended.
        - In the root of your Vue project, [initialize a new project](https://help.github.com/en/articles/adding-an-existing-project-to-github-using-the-command-line)
        - If you haven't set a git name and email before, you'll need to follow the command line prompts to do that now.
