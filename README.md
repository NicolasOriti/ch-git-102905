# ch-git-102905

Este repositorio contiene el proyecto para el curso de Git y Github.

## Setup
Para inicializar un proyecto con git utilizar
```bash
git init
```

## Uso
Para agregar archivos al área de preparación y realizar un commit, utilizar:
```bash
git add .
git commit -m "Mensaje del commit"
```

## Git Flow

Rama principal: `master`
Rama de integración: `staging`
Ramas de desarrollo: `develop`
Ramas de funcionalidades nuevas: `feature/nombre-de-la-caracteristica`
Ramas de corrección de errores: `bugfix/nombre-del-bug`
Ramas de hotfix: `hotfix/nombre-del-hotfix`