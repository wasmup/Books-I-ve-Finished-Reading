# Books-I-ve-Finished-Reading
Books I've Finished Reading

## Complex Enterprise Architecture by John D. McDowall
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