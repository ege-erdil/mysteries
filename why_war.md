## Why do wars happen?

Warfare is a puzzling human activity all around, and there are several unresolved questions about it which are mystifying. 

The first one is why wars happen at all. A good introduction to this puzzle is [Rationalist explanations for war](https://web.stanford.edu/group/fearon-research/cgi-bin/wordpress/wp-content/uploads/2013/10/Rationalist-Explanations-for-War.pdf) by James D. Fearon. As Fearon summarizes,

> The central puzzle about war, and also the main reason we study it, is that wars are costly but nonetheless wars recur. Scholars have attempted to resolve the puzzle with three types of argument. First, one can argue that people (and state leaders in particular) are sometimes or always irrational. They are subject to biases and pathologies that lead them to neglect the costs of war or to misunderstand how their actions will produce it. Second, one can argue that the leaders who order war enjoy its benefits but do not pay the costs, which are suffered by soldiers and citizens. Third, one can argue that even rational leaders who consider the risks and costs of war may end up fighting nonetheless.

While it appears intuitively "obvious" to most people why there should be wars in a world of scarcity and conflicting aims, this obvious fact is in fact not as obvious as it might first appear. Fearon proposes a simple model of a dispute, in which two agents disagree about where the value of some variable x restricted to the closed interval [0, 1] should fall: the first agent has a payoff u(1-x) while the second agent has a payoff v(x), where u and v are two increasing utility functions. They can either choose to compromise at some value of x in between, or they can choose to go to war, in which case the first agent wins with a probability p and the second agent wins with a probability 1-p. The side that wins gets to achieve the optimal outcome for themselves, however there is a fixed cost c of going to war which is wasted.

If the two sides go to war, then the first agent has an expected payoff p u(1-c) + (1-p) u(0), while the second agent has an expected payoff p v(0) + (1-p) v(1-c). Now, if we assume u and v are concave (not necessarily strictly) and strictly increasing, it's clear that both sides are better off compromising at the value x = 1-p than going to war.

This toy model is interesting because it is a proof that one of its features must be violated if war is ever to be a rational choice. Fearon explores several possibilities: perhaps the issues over which wars are fought are indivisible so that no compromises are possible, perhaps agents don't have preferences that can be represented by concave utility functions so that their willingness to take risk overwhelms the costs of war, and perhaps the two sides disagree about their own chance of winning a war. These attempts to resolve the puzzle have their own problems, however.

An alternative account which is popular among people familiar with the [hawk-dove game](https://en.wikipedia.org/wiki/Chicken_(game)#Hawk%E2%80%93dove) is that many real world interactions between governments are essentially like a hawk-dove game in which the two sides are indistinguishable, so the only Nash equilibrium is one in which people play a mixed strategy between hawk and dove, resulting in occasional wars with some arrival rate when two players play hawk simultaneously. The obvious problem with this argument is that the two sides *are* in fact distinguishable in the real world, and under those conditions the hawk-dove game does *not* have a mixed Nash equilibrium: the two equilibria are the ones in which one player plays hawk and the other player plays dove, resulting in no wars being observed in equilibrium.

In our consideration of potential explanations of the puzzle, let's start with the three I listed above.

### Compromises are impossible due to indivisibilities

This view is unfortunately very far off the mark for most wars. Civil wars can be ended in a compromise settlement through a power-sharing agreement or [through](https://en.wikipedia.org/wiki/Second_Sudanese_Civil_War) [partition](https://en.wikipedia.org/wiki/Division_of_the_Mongol_Empire), wars over territory can be ended in compromise by a cash payment from one side to the other in exchange for a territorial concession, and wars for independence can end with the [establishment of an autonomous region](https://en.wikipedia.org/wiki/Treaty_of_Berlin_(1878)) rather than a [fully independent state](https://en.wikipedia.org/wiki/Treaty_of_San_Stefano). Real world disputes are often complex with many dimensions, and it's relatively easy for a halfway decent diplomat to find innumerable options for compromise if the sides are in fact willing to compromise.

I think the assumption that real world issues are divisible is the most realistic one out of all of the toy model's assumptions, so we have to look elsewhere for a solution to the puzzle.

### States effectively have convex preferences

This view is perhaps best exemplified by a quote from Hideki Tojo, succinctly making the case for going to war with the Western powers in a meeting of Japan's privy council on 1 December 1941:

> At this moment, our Empire stands on the threshold of glory or oblivion.

This is, at first, an expression of a convex preference: only what Japan could get from a total victory is worthwhile, and all compromises are unacceptable since they leave Japan with no chance to attain this glory. However, a more sober examination of Japanese policy in the period leading up to the Pacific War reveals that the actual driver the Japanese decision to go to war was not so much the risk-loving nature of the Japanese leadership, but rather their feeling that their chance of winning a war were sufficiently high that going to war was preferable to submitting to the demands of the United States through a compromise. Japan only chose to go to war after many rounds of diplomacy with the United States failed to produce results - hardly the actions of a government which thrives in taking risks.

Convex preferences can also arise from an asymmetry in the exposure of the country's leadership to the costs and benefits of a war. If the leadership can declare war and pocket the gains from the war while suffering no consequences in the event of defeat, then this asymmetric exposure will make the country as a whole behave as if it had a convex preference. However, if we look at what actually happened to the leaders of defeated countries, we see that in many instances they suffered severe personal consequences resulting from their decision to go to war: Hitler was forced to commit suicide, Mussolini was hanged, and Tojo was found guilty by the Tokyo tribunal and executed for war crimes; meaning that the leaders of all three major Axis powers in the Second World War died as a result of their decision to go to war.

Before them, Kaiser Wilhelm II faced the serious prospect of being tried as a war criminal and was saved only by Dutch neutrality, and Napoleon was exiled first to the island of Elba and then to the remote Atlantic island of St. Helena, when he would have most certainly preferred to remain in his position as Emperor of the French. There are even examples from the ancient world; for instance, Hannibal killed three different Roman consuls in the Second Punic War which Carthage ultimately lost, showing that even the leaders of countries which win wars aren't necessarily safe from being killed as a result of the war.

While it is certainly true that the interests of the leaders of a country are almost never aligned with the country's interests as a profit-maximizing entity or with the "general interest" of the people living in the country, this lack of alignment is insufficient to produce a convex preference since the leaders still run large risks of being killed in a war or being thrown out of office or assassinated as the course of the war shifts against them. 

### There is disagreement about the chance of victory

While [Aumann's theorem](http://www.math.huji.ac.il/raumann/pdf/Agreeing%20to%20Disagree.pdf) says that rational disagreement ought to be impossible when the probability estimates of both sides are common knowledge, and our tendency to disagree vehemently is certainly a puzzle in itself, for the purposes of this analysis we can take it for granted that humans disagree all the time on every imaginable issue. Therefore, the assumption that both sides would agree on which side is how likely to win is not unreasonable, with the caveat that the disagreement has to be strong enough to overcome the cost of going to war in order to make a compromise unprofitable.

There's some evidence to lend support to this view: in the paper, Fearon documents the example of the Russo-Japanese War of 1904-1905, in which the Japanese thought that they had a 50% chance of winning a war with Russia while the Russians thought they would almost certainly win a war with Japan. This asymmetry is big enough to overcome even large costs of going to war. Several other wars exhibit patterns that fit this picture as well, though it's unclear to what extent they were decisive. Here is a list of some *potential* examples:

* **Second World War:** The Polish government gave much more credibility to the French promise of a supporting offensive in the event of a German attack on Poland than the German government did. This was an important factor in the failure to achieve a peaceful settlement of the Danzig question.  
  
Later on, both Germany and Japan underestimated the will of the United States government to wage a total war for a prolonged period of time and the warmaking capability of the United States, while the United Kingdom had a much more optimistic view of a potential US intervention. This fundamental difference in opinion arguably played a large part in the failure of diplomatic efforts to secure a peace settlement in Europe in the summer of 1940.

* **First World War:** Significant optimism on both sides about the prospect of a decisive military victory which lasted well into the war, which led to the failure of intermediation attempts by the United States before April 1917.

* **American Civil War:** The belief in the Confederate States that they had good chances to be successful in securing a European intervention on their side, supported by a [retroactive examination](https://www.nber.org/papers/w13567) of bond prices on the Amsterdam market, was not shared by the Union.

The examples may be multiplied - almost every war has some such disagreement about the facts pertaining to the balance of power which may be dug up by a tireless researcher.

There are two main problems with this line of argument:

1. The disagreement about the balance of power exists in peacetime as much as it exists in wartime, at least insofar as we can judge from intelligence reports, declassified documents and public pronouncements of official figures. If so, then why is war sporadic and rare, compared to disagreement about the balance of power which always seems to be large in magnitude, pervasive and widespread? This explanation is incapable of providing an account of the timing of wars, and if anything it seems to suggest that there should be wars happening all the time.

2. In fact we don't know the true credences of the leaders involved in the decision-making process that led to these wars. We know what they *said*, and we have access to some declassified documents, but there's no particular reason to put too much weight on these given that the people who make these forecasts are neither assessed for their predictive accuracy nor have to bet on the odds implied by their probability estimates. A parsimonious interpretation of the facts is that really there *isn't* that much disagreement to begin with. The apparent optimism and confidence exhibited by leaders on both sides of a war can be attributed to their willingness to shore up morale on their side - nobody would like to know that their own leaders believe they are fighting a war in which their chance of victory is slim.

Regardless of its serious shortcomings, I see this as the most convincing out of all of the explanations offered in this exposition - which is to say that the other explanations are even more tenuous than this one.

### In an evolutionary stable equilibrium, there is always war

This one is a very popular argument that people familiar with game theory levy against pacifism. The idea is that we can model conflict by a payoff matrix as follows:

  | War | Peace
------------ | -------------
War | ((V-C)/2, (V-C)/2) | (0, V)
Peace | (V, 0) | (V/2, V/2)

with C and V both positive real numbers. This game is either a [hawk-dove game](https://en.wikipedia.org/wiki/Chicken_(game)#Hawk%E2%80%93dove) or a [prisoner's dilemma](https://en.wikipedia.org/wiki/Prisoner%27s_dilemma) depending on whether C is greater than V or not, in other words on whether fighting is more or less costly than the prize over which the fight happens. The two games have different Nash equilibria. In the case of the prisoner's dilemma, the only equilibrium is one in which both sides play war; while in the hawk-dove game, in the only equilibrium in the presence of uncorrelated asymmetries one side plays war and the other side plays peace. 

The argument is that if we look at the *symmetric* version of the hawk-dove game, then the only equilibrium is one where both sides play a mixed strategy of both war and peace, in which case occasionally we will get random wars occuring, and the probability of war will depend on the exact balance between V and C.

This interpretation is certainly correct, but it has two problems:

1. In the real world there are uncorrelated asymmetries. For example, animals create uncorrelated asymmetries in disputes by marking their own territory and defending it against intruders of the same species, and humans are very much capable of doing the same thing. In this case there is no conflict observed in the Nash equilibrium of the hawk-dove game.

2. In the real world interactions between agents are repetitive, so an adequate model would have to be a repeated game model rather than a single game model, in which commitment strategies are possible to discourage people from going to war. In this case there is an evolutionarily stable Nash equilibrium in which both sides play peace but commit to playing war against "rebels" who try to play war. This pressure is sufficient to dissuade people from playing war, so in equilibrium we would once again observe no conflict. 

We could try to introduce "madmen" into the player pool who just play randomly in order to create some wars, but then we would have to conclude that the only way there would ever be a war between two states is if one of them were being ruled by a madman. This is not a game theoretic explanation of war, since we could just as well explain the existence of war by saying "people are irrational" and not have to consider anything related to game theory.

Perhaps the most charitable interpretation of this line of argument is that while it's true that commitment in repeated game settings can achieve a peaceful outcome, in the real world commitments aren't seen as credible unless they are reinforced by some concrete actions of going to war every once in a while, so every now and then there are wars that occur as a result of a perceived weakness in the commitment of one side to their strategy. Ultimately the theory of Nash equilibrium is based on people agreeing about the probability estimates of which side will play what with what probability, so disagreement about these probabilities simply takes us back to the point about disagreement discussed previously.
