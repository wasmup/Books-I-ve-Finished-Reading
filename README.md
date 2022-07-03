# Books-I-ve-Finished-Reading
Books I've Finished Reading

## Complex Enterprise Architecture by John D. McDowall
A large corporation is an enterprise, but that corporation may also have multiple
divisions, each of which is an enterprise in its own right.    

One of the most important things the enterprise architecture should define is one or
more controlled vocabularies that implementation teams should use to describe their
system functionality, their interfaces, and the data that flows across those interfaces.  

A reference architecture provides general guidelines,
a solution architecture provides specific instructions.  

The primary goal of the traditional practice of enterprise architecture is the eventual
development of a solution architecture.

**In practice, all architecture is ephemeral.**

no architecture ever survives contact with the development team.  
**plans rarely survive contact with reality**  
Undertaking any complex activity without an initial planning
step is setting yourself up for failure.

no plan will be executed as first
envisioned because reality and events will intervene, and the initial plan will be
modified to deal with those circumstances as they arise; in retrospect, the actions that
were taken may not resemble the original plan at all.no plan will be executed as first
envisioned because reality and events will intervene, and the initial plan will be
modified to deal with those circumstances as they arise; in retrospect, the actions that
were taken may not resemble the original plan at all.

It is much easier to deal with a problem you anticipated and planned for
than to deal with a problem that you did not consider.


An enterprise architecture project is an effort to make the enterprise architecture both more
efficient and more effective.

**goals need to be measurable and time-bound**

The purpose of modeling is to answer questions, questions that either the
enterprise architect or the enterprise’s management wish to have answers to.
Models should be created to answer those specific questions, not for the sake of
creating models.

Making sure the model is useful is the architect’s primary task:  
Precision  
Model-based engineering  
Automated analysis  
A model is a specification of a system or part of a system using formal methods.  
Formal methods are ways of using mathematically precise notation to describe something. A mathematically precise
notation is one that has rules that define the syntax (structure) and semantics (meaning)
of its symbols.  

Good rule of thumb is to:  
Model those things that need to be standardized across the enterprise.  
If different implementation teams do create incompatible versions from the same enterprise model, that is a clue that the model may not be detailed enough.

e.g.: use a common authentication component.  
Creating a single model of this component at the enterprise level will save the individual implementation teams the work of creating such a model for use in their own designs.

In general, if something is a well-defined component and analyzing it by itself might be useful, then it is probably about the right size for a separate model.  
it can answer the questions architects and managers need from the model.  

If you do not have primary objects, it is difficult to say that you have an enterprise architecture:  
Primary objects (absolutely essential - elements of models): they are the “who, what, when, where, and why” of your architecture  
(the “how” will be determined by the emergent behaviors of the enterprise)  

A goal without a strategy (**plan**) for achievement is just a wish:  
Goals are the “why” of the enterprise architecture effort (clearly defined, measurable
goals):  
If goals are not one of the primary objects of the enterprise
architecture, it is likely that architects and managers alike will lose sight of them and be
distracted by the details of the modeling process.
It is human nature for people to pay attention to those things on which they
are evaluated and to ignore things on which they are not.

Enterprise goals are those goals that the enterprise wants to achieve (important to management).  
it is important that the enterprise architecture project itself have some measurable goals.  
management is the primary customer of the enterprise architecture team.  

e.g.: improving the interoperability among systems,  increasing the consistency between architecture & implementation teams.

Strategic plans are those that express how an objective
will be achieved over a relatively long term, often a number of years. Operational plans are
smaller in scope than strategic plans, expressing how some subobjective within a strategic
plan will be achieved. Operational plans usually have a scope measured in months
or weeks. Finally, tactical plans are those day-to-day activities that address problems
encountered while achieving an objective; they consist of the process that will be used
to meet the operational and strategic goals.

Anything that is capable of undertaking an activity is an **actor**:  
Having clearly defined **goals** and **strategies** for achieving them is important, but it is
not sufficient to make progress toward achievement until each goal and strategy has one
or more actors assigned to it.

A **process** is an expression of what we think a strategy will look like in practice.  
many conceptions of processes do not survive **first contact with the real world**.  
Some processes are really idealized strategies **subject to change** as emergent behaviors reveal themselves.  

It is tempting for senior managers to mandate some processes where there is really
no reason for the current structure other than the fact that people are comfortable with
the processes.

The logic of “we have always done it this way” is
deadly to any enterprise in today’s dynamic environment.


**To harness the inherent intelligence
of any complex system, the actors must be free to innovate and find better ways to meet
the enterprise’s goals.**   
When new information becomes available, when environmental factors
change, when new technology emerges, or when any other change to the status quo
emerges, the enterprise must have the freedom to quickly respond to those changes.  


Secondary objects cannot be adequately defined until the primary objects have been defined.  

An important aspect of modeling a system at the enterprise level is to clearly and
completely document its external interfaces.  
One reason for this is that any available interface is a potential security vulnerability and understanding which security vulnerabilities exist is the first step in an effective security plan.

**Behaviors** are the manifestation of processes and strategies.

Environmental factors may make it impossible to carry out a process as first envisioned.
Modeling the **environment** is important because the environment has a number of
direct effects on how your enterprise functions:
Can suppliers provide the raw materials needed to sell that many units?
What effects will competitors’ actions have? Are there regulatory concerns such as the
need to satisfy consumer-safety regulations?


The problem is a failure to focus
on the fundamental reason the enterprise architecture was started in the first place: to
help the enterprise achieve its goals.

The architecture team is better off focusing on whether the enterprise is achieving its goals than on how the
enterprise is achieving its goals.

The goals documented for the enterprise should be those that can be directly measured.  
Goals must also be time-bound (realistic):
For example, while increasing the dollar value of sales by 25 percent in a single quarter
might be an unrealistic goal, increasing the dollar value of sales by that amount over
a year is within the scope of possibilities.  
If you are implementing a new customer
relationship management system in the first quarter of the year, it is unlikely that you
will see any significant effect on sales in that quarter because it takes time to install
and configure the software, to train users, and for users to learn how to work with the
new system.

When formulating enterprise goals, keep in mind that goals are really an expression
of what you expect the emergent behaviors of the enterprise to yield:  
**measurable metric**:
increasing the dollar value of total sales by 20 percent in the next year:  
totalSales_currentYear = totalSales_previousYear * 1.20  (beginning January 1st in USD)

What do you hope to get from all this investment of time and resources?

Effective architecture goals must be derived from the enterprise goals. It is best to avoid the trivial sorts of
objectives that are easily met with little effort.  
e.g.:
documenting the profiles of exposed interfaces of all systems in the enterprise:to understand how systems can and do interact with one another, cyberdefenses.  
documenting the data flows across every system-to-system interface in the enterprise: help
understand the data flow through the systems in the enterprise.


As a general rule, processes should initially be modeled without too much detail and
with the expectation that the process will organically change as new behaviors emerge
in the enterprise.


people are more
likely to appreciate the importance of following the process if the reason is clearly
spelled out.

**data is a commodity**  
all data should be modeled the same way.  

Behavior models need to represent real-world activities and events
to the maximum extent practicable; that is, they need to represent how the enterprise
is behaving with enough fidelity to understand how the actors’ interactions with one
another, with systems, and with the environment are producing the observed effects.


Pick a goal, identify the observable effects that
indicate whether the enterprise is making progress toward achieving that goal, and begin
documenting the behaviors that produce the observable effect.If the desired effect is
not observed in the enterprise (i.e., it appears the enterprise is not progressing toward
that goal), then there must be some observable effect that indicates the enterprise is
not achieving that goal—an undesirable effect. Use this effect as the starting point for
modeling the behavior that creates it; from there, you can begin working on changing
that behavior to produce a more desirable effect.


Application and system logs capture many of the information elements that are
important in modeling behaviors.


When modeling interfaces provided by external systems, it is important to
understand all of the functions available from those interfaces, even if they are not
currently in use.

Understanding the externally visible effects of the system, combined with its
interfaces, makes it possible to predict the effects that removing the system or attempting
to replace it will have on the enterprise.


The behaviors that emerge from any complex system are of the most
interest to the enterprise architect.

The modern enterprise is highly dynamic: Teams implement, update, and replace
systems on a nearly continuous basis; management may restructure the organization
periodically; the enterprise may change its mission or business model; and any number
of other changes come and go.


A key characteristic of emergent
behaviors is that they arise spontaneously, making it difficult to predict where and
how they will arise and what parts of the enterprise will be involved.

**modeling language**
UML is very suitable for modeling actors, systems, and aspects of the environment.  
SysML is better suited for most enterprise architecture models.  
I prefer using BPMN to model processes and behaviors because it has a much
richer set of elements for representing workflows than UML or SysML Activity diagrams.  
I use OWL for two primary purposes: modeling data and describing my architecture metamodel.





## Practical Event-Driven Microservices Architecture




## Scalability Patterns Best Practices for Designing High Volume Websites
Mean Time Between Failures (MTBF): This is defined as the difference of Total Time Elapsed and Total Downtime divided by the number of failures.  

MTBF = (Total Time Elapsed - Total Downtime)/(Number of failures)  

Mean Time to Repair (MTTR): This is defined as the average time taken to repair a failed component.

Availability (%) = (Total Time Elapsed - Total Downtime)/(Total Time Elapsed)

## Software Engineering at Google
software engineering task is a team effort.  
even the most innocuous change will break something .  
“It’s program‐ming if ‘clever’ is a compliment, but it’s software engineering if ‘clever’ is an accusation.”   
Practice and expertise are great drivers of efficiency and reliability.  

42