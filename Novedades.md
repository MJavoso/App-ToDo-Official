# Instrucciones de instalación

## Sistemas operativos soportados

- Linux (Distros basadas en Debian y con X11 como servidor o sistema gráfico de ventanas)
- Windows 10 y 11

## Novedades

> - Mejorada la interfaz de ejecutables y aplicaciones.
> - Ahora puedes cambiar entre las notas de las aplicaciones que pertenezcan al mismo ejecutable en la pantalla de notas
> - Agregada ventana de bienvenida al abrir por primera vez la aplicación
> - Corregido error donde crasheaba la aplicación al salir, debido al actualizador.
> - Corregido error visual donde no se guardaba el orden de nota al arrastrar hacia arriba o abajo.

## Linux - Debian o derivados con X11

> [!NOTE]
> Si quieres saber si tu entorno de ventanas actual es X11, ejecuta  el comando `xlogo`. Si te aparece una ventana, estas usando X11, de lo contrario, la aplicación no es compatible con tu sistema  de ventanas (ejemplo más conocido: Wayland).

Descarga el archivo App ToDo.tar.gz
Abre una terminal y entra en la carpeta donde tengas guardado el archivo. Ejecuta el siguiente comando:
`tar zxvf "App ToDo.tar.gz"`

Ahora solo ejecuta el comando:
`./install`

Y se instalará automáticamente.

> [!WARNING]
> Si no ejecutas el archivo install, solo podrás ejecutar la aplicación con sudo

## Windows

Descarga el instalador (.exe). Desactiva cualquier antivirus o agrega una excepción al archivo de instalación ya que se creó con la herramienta [Inno Setup](https://jrsoftware.org/isinfo.php), la cual lanza falsos positivos (IDP.Generic en el caso de Avast Antivirus). Si ejecutas primero el instalador y el antivirus lo bloquea, puede que se dañe y tengas que volver a descargarlo.
Sigue las instrucciones del instalador.
