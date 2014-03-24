# #pm4lib

March 24, 2014. Project management workshop led by Rosalyn Metz and Becky Yoose. Check out their [supporting docs/workshop slides](https://drive.google.com/folderview?id=0B6fFxMd8RTVhUkN4YW8wZXdwY1U&usp=sharing).

[Tweets from this session](https://twitter.com/search?q=%23pm4lib&src=typd&f=realtime)

## kicking off projects

To kick off a project, hold a meeting with your stakeholders and your developers. Use facilitating activities like "5 whys" to do discovery and find the root of the problem you're trying to solve.

Define [SMART goals](https://docs.google.com/document/d/1sOlzDUO_tFzCXiPRrEGG-nUbDqCB91ldflpR_MUfCek/edit?usp=drive_web):

 - specific: who, what, when, where, why
 - measurable: can be time-based
 - attainable: realistic given current resources. Other A's: assignable
 - relevant
 - time-bound 

## stakeholders

 - [stakeholder analysis worksheet](https://docs.google.com/document/d/1hu_xmNzAZMfOzwPv41an3eu1IJJKAxD68WA8d6K63kg/edit?pli=1)

Understand the personalities and types of stakeholders: executive sponsor, sponsor, project manager, team members, other affected groups.

## project charters

 - [Project one-pager by Tito Sierra](http://www.slideshare.net/tsierra/the-projectonepager)
 - [Example one-pager from Rosie](https://docs.google.com/document/d/1BrZzT9dHE0r9slJFJo9Jmc91rZJ3Kl0aBHrBcz4RlyE/edit?usp=drive_web)

Establish the project, set the boundaries. 

 - Objective
 - Outcomes: enumerated outcomes that must be achieved (SMART goals)
 - Out of scope
 - Team
 - Schedule (ish)

## breaking down work/assigning responsibility

- [Task breakdown worksheet](https://docs.google.com/document/d/14z3k-EJc9rbEgzrOPjmkS8T4PbSz3rXMjTxUAm8o2FQ/edit?pli=1)
- [Example breakdown](https://docs.google.com/document/d/1EmHnmrYfyszQI1sSr3Bn196FKFe9SMuNx76c0wgEplo/edit?pli=1)

Take your high-level buckets (SMART goals) and break them down into tasks. If you're doing agile, you hand goals over as user stories and developers break those down into tasks.

**Revisit tasks** regularly to make sure they're still realistic. Does the task breakdown need to be modified?

## time estimates

Often libraries don't think about project cost. We should. Estimating time helps you estimate cost.

**Track your time** to be able to estimate your time. Rosy uses an app called [Harvest](http://www.getharvest.com/).

**Empower your team** and encourage them to track their time, too. Rosy: I don't care how long it takes. I just want to know.

**Know your audience.** Some team members will give you one estimate...know how they work and adjust estimates accordingly.

**Estimate discrete tasks based on the Fibonacci sequence.** Will a task take 1, 2, 3, 5, or 8 hours?

### buffers

Choose a realistic buffer B and apply the percentage to an entire project's time T.

```
T / (1 - B%)
```

## cost estimates

 - [Example project budget spreadsheet](https://docs.google.com/spreadsheets/d/1O_nf8iqJ-Z_f8l8iVQB-cDUpDP4y3jgTOAGTbQj2hw4/edit?usp=drive_web&pli=1)

Estimate time in hours, estimte salary/hour and benefits. Take the task breakdown list and estimate time for each employee to complete each task.

```
cost = P1(hours*salary/hour) + P2(hours*salary/hour) + P3(hours*salary/hour)
```

If you want to get real about cost, include at least 25% on top of salary for HR/benefits rates.

And, include the time buffer in estimates.

### why should libraries care about cost estimates?

 - Helps project initiators understand the scope of their projects
 - Helps justify staffing decisions

## reporting your progress

 - [sample communications plan](https://docs.google.com/document/d/1TFKjDxgx25arn1nZSR73Og-mLo_-6tSj55F_3yp5xr8/edit?usp=drive_web)

What and how you report will depend on who's sponsoring the project. External agency? Internal client?

Whatever your plan, your communications need to be clear, concise and consistent.

 - **Standing meetings with your team:** what'd you get done since the last meeting? What will you work on next? Anything keeping you from doing your work? Daily grynd.
 - **Status reports:** less regular. Use less jargon, explain impact on the organization.
 - **Sponsor meetings:** as needed to discuss critical issues and potential changes to project plan.

## ticketing

Repeat after Becky: "My ticketing system is not my project management strategy."

Customize your system to solidify your workflow *before* tickets hit the system.

 - Decide: will you use your ticketing system just for bugs, or will you use it to report progress?
 - E-mail functions: how will they be used?
 - Decide types of tickets (i.e. development, design) and assign a primary contact and secondary contact.
 - Decide how long a "timely manner" is and figure out when second contact needs to come in.

Finally: make sure your users are using the ticketing system. It can be hard for people to send their communications into a "black hole" especially when they know a specific person they can contact to get a problem solved.

## tools of the trade

### [redmine](http://redmine.org)

Open-source software. Can assign users to specific roles. Can also create external forms that hook into RedMine (i.e. Drupal).

Can be used for time tracking.

Makes Gantt charts based on your time estimates.

**Protip:** we respond to people faster when they use the ticketing system.

### [basecamp](http://basecamp.com)

Can assign projects to teams. Can create checklists.

Can export calendar to Google Calendar so people can see what we're working on.

Doesn't handle files well, but integrates with Google Docs pretty well and has a text documents feature.

### [trello](http://trello.com)

Digital post-it boards. Easy to move cards between boards. Can have comment threads on cards. Really handy for scrum/agile environments.

### [github](http://github.com/)

Ticketing tied up with code repositories. Nice for integrating with workflow.

### excel spreadsheets

Using a spreadsheet to track problems, who reported it and when, what type of issue it is, when first response sent. Helps with accountability for supervisors.

## finishing projects

The project charter is your go-to guide. But your project isn't completely over when you complete all your objectives.

### postmortems

Wrapup discussion after a project. 

 - What worked? Did anything come in early or under budget? Any tools or techniques that worked?
 - What didn't work? 
 - What lessons can we learn from this project? 
 - And, how can we apply these lessons to future projects?

### product management/maintenance

Moving from project management to product management after your product ships. We assume product managers do everything from idea generation to design, development, communications/PR, etc. 

But product managers are one thing: **the voice of the user**. Your job is to coordinate the work of many teams and make the decisions about features.

Ask the hard questions and ask your developers why. Facilitate structured discussions. In an ideal world the product owner is not the direct supervisor of the team members.

Resources from Rosy:

 - [how to be a product manager](http://www.joelonsoftware.com/items/2009/03/09.html)
 - [on product management](https://medium.com/on-product-management/c664ba7e5138)