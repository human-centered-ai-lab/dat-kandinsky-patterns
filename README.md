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

