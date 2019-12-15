---
layout: post
title: Life at Low Reynolds Number - Part 2

---

<hr>

## Introduction.

In [Part 1](/texts/life-at-low-Re-1/), we discussed how the force needed to push something in water at Reynolds’ number of 1 is 10^-9 Newtons. Who cares for such tiny forces? Bacteria. In the paper, Purcell dives into talking about Bacteria, their flagella and chemotaxis. More importantly for chemical engineers, he talks about diffusion and provides a very nice framework to understand its relevance.

Purcell takes a few side-steps before getting to the point, which is great for us – each of those forays is a fun little paper that leads us into biology. The subject matter is complex enough to be fun to read, and simple enough that terms you don’t understand can be readily googled. And being a physicist, his tone is one of undergraduate-like wonder for a field he’s not done a PhD in. In his own words:

>We wander around strictly as amateurs equipped only with some elementary physics, and in the end, it turns out, we improve our understanding of the elementary physics even if we don’t throw much light on the other subjects.

Improving our understanding of elementary physics is very handy for a chemical engineer, because it’s our job to find out how it can be used to ‘throw much light’ on the ‘other subjects’ that Purcell speaks of. Anyway, onward. 

<hr>

## Flagella: do they wave or rotate?

At one point we didn’t know the answer to this question. But there was a rather cute experiment ([described in a short paper](https://www.nature.com/articles/249073a0)) that provided strong support to ‘rotate’.

The E. Coli flagella structure looks like this:

<!-- Here is the code for the figure. It's clunky and maybe we should do something in the CSS files to make it prettier -->
<center>
<figure style="border: 1px solid #C0C0C0">
<img src="/images/flagella.png" align="center" hspace="50" vspace="50" height="315" width="280" />
<figcaption>
	<a href = "https://en.wikipedia.org/wiki/Flagellum#/media/File:Flagellum_base_diagram-en.svg">
		<small><small>
			From Wikipedia 
		</small></small>
	</a>
</figcaption>
<!--
	629x561 pixels
![Flagella](/images/flagella.png "From Wikipedia")
-->
</figure>
</center>
<!-- --END FIGURE-- -->

There is a particular mutant strain of _E. Coli_ which doesn’t have the filament (green, ending in 'tip'), and has long hooks (see the blue ‘hook’ above). We’ve also got an antibody that attaches itself to the hook proteins. And it’s polyvalent, i.e. one antibody attaches to multiple hooks, so you can have two cells attached to one antibody, or one cell attached to an antibody which has also attached itself to some debris and thus immobilized itself.

In such cases – the immobilized and tethered cells _rotated_. This means the hooks (and by extension, the flagella attached to them in non-mutant strains) rotate! We take it for granted now, but must’ve been quite interesting to realize that nature has fitted molecular outboard motors on the posteriors of some cells.

Purcell then goes on detailing the math involved in corkscrew-like or flagellar motion (which I do not understand) and calculates the efficiency of such a motor, which turns out to be all of 1%.

It appears low, but the E. Coli don’t care – their total energy needs are minimal. They can usually collect sufficient energy-giving molecules by diffusion, as they move around.

Now we’ve started talking about diffusion. Which means we’ve started talking about mass-transfer. Which means it’s time for Part 3!
