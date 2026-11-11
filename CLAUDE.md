# Convenzioni del repository

- `main` contiene solo gli strumenti condivisi (skill in `.agents/skills/`, collegate in `.claude/skills/`).
- Ogni sito o bozza per un'attività va su un branch nuovo **staccato da `main`**, chiamato con il nome
  dell'attività in minuscolo e con i trattini (es. `fragranze`, `pizzeria-sofia`, `effe-barbieri`):
  `git fetch origin main && git checkout -b <nome-attivita> origin/main`
- I file di ogni attività stanno in `mockups/<nome-attivita>/`.
- Una skill nuova si installa su `main`, poi si porta nei branch aperti con `git merge main`.
- `references/awesome-design-md/` contiene la raccolta VoltAgent/awesome-design-md (84 DESIGN.md di marchi noti,
  licenza MIT, copiata dal commit fcc7028). **Non usarla finché l'utente non lo chiede esplicitamente.**
