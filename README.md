# Set Up Your Computer for VueJS

- Set up Node, NPM (NVM? Or just mention it?), VSCode + Extensions, Vue, Vue CLI

Tech to Set up

- Node ([Node.JS](https://nodejs.org/en/download/))
    - What is Node? ([Wikipedia](https://en.wikipedia.org/wiki/Node.js))
    - Open terminal, check node -v
    - If you install node on Windows, then it will come with npm
- NPM
    - What is NPM? ([Wikipedia](https://en.wikipedia.org/wiki/Npm_%28software%29))
    - [NVM](https://github.com/creationix/nvm) exists, and you might want to use it (but we won't do that now)
- VSCode
    - Extensions
        - [Sarah Drasner's Extension Pack](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-extensionpack)
        - [Extras: Gift's Recommendations](https://dev.to/lauragift21/a-collection-of-essential-vscode--extensions-26al) (goes beyond Vue)
- Vue
    - Vue CLI
        - What do each of the options mean?
            - [Babel](https://babeljs.io/docs/en) - Makes your newer JavaScript work with older versions of JavaScript.
            - [TypeScript](https://www.typescriptlang.org/index.html) - A programming that includes JavaScript, but has extra features (most importantly [strong typing](https://en.wikipedia.org/wiki/Strong_and_weak_typing)). They call it a "superset of JavaScript."
            - [Progressive Web App support](https://en.wikipedia.org/wiki/Progressive_web_applications) - Helps your site act like a native app on the device, most notably it lets you use the app offline.
            - [Router](https://router.vuejs.org/) - Mostly we think of it as helping you to create multiple linked pages within your single page application ("routes"), but Vue Router does a bunch of other things too!
            - [Vuex](https://vuex.vuejs.org/) - Helps to manage "state" in your application. It stores some data that you may want to view and manipulate, and it makes sure you're manipulating that data in a safe way.
            - [CSS Preprocessors](https://developer.mozilla.org/en-US/docs/Glossary/CSS_preprocessor) - Compiles CSS extension languages such as SASS (like CSS but with more features) down to CSS.
            - [Linter](https://en.wikipedia.org/wiki/Lint_(software)) - Analyzes your code for errors, and alerts you to what and where, roughly, the errors are.
            - [Unit Testing](https://vuejs.org/v2/guide/unit-testing.html) - Lets you choose from [Jest](https://github.com/facebook/jest) or [Mocha](https://mochajs.org/) frameworks to test chunks of code in your app.
            - [E2E Testing](https://dev.to/lambdatesting/all-you-need-to-know-about-end-to-end-testing-4nbb) - Short for "[End to End Testing](https://vuejsdevelopers.com/2019/04/01/vue-testing-unit-vs-e2e/)," [Cypress](https://www.cypress.io/)/[Nightwatch](http://nightwatchjs.org/) are set up so you can test how your app works overall (e.g., What happens if you log in with an invalid email address?)
- Let's get hacking!
    - [Hands-on Vue, part 1](https://dev.to/vuevixens/hands-on-vuejs-for-beginners-part-1-2j2g), by Marina Mosti
    - Git!
        - Sign into GitHub or GitLab
            - Make a new project
        - Install Git on the computer
        - Git init
        - Paste GH commands
        - Add name and email
        - Create ssh keys
