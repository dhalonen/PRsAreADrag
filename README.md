# PRs Are a Drag
It seems common for Scrum busness teams to manage code by an author creating & publishing a PR and then going out to the public square to beg for someone to review & approve. It’s especially problematic when more than one reviewer is required, as most reviewers have their own work to focus on during their sprint.

When solving problems, one strategy is to consider the 3 numbers that make sense: 0, 1, or infinity. Here is the case for ZERO reviewers, ie directly committing to the trunk or feature branch (teams have different practices on this).

## Benefits
1. Developers can immediately deploy into test environments.
1. Developers aren’t distracted by other dev efforts.
1. Features can be delivered to production sooner.
1. Automated validation tools have the ability to more critically review than other developers, especially junior devs.
1. Developers truly own their code.
1. Reduces the need for as many senior devs on a team.
1. Meaningful unit & other automated tests help limit the risk.

## Costs
1. Automated code inspection tools (CheckStyle, linters, Sonar, etc.) become more important and expensive to maintain.
1. Feature flag techniques or tools such as Launch Darkly need to be used to enable controlled deployment.
1. Complex or inter-twined code may add difficult coordination feature flag efforts.
1. May cause some developers to release more slowly as they are uncomfortable with the additional responsibility.
1. Young developers won’t get feedback on poorly designed classes or design decisions; expect “bad” code and more refactoring (long-term support isn’t much valued during initial dev, however

PR’s are an vestige of open source, where dev’s may be on different continents, cannot speak to each other, and never worked together. As a member of a team, we can pick up the phone and give a peer a holler to look things over. That’s the part of being a team member. There is no reason that a junior dev cannot be trusted to commit a simple, safe code change directly. Furthermore, there is no reason why more than one dev is required to approve the simplest change. (Heavy-handed beaurcpatic rules abound!) Where and when do we actually trust humans over rules?

Yes mistakes will happen, but how else will folks learn? If one is completely risk-averse, how to improve on this significant performance drag? 

What has your team done to reduce the PR drag?

## So what?
After interacting with several folks on this, I realized I've had a *great* code review practice during the 1990's. In this instance, another developer (Indu) & I were assigned to make a database application. Since there was only one other person to review & approve the code, the negotiating for a reviewer part of the process was friction-free. Since she & I were the only devs, we had complete ownership & responsibility. This greatly improved the commitment on both sides of the review process. As it turns out, it was a friendly, but ruthless competition to find the smallest item to chide our peer. And it remains the most challenging & rewarding review experience I've ever had.
