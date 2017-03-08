# Handbook

### Contents

- [Products](#products)
 - [Full Apps]()
 - [Design]()
 - [Development]()
- [Communication](#communication)
 - [Internal Communication](#internal-communication)
 - [Chat](#chat)
 - [Video Calls](#view-calls)
 - [Google Docs](#google-docs)
- [Meetings](#meetings)
 - [Weekly Meeting](#weekly-meetings)
 - [Daily Meeting](#daily-meeting)
 - [Release Retrospective](#release-retrospective)
- [Engineering](#meetings)
 - [Continuous Integration](#continuous-integration)
 - [Pair programming](#pair-programming)
- [Workflow](#workflow)
- [Tools and Tips](#tools-and-tips)

----

## :bento: Products

Caramba offers to the world 3 different kind of products: Full App Experiences, App Design and App Development. In the branches of App Design and App Development there are a lot of sub-products.

### Full Apps

Full App experiences are products that start from just and idea or briefing and end up beeing amazing digital products shipped in a Store.

### App Design

App Design includes a lot of different products.

##### Branding
TBD
##### User Experience
TBD
##### Prototyping
TBD
##### User Testing
TBD
##### User Interface
TBD
##### Interaction Design
TBD

### App Development

We consider these the most important areas in App Development. We share our knowledge with our client to make their products better.

##### Consulting

We love what we do and for that reason we love to talk, debate and discuss about anything related with Apps. (TBD)

##### Arquitecture

Any App end up being a complex piece of software with millions of lines of code. How all these lines of code are organized and structured is really important for the future of the App and the health of the engineers. We love to design architectures fully adapted to specific Apps.

##### Integrations

Integrations are important, there are tones of great services out there that can be used to power up an App. Integrate Facebook to share workout activities, integrate Fabric to report crashes and usage metrics, integrate BuddyBuild to distribute a beta or receive feedback, integrate AppBoy to launch in-app marketing campaigns, integrate Zendesk to provide in-app support. The possibilities are infinite and we can help a client to integrate them.

##### Automation

Process automation saves a lot of time and we love to **automate all the things**!
Almost everything can be automated through scripts. Process like deploy and distribute a Beta, publish a new version in the Store, check that a Pull Request doesn't break anything. There is tones of things that can be automated and we love to automate them all!

##### Sharing Knowledge

Experiences and knowledge must be shared, it's the only way to grow. We love to share what we've learnt so far. We can organize talks or workshops designed for the client needs.

## :mailbox: Communication

### Internal Communication

1. All written communication happens preferably in English, because sometimes you need to forward an email or chat.
2. Use **asynchronous communication** when possible (issues and email instead of chat), issues are preferred over email and email is preferred over chat. People should not be interrupted by chat unless it's completly necessary.
3. Direct your communication to your target and avoid make unnecessary noise to others.
4. If any decision is taken in chat or offline make sure those decisions are reflected in the corresponding issue.

### Chat

We use Slack for chat communications, the url is `carambastudio.slack.com`. These are the channels we use:

[WIP: define channels]
- General
- Bussiness
- Social Mentions
- Development
- Design
- Growth
- ...

### Video Chats

We use [appear.in](http://appear.in) for video call communications. We have a blocked room: [appear.in/caramba](http://appear.in/caramba)

1. Make sure you have an appear.in account and you are invited as member of caramba room.
2. Install appear.in chrome extensions to get push notifications and be able to share the screen.

### Google Docs

[WIP]

## :microphone: Meetings

### Weekly Meeting

1. We have a team call once a week where we review previous week work and planning work for the next week. In this meeting we also address general stuff related to the studio.
2. The schedule of this meeting is: UTC+1 TBD - TBD Monday
2. Make sure you add anything you want to address in the weekly meeting to this document: WIP

### Release Retrospectives

[WIP]

## Engineering

### Open Source
At Caramba we embrace the open value whenever it's possible, for example, when it's not a project for a client. Some examples of good candidates for open sourcing would be: command line tools, example apps and libraries. Before deciding for open sourcing a project, it should be proposed to the team, and once decided, the project should commit to these guidelines:

- The project should include a `LICENSE` file. By default, we'll share the projects with the [MIT License](https://opensource.org/licenses/MIT).
- The project should include  `README` file with:
  - A section explaining what the project is about and why a developer would need/use it.
  - A list with the project features *(the language, the platform, what makes the project unique..)*.
  - Steps to setup the project locally and start contributing. These steps should be as simple as possible to make it easier for developers to contribute. You can use bash scripting or rake for that.
  - A section at the bottom about Caramba. You can copy it from another open source repository.
  - A few examples that show how to use the project.
  - If you used external resources, like articles, documentation, libraries, include them in a references section.
- Dependencies should be explicit in a dependencies file. For example, if you use Ruby .dependencies, specify them in a `Gemfile`. Similarly with CocoaPods and the `Podfile`, and npm and its `package.json`.
- It should include a continuous integration setup that builds and runs the project tests. If the CI service provides a badge, include it at the top of the `README` file.
- Issues should be enabled.
- Enable the Wiki only if there's content, otherwise keep it closed.

### Continuous Integration

Depending on the project we use the following continuous integration setups:

##### Open Source projects
If it's an open source project we use [Travis-CI](https://travis-ci.org). Contributors can access the build outputs and debug builds by themselves. When a new repository gets integrated with Travis, the build badge should be added to the `README.md` of the project to show the state of master.

##### Private projects
For private projects we use [Jenkins](https://jenkins.io). As engineer of Caramba, you should have been given the CI server acces data. [Caramba](https://github.com/carambalabs) GitHub organization is scanned periodically by Jenkins. Whenever a new repo is added with a [Jenkinsfile](https://jenkins.io/doc/book/pipeline/jenkinsfile/), Jenkins will index it and try to build it.

You can find some examples of `travis.yml` and `Jenkinsfile` by exploring the organization repositories.

Any engineer at Caramba is responsible for ensuring a good state on CI platforms. If you find a broken build, or you broke by yourself you should fix it to prevent the  team or contributors from getting blocked by a broken CI.

### Pair programming

When any coding work needs help from two or more people we should encourage pair programming on the task. With more than one person working on the same issue, the quality of the work is higher and it's easier to identify issues in the implementation. Try to pair with someone that has more context on the issue that you are currently working on.

If you are in remote, there's a tool, [Screenhero](https://screenhero.com/) that makes it possible. If you don't have account, ask to anyone in the team for one. With the tool you can share one's screen, and both control the keyboard and the mouse.


## Tools and Tips

[WIP] Investigate or explain:
Calendly, Shush, Disabling OS X Notification Center, Zoom, Email Signature,
Appear.in, One Tab, Quitter, Trip Mode
