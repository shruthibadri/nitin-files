#books #clipping #annotation

[Diversity and Complexity](https://press.princeton.edu/books/paperback/9780691137674/diversity-and-complexity) 
Page, Scott E.. Diversity and Complexity. Ukraine: Princeton University Press, 2010.

### Introductory Chapter 
- Interplay between [[diversity]] and complexity; lies "at the core of the many challenges we face - managing ecosystems, organisations and economies."
- "Too much diversity...can produce catastrophe or inefficiency. Even if on the balance diversity is a good thing, we can have too much of it" 
- Diversity can
	- provide insurance
	- improve productivity
	- spur innovation
	- enhance robustness,
	- produce collective knowledge 
	- sustain further diversity
- Diversity can also
	- collapse
	- conflict
	- incomprehensible mangles
- Categories
	- variation within a type
	- differences across types
	- differences between systems or communities
- In empirical analysis, quantile regression techniques are better than averaging; instead of estimating the society's mean, more useful to look at the median person in the bottom fifth of the distribution etc
- Single aggregate variable cannot approximate a complex system with feedbacks
- Causes and constraints of diversity
- [[Complex systems]] are collections of diverse, connected, interdependent entities whose behaviour is determined by rules, which may adapt, but need not. The interaction often produces phenomena that are more than the parts. Such phenomena are called "emergent." #definition 
- Most [[Complex systems]] are not predictable, except in the very short run. Although often robust and stable, complex system can produce large events like mass extinctions and stock market crashes more often than Gaussian normal.
- Broad claims that hold true:
	- diversity often enhances the robustness (ie ability to maintain functionality) of complex systems
	- diversity drives innovation and productivity; 
		- for [[ecosystem productivity]], size, scale and other factors matter
		- productivity increases due to averaging (as in antenna diversity) and diminishing returns to type
		- [[followup]] =="when we don't see diverisity producing benefits -- such as in some diverse groups of people -- we should go looking for a cause"== eg inability to communicate or a lack of trust [[a-ha]] #insight 
	- "When interactions were few and far between, the resulting systems were more episodic than complex." We are dealing with complex systems in the [[notebook/Information Age]]
	- "to harness diversity, identify lever points -- points in time at which intervention can have large effects."

### Chapter 1 
- #definition Diversity - three (imperfect) types of diversity 
	- _variation_ in some attribute
	- _diversity_ of types, kinds or categories
	- differences in composition or configuration
		- modularity
- #definition Systems that produce [[complexity]] "consist if diverse rule-following entities whose behaviours are interdependent"; interaction over a network; often adapt.
- Complexity lies between order and disorder, between order and randomoness. 
- Complex systems contain contradictions: robust, yet capable of large events; can attain equibria yet produce long random sequences.  
- In a barter market: diversity in endowments, preferences and adaptation to information. If diversity is zero, no trade. Diversity in at least one of these dimensions is _necessary_ for trade. #mythoughts lack of diversity is a cause of [[market failure]] 
- Complex (non-adaptive) systems and [[notebook/Complex Adaptive Systems]]
- Complex Adaptive Systems
	- Core attributes: diverse, interdependent, networked entities that can adapt
	- individuals and types adapt; system doesn't; system level adaptation occurs when individuals alter their behaviours
	- even if individuals are selected for better performance, no guarantee that system performance will improve; as in the [[tragedy of the commons]]
	- [[Emergence]] refers to higher order structures and functionalities that arise from the interaction of entities in a complex system. 
	- Complexity - interesting behaviour produced by interactions of simple parts; Emergence - simpler higher order behaviour that arises from underlying complexit.  
	- Wolfram 2002 classifies systems as producing four types of outcomes: fixed points (equilibria), simple structures/periodic orbits, complexity or randomness. 
- Measuring Complexity
	- Description Length - the more words you need to describe an event, the more complex that event probably is. 
	- [[Kolmogorov complexity]] the minimum length of a program written in the description language that produces the desired sequence of symbols. #definition 
	- Choice of language doesn't matter if what we're describing is reasonably complex 
	- Description length assigns high value to random sequences (ie if we try to describe a random sequence we'll use a lot of words, when it's shorter to say "it's random" )
	- Gell-Mann and Lloyd modify the description length to "strip away randomness and count only what's left", effectively the "length of a highly compressed description of its regularities"
	- Complexity can be measured as the difficulty of generating the sequence: logical depth (min number of steps) or thermodynamic depth (number of steps in the most plausible sequence of events)
	- [[Statistical complexity]] Crutchfield and Young -- how difficult is it to predict the sequence as accurately as possible 
- Defining Complexity #definition 
	- BOAR - Between Order And Randomness
	- DEEP - Cannot be easily Described, Evolved, Engineered or Predicted
- Chaos is not randomness but an extreme sensitivity to initial conditions; many chaotic systems are completely deterministic.
- "Complex systems that produce randomness are extremely sensitive to initial conditions" 
	- #mythoughts This squares with my [[Basic Trinity]] where chance, course and choice determine the outcomes. 
- Complexistan is a triangle bounded by the Sea of Order, the Ocean of Chaos and the River of Randomness 
- p36 "when we ramp up the amount of diversity, the set of possible outcomes grows enormous"
- p36 "increases in variation and diversity can increase complexity but they typically won't have big effect on ordered systems unless they tip them out of the ordered region, or on random systems"
- Nowak and May's Prisoner's Dilemma (N actors on an NxN grid wrapped on a torus, each can change their choice in round K+1 depending on the payoffs they observe in round K)
	- Stable regions of cooperators & defectors with chaotic boundaries
	- Multiple regions, different states: some fixed, some period and others chaotic. The overall system is complex. 
- Diversity and complexity go hand in hand; but a system can be complex without having diverse parts. "Complexity requires little diversity in the parts, provided there are enough parts" and if they are interdependent. 
- #mythoughts Ergo: India would be a complex system even if it were little diverse, because it has a large number of people. 
- Simple non-diverse parts produce higher order parts that are diverse; and this makes the system complex. In other words #point fundamental diversity is not necessary for complexity; emergent diversity is. 
- Complexity is produced by the "rules of interaction" that must interact in particular ways. 
- "Complex systems are assembled through selection. Only entities that function well within the system survive."
- Effects of diversity
	- Hard to tease out because of three problems:
	- 1 multiple causes - correlation is not causation
	- 2 sample definition 
	- 3 selection (squared) bias 
- Stability v Robustness
	- Stability: system goes back to equilibrium if the population size is changed
	- Robustness: survives environmental shifts and loss/addition of species
	- The flu virus is unstable but robust; hence can't be eradicated by vaccine. 

### Chapter 2 

Measuring Diversity
-	Five types of measures
	-	for diversity within a type - variation, using variance and standard deviation
	-	for diversity across types - [[entropy]], distance, attribute
	-	for diversity of community composition - population measures 
-	Entropy measures, a family of measures, capture both the number of types and evenness of distribution across those types, but do not take into account the extent of differences between the types. 
-	Shannon's entropy is commonly used. 
-	Distance measures; use a distance function that captures the number of dimensions in which two things can be different
-	Attribute measures - identify attributes of each type in the set and count up the number of unique attributes.

Taxonomies and Typologies
- taxonomy classifies based on hierarchy; typology based on attributes
- types are socially, politically and economically constructed 

### Measurement Issues
- By definition, variance (sigma-squared) is high when data points are bunched towards the extremes. If we use this measure to assess the claim that "greater diversity improves adaptation of a species" we could get misleading results: for increasing variation from zero to a certain point will increase adaption, but dialling it to max will not. That's because at max variance, data points are _bunched_ at the extremes. 

### Generalised Entropy Function, G
 α = 0, G = N (or the number of types)
 
 α = 2, is the [[Diversity Index]], which is the empirical form of the [[Herfindahl Index]] [[Simpson's Index]]. Inverse of the Diversity Index is the probability that two randomly selected members of the population will be of the same type. 
 
### Creation and evolution of diversity Ch 3
- [[Zero-Force Evolutionary Law]] per McShea and Brandon: In the absence of constraints and selection, evolutionary systems will tend to produce more and more diversity; and in turn complexity. 
- Causes of variation (diversity within type)
	- mutation
	- inversion
	- recombination 
	- transfer
	- representational diversity - ==this is interesting for us== when we have multiple ways of representing something; a small change in a thing leads to wider diversity. "different representations of the same product create different likely mutations"
- Causes of diversity across types
	- isolation
	- rugged landscapes
	- coupled or dancing landscapes
	- local interactions
	- temporal variation
	- coordination
- Rugged or Dancing Landscapes
	- if a type does not have a sufficient elevation, it dies out (ideas with few followers die out)

### Concluding chapter
- "..a scientific and logical approach shows that diversity is no panacea. Too much diversity prevents meaningful structure from emerging; introduction of new species, products and ideas can destroy as well as create."
- The right amount and types of diversity depend on many attributes of a system -- connectedness, interdependencies and rates of adaptation -- and they may change over time. Diversity must strike a balance: between exploring and exploiting, redundancy and novelty, searching for the new and innovative and simply enjoying the present


## Colophon
Status: [[Brewing]]

	