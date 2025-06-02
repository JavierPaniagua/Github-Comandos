
# 🧑‍🏫 CLASE: Introducción a Git y GitHub

## 🔹 OBJETIVOS
- Comprender qué es Git y para qué sirve.
- Conocer la diferencia entre Git y GitHub.
- Aprender comandos básicos de Git.
- Realizar prácticas para usar Git en proyectos reales.

---

## 🔹 1. ¿Qué es Git?

> **Git** es un sistema de control de versiones distribuido. Permite llevar un registro de los cambios realizados en archivos (principalmente de código) y colaborar con otras personas de forma eficiente.

---

## 🔹 2. ¿Qué es GitHub?

> **GitHub** es una plataforma en línea donde se alojan proyectos que usan Git. Permite trabajar en equipo, compartir código y colaborar desde cualquier lugar.

---

## 🔹 3. Conceptos clave

| Término        | Definición                                                                 |
|----------------|---------------------------------------------------------------------------|
| Repositorio    | Carpeta donde se almacena el historial de versiones de un proyecto.       |
| Commit         | Registro de un cambio.                                                    |
| Branch         | Rama de trabajo independiente.                                            |
| Merge          | Combinar ramas.                                                           |
| Push           | Enviar cambios locales a GitHub.                                          |
| Pull           | Traer cambios desde GitHub a tu proyecto local.                           |
| Clone          | Descargar un repositorio de GitHub a tu PC.                               |

---

## 🔹 4. Comandos Básicos de Git (con ejemplos)

```bash
# Inicializa un repositorio en tu carpeta local
git init

# Configura tu nombre de usuario (una sola vez)
git config --global user.name "Pedro Paniagua"
git config --global user.email "pedro@email.com"

# Ver el estado de los archivos
git status

# Agrega un archivo al área de preparación
git add archivo.txt

# Hace un commit con un mensaje
git commit -m "Agregando archivo de ejemplo"

# Ver historial de commits
git log

# Clona un repositorio desde GitHub
git clone https://github.com/usuario/repositorio.git

# Enviar cambios al repositorio remoto
git push origin main

# Traer cambios desde el repositorio remoto
git pull origin main
```

---

## 🔹 5. Actividades prácticas

### 🧪 Práctica 1: Crear un repositorio local
1. Crear una carpeta llamada `proyecto_git`.
2. Inicializar Git con `git init`.
3. Crear un archivo `index.html`.
4. Hacer `add` y `commit`.

### 🧪 Práctica 2: Subir a GitHub
1. Crear un repositorio en GitHub (sin README).
2. Conectar tu repositorio local con:
```bash
git remote add origin https://github.com/usuario/proyecto_git.git
```
3. Subir con:
```bash
git push -u origin main
```

### 🧪 Práctica 3: Editar y hacer commit
1. Modificar el archivo `index.html`.
2. Ver los cambios con `git status`.
3. Hacer `add`, `commit` y `push`.

---

## 🔹 6. Evaluación (opcional)

**Responde:**
1. ¿Qué diferencia hay entre `git init` y `git clone`?
2. ¿Para qué sirve `git add`?
3. ¿Cómo se suben los cambios a GitHub?
4. ¿Qué hace el comando `git pull`?

---
