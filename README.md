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