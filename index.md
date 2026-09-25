---
layout: default
---
### About me

I am a postdoctoral researcher at Inria Saclay in team Partout, supervised by [Kaustuv Chaudhuri](https://chaudhuri.info/) on the AEx project IMPROOF.
Previously I did my PhD at the University of Bath in the mathematical foundations group of the computer science department, supervised by [Alessio Guglielmi](http://alessio.guglielmi.name/).

&emsp; My research is in structural proof theory, in particular the deep inference methodology for the design of proof formalisms with good properties in complexity, normalisation, and semantics. Deep-inference proof formalisms generalise sequent calculus systems by allowing more free composition of proofs, and therefore a larger collection of objects as proofs. In this larger collection, we can find better canonical representatives, better normalisation procedures, and smaller cut-free proofs.

&emsp; I am particularly interested in proof compression mechanisms that are orthogonal to the presence of cut, such as factoring repeated parts of proofs into explicit substitutions. I often work in subatomic proof systems, where the propositional atoms become logical connectives whose arguments are their truth values and the structural and logical inference rules of proof systems can be given by a common rule scheme. This increases the syntax of a proof system, but paves the way for a more general theory of normalisation, given by the relations between connectives.

### Publications

*   [Proof Compression via Subatomic Logic and Guarded Substitutions](https://arxiv.org/abs/2505.20009#) <br/>
&emsp; Joint work with Alessio Guglielmi, Ben Ralph, and Lutz Straßburger <br/>
<br/>
&emsp; Subatomic logic is a recent innovation in structural proof theory where atoms are no longer the smallest entity in a logical formula, but are instead treated as binary connectives. As a consequence, we can give a subatomic proof system for propositional classical logic such that all derivations are strictly linear: no inference step deletes or adds information, even units. In this paper, we introduce a powerful new proof compression mechanism that we call guarded substitutions, a variant of explicit substitutions, which substitute only guarded occurrences of a free variable, instead of all free occurrences. This allows us to construct “superpositions” of derivations, which simultaneously
represent multiple subderivations. We show that a subatomic proof system with guarded substitution can p-simulate a Frege system with substitution, and moreover, the cut-rule is not required to do so. <br/>
&emsp; Presented at [LICS 2025](https://lics.siglog.org/lics25/)

*   [A strictly linear subatomic proof system](.\assets\Papers\A strictly linear subatomic proof system.pdf) <br/>
&emsp; Joint work with Alessio Guglielmi and Ben Ralph <br/>
<br/>
&emsp; We present a subatomic deep-inference proof system for a conservative extension of propositional classical logic with decision trees that is strictly linear. In a strictly linear subatomic system, a single linear rule shape subsumes not only the structural rules, such as contraction and weakening, but also the unit equality rules. An interpretation map from subatomic logic to propositional classical logic recovers the usual semantics and proof theoretic properties. By using explicit substitutions that indicate the substitution of one derivation into another, we are able to show that the unit-equality inference steps can be eliminated from a subatomic system for propositional classical logic with only a polynomial complexity cost in the size of the derivation, from which it follows that the system p-simulates Frege systems, and we show cut elimination for the resulting strictly linear system. <br/>
&emsp; Presented at [CSL 2025](https://csl2025.github.io/)


### Unpublished Papers

*   [A fully local proof system for first-order logic](.\assets\Papers\lfo.pdf) <br/>
&emsp; Joint work with Kaustuv Chaudhuri <br/>
<br/>
&emsp; Under review.


### Thesis

*   [A Strictly Linear Proof System for Propositional Classical Logic](/assets/Papers/Thesis.pdf) <br/>
<br/>
&emsp; We present a proof system for a conservative extension of propositional classical logic with decision trees that is strictly linear. This means that not only there are no structural rules such as contraction and weakening but there are no rules for unit equalities either, and there is no negation. Yet, its classical semantics and proof-theoretic properties can be recovered via an interpretation map at a polynomial cost. Moreover, this system can p-simulate substitution Frege. Those results are made possible primarily by two technical advances: 1) an ‘Eversion Lemma’, that guarantees extreme flexibility in manipulating formulae to match a given logical context, and 2) a form of explicit substitution for derivations into derivations. We argue that this proof system represents a significant step towards a notion of factorisation for proofs. That will hopefully lead us to a semantics of proofs adequate to solve the proof identity problem.


### Teaching

*   [A Gentle Introduction to Deep Inference](https://www.lix.polytechnique.fr/~lutz/orgs/ESSLLI2025-course.html) <br/>
&emsp; 5 day introductory course at [ESSLLI 2025](https://2025.esslli.eu/courses-workshops-accepted/course-information.html#C14) <br/>
&emsp; Presented jointly with Lutz Straßburger


### Organisation
*   [Sixth International Workshop on Structures and Deduction 2026](https://www.lix.polytechnique.fr/~lutz/orgs/SD26.html) <br/>
&emsp; Co-organised with Lutz Straßburger <br/>
&emsp; Workshop affiliated with LICS 2026 at the Federated Logic Conference (FLoC)


### Talks

*	An introduction to deep inference <br/>
&emsp; Invited tutorial at the [8th International School on Proof Theory](https://proofsociety26.sciencesconf.org/) <br/>
&emsp; Slides available [here](/assets/ps.pdf)

*   Linearity and Deep Inference <br/>
&emsp; Invited tutorial at Trends in Linear Logic and Applications workshop 2025



