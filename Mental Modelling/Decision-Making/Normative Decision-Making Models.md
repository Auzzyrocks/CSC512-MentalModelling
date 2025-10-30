The following are examples of normative decision-making models. These models describe a perfectly rational agent, in that they depict exactly how a human being should reason given that they are fully informed and perfectly consistent. These models are **idealized** mental models. 
# Expected Utility Theory
This theory states that a rational decision-maker weighs potentials by creating expected utility values as well as calculated probability, such that decisions will always be the most rational. Expected Utility is calculated as a function of the summation of all possible probabilities of an event multiplied with the utility of the outcome. The most rational decision to be made is then the option with the highest calculated utility. 

![[Expected Utility Formula.png]]

In practice, this model can account for human deviations from expected value. Suppose one was offered a choice between either option A: a 50% chance to gain $100, or a 50% chance to gain nothing, or option B: a 100% chance to gain $40. The expected value of the first option is greater: 0.5(100) + 0.5(0) = 50 vs. 40, however most would choose option B. Suppose then that our utility function, U(x), is $\sqrt{x}$. Then we have EU(A) = 0.5($\sqrt{100}$) + 0.5($\sqrt{0}$) = 5 vs. EU(B) = $\sqrt{40}$ = 6.32. In this instance money has a utility value that supersedes expected value, and a participant tasked with this judgement would typically prefer to take a guaranteed amount rather than risk a "loss" to potentially receive more. This model can additionally represent differing attitudes, with risk averse being previously represented, risk seeking (convex), or risk neutrality. 
# Bayesian Decision Theory
### Bayes Theorem 
For two events A, B, where B has a non-zero probability, we have the following:
![[Bayes Theorem.png]]
P(A) is the prior probability of A, P(B | A) is the likelihood of B when A is true, P(A | B) is the posterior probability of A when B has occurred, and P(B) is the total probability of B. 
### Bayesian Decision Making Models
A framework for decision-making with the presence of uncertainty. Bayesian Decision Theory combines a model of one's beliefs about uncertain states in the world, and a model of one's preferences or goals (as utilities and losses). Collected evidence is used to update beliefs, and actions are chosen that either maximize expected utility, or minimize expected losses, per their beliefs. Before evidence is sourced, a decision-making agent has a set of states that represent how the world may be. Additionally, they have a probability distribution over these states which are their beliefs. Data or evidence can be sourced, which have their own probabilities. By Bayes' theorem, the prior distribution is updated to a posterior distribution, to reflect the change in belief based on evidence. The agent additionally has a set of actions. For each possible action and state, there is a utility function. Following the updated beliefs, the agent can then choose the maximum expected utility via this function: 
![[Bayesian Expected Utility.png]]
Where we have that expected utility is a function of the summation of all states w, factoring 
P(w | x) and U(a, w). which are the likelihoods of evidence (x) given state (w), and the maximum utility function U(a, w), which considers the best action given the post-evidence state. 

This model differs from Expected Utility in that it additionally considers evidence and the possibility of beliefs being updated. The agent has well-defined probabilities, likelihoods for how evidence can arise from given states, and set utility functions. 
## References
- Binmore, K. (2017). _On the Foundations of Decision Theory_. _Homo Oeconomicus_, 34(4), 259-273. https://doi.org/10.1007/s41412-017-0056-1
- Hansson, S. O. (1994). _Decision theory: A brief introduction_ [PDF]. Uppsala University. [https://people.kth.se/~soh/decisiontheory.pdf](https://people.kth.se/~soh/decisiontheory.pdf
- Joyce, J. (2003, June 28; rev. 2003, September 30). _Bayes’ Theorem_. In E. N. Zalta (Ed.), _Stanford Encyclopedia of Philosophy_. Retrieved from [https://plato.stanford.edu/entries/bayes-theorem/](https://plato.stanford.edu/entries/bayes-theorem/?utm_source=chatgpt.com)
- Schoemaker, P. J. (1982). _The expected utility model: Its variants, purposes, evidence and limitations._ _Journal of Economic Literature, 20_(2), 529-563. Retrieved from https://www.jstor.org/stable/pdf/2724488.pdf
