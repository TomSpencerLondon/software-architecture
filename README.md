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

$$ Σover all activities A = (Cost of A without AD - Cost of A with AD) > Cost of AD $$

 where "Cost of A without AD" and "Cost of A with AD" are the cost
 of performing activity A without and with (respectively) an architecture
 document. "Cost of AD" is the cost of producing and maintaining the
 architecture documentation. In other words, the payback from good
 architecture documentation should exceed the effort to create it. Payback
is measured in terms of effort saved.


```