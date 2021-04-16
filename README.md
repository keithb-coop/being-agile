Choose _being_ agile over _doing_ agile

We expect our teams to be similar but different, shaped by the context they are in but expressing the same principles

What Andy Longshaw calls "2021 style software development" 

# Principles

* Working on everything _over_ working only in my specialism
* Working together _over_ working alone
* Releasing to users often _over_ accumulating changes
* Working at a pace we can maintain _over_ working with urgency
* Checking it was valuable _over_ meeting requirements

These are in git because they should change as we learn

----

# Themes

Keith's ramblings, YYMV: back about the time that _Scrum_ was being invented and _eXtreme Programming_ discovered, about 1996, I was working on a product that staggered through one release to customers per year, after which the Project Manager would be fired and a bunch of burned-out engineers would quit in disgust. On that product we had to "design" the software using boxes and arrows and upside-down A's and back-to-front-E's and have our designs reviewed before we started coding. We did however have comprehensive suites of fully-automated unit tests (albeit we wrote them after the code that they tested). I myself burned out and quit, and ended up in a place where I wasn't allowed to write code at all, I had to "forward engineer" my code from drawings in Rational Rose. In my next job, a team of BAs flew around the world gathering requirements, which a bunch of architects in London turned into a design, and then I flew to New York, NY to explain the design to the developers. That all worked about as well as you'd imagine. Along the way I'd have conversations with Project Managers along the lines of "says here, Keith [pointing to 3cm thick A3 printout of the Gantt Chart] that next April you'll be working on task THX1138, how long is that going to take you? In hours. To one decimal place."

So, to begin with, we thought that Scrum and XP were there to fix that stuff, and they did. Scrum set out to make the development of software-intensive products in the 1990s work pretty much the same way that the development of tangible products had since the 1980s. The caveat here is that the product development episodes that Scrum was inspired by were on the one hand last-ditch, bet the company stuff and on the other hand were aimed at disrupting entire markets. That's an unusual combination, which would make Scrum a relatively poor fit for incremental BAU enhancements to products in service. That turns out to not really be a problem, though, since approximately no teams whatsoever actually do Scrum.

XP sets out to make all software development work as much as possible they way development works in Smalltalk. A Smalltalk system doesn't really have any representation other than the running system itself, so Continuous Integration is the norm, and Smalltalk has supported it well since 1980. For a long time, the only way for two Smalltalk developers to collaborate was to swap patches to be applied to each other's running systems, each of which had distributed version control built in. Smalltalk developers always did explore the solution space by iterating over examples drawn from the problem space. Beck created tooling for that and the result was TDD, and so on. Smalltalk was also very expensive, so it was used by big outfits for big problems. XP was created to build business-critical back-office enterprise systems, so that might make it a poor fit for, say, end-user mobile apps. That turns out to not really be a problem, though, since approximately no teams whatsoever actually do XP..

I recall sitting in a meeting room in a Washington DC hotel when David Anderson introduced his Kanban approach. The case he discussed was the rescue of a struggling support and maintenance organisation operating a on-line service. Kanban aims to make the management of requests for work on  an IT system behave as much as possible like the requests for stock into a supply chain. Kanban emphasises the benefits of low work-in-progress to promote high throughout of uniform work items, and therefore high levels of responsiveness to ad-hoc requests. Kanban also promotes very consistent throughput and encourages the use of leading measures for forecasting. This might not make Kanban particulalry well suited to exploratory product development based on learning. That turns out not to really be a problem, though, since approximately no teams whatsoever actually do Kanban.

What we've learned over the past decade or so is that the effect of Agile approaches in general is to place product and service development under _closed-loop control_. This means that all aspects of development, from what features to offer next to the users down to how each line of code should be (re)designed, is planned in terms of being a hypothesis to be tested against reality, being revised and refined based on information received after the fact rather than on predictions made ahead of time. This is what Scrum is _supposed_ to have at its core, but Scrum fails to extend that far enough out into the world.

And we've learned that the engineering practices, from TDD out to Continuous Integration (and Test, and Deploy, and on again to DevOps) have the effect of moving the tightest constraint on how fast that closed-loop can respond to new information away from software development. The managers of that product I worked on back in 1996 simply could not consider feedback cycles shorter than two years. What sincere application of XP-style engineering practices is to allow, and encourage, the managers of a product or service to learn from their users pretty much as quickly as they want. This means that product and service managers then end up owning the tightest constraint on how fast the organisation can learn what their users or market thinks is next most useful or valuable. In my personal view, this is why Agile in general and XP in particular have struggled to win widespread adoption.

So then what does any particular engineering organisation do about that?
