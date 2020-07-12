---
layout: single
classes: wide
mathjax: true
title: Nonlinear Dynamics of a Non-Contact Translational-to-Rotational Magnetic Transmission
permalink: /research/magnetic-transmission
typora-root-url: ../../
author_profile: true
---

* **NOTE:** *This page is a brief introduction of a published work. The detailed information can be found on [Journal of Sound and Vibration](https://www.sciencedirect.com/science/article/abs/pii/S0022460X19304158) and [Nonlinear Structure and Systems](https://link.springer.com/chapter/10.1007/978-3-030-12391-8_12).*

## Abstract

* This work presents an exploratory transmission design to combine three features together: **1) translation-to-rotation, 2) non-contact, and 3) nonlinearity**.

* The system's **governing equations** were derived under the idealization of a magnetic dipole, and were used to obtain analytical expressions for the system's **equilibria and stabilities**.

* Theoretical, numerical and experimental investigations all unveil **nonlinear dynamical behaviors**, such as coexisting harmonic, sub-harmonic, and chaotic responses, under sinusoidal excitation.

## Background and Motivation

The conversion of **translational** motion into **rotational** motion, and vice versa, is an important problem area with widespread practical applications and challenges. A primary **shortcoming**, inherent in systems with mechanical **contact and friction**, is a reduction in transmission efficiency and the generation of noise. To overcome these shortcomings, various **non-contact** transmissions were investigated, among which **magnetic force** is widely used to achieve conversion between rotary and translational motion. 

Although various types of magnetic transmission systems have been proposed, considerably less research has embraced their **nonlinear** behaviors, which are potentially valuable in many applications. For example, in the field of energy harvesting, 1) a **non-contact transmission** is needed for low friction and high energy efficiency, 2) **translation-to-rotation** is needed for saving space and connecting to a motor/generator, and 3) **nonlinearity** is also needed for broad-band frequency responses. This work therefore presents an exploratory transmission design to combine the three features together, and gives a thorough investigation of the system's static behavior and dynamic responses.

## Equations of Motion

As shown in **Fig. 1**, the **drive magnet** is fixed to a vibration source and has a prescribed **translational harmonic** motion. The **driven magnet** is pinned and limited to **pure rotation** about its center of mass. The drive magnet applies a non-contact **magnetic force** to the driven magnet to achieve translational-to-rotational conversion. In addition to the magnetic force, the driven magnet is also subject to a **linear restoring torque** from mechanical springs and a **damping torque** which is assumed to be **viscous** and proportional to the driven magnet's angular velocity. 

<figure style="width: 80%" class="align-center">
	<a href="/assets/images/research/magnet/schematic.png"><img src="/assets/images/research/magnet/schematic.png"></a>
	<figcaption><b>Figure 1</b>. Schematic diagram of the non-contact translational-to-rotational transmission system. </figcaption>
</figure>

Therefore, the **equation of motion** can be written as a linear mass-spring-damper system driven by magnetic torque:

$$
\begin{split}
I \ddot{\theta} + c \dot{\theta} + k \left( \theta - \theta_0 \right) = \qquad\qquad\qquad\qquad\qquad\qquad\qquad\\
\alpha \left[ \frac{\sin \theta}{\left[ \left( b + A \cos(\Omega t) \right) ^ 2 + h ^ 2 \right] ^ {3/2}} - 3 \frac{\left[ b + A \cos(\Omega t) \right] \left[ h \cos \theta + \left( b + A \cos(\Omega t) \right)\sin \theta \right]}{\left[ \left( b + A \cos(\Omega t) \right) ^ 2 + h ^ 2 \right] ^ {5/2}} \right].
\end{split}
$$

In the **LHS**, $$I$$, $$c$$, $$k$$ and $$\theta_0$$ are the driven magnet's moment of inertia, torsional spring coefficient, torsional damping coefficient, and offset bias angle of spring respectively. The **RHS** is the expression of magnetic torque derived by using **Dipole model**, which is determined by three variables: the angle of the driven magnet $$\theta$$, the horizontal distance between two magnets $$x$$, which is described by $$b + A\cos(\Omega t)$$, and the vertical distance between two magnets $$h$$. The factor $$\alpha$$ is a constant describing properties of the drive and driven magnets. The detailed derivation of this equation of motion can be found in the published paper (**see links at the top of this page**).





