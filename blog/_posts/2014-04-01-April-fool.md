--- 
layout: blog-post
title: A test (equations are not displayed)
location: Santiago
---

This test is just to validate the `use_math` variable and the
`mathjax` stuff.
Form this small test, it is working very well.

I check `use_math`

$$
\newcommand{\myint}{ \int }
\newcommand{\myref}{ Eq. }
$$

Ya, let do it.
scroutch.

And,
\begin{equation}\label{da} 
\int f
\end{equation}

now we write some text blabla then $f(x) = x^2$ and so, $\myref$\ref{da}
gives
$$ \myint x^2 $$

Done.
