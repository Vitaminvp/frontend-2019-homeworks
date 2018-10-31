[![MIT Licensed][icon-mit]][license]
[![Kottans-Frontend][icon-kottans]][kottans-frontend]
#  Frontend 2019 course homeworks
This repo was created for students to submit their homeworks for review. 

### How to submit
- fork this repository
- clone the your fork to your local machine: 'git clone tream https://github.com/YOUR_NUSERNAME/frontend-2019-homeworks.git`
- add this repository as an upstream: 'git remote add upstream https://github.com/kottans/frontend-2019-homeworks.git`
- in your local repository, add a folder with your github name under  `submissions` (if you haven't yet)
- in your local repository, under your name folder, add a folder with task name and put your code in the folder

  See example file structure you are expected to have below:

  ![File structure example](img/file-structure.png)

- make pull-request to this repository following these steps:
  - create new branch, name it according to task performed (aka feature branch): `git checkout -b dom-api-task`. In this example feature branch is called `dom-api-task`
  - commit your changes to newly created feature branch
  - checkout `master` branch: `git checkout master`
  - pull latest changes from upstream `master` branch: `git pull upstream master`
  - merge `master` branch into your feature branch: `git checkout dom-api-task && git merge master`
  - resolve any merge conflicts if there are any
  - push feature branch to your remote repository: `git push origin dom-api-task`
  - make pull-request from your repository to this repository via GitHub web-interface
- wait for review from course mentors
- if necessary, make changes, until your code will be approved and merged

[icon-mit]: https://img.shields.io/badge/license-MIT-blue.svg
[license]: https://github.com/OleksiyRudenko/a-tiny-JS-world/blob/master/LICENSE.md

[icon-kottans]: https://img.shields.io/badge/%3D(%5E.%5E)%3D-frontend-yellow.svg
[kottans-frontend]: https://github.com/kottans/frontend
