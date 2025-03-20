## 📦 Semantic Versioning (SemVer) Cheat Sheet

| 🔖 Tipo | 🔢 Version | ⚠️ Breaking? | 📋 Cuándo usarlo | 🛠 Qué cambia | 💬 Commit message | 🚀 Ejemplo Release |
|---------|-----------|--------------|------------------|--------------|--------------------|--------------------|
| 🔥 **MAJOR** | X.0.0 → (X+1).0.0 | ✅ | Cambios incompatibles en API | Refactor masivo, eliminar endpoints | `feat!: remove “age” field — breaking change` | `v2.0.0` Migración completa de contrato REST |
| ✨ **MINOR** | 1.X.0 → 1.(X+1).0 | ❌ | Nuevas funcionalidades | Añadir endpoints, nuevos campos opcionales | `feat: add GET /orders endpoint` | `v1.5.0` Módulo historial de pedidos |
| 🐛 **PATCH** | 1.5.X → 1.5.(X+1) | ❌ | Corrección de bugs | Fix validaciones, refactor interno | `fix: validate email format in UserService` | `v1.5.1` Corrige bug en login |
| ⚗️ **PRERELEASE** | 1.5.0 → 1.5.1‑alpha.0 | — | QA interno / testing | Features inestables, pruebas | `chore: bump to 1.5.1-alpha.0` | `v1.5.1-alpha.0` Build para testers |
| 📦 **BUILD META** | 1.5.0 → 1.5.0+build.45 | — | Tracking de compilación | IDs CI/CD, fecha, hash | `ci: add build metadata +build.20250320` | `v1.5.0+build.20250320` Azure Pipelines build |
