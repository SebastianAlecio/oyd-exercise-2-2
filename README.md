# oyd-exercise-2-2

Ejercicio 2.2 — GitHub Actions CI Workflow for Terraform (Optimizaciones y Desempeño, Sesión 2).

El pipeline valida cada pull request contra `main` con `terraform fmt → init → validate → plan` y publica el plan completo como comentario colapsable en el PR.

## Evidence

- Pull request: <https://github.com/SebastianAlecio/oyd-exercise-2-2/pull/N>

![PR comment](evidence/pr-comment.png)
