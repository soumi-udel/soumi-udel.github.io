---
layout: post
title: Life at Low Reynolds Number - Part 1

---

<hr>

## Introduction.

Life at Low Reynolds Number is the title of a really fun paper, one which I think should be mandatory reading for chemical engineering undergraduates. The personal tone and sporadic humor is all part of the original, since the 'paper' is in fact a transcript of a lecture. The foreword ends with the statement: “Some essential hand waving could not be reproduced.”

>I want to take you into the world of very low Reynolds number. This world is quite different form the one that we have developed our intuitions in.

The counter-intuitive nature of low-Re systems is something chemical engineers need to come to grips with sooner rather than later. To that end, this paper is insightful stuff. I like it because it illustrates the following really well:
* Momentum transfer and its counter-intuitive nature
* Combined mass and momentum transfer
* The usefulness of dimensional analysis

I started writing a post about it, and it quickly became a three part series. Let's dive right in. 

<hr>

## Who Cares?

We will answer that indirectly – by looking at _forces_. Remember – the Reynolds number is a ratio of inertial (push/pull) forces vs viscous forces. As humans (i.e. with our characteristic length and time scales), inertial forces dominate all the time. When is the last time you went swimming in a purely laminar regime? Never. That’s right, you inertial bad-boy.

Back to forces. What’s the force required to produce a (low) Reynolds number of 1?

$$ Re = \frac{\rho v R}{\eta} $$

Put $$Re = 1$$ and we get

$$ vR = \frac{\eta}{\rho} $$

Now, the viscous force on a sphere is given by Stokes Law:

$$ F = 6 \pi \eta v R $$

Substitution for $$vR$$ gives

$$ F = \frac{6 \pi \eta^2}{\rho} $$

That’s the force which pulls a sphere along with a Reynolds number of one. Drop the scaling factor for the sphere to get _some force_ that pulls some object in a regime that has significant viscous forces.

$$ \textrm{some force} = \frac{\eta^2}{\rho} $$

Notice that viscosity and density are both fluid properties, hence _some force_ is independent of the object being pulled. For water 

$$ \textrm{some force} = ~ 1 \times 10^{-9}  \textrm{Newtons}$$ 

Is a force of this magnitude significant for your system? If you are a submarine moving in the Indian ocean, clearly it’s not. If you are an _E. Coli_ bacterium, then it probably is. Let's talk more about _E. Coli_ in [Part 2](/texts/life-at-low-Re-2/)!
