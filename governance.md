# Brigade Governance

The following document describes how the Brigade project governance operates.

## The Brigade Project

The Brigade project is made up of several codebases with different release cycles. These codebases include:

- Brigade
- Kashti
- gateways, libraries, and integrations

There are two levels of maintainers for Brigade: org maintainers and project maintainers. Project maintainers focus on a single codebase or a group of related codebases. For example, a gateway maintainer manages a gateway repository or a utility project has a related project manager."

## Brigade Org Maintainers

The Brigade org maintainers are responsible for:

- Maintaining the mission, vision, values, and scope of the project
- Refining the governance and charter as needed
- Making project level decisions
- Resolving escalated project decisions when responsible project maintainers are blocked
- Managing the Brigade brand
- Managing access to Brigade assets such as source repositories, hosting, project calendars
- Handling code of conduct violations
- Deciding what sub-groups are part of the Brigade project
- Overseeing the resolution and disclosure of security issues
- Managing financial decisions related to the project

The org maintainers have to match the following criteria:

- There will be between 3 and 5 people with a diverse representation from multiple companies
- Any project maintainer is eligible for a position as an org maintainer
- Org maintainers MUST remain active on the project. If they are unresponsive for > 3 months, they will lose org maintainership, unless a [super-majority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) of the other org maintainers agrees to extend the period to be greater than 3 months

Changes to the org maintainers use the following:
- An org maintainer may step down by emailing the org maintainers mailing list
- When there is an opening for a new org maintainer, any contributor to any Brigade project may nominate a suitable maintainer as replacement
    - The nomination period will be one month starting the day after the position becomes available
    - The nomination must be made via the Brigade mailing list
- When nominated individual agrees to be a candidate, the project maintainers may vote.
    - The voting period will be open for a minimum of three business days and will remain open until a super-majority of project maintainers has voted
    - Only current project maintainers are eligible to vote
    - When the number of nominated individuals matches the number of openings each individual needs to have a yes vote from a super-majority of those that voted
    - When there are more individuals than open positions voting will use [Condorcet](https://en.wikipedia.org/wiki/Condorcet_method) ranking on [CIVS](http://civs.cs.cornell.edu/) using the [Schulze method](https://en.wikipedia.org/wiki/Schulze_method)
- When an org maintainer steps down, they become an emeritus maintainer

Once an org maintainer is elected, they remain a maintainer until stepping down (or, in rare cases, are removed). Voting for new maintainers occurs when necessary to fill vacancies. Any existing project maintainer is eligible to become an org maintainer.

The Org Maintainers will select a chair to set agendas and call meetings of the Org Maintainers.

## Brigade Project Maintainers

Project maintainers are responsible for activities surrounding the development and release cycle of the project they own. Technical decisions for code resides with the project maintainers, unless there is a decision related to cross maintainer groups that cannot be resolved by those groups. Those cases can be escalated to the org maintainers.

Project maintainers do not need to be software developers. No explicit role is placed upon them, and they can be anyone appropriate for the work being produced.

Changes to project maintainers use the following:
- A project maintainer may step down by emailing the mailing list
- Project maintainers MUST remain active on the project. If they are unresponsive for > 3 months, they will lose project maintainership, unless a [super-majority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) of the other project maintainers agrees to extend the period to be greater than 3 months
- New maintainers can be added to a project by a [super-majority](https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote) vote of the existing maintainers
- When a project has no maintainers the org maintainers become responsible for it, and may archive the project, or find new maintainers

## Decision making at the org level

When maintainers need to make a decision, there are two ways decisions are made, unless described elsewhere. The default decision making process is [lazy-consensus](http://communitymgt.wikia.com/wiki/Lazy_consensus). This means that any decision is considered supported by the team making it, as long as no one objects. Silence on any consensus decision is implicit agreement and equivalent to explicit agreement. Explicit agreement may be stated at will.

When a consensus cannot be found a maintainer can call for a [simple majority](https://en.wikipedia.org/wiki/Majority) vote on a decision.
