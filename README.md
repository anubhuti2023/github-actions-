# Github-Actions for Beginners
A series of basic workflows important for learning basic github actions.


# What is Github Actions?
GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline. You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.

# Components of Github Actions
1.) Workflows: Workflow is an automated process that runs one or more jobs. It is written in YAML Format and will run when triggered by an event in your repository, or they can be triggered manually, or at a defined schedule.
Workflows are defined in the .github/workflows directory in a repository, and a repository can have multiple workflows.

2.)Events: An event is a specific activity in a repository that triggers a workflow run . For example,when someone creates a pull request, opens an issue, or pushes a commit to a repository.<br>
For a complete list of events that can be used to trigger workflows,<br>
visit -> `https://docs.github.com/en/actions/using-workflows/events-that-trigger-workflows`.

3.)Jobs: A job is a set of steps in a workflow that is executed on the same runner. Each step is either a shell script that will be executed, or an action that will be run.

4.)Actions: An action is a custom application for the GitHub Actions platform that performs a complex but frequently repeated task. Using an can action to help reduce the amount of repetitive code that you write in your workflow files.

5.)Runners: A runner is a server that runs your workflows when they're triggered. Each runner can run a single job at a time. GitHub provides Ubuntu Linux, Microsoft Windows, and macOS runners to run your workflows; each workflow run executes in a fresh, newly-provisioned virtual machine.

You can visit : `https://docs.github.com/en/actions/learn-github-actions/understanding-github-actions` for more knowledge on the same.

You can create end to end CI and CD automated builds with Github Actions .<br>
CI-build: your CI build should have the unit tests or any kind of tests you want to run for your project <br> 
CD-build: Your CD build should have the code may it be a docker image or any kind of helm deployments where you deploy to lower or higher envrionments based on your needs which would ensure Continuous Deployment

For learning Github-Actions extensively ,you can go through this course available on Udemy -> `https://fico.udemy.com/course/github-actions/`

