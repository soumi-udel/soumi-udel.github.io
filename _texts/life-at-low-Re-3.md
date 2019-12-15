---
layout: post
title: Life at Low Reynolds Number - Part 2

---

<hr>

## Introduction.

We are at Part 3, where we’ll talk about mass transfer and how it relates to low Reynolds number environments. If you haven’t yet done so, go read [Part 1](/texts/life-at-low-Re-1/) and [Part 2](/texts/life-at-low-Re-2/).

So far, Purcell has spoken about what kind of organisms live in low-Re environments – E. Coli, for example – and how they move. Now he discusses how their motion ensures they get enough nutrients.

Mass transfer in dissolved molecules occurs when they diffuse through their solvent, and when they are bodily pushed by currents in the solvent (i.e. stirring). However, we’re talking about low-Re systems – there is no meaningful stirring, the velocities and length scales are too small.

## The ‘Stirring’ number (Sherwood or Peclet?)

To demonstrate the above idea, Purcell actually begins this section by deriving a dimensionless number which he calls the ‘Stirring number’. It’s a ratio of advective mass transport to diffusive mass transport. When we plug in the values of our swimming-E. Coli system, we see this ‘Stirring number’ is really small. This means there’s no point for the E. Coli to try and ‘stir’ is local environment because diffusion mass flowrates are going to be about two orders of magnitudes more. A good example of the conclusions we can get from dimensionless analysis.

For this dimensionless ‘Stirring’ number, Purcell says:

>I don’t know the literature and I don’t know whose number that’s called.

He later adds a footnote:

I’ve recently discovered that it’s official name is Sherwood Number.

But wait! What about the [Peclet number](https://en.wikipedia.org/wiki/P%C3%A9clet_number)? It’s a ratio of advective transfer to diffusive transfer, whereas Sherwood is a ratio of _convective_ transfer to diffusive. Moreover, the Peclet number has the exact same formula as the ‘Stirring’ number.

$$ Pe = \frac{\textrm{advective transport rate}}{\textrm{diffusive transport rate}} $$

$$ Pe = \frac{Lu}{D} = Re \times Sc $$

Going down a rabbit hole about the difference between ‘advection’ and ‘convection’ hasn’t been satisfying. I thought ‘convective’ mass transfer was something like dissolving walls, but I’m not certain anymore. Please tell me if you know!

## Running to Stand Still

Anyway, what does this mean for the E. Coli? It means there’s absolutely no point in using motion as a way to increase collection of (energy-giving) molecules. You know how whales open their mouths and swim to gather whatever krill might be floating about? That does _not_ work for E. Coli. Or rather, it doesn’t work for the speeds the E. Coli. can swim in.

Rather, it just needs to sit in place and allow molecules from its local environment to diffuse into it.

That doesn’t mean it should never move – if it finds itself in an environment where the local concentration of molecules is insufficient, the E. Coli would benefit from moving into a new environment – and it does.

The takeaway is this – the motion doesn’t lead to increased nutrient-molecule uptake. Rather, motion leads to the E. Coli. to a new environment, which might have a higher concentration of these molecules. Once in this new environment, increased _diffusion_ (due to the new environment having higher concentrations of our molecule) leads to increased nutrient-uptake.

## Finishing up

Purcell shows how the length scale for reaching a new environment is at least 30 microns (again, dimensional analysis), and he throws in a few words about the algorithm that the cells follow in order to accurately move up a concentration gradient. Simple yet effective, it’s one of those things that’s so elegant when you pause and think about it. We’re looking at something that’s worked and been refined since millions of years.

<hr>

This brings us to the end of the lecture. I don’t know about you, but for me, it’s been a fun ride. Dimensional analysis, momentum transfer, momentum+mass transfer – as an undergraduate chemical engineering student, these were some of the less straightforward concepts that I encountered in my coursework. So I’m glad to find material that covers these ideas with so well!
