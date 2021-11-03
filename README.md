# Coding 101 - Unit Testing

# Setup

[Fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) this repository

Create a [new branch](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-and-deleting-branches-within-your-repository) - name it whatever you like, but note it down!

[Clone](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) to your local machine

On your local machine, `cd` into the directory created for your clone and switch to your new branch using the command:

`git checkout <branchname>`

## Challenge

1. Build out the ./force-app/main/default/OpportunityUtils_Test.cls class to cover all scenarios you can identify. Note that 100% test coverage does not indicate all scenarios are covered! Check all of your unit tests pass before submitting your solution. There are a couple of ways of doing this.

### Notes
The following Trailhead modules are available to learn more about unit testing in Apex:

* [Apex Testing](https://trailhead.salesforce.com/en/content/learn/modules/unit-testing-on-the-lightning-platform)
* [Unit Testing on the Lightning Platform](https://trailhead.salesforce.com/en/content/learn/modules/unit-testing-on-the-lightning-platform)

## Implementing

Carry out all work in your local filesystem using VS Code, as you will 
need to send them back to Github.

1. Create a scratch org (or connect to an existing one)
1. Push the code to your scratch org - this will check that your code compiles
2. Execute the tests - this will check that your tests are doing what you think they are

## Submitting Your Solution for Assessment

Please note that assessment is only available to BrightGen employees or by prior arrangement with Keir Bowden (aka Bob Buzzard). If you don't satisfy this criteria your pull request will not be reviewed.

Add `keirbowden` as a [collaborator](https://docs.github.com/en/github/setting-up-and-managing-your-github-user-account/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository) to your new repository

The commands below are if you are using Git from the command line - you can also use the VS Code built-in [source control functionality](https://code.visualstudio.com/docs/editor/versioncontrol).

Stage your updated class using the following command: 

`git add force-app/main/default/classes`

and then commit the changes :

`git commit`

and push these to the remote repository

`git push origin <branchname>`

Once you are happy with your solution, [open a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request)

Then wait!

