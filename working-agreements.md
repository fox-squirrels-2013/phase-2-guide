# Working Agreements
Working agreements are rules followed by everyone on a team. There are three
mandatory working agreements for group projects in week 1:

1. [Master Stays Green](#master-stays-green)
1. [What and Why](#what-and-why)
1. [Always Be Pull Requestin'](#use-pull-requests)
1. [Deploy early, deploy often](#deploy-early-deploy-often)

## Master Stays Green
Before merging, ensure you have not broken previous functionality. Your tests
are there to ensure functionality remains working.

1. Run your tests before merging.
1. Have a really good reason for deleting or pending out a test.
1. Add tests when functionality breaks and the tests stay green.

## What and Why
Every single team member must be able to answer two questions about every
single line of code in the project:

  * "What does this line of code do?"
  * "Why does this line of code exist?"

If you understand something another team member doesn't, it's your
responsibility to help them understand it.

## Use Pull Requests
Pull requests:
1. Provide a natural pause for you to check in with your team
1. Ensure that your code is reviewed by an instructor

So do pull requests. Seriously.

Every good pull request:
1. Provides 1 user-perceptible feature
1. Including the tests, models, routes, migrations, and views
1. Are ran locally and played with on someone elses computer before being merged
1. Are merged by someone who didn't have a hand in writing the code


## Deploy Early, Deploy Often
Ideally, each pull request should be deployed to Heroku immediately after merge.
You may choose to wait until you've completed all the requirements in your
projects release, however.

