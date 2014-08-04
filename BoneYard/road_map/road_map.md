The purpose of this study is to provide a conceptual road map for applying the feasible set approach to understanding variation in the shapes of ecological patterns, to extend the existing feasible set appraoch to the SSAD, and to introduce more efficient sampling algorithms for constructing feasible sets.

#### A conceptual guide to the feasible set

**Understanding the shapes of patterns:**
Much of ecology is pattern oriented. 
More specifically, much of ecology is oriented on the shapes of patterns.
Regularities in the shapes of unlabeled statistical curves and frequency distributions have provoked some of the most long-standing and intensively studied questions in ecology.
Indeed, the influence of a process or mechanism is more often explored in the shape of a pattern, than it is observed in action.
And more often than not, it is the shapes of patterns that ecological theories predict and are tested against.

Despite ecology's focus on the processes and mechanisms that drive the shapes of patterns, ecologists rarely ask how the patterns they study are limited in shape. Yet, attention to the feasible set suggests that some of ecology's general patterns can be constructed solely from inputs that are common to the ecological theories (Table 1).
For example, *N* and *S* are common inputs to theories used to predict the form of the SAD, the success of which is attributed to the mechanisms or processes that underpin the theory.
Yet, all possible shapes of the SAD can be constructed from *N* and *S* to reveal that most of the possible shapes strongly resemble that of the observed pattern (Locey and White 2013).

**Putting predictions into perspective:**
An ecological theory or model requires inputs that contribute to the form of predicted patterns, and hence, to a model or theory's predictive power.
These inputs can be observed values or fitted parameters.
While the success of a model is generally attributed to the processes and mechanisms that underpin it, the influence of the inputs is generally ignored except to address over-parameterization or over-tuning.
That is, when a model contains enought tunable parameters or enough information that a good fit is almost certain, but trivial.

As an example, Haegeman and Loreau (2008) used a feasible set approach to show that ecological MaxEnt models can include so much information the predicted SAD is drawn from a feasible set with only one SAD shape in it, i.e., the observed SAD.
In this way, the feasible set was an effective tool that demonstrated how the accurate predictions of a MaxEnt model (Shipley et al. 2006) were not necessarily powerful or meaningful.
This is an important issue in ecology and the feasible set provides a clear way to address it. However, the feasible set has even more important and novel implications for interpreting ecological predictions, specifically in regards to how we interpret comparisons to random samples and null models.

What does it mean when a prediction provides a better fit than 99% of a random sample when there are countless random sampling methods and each produces samples with different statistical properties? We can draw random samples from different statistical distributions, randomly permute data structures (e.g. site by species matrices), and simulate systems using stochastic null models. In the end, we compare our observed and/or predicted pattern to a random set of biased outcomes.
What if, instead, we used the set of all possible outcomes or an *unbiased* sample of it, and concluded that the predicted pattern is more similar to the observed pattern than 99% of all possible alternative outcomes having the same input values? We will have, at least, shown that the mechanism of our model could be more responsible for the pattern we observed, than the inputs.

**A context for constraints:**
What if 90% of the variation in an observed pattern is explained by the vast majority of 10<sup>10</sup> possible outcomes?
This is what Locey and white (2013) showed when using the SAD feasible set based on total community abundance *N* and species richness *S* to examine nearly 1600 SADs for breeding birds of North America. 
Their intent was not to challenge the predictions of any particular theory, but to explore the statistical characteristics of the SAD when constrained by *N* and *S* and to explore whether the general shape of the SAD could be explained by the majority or average member of the feasible set.
In this way, they used the feasible set as a context for understanding the influence of constraints on the observable variation. 

**The feasible set: the sampling universe for null models:**
This is basically how I view the feasible set in regards to null models. 
That is, just like MaxEnt infers the most likely macrostate from a feasible set, so does, I think the MLE for every other model. 
MaxEnt is the easiest case for me to envision, next are permutations of site-by-species matrices, uniform random sampling, binomial-multinomial random sampling, and so on.