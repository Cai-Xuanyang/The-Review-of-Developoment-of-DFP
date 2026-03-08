DFP Development Notes
LaTeX source for "The Development of DFP" by Xuanyang Cai.
Local Build
Run in the root directory:
latexmk -pdf Cai_Xuanyang_The_Development_of_DFP.tex
GitHub Actions
Every push triggers:
PDF Compilation: Generates the PDF and saves it as an artifact.
Spell Check: Validates text against a custom dictionary.
Download the latest PDF from the Actions tab under the most recent workflow run.
