---
layout: default
---

### Publications

*   [Proof Compression via Subatomic Logic and Guarded Substitutions](https://arxiv.org/abs/2505.20009#) <br/>
&emsp; Joint work with Alessio Guglielmi, Ben Ralph, and Lutz Straßburger <br/>
<br/>
&emsp; Subatomic logic is a recent innovation in structural proof theory where atoms are no longer the smallest entity in a logical formula, but are instead treated as binary connectives. As a consequence, we can give a subatomic proof system for propositional classical logic such that all derivations are strictly linear: no inference step deletes or adds information, even units. In this paper, we introduce a powerful new proof compression mechanism that we call guarded substitutions, a variant of explicit substitutions, which substitute only guarded occurrences of a free variable, instead of all free occurrences. This allows us to construct “superpositions” of derivations, which simultaneously
represent multiple subderivations. We show that a subatomic proof system with guarded substitution can p-simulate a Frege system with substitution, and moreover, the cut-rule is not required to do so. <br/>
&emsp; To be presented at [LICS 2025](https://lics.siglog.org/lics25/)

*   [A strictly linear subatomic proof system](.\assets\Papers\A strictly linear subatomic proof system.pdf) <br/>
&emsp; Joint work with Alessio Guglielmi and Ben Ralph <br/>
<br/>
&emsp; We present a subatomic deep-inference proof system for a conservative extension of propositional classical logic with decision trees that is strictly linear. In a strictly linear subatomic system, a single linear rule shape subsumes not only the structural rules, such as contraction and weakening, but also the unit equality rules. An interpretation map from subatomic logic to propositional classical logic recovers the usual semantics and proof theoretic properties. By using explicit substitutions that indicate the substitution of one derivation into another, we are able to show that the unit-equality inference steps can be eliminated from a subatomic system for propositional classical logic with only a polynomial complexity cost in the size of the derivation, from which it follows that the system p-simulates Frege systems, and we show cut elimination for the resulting strictly linear system. <br/>
&emsp; Presented at [CSL 2025](https://csl2025.github.io/)


### Thesis

*   [A Strictly Linear Proof System for Propositional Classical Logic](.\assets\Papers\Thesis.pdf) <br/>
<br/>
&emsp; We present a proof system for a conservative extension of propositional classical logic with decision trees that is strictly linear. This means that not only there are no structural rules such as contraction and weakening but there are no rules for unit equalities either, and there is no negation. Yet, its classical semantics and proof-theoretic properties can be recovered via an interpretation map at a polynomial cost. Moreover, this system can p-simulate substitution Frege. Those results are made possible primarily by two technical advances: 1) an ‘Eversion Lemma’, that guarantees extreme flexibility in manipulating formulae to match a given logical context, and 2) a form of explicit substitution for derivations into derivations. We argue that this proof system represents a significant step towards a notion of factorisation for proofs. That will hopefully lead us to a semantics of proofs adequate to solve the proof identity problem.