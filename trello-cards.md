# How we write our Trello Cards

_This outlines how the product team tries use Trello. This is not prescriptive, but might be helpful for other teams, plus serve as a reminder for existing and new team members_

A ticket is considered ready when it has:

# 1. A user story / job story 

A user story would normally take the following format:

```
As a {persona}
I want {what}
So that {why}
```

A key thing to remember is to base the user stories on real users and their needs, as summarised nicely in [this quote](http://www.romanpichler.com/blog/10-tips-writing-good-user-stories/):

> If you don’t know who the users and customers are and why they would want to use the product, then you should not write any user stories. Carry out the necessary user research first, for example, by observing and interviewing users. Otherwise, you take the risk of writing speculative stories that are based on beliefs and ideas—but not on data and empirical evidence.

Another option is to use a job story. The advantage of this is that it focuses on the _causality, anxieties, and motivations_ of the user, e.g. why they are doing what they're doing. It's still based on research into real users.

A problem that this approach is trying to solve is that:

> _Personas are imaginary customers defined by attributes that don’t acknowledge causality._

> These attributes, generally in the form of demographics, do not bring a team closer to understanding a customer’s consumption, or non-consumption, of a product. The characteristics of a Persona (someone’s age, sex, race, and weekend habits) does not explain why they ate that Snickers bar; having 30 seconds to buy and eat something which will stave off hunger for 30 minutes does explain why.

_—[Designing features using Job Stories](https://blog.intercom.com/using-job-stories-design-features-ui-ux/)_

The format for a Job Story is:

```
When {situation} 
I want to {motivation}
so I can {outcome}
```

The user / job stories are generally best placed in the Description of the card.

![](/img/trello-card.png "An examplary Trello card")

# 2. Acceptance criteria

In order to know (and test) whether a ticket is done it's really helpful to create acceptance criteria. From [a well-linked article](http://www.seguetech.com/what-characteristics-make-good-agile-acceptance-criteria/) on what makes a good acceptance criteria:

> Acceptance Criteria are a set of statements, each with a clear pass/fail result, that specify both functional (e.g., minimal marketable functionality) and non-functional (e.g., minimal quality) requirements applicable at the current stage of project integration. These requirements represent “conditions of satisfaction.” There is no partial acceptance: either a criterion is met or it is not.

> These criteria define the boundaries and parameters of a User Story/feature and determine when a story is completed and working as expected. They add certainty to what the team is building.

> Acceptance Criteria must be expressed clearly, in simple language the customer would use, just like the User Story, without ambiguity as to what the expected outcome is: what is acceptable and what is not acceptable. They must be testable: easily translated into one or more manual/automated test cases.

These can be listed in a Checklist to allow you to update their status as you work on the ticket.

# 3. Comments

Use comments to leave a running commentary on the status of the ticket. Making a habit of doing this when you leave it to work on something else / sign off for the day helps everyone else to see where things are left.

# 4. Links 

Links to Pull Requests, associated cards, documents and other related URLs is best placed in the Description as they easily get lost in the comment feed.

# 5. Labels

We use labels to identify blockers, epics, stories and chores. The labels are flexible and can be changed to accommodate the particular needs of the team.

# 6. Definition of Ready

A story is **Ready for Development** when it is captured in Trello with:
- A title
- A description that articulates the 'What', the 'Why', and the Persona
- All acceptance criteria (BDD scenarios, if useful to define failures cases, edge cases etc.)
- A priority (the higher a story is in the backlog, the higher the priority) that has been agreed by the Product Owner and the whole team
- An estimate (story points)
- UX wireframes/mockups (when relevant to the story)
- Dependencies (if applicable)
- And it is achievable in one sprint
Until a story is **Ready for Development** it cannot be added to a sprint.
