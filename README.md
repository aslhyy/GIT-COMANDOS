# GIT-COMANDOS

# Comandos básicos de Git (control de versiones, local)

Estos comandos se usan en la **terminal** para manejar tu proyecto en tu computadora:

## Inicializar y clonar repositorios
- `git init` → Inicializa un nuevo repositorio en el directorio actual.  
- `git clone <url>` → Descarga un repositorio remoto (ej. de GitHub) a tu máquina local.  

## Estado y seguimiento
- `git status` → Muestra el estado de los archivos (modificados, agregados o no rastreados).  
- `git add <archivo>` → Agrega archivos al área de preparación (*staging*) para el próximo commit.  

## Guardar cambios
- `git commit -m "mensaje"` → Guarda los cambios preparados en el repositorio local con un mensaje descriptivo.  

## Historial
- `git log` → Muestra el historial de commits (versiones).  
<<<<<<< HEAD
>>>>>>> e528e91f5a3cff62663708c6e19e0b78cd754032
 
=======

# Comandos de ramas y fusiones en Git

Permiten trabajar con distintas versiones del proyecto en paralelo:

## Ramas
- `git branch` → Lista todas las ramas del proyecto.  
  También se puede usar `git branch <nombre>` para crear una nueva rama.  

- `git checkout <nombre-de-rama>` → Cambia a otra rama y actualiza los archivos de trabajo.  

## Fusiones
- `git merge <nombre-de-rama>` → Fusiona los cambios de una rama con la actual.  

 Estos comandos son muy usados cuando se trabaja en equipo para separar tareas y luego unirlas.

>>>>>>> c0a7657adbecbb8938e7fc177e375a80bf9ee64e

# Comandos de GitHub y repositorio remoto

Estos comandos permiten conectar tu repositorio local con uno en la nube (GitHub, GitLab, etc.):

## Conexión con remoto
- git remote add origin <url> → Conecta el repositorio local con uno remoto.  

## Subir cambios
- git push origin <rama> → Sube los commits locales al repositorio remoto.  

## Descargar cambios
- git pull origin <rama> → Descarga los cambios del remoto y los fusiona con tu rama local.  
- git fetch → Descarga los cambios del remoto sin fusionarlos automáticamente.  

## Repositorio remoto
Un repositorio remoto es una copia de tu proyecto guardada en un servidor en la nube (ej. GitHub).  

Sirve para:  
- Compartir tu código.  
- Colaborar en equipo.  
- Respaldar tu proyecto.  
- Acceder desde cualquier lugar con internet.