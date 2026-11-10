# 🎯 Custom Skills - Bug Bounty & Pentesting

Colección de skills (prompts especializados) para automatizar y estandarizar tareas de bug bounty y pentesting.

## 📁 Estructura

```
skills/
├── recon/                 # Reconocimiento y enumeración
│   ├── subdomain-enum.md
│   ├── tech-stack.md
│   ├── api-discovery.md
│   └── cloud-recon.md
├── vuln-analysis/         # Análisis de vulnerabilidades
│   ├── sql-injection.md
│   ├── xss-analysis.md
│   ├── ssrf.md
│   ├── idor.md
│   ├── auth-bypass.md
│   ├── race-condition.md
│   └── logic-flaws.md
├── exploitation/          # Explotación y PoC
│   ├── poc-generator.md
│   ├── chain-attacks.md
│   └── privilege-escalation.md
├── reporting/             # Reportes y documentación
│   ├── bug-report.md
│   ├── executive-summary.md
│   └── remediation-guide.md
├── automation/            # Automatización y workflows
│   ├── nuclei-templates.md
│   ├── custom-wordlists.md
│   └── pipeline-setup.md
└── methodology/           # Metodologías y checklists
    ├── web-app-checklist.md
    ├── api-checklist.md
    ├── mobile-checklist.md
    └── cloud-checklist.md
```

## 🚀 Uso Rápido

Cada skill es un archivo Markdown con:
- **Contexto**: Qué hace y cuándo usarlo
- **Prompt**: El prompt optimizado para el LLM
- **Variables**: Parámetros que debes rellenar
- **Ejemplos**: Casos de uso reales
- **Output esperado**: Formato de respuesta

### Ejemplo de uso

```bash
# Copia el prompt del skill y rellena las variables
# Pégalo en tu LLM favorito (Claude, GPT, etc.)
```

## 📋 Categorías Principales

| Categoría | Skills | Uso |
|-----------|--------|-----|
| **Recon** | 4 | Descubrimiento de superficie de ataque |
| **Vuln Analysis** | 8 | Análisis profundo de clases de vulnerabilidades |
| **Exploitation** | 3 | Generación de PoCs y cadenas de ataque |
| **Reporting** | 3 | Reportes profesionales listos para enviar |
| **Automation** | 3 | Escalado y automatización de hunting |
| **Methodology** | 4 | Checklists completas por tipo de target |

## 🎯 Objetivo

Estandarizar tu workflow de hunting para:
- ✅ No olvidar vectores de ataque
- ✅ Generar reportes consistentes
- ✅ Automatizar tareas repetitivas
- ✅ Escalar hallazgos a PoCs explotables
- ✅ Documentar metodología reproducible

---

> **Tip**: Combina skills de `recon/` + `vuln-analysis/` + `reporting/` para un workflow completo end-to-end.