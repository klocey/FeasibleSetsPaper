##### INTRODUCTION

**Paragraph 1:** The aggregation of intraspecific individuals in space, the independence of interspecific individuals in space, and the uneven distributions of abundance among species are unifying assertions of unified theories of biodiversity (McGill 2010). Moreover, these assertions are presumably the minimally sufficient set of assertions or rules needed to predict or explain a host of general biodiversity patterns. However, as of yet, only one of these unifying assertions, the uneven distribution of abundance, has been given a general explanation, which is likewise based on first principles (Locey and White 2013). 

**Paragraph 2:** A recent approach to understanding patterns of abundance suggests that, regardless of how abundance comes to vary among species, most of the possible outcomes are uneven and similar. Feasible set..."mechanism-free". From this perspective, this unifying aspect of ecological theories of biodiversity is unifying simply because it almost inevitably occurs regardless of the ecological or statistical mechanism.

**Paragraph 3:** Aggregated spatial distributions are another unifying aspect of ecological theories of biodiversity. Like distributions of abundances among species, distributions of a species abundance across a landscape should also have a feasible set characterizing the set of observable outcomes. Because many spatial patterns are generated from discrete samples and discretized landscapes, feasible sets for these patterns should be amenable to an approach like that used by Locey and White (2013). 

**Paragraph 4:** The feasible approach to SADs suggests an explanation for the universality of the hollow-curve distribution of abundance (Locey and White 2013). We expand this approach ask whether the characteristics of the feasible set for the species spatial abundance distribution SSAD (i.e. the vector of patch or sample abundances of a species across a landscape) explain the aggregated (or uneven) nature of this pattern. In doing so, we improve previous methods and provide open source software for making feasible sets more tenable. We conclude that many ecological patterns are likely to have a mechanism-free component that accounts for their general form and universal nature, but leaves a substantial degree of variation to account for.




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