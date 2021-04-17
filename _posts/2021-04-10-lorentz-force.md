---
layout: post
title: "Lorentz Force from symmetry"
author: "Diego S"
categories: journal
tags: [quantum mechanics]
image: aurora.jpg
---
Deduction of the Lorentz force as a relation of expected values on the quantum mechanical formalism using symmetry arguments.

## Klein-Gordon equation with electromagnetic interaction

### Lorentz symmetry

It can be showed that the only possible terms of the lagrangian for a (complex) scalar field $ \Phi (x) $ are of the form

$$
\begin{equation}\label{1}
	S = \int \mathrm{d}^4 x \ \mathcal{L} = \int \mathrm{d}^4 x \ [ C_1 \partial_{\mu }\Phi ^* \partial ^{\mu }\Phi + C_2 \Phi ^* \Phi ] \tag{1} 
\end{equation}
$$

Renaming the constants $ C_1 = 1 $ and $ C_2 = -m^2 $, we can call this the Klein-Gordon lagrangian. Using the least action principle, one can obtain the Klein-Gordon equation

$$
\begin{equation}\label{2}
	\delta _{\Phi ^*} S = 0 \quad \Rightarrow \quad \partial _{\mu } \partial ^{\mu } \Phi + m^2 \Phi = 0 \tag{2}
\end{equation}
$$

We can use separation of variables $ \Phi (x) = \phi (\vec{x}) \exp \{ -iEx^0 \} $ obtaining the following equation for the spatial part

$$
\begin{equation}
	\nabla ^2 \phi + (E^2 - m^2) \phi = 0
\end{equation}
$$

Taking into account the Einstein energy-mass relation $ E^2 = p^2 + m^2 $ we can solve this equation. We will not do that here.

### Gauge symmetry

We can make this field interact with electromagnetism by making the Klein-Gordon lagrangian $ U(1) $ gauge invariant. The $U(1)$ gauge transformation is given by

$$
\begin{equation}
	\Phi(x) \quad \mapsto \quad \Phi '(x) = \Phi(x) \exp \{ -i \alpha (x) \}
\end{equation}
$$

where $ \alpha (x) $ is a function. At first sight, the lagrangian $ \eqref{1} $ is not gauge invariant, but we can make it so by replacing the derivative with the covariant derivative

$$
\begin{equation}
	\partial _{\mu } \quad \mapsto \quad D_{\mu } = \partial _{\mu } + iqA_{\mu } (x)
\end{equation}
$$

where $ A_{\mu } $ is the electromagnetic field, with gauge transformation law 

$$
\begin{equation}
	A_{\mu } (x) \quad \mapsto \quad A'_{\mu } (x) = A_{\mu } (x) + q^{-1}\partial _{\mu } \alpha (x)
\end{equation}
$$

Now

$$
\begin{equation}
	\mathcal{L} = (\partial _{\mu } - iqA_{\mu }) \Phi ^* (\partial ^{\mu } + iqA^{\mu }) \Phi - m^2 \Phi ^* \Phi
\end{equation}
$$

is gauge invariant. The principle of least action gives the following equation for the scalar field

$$
\begin{equation}\label{3}
	\partial _{\mu } \partial ^{\mu } \Phi + [iq(\partial _{\mu } A^{\mu }) + 2iq A^{\mu } \partial _{\mu } - q^2 A^2 + m^2 ] \Phi = 0 \tag{3}
\end{equation}
$$

### Non-relativistic limit

We take the separation of variables for $ \eqref{2} $ as a reference to make the following ansatz for $ \eqref{3} $:
$$
\begin{equation}
	\Phi (x) = \Psi (x) \exp \{ -imx^0 \} \qquad \text{where} \qquad \Psi (x) = \phi (\vec{x})\exp \{ -i(E - m)x^0 \}
\end{equation}
$$

then

$$
\partial _{\mu } \partial ^{\mu } \Phi = (\partial ^2 _0 - \nabla ^2 )\Phi = -(m^2 \Psi + 2im \partial _0 \Psi - \partial ^2 _0 \Psi + \nabla ^2 \Psi ) \exp \{-imx^0 \}
$$

and

$$
A^{\mu } \partial _{\mu } \Phi = A^0 \partial _0 \Phi + \vec{A} \cdot \nabla \Phi = [ A^0 (-im \Psi + \partial _0 \Psi ) + \vec{A} \cdot \nabla \Psi ] \exp \{-imx^0 \}
$$

Replacing these results in $ \eqref{3} $ we end up with

$$
\begin{align}
	-2im \partial _0 \Psi + \partial ^2 _0 \Psi - \nabla ^2 \Psi & + iq (\partial _0 A^0 ) \Psi + iq (\nabla \cdot \vec{A}) \Psi + 2qm A^0 \Psi \\
    & + 2iq A^0 \partial _0 \Psi + 2iq \vec{A} \cdot \nabla \Psi - q^2 (A^0 )^2 + q^2 \vec{A}^2 = 0
\end{align}
$$

which can be rewritten as

$$
\begin{equation}
	i \partial _0 \Psi - \frac{\partial ^2 _0 \Psi }{2m} - iq \frac{A^0 \partial _0 \Psi }{m} = \frac{1}{2m} (i\nabla + q \vec{A})(i\nabla + q \vec{A}) \Psi + q A^0 \Psi + iq \frac{\partial _0 A^0 }{2m} \Psi - q^2 \frac{(A^0 )^2 }{2m}
\end{equation}
$$

Using the non-relativistic limit $ p \ll m $ for the Einstein relation
$$
\begin{equation}
	E = \sqrt{p^2 + m^2} \approx \frac{p^2}{2m} - m
\end{equation}
$$

we found

$$
\begin{equation}
	|i\partial _0 \Psi | = | (E - m) \Psi | \approx \left | \frac{p^2}{2m} \Psi \right | \ll | m \Psi |
\end{equation}
$$

and supposing that $ | qA^0 | \ll m $,  we make these approximations in $ \eqref{3} $ obtaining
$$
\begin{equation}\label{4}
	i \partial _t \Psi = \frac{1}{2m} (i\nabla + q \vec{A}) \cdot (i\nabla + q \vec{A}) \Psi + q A^0 \Psi \tag{4}
\end{equation}
$$
If we interpret $ \Psi (x) $ as the probability amplitude to find a particle  between $\vec{x}$ and $ \vec{x} + \mathrm{d} \vec{x} $, his is the Schrodinger equation with minimal coupling
$$
\begin{equation}\label{5}
	i \partial _t \Psi (t, \mathbf{x}) = \left [ \frac{1}{2m} (\mathbf{p} - q \mathbf{A}) \cdot (\mathbf{p} - q \mathbf{A}) + q V \right ] \Psi (t, \mathbf{x}) = H \Psi(t, \mathbf{x}) \tag{5}
\end{equation}
$$
where $ \mathbf{p} = -i\nabla $ and $ A^0 = V$.

## Quantum mechanics 

