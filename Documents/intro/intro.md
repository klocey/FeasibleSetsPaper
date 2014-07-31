##### INTRODUCTION
Understanding patterns of abundance, distribution, and diversity is a primary goal in ecology (Brown 1995; Rosenzweig 2002; Blackburn & Gaston 2003). 
These macroecological patterns characterize aspects of community structure and are frequently used to provide insight into mechanisms that shape communities.
Likewise, the ability to predict the shapes of macroecological patterns serves as the primary basis for evaluating ecological theories (e.g. MacArthur & Wilson 1967; Scudo & Ziegler 1978; May 1981; McGill 2003; Hubbell 2001; Harte 2011).
Difficulty in comparing disparate theories arises when very different theories predict similarly shaped patterns.
This may be due to the fact that although the theories differ in which mechanisms they invoke (e.g., niche partitioning, metacommunity dynamics, stochastic population dynamics, random sampling) they all share a similar set of quantitative variables as inputs (e.g., number of species and total abundance) (McGill 2010). 

General variables like total community abundance (*N*) and species richness (*S*) can strongly influence the shapes of ecological patterns (Harte et al. 2008; McGlinn & Hurlbert 2012; Supp et al. 2012; White et al. 2012; Locey & White 2013).
For example, more than 90% of observed variation in the species abundance distribution (SAD), the vector of abundances of species in a community (McGill et al. 2007), can be explained using statistical models constrained only by *N* and *S* (Harte 2011; White et al. 2012).
In fact, the majority of possible SAD shapes having the same *N* and *S* (the SAD feasible set) can often explain the general shapes of empirical SADs apart from any assumptions about ecological mechanisms or random sampling (Locey & White 2013). 
The feasible set acknowledges that regardless of *how* the shape of a pattern could arise, whether by ecological mechanism or random sampling, there only so many possible shapes of a pattern that *can* arise.
The feasible set allows us to examine whether the shape of an observed ecological pattern can be explained by the variation in the shapes that are possible.The feasible set approach is potentially applicable to many ecological patterns and should be extended beyond examinations of the SAD in terms of *N* and *S*.
The species spatial abundance distribution (SSAD) is the next logical extension of the feasible set approach used to examine the SAD.
The SSAD describes the frequency with which individuals of a species occupy areas within a landscape (Brown et al. 1995; Harte et al. 2008; Haegeman & Etienne 2010; Harte 2011).
The SSAD reflects aggregation across a landscape and is mechanistically linked to the SAD and other patterns (Brown et al. 1995; Harte 2011).
Like the SAD, the SSAD can be defined as a vector, i.e., of the abundances of a single species for all sites in a landscape.
Unlike the SAD, where each species has a non-zero abundance, the SSAD can contain zero values because individuals can be absent from areas of the landscape. 
Examination of the SSAD feasible set will not only provide a second example of how the shapes of ecological patterns are constrained by general variables, but will reveal how the shapes of ecological patterns are mathematically coupled.
	
The purpose of this study is to provide a conceptual road map for applying the feasible set approach, to extend the existing feasible set appraoch to the SSAD, and to introduce more efficient sampling algorithms for constructing feasible sets. 
Our examination also reveals that the shapes of the SAD and SSAD are mathematically coupled by the properties of their feasible sets.
In the process of examining the SSAD feasible set, we find that small modifications to the approach of Locey and White (2013) can lead to drastic increases in the efficiency of generating random samples from feasible sets that are otherwise computationally untenable.
We provide these computational tools in R and Python along with testing software.