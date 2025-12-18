# 🚀 Repositorio de Práctica Git

¡Bienvenido al repositorio de práctica! Este es un espacio seguro para que todos practiquen el flujo de trabajo con Git y GitHub.

## 📋 Objetivo

El objetivo es simple: cada miembro del equipo debe:
1. Clonar este repositorio
2. Crear su propia rama (branch)
3. Crear un archivo con su nombre
4. Hacer commit de los cambios
5. Crear un Pull Request

## 🛠️ Requisitos Previos

- Tener Git instalado en tu computadora ([Descargar Git](https://git-scm.com/downloads))
- Tener una cuenta en GitHub
- (Opcional) Tener configurado tu nombre y email en Git:
  ```bash
  git config --global user.name "Tu Nombre"
  git config --global user.email "tu.email@ejemplo.com"
  ```

## 📝 Instrucciones Paso a Paso

### 1. Clonar el Repositorio

Abre tu terminal o Git Bash y ejecuta:

```bash
git clone [URL_DE_ESTE_REPOSITORIO]
cd [NOMBRE_DEL_REPOSITORIO]
```

### 2. Crear tu Rama (Branch)

Crea una nueva rama con tu nombre (usa guiones en lugar de espacios):

```bash
git checkout -b mi-nombre
```

Por ejemplo: `git checkout -b juan-perez`

### 3. Crear tu Archivo

Crea un archivo con tu nombre en la carpeta raíz del proyecto:

```bash
touch tu-nombre.txt
```

O en Windows (CMD):
```bash
echo. > tu-nombre.txt
```

Puedes abrir el archivo y agregar información sobre ti (opcional):
- Tu nombre completo
- Tu rol en el equipo
- Tu lenguaje de programación favorito
- Un dato curioso sobre ti

### 4. Verificar los Cambios

Verifica que Git detectó tu nuevo archivo:

```bash
git status
```

Deberías ver tu archivo en rojo, indicando que no está en el área de preparación (staging).

### 5. Agregar el Archivo al Staging

Agrega tu archivo al área de preparación:

```bash
git add tu-nombre.txt
```

O para agregar todos los archivos nuevos:
```bash
git add .
```

### 6. Hacer Commit

Crea un commit con un mensaje descriptivo:

```bash
git commit -m "Agrego mi archivo personal - [Tu Nombre]"
```

### 7. Subir tu Rama a GitHub

Envía tu rama al repositorio remoto:

```bash
git push origin mi-nombre
```

### 8. Crear un Pull Request

1. Ve a la página del repositorio en GitHub
2. Verás un mensaje que dice **"Compare & pull request"** (aparece automáticamente después de hacer push)
3. Haz clic en ese botón
4. Agrega un título descriptivo, por ejemplo: "Agregar archivo de [Tu Nombre]"
5. (Opcional) Agrega una descripción
6. Haz clic en **"Create pull request"**

¡Listo! 🎉

## ❓ Preguntas Frecuentes

**P: ¿Qué hago si me equivoco?**  
R: ¡No te preocupes! Puedes deshacer cambios con `git reset` o pedir ayuda al equipo.

**P: ¿Puedo hacer varios commits en mi rama?**  
R: ¡Sí! Puedes hacer todos los commits que necesites antes de crear el Pull Request.

**P: ¿Qué pasa después de crear el Pull Request?**  
R: Un miembro del equipo revisará tu PR y lo aprobará para fusionarlo (merge) con la rama principal.

## 🆘 Comandos Útiles

```bash
# Ver en qué rama estás
git branch

# Ver el estado de tus archivos
git status

# Ver el historial de commits
git log --oneline

# Volver a la rama principal
git checkout main
```

## 🎯 Tips Adicionales

- **Nombres de rama**: Usa nombres descriptivos y en minúsculas con guiones
- **Mensajes de commit**: Sé claro y conciso sobre qué cambios hiciste
- **Pull Requests**: Agrega contexto en la descripción si es necesario
- **Sincronización**: Antes de empezar, asegúrate de tener la última versión: `git pull origin main`

## 🤝 ¿Necesitas Ayuda?

Si tienes problemas o dudas:
- Revisa la documentación oficial de [Git](https://git-scm.com/doc)
- Pregunta en el canal de Slack/Teams del equipo
- Contacta a [nombre del líder técnico]

---

**¡Feliz colaboración! 💻✨**
