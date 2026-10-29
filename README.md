# Workflows de GitHub Actions en español (gratis)

Workflows de CI comentados línea por línea en español, con permisos mínimos y caché.

**Gratis y de código abierto (MIT).** Úsalo en tus proyectos y en los de tus clientes.

## Qué incluye

- `node-ci.yml`: lint y tests en Node 20 y 22 con caché de npm
- `python-ci.yml`: ruff y pytest con uv en 3.11–3.13
- `auditoria-dependencias.yml`: revisión semanal de vulnerabilidades

## Instalación

```bash
git clone https://github.com/carlosp5751258-lgtm/github-actions-ci-espanol.git
mkdir -p .github/workflows
cp github-actions-ci-espanol/.github/workflows/node-ci.yml .github/workflows/   # o el de tu lenguaje
```

Haz commit y push: el workflow corre solo en cada push y pull request. Cada archivo indica qué cambiar.

## ¿Quieres la versión completa?

Esta es la versión gratis y funciona sola. La **versión Pro** añade:

- 5 workflows más: Go, Docker a GHCR, releases por tag, deploy a GitHub Pages y patrones de caché
- Guía LEEME con requisitos y ajustes

👉 [Ver la versión Pro](https://claudecodees.gumroad.com/l/github-actions-ci) · paga lo que quieras desde 2 USD. Comprarla también ayuda a que sigamos publicando recursos gratis.

---
Parte de **[Ctrl+IA](https://carlosp5751258-lgtm.github.io/ctrlia/)**: recursos en español para programar con IA. Hecho por Carlos P.
