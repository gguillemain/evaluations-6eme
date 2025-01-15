# Évaluations Mathématiques 6ème

Ce repository contient les évaluations de mathématiques pour le niveau 6ème, disponibles en version bilingue (français-allemand) et non bilingue (français uniquement).

## Structure du repository

```
evaluations-6eme/
├── README.md
├── debut.tex                    # Fichier de configuration LaTeX
├── IE/                         # Interrogations Écrites
│   ├── bilingue/              # Versions bilingues
│   └── non-bilingue/          # Versions non bilingues
└── DS/                        # Devoirs de Synthèse
    ├── bilingue/              # Versions bilingues
    └── non-bilingue/          # Versions non bilingues
```

## Convention de nommage

Les fichiers suivent la convention de nommage :
`6{langue}-{type}-{chapitre}.tex`

Où :
- langue : bil (bilingue) ou nonbil (non bilingue)
- type : IE (Interrogation Écrite) ou DS (Devoir de Synthèse)
- chapitre : nom du chapitre concerné

## Compilation

Chaque fichier inclut :
```latex
%%!TEX TS-program = latex
\include{debut}
```