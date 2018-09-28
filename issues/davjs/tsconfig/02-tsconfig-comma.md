## first-timers-only

This issue is tagged :octocat: **first-timers-only**. It is only for people who have never contributed to open source before, and are looking for an easy way take their first steps.

Consider this your chance to dip your toe into the world of open-source, and get some bragging rights for writing code that makes drones fly, lets cars find charging stations, helps people and goods get from place to place, and more.

Find more **first-timers-only** issues from DAV Foundation [here](https://github.com/search?q=first-timers-only+org%3ADAVFoundation+label%3A%22up-for-grabs%22&state=open&type=Issues).

Thank you for your help :heart:

## What is this project? 

DAV (Decentralized Autonomous Vehicles) is a new foundation working to build an open-source infrastructure for autonomous vehicles (cars, drones, trucks, robots, and all the service providers around them) to communicate and transact with each other over blockchain.

As an organization that believes in building a large community of open-source contributors, we often create issues like this one to help people take their first few steps into the world of open source.

### dav-js

This repo contains the DAV JavaScript SDK. This SDK allows developers to build applications and servers that connect to the DAV network. For example, allowing a drone to find charging stations, or an autonomous car to ask for traffic data.

### The Issue

At the root level, we have a file named `tsconfig.json`. The JSON object contains trailing commas that makes it an invalid JSON object.

![Comma][comma]

Please remove the trailing commas highlighted in the screenshot above. 

> These highlights can be toggled with **ES Lint** by setting a rule for __comma-dangle__.

### Contributing to dav-js

- [ ] Make sure this issue is labeled `up-for-grabs` and not labeled `claimed`, to verify no one else is working on it.
- [ ] Comment in this issue that you would like to do it.
- [ ] Open [dav-js GitHub page](https://github.com/DAVFoundation/dav-js) and click the ★ Star and then ⑂ Fork buttons.
- [ ] Clone a copy to your local machine with `$ git clone git@github.com:YOUR-GITHUB-USER-NAME/dav-js.git`
- [ ] **Code Code Code**
- [ ] Once you've made sure all your changes work correctly and committed all your changes, push your local changes back to github with `$ git push -u origin master`
- [ ] Visit your fork on GitHub.com ([https://github.com/YOUR-USER-NAME/dav-js](https://github.com/YOUR-USER-NAME/dav-js)) and create a pull request for your changes.
- [ ] Make sure your pull request describes exactly what you changed and references this issue (include the issue number in the title like this: `#7`)
- [ ] Please do not fix more than one issue at a time. Your pull request should only fix what is described in this issue.

### Asking for help

We appreciate your effort in taking the time to work on this issue and help out the open source community and the foundation. If you need any help, feel free to ask below or in our [gitter channel](https://gitter.im/DAVFoundation/DAV-Contributors). We are always happy to help 😄


[comma]: https://raw.githubusercontent.com/mariolo1985/opensource-issue-list/newissue/tsconfigComma/issues/davjs/tsconfig/trailingcomma.png "Trailing Commas"
