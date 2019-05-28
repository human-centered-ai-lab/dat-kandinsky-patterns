# Test Data Sets for Kandinsky Patterns
In the following we provide a few definitions, for more information please refer to our ArXiV paper.

Definition 1 : Kandinsky Figure
is a square image containing 1 to n geometric objects.
Each object is characterized by its shape, color, size and position within this square.  Objects
do not overlap and are not cropped at the border.  All objects must be easily recognizable and
clearly distinguishable by a human observer.

Remark: The set of all possible Kandinsky Figures K is given by the definition 1 with a specific
set of values for shape, color, size, position and the number of geometric objects.  In the
following examples we use for shape the values circle, square and triangle; for color we use
the values red, blue, yellow, and we allow arbitrary positions and size with the restriction of
recognizably.  Furthermore, we require each Kandinsky Figure to contain exactly 4 objects
in the following illustrative examples.  In the demo implementation this fact is embedded
in the base class ”Kandinsky Universe”, and in the generator functions, see:
https://github.com/human-centered-ai-lab/app-kandinsky-pattern-generator

Definition 2 : A Statement \textbf{$s(k)$} about a Kandinsky Figure $k$ is either a mathematical function, $s(k) \to B$; with $B (0,1)$ or a natural language statement, which can be either true or false. 

Remark: The evaluation of a natural language statement is always done in a specific context. In the followings examples we we use well known concepts from human perception and linguistic theory.  If k is given as an algorithm, it is essential that the function is a pure function, which is a computational analogue of a mathematical function.

Definition 3: A Kandinsky Pattern $K_p$ is defined as the subset of all possible Kandinsky Figures $K$ with $s(k) \to 1$ is true.  $s(k)$ and a natural language statement are equivalent if and only if the resulting Kandinsky Patterns contain the same Kandinsky Figures. $s(k)$ and the natural language statement are defined as the \textbf{Ground Truth} of a Kandinsky Pattern.



