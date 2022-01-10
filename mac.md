# Setting Up Your Computer

Welcome to day 1 at BloomTech, today we are going to spend time setting up your computer and learning the tools that you will be using to complete this program. Just like day 1 at a job, you will need to get your environment set up to build and run your code. Complete the set up tasks below and then get started on the research questions. Once you have finished check out the submission instructions in the `README.md` file to turn in your assignment for the day. 

## Set Up Tasks 
1. [X] [Download xcode](https://apps.apple.com/us/app/xcode/id497799835?mt=12) - these are your developer tools for mac 
2. [X] sign up for a [GitHub account](https://github.com/join) - please use a professional username. We recommending using your `firstname` `lastname`
3. [X] [Set up your SSH key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) - GitHub uses SSH to keep their files secure. You will need to set up one SSH key for every computer that you want to access your GitHub account on. Please ensure you go through all of the steps to generate a new key, add a new key and test your connection.
4. [X] [Download Zoom](https://zoom.us/download) - make sure your zoom display name is your `first name` `last name`
5. [X] [Download Slack](https://slack.com/help/articles/207677868-Download-Slack-for-Mac) - make sure your slack display name is your `first name` `last name` 
6. [X] [Download VS code](https://code.visualstudio.com/download) - this will be the tool you use to write all of your code. We recommend installing the following extensions: 
- [ES Lint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
7. [X] [Download Node.JS](https://nodejs.org/en/) - Please download the latest stable version. We will be using Node.JS to run the tests in all of our javaScript assignments. Test driven development is a common practice in the world of web dev. You can read more about it [here](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/) 
8. [X] Sign up for a free [codepen account](https://codepen.io/accounts/signup/user/free)
9. [X] Sign up for a free account on [Lucid Chart](https://www.lucidchart.com/pages/landing?utm_source=google&utm_medium=cpc&utm_campaign[…]tTwOoXp_lCeLTC97pikTFa5cE58FWHwjjpTSGsGPRqR2AAaAh-MEALw_wcB)

## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You can type your answer below the questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en) doc short for documentation are the instructions on how to use a languge, or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your google skills. 

1. What is git? What is the difference between git and GitHub?
    Git is framework of organizing versions of software locally, and across teams. Git and Github differ in the fact that Git it the process by which versions are managed, and Github is a hosting party enabling teams to be able to access those versions/files universally. 
2. Why do we create a branch? 
    Creating a branch is a key function of Git, allowing the users to work within a separate flow of the main file. We at Bloom Tech do this as a way of managing the large class of students, but in real world application, branches will be used to do things such as build out different features of a software. 
3. What is the purpose of a pull request? 
    A pull request exists to aid in collaboration across projects, as an indicator that a change has been made at a given branch. From this pull request teams can give feedback, as well as merge that branch to the main file. 
4. What is the command you can use to switch between branches? For example you are working on a feature branch and you want to switch back to main. 
    To switch between branches use the [git checkout 'destination'] command, whereas the destination is the name of the main branch. You can also use the [git checkout -] to navigate back to main. 
5. Explain the difference between `git fetch`, `git merge` and `git pull` what does each command do? 
    git fetch: receives branches from remote location, and uploads them to the local machine. Does not change local code. 
    git merge: Functionality to merge multiple branches together.
    git pull: Initially fetches, and then merges back to main. 

    Git fetch will only receive remote updates, Git merge will combine the branches of your choosing, and git pull will automate this process, by fetching updates from the master and merging branches. 
6. What is a merge conflict? How do you resolve a merge conflict? 
    A git merge conflict happens when there is conflicting code within the master, and a branch that is attempted to be merged. This can be resolved be simply removing the conflicting code from the branch or the master. 
