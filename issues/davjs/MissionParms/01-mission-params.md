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

## How you can help

In order to foster a community that is welcoming for open source contributions, it is important for us to have good test coverage. And good tests are simple, readable tests.

Here is a good opportunity to simplify one of our tests.

### The Issue

In `src/ride-hailing/MissionParams.test.ts` we defined the following parameters at the beginning of the `describe()` block.

```javascript
const missionParams = new MissionParams({});

const serializedMissionParams: any = {
    ttl: undefined,
    protocol: 'ride_hailing',
    type: 'mission',
    price: undefined,
    vehicleId: undefined,
};
```

These parameters will need to accommodate new tests. 

Please update these parameters to be more dynamic by defining them to be mutable similar to `src/vessel-charging/MissionParams.test.ts`.

![Parameters][parameters]

After making your changes, make sure the tests still pass by running `npm run jest`

### Contributing to dav-js

- [ ] Make sure this issue is labeled `up-for-grabs` and not labeled `claimed`, to verify no one else is working on it.
- [ ] Comment in this issue that you would like to do it.
- [ ] Open [dav-js GitHub page](https://github.com/DAVFoundation/dav-js) and click the ★ Star and then ⑂ Fork buttons.
- [ ] Clone a copy to your local machine with `$ git clone git@github.com:YOUR-GITHUB-USER-NAME/dav-js.git`
- [ ] Install dependencies by running `npm install`
- [ ] **Code Code Code**
- [ ] Once you've made sure all your changes work correctly and committed all your changes, push your local changes back to github with `$ git push -u origin master`
- [ ] Visit your fork on GitHub.com ([https://github.com/YOUR-USER-NAME/dav-js](https://github.com/YOUR-USER-NAME/dav-js)) and create a pull request for your changes.
- [ ] Make sure your pull request describes exactly what you changed and references this issue (include the issue number in the title like this: `#7`)
- [ ] Please do not fix more than one issue at a time. Your pull request should only fix what is described in this issue.

### Asking for help

We appreciate your effort in taking the time to work on this issue and help out the open source community and the foundation. If you need any help, feel free to ask below or in our [gitter channel](https://gitter.im/DAVFoundation/DAV-Contributors). We are always happy to help 😄

[parameters]: https://raw.githubusercontent.com/mariolo1985/Simply-Paging/fix/controlstyle/demo/images/demo_sm.gif "Update Parameters"

