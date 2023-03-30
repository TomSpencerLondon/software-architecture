### Architecture
This is an overview of architecture best practices

### Documenting Software Architectures

- Bird's wing metaphor for describing systems:
```text
How would you "document" a bird's wing for someone who did not
know what it was? A bird's wing, like a software system, can be shown
by emphasizing any of a number of structures-nerves, feathers, bones,
blood vessels, muscles; each structure must be compatible with the
others and must work toward fulfilling a common purpose. Feathers
 are elements that, at a glance, appear to be replicated countless times
 across the wing; on closer inspection, however, the feathers reveal a
rich substructure of their own and small but systematic variations. All
feathers are almost alike, but no two are identical.
```
- Views
```text
And, to understand and reason about the architecture of a software-intensive
system, one has to consider multiple views from the perspectives of
specific concerns from multiple classes of stakeholders.
```
- Multidimensional nature of systems:
```text
We discovered rapidly that architecture is not flat but rather a
multidimensional reality, with several intertwined facets, and some facets 
or views-of interest to only a few parties.
```
- Definition of a view:
```text
A view is a representation of a set of system elements and relationships among them.
```
- Definition of architecture:
```text
Architecture is roughly the prudent partitioning of a whole into parts, with specific relations 
among the parts.
```

- Views and Beyond "Method"
```text
P.2.5 The Views and Beyond "Method"
We call our approach to documentation Views and Beyond. This is
to emphasize that we use the concept of a view-explained in the
next section-as the fundamental organizing principle for architecture
documentation, but also because we go beyond views to include additional information that 
belongs in an architecture document. Views and Beyond is not actually a method. 
It does not have a sequence of steps, with entry and exit criteria for each. 
Rather, it is more a collection of techniques that carry out an underlying philosophy. The philosophy
is that an architecture document should be helpful to the people who depend on it to do their work 
(far from least of which is the architect). The techniques can be bundled into a few categories:
1. Finding out what stakeholders need. If you don't do this, you're going to
  end up with documentation that may serve no one.
2. Providing the information to satisfy those needs by recording design
  decisions according to a variety of views, plus the beyond-view
  information.
3. Checking the resulting documentation to see if it satisfied the needs.
4. Packaging the information in a useful form to its stakeholders.
```
- formula for calculating cost:
```text
A formula to show the savings looks like this:

∑ over every activity A in the project (cost_of_A_without_AD - cost_of_A_with_AD) > cost_of_AD

where "Cost of A without AD" and "Cost of A with AD" are the cost
of performing activity A without and with (respectively) an architecture
document. "Cost of AD" is the cost of producing and maintaining the
architecture documentation. In other words, the payback from good
architecture documentation should exceed the effort to create it. Payback
is measured in terms of effort saved.
```

- Rules for documenting software architecture
```text
These are the rules for any technical documentation, including
 software architecture documentation:
 1. Write documentation from the reader's point of view.
 2. Avoid unnecessary repetition.
 3. Avoid ambiguity.
 4. Use a standard organization.
 5. Record rationale.
 6. Keep documentation current but not too current.
 7. Review documentation for fitness of purpose.
```
- Documenting architecture:
```text

In the Views and Beyond approach, documenting architectural decisions enjoys first-class 
status. When we introduce the templates for software architecture documentation in 
Chapter 10, you will see that they contain dedicated places to record architectural 
decisions. Documenting architectural decisions as you go results in an architecture
that is demonstrably aligned with the business and technical goals of
the system. This is a theme we have tried to emphasize throughout
the book. Documentation isn't something you do after the architecture
is finished. Documenting the architecture helps you design the architecture.
Documenting the decisions as you make them helps you make them

```

#### Interview with Paulo Merson
Interview and Book Review: Documenting Software Architectures: Views and Beyond, 2nd Edition
https://www.infoq.com/articles/merson-documenting-software-architectures-second-edition/

- The book covers different architectural styles like service-oriented architectures (SOA), multi-tier architectures, and data models. The discussion also includes reference guides for three architecture documentation languages: Unified Modeling Language (UML), Architecture Analysis and Design Language (AADL), and Systems Modeling Language (SySML).
- If you create the best software architecture in your head but fail to communicate it to the developers and other stakeholders, what is that architecture worth? As we say in the preface of the book, designing an architecture without documenting it is like winking at a girl in the dark. You know what you’re doing, but nobody else does.

#### wiki on Documenting Software Architecture
https://wiki.sei.cmu.edu/confluence/display/SAD/Main+Page

- View Template
#### Primary Presentation
TODO: Add here the diagram (or non-graphical representation) that shows the elements and relations in this view. Indicate the language or notation being used. If it's not a standard notation such as UML, add a notation key.

#### Element Catalog
TODO: This section can be organized as a dictionary where each entry is an element of the Primary Presentation. For each element, provide additional information and properties that the readers would need that would not fit in the Primary Presentation. Optionally, you can add interface specifications and behavior diagrams (e.g., UML sequence diagrams, statecharts).

#### Context Diagram
TODO: Add here a context diagram that graphically shows the scope of the part of the system represented by this view. A context diagram typically shows the part of the system as a single, distinguished box in the middle surrounded by other boxes that are the external entities. Lines show the relations between the part of the system and the external entities.

#### Variability Guide
TODO: Describe here any variability mechanisms used in the portion of the system shown in this view, along with how and when (build time, deploy time, run time) those mechanisms may be exercised.

Examples of variability include: optional components (e.g., plug-ins, add-ons); configurable replication of components and connectors; selection among different implementations of an element or different vendors; parameterized values set in build flags, .properties files, .ini files, or other config files.

#### Rationale
TODO: Describe here the rationale for any significant design decisions whose scope is limited to this view. Also describe any significant rejected alternatives. This section may also indicate assumptions, constraints, results of analysis and experiments, and architecturally significant requirements that affect the view.

#### Related Views
TODO: Add here links to the parent view and to any children (i.e., refined) views, if they exist.

