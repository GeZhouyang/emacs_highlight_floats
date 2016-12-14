# emacs_highlight_floats
A not-so-elegant-but-sort-of-works solution for highlighting floating numbers in .f90 files in emacs.

Installation:

1. Copy the parent-mode.el in the ./emacs.d/elpa, install it within emacs.
2. Copy the highlight-number-mode.el in the ./emacs.d/elpa, install it within emacs.

Afterwards, when opening a f90 file, floating numbers (such as 0.2 or 2.) will be in a different color from integers.

Acknowledgement: The original author of both modes is Fanael Linithien <fanael4@gmail.com>, as claimed in the source codes. What I did was minor modifications only to suit a slightly different purpose.
