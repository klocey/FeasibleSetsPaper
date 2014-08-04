#### Short title: FEASIBLE SETS OF ECOLOGICAL PATTERNS

**VERSION 1**

Uneven distributions of abundance and the aggregation of intraspecific individuals are unifying aspects of ecological theories of biodiversity. 
A recent approach to understanding patterns of abundance suggests that, regardless of how abundance comes to vary among species, most of the possible outcomes are uneven and similar. 
We show how the same is true for spatial distributions, and hence, why these patterns are unifying. 
That is, uneven distributions of abundance and aggregated spatial distributions are "mechanism-free" patterns because most of the observable outcomes, i.e. the feasible set, have the same general appearance, regardless of how they can arise. 
We improve the efficiency of previous methods, define the feasible sets of additional patterns, and provide open source software for making feasible sets more tenable. 
Many ecological patterns are likely to have a mechanism-free component that accounts for their general form and universal nature, but leaves a substantial degree of variation to account for.   

However, before curve fitting can be invoked as support for a theory, it is important to account for how strongly constrained a pattern is byprimary  variables thatmay  also serve as model inputs.
For example, the shape of the species abundance distribution (SAD) can often be explained by the majority of possible SAD shapes having the same total abundance (*N*) and species richness (*S*), i.e. the SAD feasible set. 
The SAD feasible set reveals how *N* and *S* constrain the shape of the SAD and whether the variation that is possible is sufficient for interpreting the SAD shape in terms [DM: don't we mean 'in lieu' here?] of ecological mechanisms or random sampling.
We present a conceptual road map for applying the feasible set approach to 1.) explore how general variables constrain observable variation in the shapes of other ecological patterns, and 2.) examine how the shapes of several ecological patterns are mathematically coupled. [DM: we had discussed trying to put the feasible set into context so that ecologists better know how the feasible set approach compares conceptually to tools such as randomization based null models and/or a neutral model approaches - this may be lower hanging than our current #2] [KL - I think this is important, but not simpler]
Additionally, we extend the SAD feasible set to the species spatial abundance distribution (SSAD) using modifications to a previous approach, drastically improving computing speed.
The SSAD feasible set reveals a constraint-based explanation for general patterns in the SSAD and how the shape of the SSAD is mathematically coupled to the shape of the SAD.
Finally, 
We provide Python and R based implementations along with testing software for our methods. 