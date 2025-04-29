# Comandos Básicos de Git/GitHub

## Guardar cambios en el repositorio

### 1. Verificar cambios
```bash
git status
```

### 2. Agregar archivos al staging
```bash
# Todos los archivos
git add .

# Archivo específico
git add nombre_archivo
```

### 3. Confirmar cambios (commit)
```bash
git commit -m "Mensaje descriptivo"
```

### 4. Subir cambios a GitHub (push)
```bash
git push origin nombre_rama
# Ejemplo para rama main:
git push origin main
```

## Clonar un repositorio

### 1. Obtener URL
HTTPS: `**https://github.com/usuario/repositorio.git**`

SSH: `**git@github.com:usuario/repositorio.git**`

### 2. Clonar
```bash
# Opción HTTPS
git clone https://github.com/usuario/repositorio.git

# Opción SSH
git clone git@github.com:usuario/repositorio.git

# En carpeta específica
git clone URL repositorio carpeta-destino
```

### 3. Navegar al directorio
```bash
cd nombre-repositorio
```

## Comandos adicionales útiles

| Comando                     | Descripción                          |
|-----------------------------|--------------------------------------|
| `git pull origin <rama>`     | Actualizar repositorio local         |
| `git branch -a`              | Listar todas las ramas (locales y remotas) |
| `git checkout <rama>`        | Cambiar de rama                      |
| `git fetch --all`            | Descargar cambios sin fusionar       |
| `git merge <rama>`           | Fusionar una rama con la actual      |
| `git log --oneline`          | Ver historial de commits resumido    |
| `git remote -v`              | Ver repositorios remotos configurados |