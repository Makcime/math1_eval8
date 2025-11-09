# Math 1 – Évaluation 8

- Sujet: divisions euclidiennes (poser la division, quotient et reste).
- Versions: A, B, C, D (EABS) + correctifs.

Barèmes
- A–C: 1 question, 12 pts (6 divisions, 2 pts chacune).
- D (EABS): 1 question, 8 pts (4 divisions, 2 pts chacune).

Grille de correction (src/corr.docx)
- Quotient et reste corrects: 2 pts
- Quotient correct, reste erroné: 1 pt
- Quotient erroné, reste correct: 0 pt
- Division bien posée mais non euclidienne (résultat décimal): 1 pt de présentation

Sources
- `src/questions/q1.tex`: énoncé; A–C en tableau 3×2 (6 divisions), D/EABS en 2 colonnes (4 divisions).
- `src/answers/a1.tex`: réponses (en correctif).
- `src/corr.docx`: grille de correction.
- `base/`: sous-module de style.
- `build/`: sorties PDF (ignorées).

Compilation
- `make A` · `make B` · `make C` · `make D`
- `make correctif_A` … `make correctif_D`
- `make all` · `make clean`
