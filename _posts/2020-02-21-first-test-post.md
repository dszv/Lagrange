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

The process of measurement in quantum mechanics consists of three successive stages: (1) a _preparatory stage_ when the micro-particle is "prepared" in a certain state $$\langle \alpha \mid $$, considered below as a the _initial state_; (2) a _working stage_ in which the "prepared" micro-particle interacts with a certain analyzer and goes over the _superposition state_, and (3) a _registering stage_ in which the micro-particle is registered in one of the basic states forming the superposition. In this stage the micro-particle interacts with some macroscopic body, capable of changing its state under the influence of the micro-particle. This macroscopic body is called the detector.

If for the sake of simplicity we do not consider the preparatory stage the abstract "scheme" of the measurement process may be written in the following way:

$$
\begin{equation}\label{T11.5}
\langle s | \xrightarrow{1} \sum_i \langle s | \beta_i \rangle \langle \beta_i | \xrightarrow{2} \langle \beta_i | \tag{2}
\end{equation}
$$

Here the arrow $$1$$ corresponds to the working stage, and the arrow $$2$$ to the registering stage.

The basic elements of the measuring instrument (measuring apparatus) are thus the analyzer and the detector. Figuratively speaking, its role boils down to "spying" on how the micro-particle "behaves itself in the superposition state which was created by the analyzer". If we make use of the above examples of analyzers, this "spying" could provide an answer to the question: Which slit did a particular electron pass through? Which nucleus of the crystal lattice scattered a particular neutron? What is the spin state of a particular atom? The reader who is familiar with the results of similar "spying" may foresee that an "intervention" by the detector leads to the destruction of the superposition of states. The detector registers the micro-particle each time in one of the states which constitute the superposition. This is done at the expense of the _destruction of superposition_. This means that the detector converts indistinguishable alternatives into distinguishable ones and thus destroys the interference of the transition amplitudes.

We separate from the "scheme" $$\eqref{T11.5}$$ the registering stage corresponding to the interaction of the micro-particle with the detector:

$$
\begin{equation}\label{T11.6}
\sum_i \langle s | \beta_i \rangle \langle \beta_i | \rightarrow \langle \beta_i | \tag{3}
\end{equation}
$$

It is often said that a "scheme" of the type of the type $$\eqref{T11.6}$$ describes a "construction" of the superposition $$\sum _i \langle s \!\!\mid\!\! \beta_i \rangle \langle \beta_i \mid$$ to the state $$\langle \beta_i \mid$$. This process is also known as "reduction of the wave packet".

Thus, while the analyzer creates a definitive superposition of states, the detector destroys it by confining this superposition of states to one of the states constituting it. It is obvious that if the "scheme" $$\eqref{T11.5}$$ is tried on a single micro-particle, it is difficult to say anything about getting any useful information. It is necessary to repeat the measuring process for a sufficiently large number of micro-particles. In this case the observer may find out, firstly, the values of the quantities of the $$\beta$$-set encountered in practice, and, secondly, the frequency with which the micro-particles is found in one $$\beta$$-set or another. This allows us to experimentally determine, firstly, the spectrum of the values of the quantities in a $$\beta$$-set and, secondly, the probabilities $$\mid \langle s \!\!\mid\!\! \beta_i \rangle \mid^2 $$.

## Some Peculiarities of the Quantum-Mechanical Measuring Process

In the first place we note that the process of measurement has a radical influence on the micro-particle. It is enough to point out that a change in the initial state of the micro-particle in the measuring process is a circumstance of fundamental importance. It is well known that while carrying out measurements with macroscopic bodies it is possible to isolate the object to a certain extent from the means of measurement. In quantum mechanics this is in principle impossible to do so. In other words, it is impossible to neglect the interaction of the micro-particle with its surroundings.

The "scheme" of the measuring process, and more concretely that part which is described by $$\eqref{T11.6}$$, is a demonstration of the existence of the element of chance in the behavior of a micro-particle. Indeed, it is impossible to predict unambiguously in which $$\beta$$-state a certain micro-particle will be finally found.

The impossibility of a graphic representation of the first stage of the process (when the analyzer creates a superposition of states) or the final stage (when the detector "confines" this superposition to a single state) is also a specific feature of the quantum-mechanical measuring process.

Thus, obviously, in the first stage of the process of measurement it must not be assumed that a micro-particle is literally "spread" over various states of superposition (for example, that it passes partially through one slit and and partially through the other in the well-know two slit experiment).

[Transcript of L. V. Tarasov, *Basic Concepts of Quantum Mechanics*]