# Git
## Comprobar que Git esté instalado

```
git -v
git version 2.38.1.windows.1
```

## Configuración global

```
git config --global user.name "Jhon Doe"
git config --global user.email "example@example.com"
```
## Crear un repositorio desde Github

## Inicializar git

```
git init
```

## Enlazar nuestro repositorio remoto

```
git remote add origin https://github.com/jorgelijah/CodiGO.git
```

## Definir la rama principal

```
git branch -M main
```
## Subir los cambios

```
git add --all
git commit -m "my first commit"
git push origin main
```