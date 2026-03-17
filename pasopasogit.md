# 📚 Guía completa de Git

---

## 🎈 Clonar un proyecto

Abre **Git Bash** o la terminal de Git y ejecuta:

```bash
git clone https://github.com/LillianaU/tallerAlertasJs.git
```

Esto descargará el proyecto desde GitHub a tu computador.

---

## 👤 Configurar tu usuario de Git

Configura tu nombre y correo para identificar tus commits:

```bash
git config --global user.name "miusuario"
git config --global user.email "micorreo@gmail.com"
```

### 🧪 Verificar configuración

```bash
git config --list
```

---

## 🥽 Inicializar Git en un proyecto

Si el proyecto no tiene Git inicializado:

```bash
git init
```

---

## 🔍 Verificar la rama actual

```bash
git branch
```

---

# 🚀 Subir un proyecto a GitHub (paso a paso)

### 1️⃣ Conectar el repositorio local con GitHub

```bash
git remote add origin https://github.com/LillianaU/expresiones_regulares.git
```

### 2️⃣ Establecer la rama principal

```bash
git branch -M main
```

### 3️⃣ Agregar archivos al repositorio

Agregar **todos los archivos**:

```bash
git add .
```

📌 El punto `.` significa **todos los archivos de la carpeta**.

---

### ✨ Agregar un archivo específico

```bash
git add NombreArchivo.extension
```

Ejemplo:

```bash
git add menu.html
```

---

### 4️⃣ Crear un commit

```bash
git commit -m "Estamos subiendo el index al repositorio con la documentación de JavaScript sobre expresiones regulares. Esta es la plantilla inicial sin funciones."
```

---

### 5️⃣ Subir el proyecto a GitHub

```bash
git push -u origin main
```

---

# 🔄 Actualizar y subir cambios después

Si ya hiciste cambios y quieres **volver a subirlos**:

### 1️⃣ Verificar estado del repositorio

```bash
git status
```

---

### 2️⃣ Agregar cambios

```bash
git add .
```

o archivos específicos:

```bash
git add pasopasogit.md
```

---

### 3️⃣ Crear un nuevo commit

```bash
git commit -m "Complementé el tutorial de Git"
```

---

### 4️⃣ Subir los cambios

Si ya configuraste el repositorio remoto:

```bash
git push -u origin main
```

Si necesitas **loguearte de nuevo** (GitHub puede pedir token o usuario):

```bash
git push
```

- Ingresa tu **usuario de GitHub**  
- Ingresa tu **token de acceso personal** (si GitHub pide autenticación)

---

# 🔁 En caso de conflicto con cambios remotos

Si el repositorio remoto tiene cambios que tu local no tiene:

```bash
git pull origin main --allow-unrelated-histories
```

Luego vuelve a subir tus cambios:

```bash
git push -u origin main
```

---

# 🧠 Resumen rápido

```bash
git add .
git commit -m "mensaje del cambio"
git push
```

✅ Este flujo cubre:  
- Clonar repositorio  
- Configurar usuario  
- Inicializar Git  
- Agregar archivos  
- Crear commits  
- Subir cambios  
- Reconectar con el repositorio y loguearse si es necesario  
- Resolver conflictos

git pull origin main --rebase
git push -u origin main

### 1. Traer los cambios de GitHub a tu PC
Ejecuta este comando para descargar lo que está en la nube y mezclarlo con tu trabajo:
bash
git pull origin main --allow-unrelated-histories
