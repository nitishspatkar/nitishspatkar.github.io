## Moldable Requirements

Requirements engineering is a sequential as well as a cyclic process. Several stakeholders motivated to make a project successful are ready to go on a battlefield with their favorite tools in their arsenal. Sadly, enabling coordination or collaboration between these highly motivated stakeholders also means making their tools interact with each other.

![RE process: it is sequential and cyclic, with many stakeholders and tools](images/benevol-demo.png)

I argue that the requirements must be specified, managed, and implemented in a single environment. 
Such an approach will be useful only when representations of requirements are adapted (i.e., molded) to suit the needs of various technical and non-technical stakeholders. 
Provided right interfaces, an IDE can be an excellent venue for such a confluence of static requirements and live domain objects. 

With Moldable Requirements, requirements are specified, maintained, and implemented as first-class citizens within an IDE.
To achieve that, requirements hierarchies, as well as their representations, are molded to suit the application domain and project needs. 
Developers first create custom requirements hierarchies, i.e., from high-level epics down to concrete scenarios.
Next, developers build interfaces, such as graphical ones, that enable other stakeholders to create, access, and navigate the corresponding requirements. 
Developers also craft domain-specific representations for the involved domain entities in the requirements.
The same approach allows us to represent design models, such as a use case diagram, as just another representation of a particular instance of a use case.

Curious? Check out the proposal for [Moldable Requirements](http://scg.unibe.ch/archive/papers/Patk20c.pdf)