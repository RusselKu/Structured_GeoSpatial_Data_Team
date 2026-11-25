# Reglas de Pull Requests (PRs)

> [!CAUTION]
> **NO TOCAR / NO MODIFICAR:** El archivo [`.github/CODEOWNERS`](../.github/CODEOWNERS) y esta carpeta (`RulesPr/`) no deben ser modificados ni eliminados sin autorización del equipo responsable.

## ¿Cómo funciona el control de PRs?

1. **Ubicación obligatoria de `CODEOWNERS`:**
   GitHub únicamente reconoce el archivo `CODEOWNERS` si se encuentra en `.github/CODEOWNERS`, `docs/CODEOWNERS` o en la raíz del repositorio. Por eso se mantiene en `.github/CODEOWNERS` y no dentro de `RulesPr/`.

2. **Revisores automáticos para todo el repositorio (`*`):**
   Cualquier cambio en el repositorio (incluyendo `.github/CODEOWNERS` y `RulesPr/`) solicita revisión de:
   - `@RusselKu`
   - `@karencardiel`
   - `@Rivaldo2309030`
   - `@RamiroChay`

   Con **Require a pull request before merging** y **Require review from Code Owners** activadas en GitHub, basta con la aprobación de cualquiera de estos Code Owners (distinto al autor del PR) para poder hacer merge.
