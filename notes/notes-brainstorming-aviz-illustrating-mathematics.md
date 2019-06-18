---
title: Illustrating mathematics
subtitle: research project brainstorming
author: Alba Marina MÁLAGA SABOGAL
date: 18 June 2019
sansfont: TeX Gyre Heros
slide-numbers: true
---

# Abstract to concrete through illustrations

I see:

- mathematical objects as abstract
- illustrations as concrete

What I mean by illustrations: images, tangible objects, interactive pieces of software...

. . .

**Problem:**

- On one side, a concrete illustration representing an abstract object modifies the perception of this abstract object and the internalized knowledge we have of it.

- On the other side, many abstract mathematical concepts that do not possess "nice" illustrations (yet) remain esoteric and their knowledge and perception is reserved to a narrow set of specialists. 

# First example : Kummer surfaces

![A Kummer surface with 8 double points from the IHP collections](../media/kummer-8.jpg)\

\note{
Surfer image.
}

## And a block

And some text underneath.


\note{

Here are my notes.

}

# Second example : Proof visualisation

- With a
- list.

::: notes

A note on my list.

:::

# A slide to show overlay tricks

\only<1,3>{This text appears on the first and third versions of the slide, but not the second.}

This uses beamer's highlighting command to \alert<2>{draw attention here}, but only on the second slide.

\note<1>{

Notes can also have overlay specs. First slide version note.

}

\note<2>{

Second.

}

\note<3>{

And third. Use \LaTeX\ macros in notes, like \emph{emphasis}.

}

# TeX-LOGO

\begin{textblock}{4}(0,1)
Grid demo UL
\end{textblock}

\begin{textblock}{4}(7,1)
Grid demo UR
\end{textblock}

\begin{textblock}{4}(0,5)
Grid demo LL
\end{textblock}

\begin{textblock}{4}(7,5)
\only<2>{Grid demo LR}
\end{textblock}

\note<2>{

To get overlay effects with materials placed using \texttt{textpos}, you have to specify the overlay within the \texttt{textblock} environment.

}
