# Code insights team

The code insights team will be responsible for building and delivering code insights to engineering leaders, empowering data-driven decisions in engineering organizations.

<img src="./screenshot.svg" alt="Screenshot of a code insights dashboard with graphs" />

## What is code insights?

Code insights is the first feature in Sourcegraph that can tell you things about your code at a **high level**.

Code insights dashboards will answer questions like "How is a migration progressing?", "What areas of the code are most vulnerable to bugs?", and "How many developers are using a specific API?" Code insights will also incorporate third-party data like code coverage or static analysis metrics to deliver on the promise of aggregating everything you can know about your code.

Sourcegraph is in the unique position to give these insights because we have universal code search: to know _anything_ about your code at a high level confidently means you must know _everything_ about your code at a low level.

Code insights connects many features that Sourcegraph already has and builds on top of them.
We go beyond single-step code intelligence and search to connect the full cycle of analyzing (code intelligence), monitoring (code insights), and actionably changing a codebase (campaigns).

Code insights is the first feature primarily built for non-search-based user personas (developers), instead focusing first on the needs of engineering directors and VPs.

For more information about code insights, see the original [product document](https://docs.google.com/document/d/1EHzor6I1GhVVIpl70mH-c10b1tNEl_p1xRMJ9qHQfoc/edit) or this [demo](https://www.youtube.com/watch?v=XqeRb6Mc4Co) of a code insights prototype. Anyone on the Sourcegraph team can create your own insight using the [quickstart guide](https://gist.github.com/Joelkw/f0582b164578aabc3ac936dee43f23e0), which is explicitly not in the Sourcegraph docs because code insights is undergoing rapid development and this setup will soon change. 

## Contact
- [#code-insights](https://sourcegraph.slack.com/archives/C014ZCKMCAV) channel or @codeinsights in Slack.
- [team/code-insights](https://github.com/sourcegraph/sourcegraph/issues/new?labels=team/code-insights) label on GitHub.

## Goals and roadmap

[Goals and roadmap](goals.md)

The code insights team also keeps a [backlog GitHub project board](https://github.com/orgs/sourcegraph/projects/118). We use the backlog for tracking bugs, small features, and unplanned work. We don't use the backlog for tracking work that is expressly planned in our [roadmap](goals.md#roadmap).

## Members

- [Joel Kwartler](../../../company/team/index.md#joel-kwartler-he-him) ([Product Manager](../../../product/roles/index.md#product-manager))
- [Alicja Suska](../../../company/team/index.md#alicja-suska-she-her) ([Product Designer](../../../product/roles/index.md#product-designer))
- [Felix Becker](../../../company/team/index.md#felix-becker) ([Engineering Manager](../../roles.md#engineering-manager)) {#code-insights-eng}
  - V. K. starting 2021-03-22
  - FQ1 [backend engineer](https://jobs.lever.co/sourcegraph/5a25e568-575a-4209-b887-05f914ff0650)
  - [Valery Bugakov](../../../company/team/index.md#valery-bugakov-he-him) (joins from Frontend Platform in FQ2)

## Processes

### Communication

We recognize that frequent, open communication is key to the success of our team, especially in an all-remote environment.
We default to asynchronous communication in Slack and GitHub issues over other mediums (video calls, emails) as we are respectful of our teammates' time. 

The team communicates in the following channels in Slack:

[**#web-chat**](https://sourcegraph.slack.com/archives/CMT39K56Z): All work related commmunication happens in this channel. This is also the primary channel for teammates outside of the team to reach out to us.

[**#web-team**](https://sourcegraph.slack.com/archives/C01EM5J1NF8): Our daily standups (facilited through Geekbot) go into this channel as well as all non-work related commmunication. Random conversations, banter, jokes etc. are all welcome here. 

[**#web-onboarding**](https://sourcegraph.slack.com/archives/C01K7TKKR09): This channel is dedicated to questions or thoughts that new teammates have while they onboard. It's a safe space to simply think out load and the goal is to identify things that we can improve and things we should make more clear in the handbook.

#### Daily Slack updates

Collaborating across timezones requires regular communication to keep each other updated on our progress, and coordinate work handoff if needed. We also use this opportunity to build camaraderie between team members by sharing some non-work related aspects of our lives with each other.

We use [Geekbot](https://geekbot.com/) to facilitate all this and these updates are purely for coordination within the team (as opposed to for external stakeholders). At the start of each working day, Geekbot will ask each teammate a set of questions and the responses will be posted in the #web-chat Slack channel.

All teammates are expected to be part of this channel, and should read the updates, to learn what your teammates have been working on, and check if they need your help.

### Backlog

The web team keeps a backlog GitHub project board for each of our focus areas: [frontend platform backlog](https://github.com/orgs/sourcegraph/projects/117) and [extensibility backlog](https://github.com/orgs/sourcegraph/projects/116). 

We use the backlogs for tracking bugs, small features, and unplanned work. We don't use the backlog for tracking work that is expressly planned in our [roadmap](goals.md#roadmap). 

To add an issue, tag it `team/web` to notify the web team PM and put it in the "to triage" column of the board. Unless you're directly asked, only web team members should move issues out of the "to triage" column on the board. A web team member will confirm the issue is web team-related, and then move it to the appropriate column.

#### Tracking Issues
The web team makes use of [tracking issues](../tracking_issues.md) for tracking progress on the implementation of new features. The web team should ensure that a tracking issue is created when starting work on features that are expected to take longer than a single iteration to deliver.

#### Product Feedback

Specific product feedback about well-defined, small features can be found directly in the backlog boards. More general product feedback that applies to larger features, or that needs more research and planning to be actionable, is kept in Productboard, separated by focus area: [extensibility feedback](https://sourcegraph.productboard.com/feature-board/2330167-web-extensibility) and [frontend platform feedback](https://sourcegraph.productboard.com/feature-board/2330177-web-frontend-platform). 

### Iterations

The web team has a large ownership area, so the team creates a focused plan each iteration, by agreeing on an appropriately small set of [iteration goals](../../../company/goals/index.md).

We plan our work in **2-week iterations**.

Our goals for the current and past iterations can be found in our [iteration goals living Google Doc](https://docs.google.com/document/d/1n9WKjieKmd2YYkNrEsOfdmxRYUrbowLWjq05phLoQ6s/edit).

The individual tasks and progress of the current iteration can be found as GitHub issues in our [GitHub project board](https://github.com/orgs/sourcegraph/projects/45?fullscreen=true), with estimate labels and assignees.
At the beginning of an iteration, we fill the "Planned" column with all issues we want to accomplish by the end of the iteration and make sure they have estimates and assignees.
Each issue should be as small as possible.
Over the course of the iteration, we strive to close issues with small, iterative pull requests that we review and merge timely (generally a day).
By the end of an iteration, all issues should be in the "Done" column and the board gets emptied.

#### Iteration planning

To ensure the team can be productive right from the start of an iteration we start planning for our next iteration as soon as a new iteration starts.

1. First week of the iteration
   1. The EM & PM will add tasks that should be considered for the iteration throughout the week.
      1. Tasks are added to the [Iteration planning scratchpad](https://docs.google.com/spreadsheets/d/1PKxOps4AWlqdI-H2eKSRzNhw4XT-oiwOpKF4UdN_1b8/edit); a spreadsheet we use to propose work items for the upcoming iteration
      1. The PM will focus on adding items that are aligned with our roadmap so that we keep working towards our goals
      1. The EM will focus on adding bugs and tech debt issues to ensure we maintain a high quality code base and product.
   1. The EM & PM work on getting all tasks to a "Ready for dev" status.
      1. A "Ready for dev" status means that all the necessary information has been captured or prepared so that the engineer taking up the issue can essentially start working on it immediately.
         1. This does not involve figuring out implementation detail, as we do not tell engineers how to execute a task, but rather tell them the problem and make the requirements clear, and then ask them to figure out the best way to implement the solution.
         1. We don't block on design dependencies for a task, but try to identify any dependency early on and communicate this requirement to the product designer.
   1. The PM identifies and communicates design input needed from the Product Designer and works to prioritize it with them.
1. Second week of the iteration
   1. By the Wednesday, the EM and PM should have ensured that:
      1. All planned work have refined issues in GitHub and are added to the 'Next iteration' column on the backlog board
      1. All issues are in a "Ready for dev" state
      1. All issues have effort estimates and have been prioritized
      1. The team’s available capacity for the next iteration is known.
         1. A teammates capacity is calculated at 80% of the iteration days - vacation days.
   1. On the Wednesday, the teammates are invited to review the planned iteration scope and to provide feedback.
   1. On the Thursday, the EM and PM will have a sync call to finalize the next iteration’s scope. In determining the iteration scope they will factor in:
      1. The priority
      1. The effort estimate
      1. The available capacity of the team
      1. Any left over issues that won't be complete from the prior iteration, and whether those issues should still be prioritized next iteration or moved to a backlog category.
      1. Feedback from the teammates
   1. The PM will prepare the current iteration project in GitHub with the relevant issues.
   
#### Progress monitoring

We monitor the progress of the work in an iteration in the following ways:
1. Iteration: The overall iteration progress is monitored through a GitHub project board (See [Iterations](#iterations).)
1. Tracking issue: If a feature is made up out of multiple issue we use a tracking issue to keep track of its progress. (See [Tracking issues](#tracking-issues).)
1. Pull request: The implementation of a feature is tracked through a checklist in description of the pull request.  (See [PR template](https://github.com/sourcegraph/sourcegraph/blob/main/.github/PULL_REQUEST_TEMPLATE/pull_request_template.md).)

### Updates

We do regular updates to communicate our progress to members of the team, and to external stakeholders.

### Retrospectives

After each iteration, we hold a sync retrospective meeting to reflect on the past iteration. We use this meeting to:

- Review the previous retro’s action items to ensure we hold teammates accountable for actioning them
- We give _Shoutouts!_ to teammates to show appreciation for something they did that we appreciated.
- Discuss things that went well in the past iteration and that we should do more of / invest more into it.
- We discuss the things that could have gone better and what we can learn from it to improve.
- We talk about processes that we should revisit/refine/propose to improve our efficiency?

We capture and assign actions to teammates to action. Teammates should consider actions coming out of the retrospective as a very high priority.

Teammates contribute to the retrospective asynchronously during the iteration by adding their thoughts to our [retrospective document](https://docs.google.com/document/d/1YW45Dksk0vIn7drhatwLyo6YbMMkS-naHcuShUi1OOw/edit). Teammates are highly encouraged to comment on points raised before the sync meeting in the document.

We rotate who leads the retrospective to allow all teammates an opportunity to lead the session. Teammates can find the rotation schedule at the top of the [retrospective document](https://docs.google.com/document/d/1YW45Dksk0vIn7drhatwLyo6YbMMkS-naHcuShUi1OOw/edit). 

### Code reviews

The team follow's the [default code review guidelines](https://docs.sourcegraph.com/dev/background-information/code_reviews) with the following addition:

1. If the author would like any of the requested reviewers to merge the PR after approval they add the label `merge-on-any-approve`
1. If the author would like their PR to be merged once all of the requested reviewers have approved it they add the label `merge-on-all-approve`

## Team syncs

The web team holds weekly syncs.

The meeting notes of web team syncs can be found [in this doc](https://docs.google.com/document/u/1/d/1IUsjbtYdGiAHvRUB1yf4eqnynin9WsxFR2zFCMm78jw/edit#).

Before web team syncs, teammates and stakeholders should write down under "Discussion items" in the meeting notes document anything that they'd like to bring up for discussion with the whole team.

## Hack time

The web team engineers hold a weekly "hack time" session: a scheduled block of time dedicated to pair programming (or, more accurately, crowd/mob programming) on a task together as a team.

The reasons why we do hack time as a team:

- it lets the team share knowledge and context
- it builds shared ownership over the work
- it's also an opportunity to discuss ideas and socialize

The team chooses a tasks (or topic) for hack time in advance, in order to avoid spending time deciding what to work on at the beginning of the session. The process is:

- A weekly Slack reminder in the `#web-team` channel creates a thread for the team to propose ideas for the next hack time.
- By default, if the work from the last hack time session was unfinished, then the team continues on that work.
- If no task has been proposed by the time that the hack time session starts, and there's no task to continue from last time, then that session is cancelled.