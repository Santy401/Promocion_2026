Estos serian los pasos para tener un repositorio y sistema de auto actualización en nuestro sistema actualmente tenemos un modo de auto Actualización con TERMUX que debemos instalarlo desde la app F-DROID, ya que hallamos hecho eso debemos configurar lo que viene siendo el TERMUX con algunos comandos y archivos que crearemos.

## Requisitos Para Seguir
- Tener Github instalado
- Tener F-DROiD instalado y dentro instalaremos:
	- Termux
	- Termux Api
- Tener Obsidian con estas extensiones 
	- Git
	- Excalidraw

## Guía De Instalación y Configuración De TERMUX

Ya cuando hallamos cumplido con los requisitos debemos instalar las herramientas en TERMUX que vendrían siendo estas :
### Git

```
$ pkg install git
```

### SSH

```
$ pkg install openssh
```

### TERMUX API

```
$ pkg install termux-api
```

## Bajamos El Repositorio
Antes de ir a Obsidian debemos tener bajado lo que viene siendo el repositorio de Github que lo bajaríamos ejecutando el siguiente comando :

```
$ git clone https://github.com/Santy401/Promocion_2026.git 
```

*NOTA : Debes de tener configurada las credenciales de tu Github para sincronizar los cambios sin errores.*

## Configuración De Automatización
Después de bajarnos el repositorio y estar con las herramientas descargadas deberíamos de poder comenzar con la configuración de la automatización cuando entremos a TERMUX cuando hagamos un " **ls** " deberíamos de ver una carpeta llamada " **Storage** " debemos hacer un " **cd storage** " y ahi pasamos a la carpeta " **shared** " dentro de esa carpeta ejecutaremos un " **mkdir Obsidian** " Luego hacemos un " **cd Obsidian** " luego dentro estara el repo y accederemos a el 