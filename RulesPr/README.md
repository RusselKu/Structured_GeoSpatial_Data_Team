# Reglas de Pull Requests (PRs)

> [!CAUTION]
> **NO TOCAR / NO MODIFICAR:** El archivo [`.github/CODEOWNERS`](../.github/CODEOWNERS) y esta carpeta (`RulesPr/`) no deben ser modificados ni eliminados sin autorización expresa de `@RusselKu`.

## ¿Cómo funciona el control de PRs?

1. **Ubicación obligatoria de `CODEOWNERS`:**
   GitHub únicamente reconoce el archivo `CODEOWNERS` si se encuentra en `.github/CODEOWNERS`, `docs/CODEOWNERS` o en la raíz del repositorio. Por eso se mantiene en `.github/CODEOWNERS` y no dentro de `RulesPr/`.

2. **Revisores automáticos para el proyecto (`*`):**
   Cualquier cambio en el repositorio solicita automáticamente revisión de:
   - `@karencardiel`
   - `@Rivaldo2309030`
   - `@RamiroChay`

3. **Protección de reglas de PR:**
   - `/.github/CODEOWNERS @RusselKu`
   - `/RulesPr/ @RusselKu`

   Con las opciones **Require a pull request before merging** y **Require review from Code Owners** activadas en GitHub, nadie puede fusionar cambios a `.github/CODEOWNERS` ni a `RulesPr/` sin la aprobación de `@RusselKu`.
