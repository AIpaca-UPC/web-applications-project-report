# Guía de contribución — Rumbo Project Report

Este repositorio contiene el informe oficial del curso **1ASI0730 Aplicaciones Web**. El archivo principal del informe se mantiene en `README.md`, de acuerdo con el Final Project Statement 2026-20.

## GitFlow

- `main`: versión estable y entregable.
- `develop`: integración del trabajo del equipo.
- `feature/...`: trabajo de una sección o artefacto específico.
- `release/...`: preparación de una entrega cuando corresponda.
- `hotfix/...`: correcciones urgentes sobre una versión estable.

### Flujo esperado

1. Crear la rama de trabajo desde `develop`.
2. Realizar commits pequeños y coherentes.
3. Usar Conventional Commits.
4. Abrir Pull Request hacia `develop`.
5. Revisar y corregir antes de hacer merge.
6. Para cada entrega, integrar `develop` hacia `main` mediante Pull Request.

## Conventional Commits

Ejemplos:

- `docs(chapter1): add startup profile`
- `docs(chapter2): add interview evidence`
- `docs(chapter3): add impact map`
- `docs(chapter4): add landing page wireframes`
- `docs(chapter5): add sprint 1 evidence`
- `fix(report): correct table of contents`

## Evidencias

Las imágenes y evidencias se almacenan dentro de `assets/` por capítulo. No subir archivos de IDE, temporales ni duplicados.

## Importante

Cada integrante debe aportar mediante su propia cuenta, rama, commits y Pull Requests para que la evidencia de colaboración refleje el trabajo real del equipo.
