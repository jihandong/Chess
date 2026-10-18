# Chess Notes

Personal chess notes in a compact, two-column LaTeX layout.

- [Minor-Piece Checkmate Patterns](Endgames/minor-piece-checkmates.tex)
- [Checkmate Patterns](Checkmates/checkmate-partterns.tex)
- [Reusable template](Templates/template.tex)

Build with `latexmk -xelatex <file>.tex`.

For emoji, use `\texttwemoji{clown face}`; 🤡 and 🧪 also work directly in the checkmate notes.

**Diagram key:** The standard square beside each board shows who moves next (empty: White; filled: Black). Black moves use yellow arrows and yellow labels with black text; White moves use blue arrows and blue labels with white text. Labels match the move numbers below each board. Purple circles mark the relevant h-pawn. Red fill marks current threats; unnumbered dashed red arrows trace attacks opened by a move; green marks remaining escape squares.

In back-rank diagrams, red arrows show Black's attacks, yellow arrows show White's defenses, and labels above the board show signed square scores (White positive). Negative scores use red labels; other scores use blue labels.
