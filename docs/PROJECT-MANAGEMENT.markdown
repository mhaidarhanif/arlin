Project Management Documentation
================================

Method
------

Here we have picked the most appropriate project management method and style depending on our team member capabilities.

For Michi team, we're using Minimal Agile Kanban with GitHub and Waffle.

---

### Agile

> This principles does work

**Agile Principles** or Agile Software Development is a set of principles for software development in which requirements and solutions evolve through collaboration between self-organizing, cross-functional teams. It promotes adaptive planning, evolutionary development, early delivery, and continuous improvement, and it encourages rapid and flexible response to change.

This principles value:
- Individuals and interactions over processes and tools
- Working software over comprehensive documentation
- Customer collaboration over contract negotiation
- Responding to change over following a plan

Ref:  
- http://agilemanifesto.org
- https://en.wikipedia.org/wiki/Agile_software_development
- http://www.allaboutagile.com/what-is-agile-10-key-principles

---

### Kanban

> This method does work

**Kanban Methodologies** is a new technique for managing a software development process in a highly efficient way. It is another framework used to implement agile. Kanban underpins Toyota's "just-in-time" (JIT) production system. Although producing a software is a creative activity and therefore, different to mass-producing cars, the underlying mechanism for managing the production line can still be applied.

Ref:  
- https://www.atlassian.com/agile/kanban
- http://kanbanblog.com/explained
- http://leankit.com/learn/kanban/what-is-kanban
- http://info.leankit.com/kanban-roadmap
- https://en.wikipedia.org/wiki/Kanban
- <https://en.wikipedia.org/wiki/Kanban_(development)>

![Kanban board sample](http://leankit.com/learn/wp-content/uploads/2015/11/kanban-board-e60650d1-1.jpg)

---

### Minimal

> This method does work

**Minimal Project Management** consists of only a few steps (and one change process):

- Assignment and prioritization of work.
- A Statement of Work (SOW) to define the task or project.
- A single weekly review of progress.
- A Management of Change process.

> That’s all there is to it. The team gets to manage their own time. They know the priority and impact of the work, the dependencies, the business needs and their key deliverables as its discussed in the meeting. They know the standards expected of their work, the tests to run to be sure their deliverables are correct and the pressure we are all under.

Ref:  
- http://hiltmon.com/blog/2016/03/05/minimal-project-management

---

### GitHub Flow

> This method does work

**GitHub Flow** is a lightweight, branch-based workflow that supports teams and projects where deployments are made regularly.

Ref:  
- https://guides.github.com/introduction/flow

---

### Waffle Board

> This doesn't work well. Migrated to ZenHub.

Previously, our project management, progress documentation, and kanban board are also available on Waffle.io (https://waffle.io/gunadarma-academy/asde-michi). It automatically put all of the GitHub issues –including all of the Statement of Work (SOW) in our case– in the appropriate columns.

---

### ZenHub Board and Burndown

> This way does work.

Currently our project management, progress documentation, and kanban board are also available on through [ZenHub](http://zenhub.io). It automatically put all of the GitHub issues –including all of the Statement of Work (SOW) in our case– in the appropriate columns. Along with that, we can also see our burndown progress for each milestones.

---

### Design Sprint

> This doesn't happen. The understanding requires a lot of adjustment in successive time, a whole week without interruption at the same place.

In addition, we havee to test our ideas and app to actual users outside of us. We might consider to use design sprint method.

![Sprint Diagram](http://www.gv.com/sprint/img/sprint-diagram.png)

> The sprint is a five-day process for answering critical business questions through design, prototyping, and testing ideas with customers. Developed at Google Ventures (now just GV), it’s a "greatest hits" of business strategy, innovation, behavior science, design thinking, and more — packaged into a battle-tested process that any team can use.

> Working together with companies in a sprint, we shortcut the usual endless-debate cycle and compress months of time into a single week. Instead of waiting to launch a minimal product to understand if an idea is any good, teams get great data from a prototype. The sprint gives these companies a superpower: The ability to build and test nearly any idea in just 40 hours.

Ref:  
- http://www.gv.com/sprint

---

### Semantic Versioning

> This does work for some part.

**Semantic Versioning** is a simple set of rules and requirements that dictate how version numbers are assigned and incremented. These rules are based on but not necessarily limited to pre-existing widespread common practices in use in both closed and open-source software. Under this scheme, version numbers and the way they change convey meaning about the underlying code and what has been modified from one version to the next.

Given a version number MAJOR.MINOR.PATCH, increment the:
- MAJOR version when you make incompatible API changes,
- MINOR version when you add functionality in a backwards-compatible manner, and
- PATCH version when you make backwards-compatible bug fixes.
- Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

Ref:  
- http://semver.org

---

### Holacracy

> This does work.

Related to https://github.com/gunadarma-academy/asde-michi/issues/16, if team member roles need to be defined clearly, communicative, and informative. There's a flexible yet comprehensive guide on how to arrange our team circle of work and roles, named Holacracy. **Holacracy** is a complete system for self-organization. It brings structure and discipline to a peer-to-peer workplace.

**The Holacracy Constitution** documents the core rules, structure, and processes of the Holacracy “operating system” for governing and managing an organization. It provides the foundation for an organization wishing to use Holacracy, by anchoring the shift of power required in concrete and documented “rules of the game”, which everyone involved can rely upon.

Ref:  
- http://holacracy.org
- https://github.com/holacracyone/Holacracy-Constitution
- https://www.blinkist.com/page19/about-holacracy
- https://www.blinkist.com/page19/holacracy-explained
- https://www.blinkist.com/page19/blinkracy-ebook

---

### Continuous Integration (CI)

> This presumably will work along with automated testing.

**Continuous Integration (CI)** in software development and engineering is the practice of merging or integrating all developer working code and copies with a shared repository/mainline several times a day. Each check-in is then verified by an automated build, allowing teams to detect problems early. CI is very frequently accompanied by **Continuous Delivery/Deployment (CD)** and very often when people talk about CI they refer to both.

CI relies on two main principles:

1. Changes are merged to main source branch as often reasonably possible. The tasks are explicitly split up in such a way so that to avoid creating gigantic change sets.
2. Each change is fully tested. Automated testing is the cornerstone of CI. In a team environment, and even on a personal project, it’s nearly impossible to insure that latest changes don’t break existing code without tests. Every time a change set is merged to master, CI runs entire suite to guarantee nothing was impacted negatively.

Ref:  
- https://strongloop.com/strongblog/node-js-travis-circle-codeship-compare
- http://devops.com
- https://travis-ci.org
- https://circleci.com
- https://codeship.com
- http://wercker.com
