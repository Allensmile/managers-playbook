[principles]: https://github.com/ksindi/managers-playbook/blob/master/README.md#principles
[one-on-ones]: https://github.com/ksindi/managers-playbook/blob/master/README.md#one-on-ones
[coaching]: https://github.com/ksindi/managers-playbook/blob/master/README.md#coaching
[feedback]: https://github.com/ksindi/managers-playbook/blob/master/README.md#feedback
[thinking-strategically]: https://github.com/ksindi/managers-playbook/blob/master/README.md#thinking-strategically
[making-decisions]: https://github.com/ksindi/managers-playbook/blob/master/README.md#making-decisions
[coding]: https://github.com/ksindi/managers-playbook/blob/master/README.md#coding
[ticket-and-pr-process]: https://github.com/ksindi/managers-playbook/blob/master/README.md#ticket-and-pr-process
[meetings]: https://github.com/ksindi/managers-playbook/blob/master/README.md#meetings
[hiring]: https://github.com/ksindi/managers-playbook/blob/master/README.md#hiring
[onboarding]: https://github.com/ksindi/managers-playbook/blob/master/README.md#onboarding
[announcing-change]: https://github.com/ksindi/managers-playbook/blob/master/README.md#announcing-change
[further-reading]: https://github.com/ksindi/managers-playbook/blob/master/README.md#further-reading

# Manager's Playbook

Heuristics for effective management.


## Table of Contents

1. [Principles][principles]
1. [One on ones][one-on-ones]
1. [Coaching][coaching]
1. [Feedback][feedback]
1. [Thinking strategically][thinking-strategically]
1. [Making decisions][making-decisions]
1. [Coding][coding]
1. [Ticket and PR process][ticket-and-pr-process]
1. [Meetings][meetings]
1. [Hiring][hiring]
1. [Onboarding][onboarding]
1. [Announcing change][announcing-change]
1. [Further reading][further-reading]


## Principles

1. Always be aware of what's going on in your team and product.
1. Know the architecture just as well as anyone else — and stay current with the tech stack.
1. Schedule 1-1s with your direct reports on a weekly basis. Schedule skip-levels on a monthly basis.
1. Be customer-focused. Understand how your products are used in the wild. For example, join sales and support calls.
1. Set aggressive but achievable goals. Work backwards by focusing on the outcomes you want to achieve.
1. When giving advice or feedback, encourage ownership by asking open questions.
1. Have a bias for action and decision-making over planning and consensus.
1. Be the team coach and cheerleader. Celebrate success often and reinforce positive behavior.
1. Know to differentiate between [reversible and irreversible decisions][making-decisions].
1. Ensure every report is aware of the top priorities of the team, organization and company.
1. No task is below a manager. Get your hands dirty even if it's not coding:
    <img src="images/non-coding-contributions.jpg" width="400">


## One on ones

1. Never skip one on ones. It's the best platform for getting and providing feedback. Most teammates value it and usually when they don't it's because they haven't seen one conducted well.
1. Aim for weekly one on ones.
1. Focus on 5 topics:
    - Predictability: create routine, set expectations, normalize change.
    - Ownership: offer options, clarify ownership, give more responsibilities.
    - Purpose: clarify the big picture value and importance of their tasks.
    - Progress: create milestones, share wins, celebrate progress.
    - Belonging: team culture and management.
1. Questions to help frame each topic. "On a scale of 1-10 how would you rate:..."
    - Predictability: How clear do you feel about what's expected of you?
    - Ownership: Your satisfaction with decision power and direction?
    - Purpose: How much your work makes a difference for the team?
    - Progress: The sense of progression each week?
    - Belonging: Your feeling of connection to the team?
1. Additional questions to ask on a less frequent basis:
    1. Motivators:
        1. Which part of your work is most fun?
        1. What's not fun about working here?
        1. What are the biggest time wasters for you each week?
    1. Long term goals:
        1. What skills do you want to improve?
        1. What career path are you looking for?
        1. Who in the company would you be excited to learn more from?
        1. What parts of the business would you like to be more involved in?
    1. Organization awareness:
        1. What don't you like about the product?
        1. What's the biggest opportunity that we're missing out on?
        1. What do you see as your top 3 priorities this quarter? The team’s? The org's?
        1. If you were CEO, what would you do differently?
    1. Manager's role:
        1. What could I do to support you better?
        1. If you were me, what are 1 to 3 things you would change?
        1. How do you feel about the amount of feedback you are getting?
        1. I need feedback. What are two things that I can do differently?
        1. What's one thing we could do to improve our way of collaborating?
    1. Priorities:
        1. "What are your top priorities this week?"
        1. "What will success look like?"
        1. "What are obstacles?"
1. Encourage your direct reports to bring up topics in 1-1. [Julia Evans](https://twitter.com/b0rk) made a great [zine](https://jvns.ca/blog/2018/09/22/new-zine--help--i-have-a-manager/) on it:
    <img src="images/1_1s.jpg" width="400">  


## Coaching

1. Default to open questions: ask questions starting with **what**, **how**, **who** instead of closed-ended ones like **do**, **have**, **is** to invite conversation and give ownership over a problem.
    - "What questions do you have?" is better than "Do you have any questions?".
    - "Why do you think this is the right approach?" is better than "Is this a good idea?".
    - Respond with "What are your thoughts so far?" when asked "What should I do?"
1. Summarize what the person is saying so you're both on the same page and are pinpointing the problem.
    -  "It sounds like there are two issues, x and y. Which should we focus on first?"
1. Figure out how to make this meeting productive.
    - "What's the next step?"
    - "How should we track this?"


## Feedback

1. Be prompt, ideally providing feedback the same day of the event that prompted it.
1. Get buy-in about providing feedback and reduce mystery:
    - "Do you have 10 minutes to talk about this morning's stand up?"
    - "Can I share some thoughts with you about how we've been working together?"
1. Don't "pad" negative feedback by beginning with compliments - it gives mixed signals.
1. Be specific even if it's positive feedback.
    - "Good job!"  ⛔️
    - "I like the initiative you took to reduce the service's memory footprint. It shows ownership and leadership."
1. Focus on data and not behavior:
    - "I noticed you didn't address any of the comments made in your last three PRs"
    - "I noticed that you didn't pick up the ticket I asked you to do"
    - "I noticed your last feature release didn't have any tests"
    - "Your code is buggy"  ⛔️
    - "You are always late"  ⛔️
1. Talk about why this matters and who it's affecting:
    - "I mention it because it's important we work as a team"
    - "I mention it because the ticket I assigned you is critical to this quarter's roadmap"
1. Figure out together how to fix the problem:
    - "What do you think of our process?"
    - "How do you see it?"
1. Agree on an action plan:
    - "How do we ensure we don't miss a ticket due date next time?"
    - "What are a couple of actions you could take right now?"
    - "What are our action items?"
1. Highlight positive patterns (remember to be specific).
    - "I like when you take initiative in cleaning up code because it shows initiative and ownership."
    - "It's great to see you teach X about Y so that they're. That's a positive trait of a senior engineer."
1. Replay instinctive reactions to help frame the conversation:  
    <img src="images/replay-instinctive-reactions.png" width="400">


## Thinking strategically

1. What would you do with more one person?
1. How is your team moving the needle? Are you focusing on the right things? How do you know the features you're building will benefit the customer?
1. What are your product's mission and tenets?
1. What pillars is your team driving and in what way?
1. What are your team's pain points? How can you move 2x faster?
1. What "dogs not barking" do you worry about? What are areas in your team you worry about?


## Making decisions

1. Determine if the decision is [reversible vs. irreversible](https://fs.blog/2018/04/reversible-irreversible-decisions/).
    - Reversible decisions can easily be changed. Examples: changing stand up time, contributing guidelines.
    - Irreversible decisions cannot be changed without significant rework. These decisions should take
  longer and be documented and discussed. Examples: architecture changes, language decision, data models.  
1. Whenever there is disagreement, focus on the intended outcome of the decision and make sure the team
is aware of your reasoning.
    - "While database X is better, I want us to standardize on one stack so that it's easier to maintain."
1. If someone disagrees with a reversible decision, set a date to revisit that decision with the team.
Ideally you also have metrics to define the success of that decision.
    - "I understand your concerns. Let's revisit this in a month and see where we stand."
    - "We're tracking X now, let's revisit next quarter if it improves with these changes."
1. If someone disagrees with an irreversible decision, give them the opportunity to present their case.
Regardless, everyone should be aware the decision is ultimately yours and the team needs
to [disagree and commit wholly](https://tomtunguz.com/disagree-and-commit/) to the decision made.


## Coding

Avoid coding in the critical path. [Tips](https://charity.wtf/2019/01/04/engineering-management-the-pendulum-or-the-ladder/) from [Charity Majors](https://twitter.com/mipsytipsy):
  1. Authoring a feature?  ⛔️
  1. Covering on-call when someone needs a break?  ✅
  1. Diving on the biggest project after a postmortem?  ⛔️
  1. Code reviews?  ✅
  1. Picking up a p2 bug that's annoying but never seems to become top priority?  ✅
  1. Insisting that all commits be gated on their approval?  ⛔️
  1. Cleaning up the monitoring checks and writing a library to generate coverage?  ✅


## Ticket and PR process

1. Set contributing guidelines for the team.
1. PRs should always be prioritized. Aim for review SLA of 1 hour.
1. Automate opinions like style with linting or code formatters like [black](https://github.com/ambv/black).


## Meetings

1. Avoid [shitty brainstorm sessions](https://erikbern.com/2017/12/29/toxic-meeting-culture.html). Don’t defer decisions to meetings. Make decisions on the spot, communicate it over email, and use the meeting to discuss it.
1. Always end a meeting with actions, owners and timing.
1. Encourage ["6 pagers" and "2 pagers"](https://medium.com/@inowland/using-6-page-and-2-page-documents-to-make-organizational-decisions-3216badde909).
1. For "staff meetings", go around the table and asking what's their biggest concerns. "Many managers want to attend executive staff meetings, as it makes them feel needed and puts them in the know. I made use of this desire by setting a price of admission to the meeting: you had to fess up to at least one thing that was 'on fire.'" - Horowitz


## Hiring

> The best programmers are not marginally better than merely good ones. They are an order-of-magnitude better, measured by whatever standard: conceptual creativity, speed, ingenuity of design, or problem-solving ability. – Randall E. Stross

Hiring is the most important decision a manager makes.

What to look for in senior engineers:

1. **Owner**. Takes ownership of a problem even when it's not 100% their responsibility; understands the why.
    1. "Tell me about a time when you took on something significant outside of your area of responsibility. Why was it important? What was the outcome?"
    1. "Tell me about a time when you made a hard decision to sacrifice short term gain for a longer term goal."
1. **Handles ambiguity**
    1. "Can you tell me about a time when you had to solve an ambitious problem? Why was the problem important?"
    1. "Can you tell me about a time when you had to make a decision without complete information? What was the situation? What risks did you take? Why did you make the decision you made?"
1. **Team player**. Takes feedback well.
1. **Communicator**. Can articulate ideas at different levels.
    1. "Describe to me something you know well."
    1. "You mentioned X in your resume. Explain it to me as if I've never come across it?"
1. **Teacher**. Enjoys growing other engineers. Especially important for senior-level engineers.
    1. "Tell me of a time where you helped someone in your team grow."
1. **Deep diver**. Digs a level deeper to understand what's happening under the hood.
    1. "Tell me about a time you were trying to understand a problem on your team and you had to go down several layers to figure it out."
1. **Simplifier**. Simplifies problems instead of just hacks at things and adds tech debt. Does the person have a build vs. buy mentality.
    1. "Tell me a about a complex problem that you solved with a simple solution."
1. **Missionary**. Interested in company's mission or technology.
    1. "Explain to me what your current company does and why it's important."
    1. "What interests you working at [INSERT COMPANY]?"

What to watch out for:

1. **Short tenure at companies**. If a candidate typically stays at companies for less than a year, ask them why. There might be perfectly valid reasons or it might indicate a pattern that the person is difficult to work with.
    1. Why did you only work at X for less than 1 year?
1. **Menu of technologies**. Resumes that just list technologies used instead of problems solved may indicate person may not be thinking big picture. Also a typical trait of junior engineers.
1. **More than 2 page resumes**. More than two pages may indicate the person has difficulty distilling what's important. There are also culture reasons to be aware of. For example, in Europe, especially Germany, resumes (_lebenslauf_) are encouraged to be long.


## Onboarding

Having a good onboarding process is crucial to the success of your team and new team members. It insures team members are contributing as early as possible and are assimilated.

An onboarding process is successful if your new team member can contribute a bug fix on the first day of joining.

Onboarding material:
1. Team mission
    1. How is your team moving the needle for the customer?
1. Team members
1. Repositories and services
1. Documentation:
    1. Code contributing guidelines
    1. Ticketing process. E.g. label and story pointing guidelines.
    1. Glossary of terms.
    1. Releasing code.
    1. How tos (e.g. migrate database, add secrets)
1. Getting started:
    1. Installation instructions (e.g. Docker, postgres).
    1. Getting the right accesses (e.g. PagerDuty).
    1. Running your apps locally.
1. Meeting setups. Who should your new team member meet with?


## Announcing change

WIP

1. Examples of change: promotions, reshuffles, restructuring.
1. Acknowledge the difficulty or opportunity of the change.
1. Appeal to emotions and narrative to explain the why.
    1. Why is this change important now for the company?
1. Use facts to explain what happened.
    1. What metrics will this change achieve?


## Further reading

1. [The Feedback Fallacy](https://hbr.org/2019/03/the-feedback-fallacy): focus on replaying positive performance so team members know how to repeat excellence.
1. [Manager's Path](https://www.amazon.com/Managers-Path-Leaders-Navigating-Growth/dp/1491973897/): Excellent guide for all levels of management.
1. [97 Things Every Engineering Manager Should Know](https://www.amazon.com/Things-Every-Engineering-Manager-Should-ebook/dp/B081TPX6NS): Collection of management tips from various practitioners.
1. [The Pendulum or the Ladder](https://charity.wtf/2019/01/04/engineering-management-the-pendulum-or-the-ladder/)
1. [Hard Thing About Hard Things](https://www.amazon.com/Hard-Thing-About-Things-Building-ebook/dp/B00DQ845EA): More on the exec side but still worthwhile.
1. [What You Do Is Who You Are](https://www.amazon.com/What-You-Do-Who-Are/dp/0062871331): Why company culture matters and how to establish one.
1. [Trillion Dollar Coach](https://www.amazon.com/Trillion-Dollar-Coach-Leadership-Playbook/dp/0062839268): Book about Bill Campbell, the silicon valley coach.
1. https://github.com/charlax/engineering-management: Great collection of management articles.
1. https://medium.com/@radoshi/hiring-engineering-leaders-ca55a87db204: Hiring engineering leaders.
1. https://erikbern.com/2020/01/13/how-to-hire-smarter-than-the-market-a-toy-model.html: Berkson's paradox and engineering hiring.
1. https://lifelabslearning.com/. Great workshop for new and experienced managers.
1. https://blog.newrelic.com/technology/hiring-software-engineering-managers-interview/
