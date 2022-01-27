# Codigo 13

## Comando para GIT

```
git init
```
- Este comando solo se hace una ve por proyecto, sirve para inicializar nuestro proyecto con git.
- :eye: crea una :file_folder: carpeta oculta llamada .git

```
git status
```
- Poder listar y ver si los archivos estan listo para subir.
- :eye: en caso de los archivos no esten listos se veran de color rojo y cuando lo esten seran de color verde.


```
git add .
git add . nombre_de_archivo
```
- Se encarga de agregar los archivos a la memoria de GIT, es decir los guarda en un stash.

```
git commit -m "comentario"
```
- Crear un punto en la linea de tiempo :time: de nuestros cambios y a estos se le es posible adjuntar un comentario.
- :eye: Los comentarios deben estar relacionados a los cambios que hice, esto es una recomendacion.

```
git push origin main
```
- Sirve para poder subir los cambios a nuestro repositorio en la nube, en este caso github
