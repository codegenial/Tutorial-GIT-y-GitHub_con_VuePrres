# Fundamentos de GIT

En este apartado podrás comenzar a trabajar con git.

## Comandos básicos

Aprendamos los primeros comandos con git

```javascript
//Conocer la versión de git instalada
git version
```
```javascript
// Ayuda sobre los comandos
git help
```
```javascript
// Iniciar un nuevo repositorio
// Crear la carpeta oculta .git
git init
```
```javascript
// Ver que archivos no han sido registrados
git status
```
```javascript
// Agregar todos los archivos para que esté pendiente de los cambios
git add .
```
```javascript
// Crear commit (fotografía del proyecto en ese momento)
git commit -m "primer commit"
```
```javascript
// Muestra la lista de commit del mas reciente al más antigüo
git log
```

En resumidas cuentas nosotros realizamos cambios en nuestros archivos, el comando status verificará que archivos han sidos modificados. Cuando deseemos registrar esos cambios tendremos que agregarlos con add . así ya estará listo para poder hacer un commit. El commit realiza la copia de ese instante para poder volver en el tiempo si es que es necesario.

## Trucos

```javascript
// Muestra en una línea los commit realizados
git log --oneline
```
```javascript
// Muestra en una línea los commit realizados pero más elegante
git log --oneline --decorate --all --gr
```
```javascript
// Solo muestra los archivos modificados
git status -s
```

::: tip Diferencias entre -- y -
`--decorate` hace referencia a una palabra
`-s` hace referencia al comando o a varios comandos, `-sa` serían dos comandos diferentes.
:::

```javascript
// Vemos información de la rama maestra
git status -s -b
git status -sb //Hace lo mismo que el comando anterior
```
