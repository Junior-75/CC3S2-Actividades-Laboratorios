# Actividad 6 - Git: conceptos básicos y operaciones esenciales


## Introducción
En esta actividad se puso en práctica el uso de **Git** como sistema de control de versiones distribuido.  
Se realizaron operaciones esenciales como inicializar repositorios, configurar identidad de usuario, crear confirmaciones (*commits*), manejar ramas y resolver conflictos.

El objetivo principal fue **aprender el flujo de trabajo básico con Git** y dejar evidencia de cada comando ejecutado en archivos `.txt`.

---

## Comandos ejecutados y evidencias

### 1️ Verificación de instalación
Se comprobó la versión instalada de Git.  
📄 Evidencia: [`logs/git-version.txt`](logs/git-version.txt)

---

### 2️ Configuración del usuario
Se configuró el nombre y correo electrónico para asociar los commits al autor.  
📄 Evidencia: [`logs/config.txt`](logs/config.txt)

---

### 3️ Inicialización de un repositorio
Se creó un nuevo repositorio en la carpeta de trabajo y se verificó su estado inicial.  
📄 Evidencia: [`logs/init-status.txt`](logs/init-status.txt)

---

### 4️ Creación de commits
Se añadió un archivo (`README.md`) y se registraron cambios con mensajes descriptivos.  
📄 Evidencia: [`logs/add-commit.txt`](logs/add-commit.txt)

---

### 5️ Inspección del historial
Se listó el historial de confirmaciones en formato resumido con `git log --oneline`.  
📄 Evidencia: [`logs/log-oneline.txt`](logs/log-oneline.txt)

---

### 6️ Trabajo con ramas
Se crearon ramas nuevas, se listaron y se verificó el estado de la rama actual.  
📄 Evidencia: [`logs/branches.txt`](logs/branches.txt)

---

### 7️ Fusión y resolución de conflictos
Se intentó fusionar la rama `feature/advanced-feature` en `main`, lo que generó un conflicto.  
El conflicto se resolvió manualmente en el archivo `main.py`.  
📄 Evidencia: [`logs/merge-o-conflicto.txt`](logs/merge-o-conflicto.txt)

---

## Extras

- No se usó ningún **repositorio remoto** (GitHub/GitLab).  
- No se usaron comandos avanzados opcionales (`git rebase`, `git revert`, `git stash`, `git cherry-pick`).  
- Se incluyó un archivo `.gitignore` para evitar el versionado de `venv/` y `__pycache__`.



