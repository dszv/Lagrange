---
layout: post
title: "Measurement in Quantum Mechanics"
author: "Diego S"
categories: journal
tags: [sample]
image: cards.jpg
---
The question of carrying out measurements in quantum-mechanical systems and an interpretation of the results so obtained is rightly considered to be very complicated, requiring even today further research. We shall not given a detailed analysis of the problem of quantum-mechanical measurements, but shall try to describe a number of fundamental statements which have been explained clearly, and demonstrate them using some examples. 

## The Origin of the Superposition of States and the Meaning of the Amplitudes of States

Suppose that a micro-particle is in a certain state $$\langle \alpha \mid $$. According to the principle of superposition, the state $$ \langle \alpha \mid $$ may be expanded in terms of any system of basic states, for example, in the $$ \{ \mid\!\! \beta_i \rangle \} $$:

$$
\begin{equation}\label{T11.1}
\langle  \alpha | = \sum_i \langle \alpha | \beta_i \rangle \langle \beta_i | \tag{1}
\end{equation}
$$

The numbers $$ \langle \alpha \!\!\mid\!\! \beta_i \rangle $$ in the superposition above are essentially the amplitudes of the states $$ \langle \beta_i \mid $$ or, more accurately, the amplitudes of the probabilities with which the various basic states $$ \langle \beta_i \mid $$ are "represented" in the state $$ \langle \alpha \mid $$.

It is appropriate now to make things more precise.

Firstly, we shall note that any definite superposition of states in a micro-particle arises as a result of its interaction with the surroundings. The latter may be some macroscopic body (which is either produced artificially or is a part of the natural external conditions). This macroscopic body is referred to as the _analyzer_. The expression $$\eqref{T11.1}$$ should be interpreted in the following way: as a result of the interaction with a particular analyzer (in this case, we may speak of a $$\beta $$-analyzer), a micro-particle lying in the state $$\langle \alpha \mid$$ is transformed into the superposition state $$\sum _i \langle \alpha \!\!\mid\!\! \beta_i \rangle \langle \beta_i \mid$$.

Taking into account that the quantum-mechanical nature of the superposition state, it may be said that by interacting with the $$\beta $$-analyzer, the micro-particle in some sense is "transformed" at once into all the states $$\langle \beta_i \mid$$. Here, the amplitude $$\langle \alpha \!\!\mid\!\! \beta_i \rangle$$ should be treated as the amplitude caused by the indicated interaction of the transition $$\langle \alpha \!\!\mid\, \rightarrow \langle \beta_i \mid $$. The quantity $$\mid \langle \alpha \!\!\mid\!\! \beta_i \rangle \mid^2 $$ is the probability of finding the micro-particle finally in just the $$\langle \beta_i \mid$$ state.

One can anticipate at least three questions.

_First question_: What do we really mean by the expression "the micro-particle is at once transformed into all the $$\langle \beta_i \mid $$ states"? The answer to this question will be given below in the subsection "Potentialities and their realization in the measuring process". Here, we just remark that although the micro-particle is "simultaneously transformed into all the $$\langle \beta_i \mid$$ states" as a result of its interaction with the $$\beta$$-analyzer, it can be found in principle each time in only one $$\beta $$-state. Hence it may be said that no confusion arises. 

_Second question_: If the amplitude of state is really the transition amplitude, what about the definitions of amplitudes of states that says "$$\langle \alpha \!\!\mid\!\! \beta \rangle$$ is the probability amplitude of a micro-particle existing in state $$\langle \alpha \mid$$ begin also registered in state $$\langle \beta \mid $$" ? In this definition the word "existing" should be replaced by the more accurate word "existed", since after interaction with the analyzer the micro-particle no longer exists in the state $$\langle \alpha \mid $$. Now the word "also" becomes redundant. The definition then assumes the following form: "$$\langle \alpha \!\!\mid\!\! \beta \rangle$$ is the probability amplitude of a micro-particle that existed in state $$\langle \alpha \mid$$ begin registered in state $$\langle \beta \mid $$" . Registering is a kind of measuring process and $$\langle \alpha \!\!\mid\!\! \beta \rangle$$ plays the role of the amplitude of the transition $$\langle \alpha \!\!\mid\, \rightarrow \langle \beta \mid $$ which takes place in this process. Here we remark that in the above-mentioned interaction of the micro-particle with the analyzer is just one part of the measuring process.

_Third question_: It was agreed earlier to read the transition amplitudes from right to left. If $$\langle \alpha \!\!\mid\!\! \beta_i \rangle$$ is also transition amplitude, it should also be read in the reverse direction (from left to right). Isn't it confusing? Actually, if we strictly follow the condition to writing the preceding states to the right of the ones that follows, then $$\eqref{T11.1}$$ should be written as

$$
\sum_i | \beta_i \rangle \langle \beta_i | \alpha \rangle = | \alpha \rangle
$$

However, such a notation, as a rule, is not used. Hence we decided to allow some inconsistency, and in order to avoid possible confusion in this connection we shall in future retain the term amplitude of state along with the term transition amplitude. When using both these terms the reader must remember that from the point of view of physical meaning, the amplitude of state is nothing but the transition amplitude.

### Examples of Analyzers

_First example_: the analyzer is a screen with two slits. It gives rise to the superposition

$$
\langle s | = \langle s | A \rangle \langle A | + \langle s | B \rangle \langle B |
$$

_Second example_: the analyzer is a crystal lattice consisting of nuclei of the same type with zero spin. It generates the superposition

$$
\langle s | =  \sum_i^N \langle s | i \rangle \varphi \langle i |
$$

_Third example_: The analyzer is a nonuniform magnetic field $$B_1 $$. It gives rise to the superposition

$$
\langle s | = \sum_i^N \langle s | i \rangle \langle i |
$$

It may be said that an analyzer, generating a certain superposition of states. in fact ensures the emergence of indistinguishable alternatives. Moreover, the number of alternatives is equal to the number of basic states in the given superposition, In the first example this number is just equal to two (i.e. to the number of slits in the screen); in the second example, it is equal to the number of nuclei in the crystal, while in the third example it is equal to the number of spin states (i.e. to $$2s+1$$, if $$s$$ is the spin of the atom).

## The Essence of Measuring Process

The process of measurement in quantum mechanics consists of three successive stages: (1) a _preparatory stage_ when the micro-particle is "prepared" in a certain state $$\langle \alpha \mid $$



[Transcript of L. V. Tarasov, *Basic Concepts of Quantum Mechanics*]