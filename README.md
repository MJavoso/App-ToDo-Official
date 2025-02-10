# App-ToDo-Official

Una aplicación que te ayuda a organizar tus notas por cada ventana que utilizes. Para las personas que colocan sus recordatorios en el bloc de notas
y guardan su archivo raápidamente en alguna carpeta, y que después se olvidan de donde lo guardaron.

## Instalación

>[!NOTE]
> Las instrucciones de instalación se muestran primero antes que los archivos a descargar. Síguelas para evitar errores de instalación.

Ve a la pestaña de "Releases" o da click [aquí](https://github.com/MJavoso/App-ToDo-Official/releases) y descarga la versión más reciente de la aplicación.
Los sistemas operativos soportados son:

- Windows 10/11
- Linux (Distros basadas en Debian y con sistema de ventanas X11)

## Uso

Para Windows 10 y 11, si instalaste la aplicación dentro de los directorios "Archivos de programa" o "Archivos de programa (x86)" entonces necesitarás ejecutar con permisos administrativos.
En Linux no se requiere ejecutar con "sudo", siempre y cuando se instale la aplicación con el script "install" y no manualmente con el comando "dpkg".

### Pantalla principal

![Pantalla principal](images/Pantalla%20principal.png)

Aquí podrás ver todas las ventanas (junto con su ejecutable y su ruta) que has abierto al menos una vez.

Para abrir las notas asociadas a determinada aplicación, primero expande la lista de ventanas de un ejecutable con el botón '+'. La pantalla debería verse así:

![Ejecutables expandidos](images/Pantalla%20principal%20(expansion).png)

En esta pantalla podrás buscar aplicaciones que pertenezcan solo al programa al que pertenecen.

Se puede abrir las notas de una ventana de dos maneras:

1. Doble click al elemento.
2. Click al elemento para seleccionarla y darle click al botón de documento a la derecha

Al estar seleccionado:
![Elemento de ventana](images/Pantalla%20principal%20(elemento%20selec).png)

Los ejecutables se caracterizan por el ícono binario, mientras que las ventanas son distinguidas por un logo de ventana estilo Mac OS.
También se cuenta con el botón "Ver notas comunes", por si necesitas escribir notas que no estén asociadas a una ventana o ejecutable en específico.

### Pantalla de notas

![Notas](images/Pantalla%20Notas.png)

En esta pantalla podrás ver todas tus notas asociadas a una aplicación. Para ver una nota o editarla, dale doble click al elemento, o selecciona un elemento y dale click al lápiz.
También puedes borrar la nota al tenerla seleccionada. Dale click al botón de la basura rojo a la derecha. Si deseas marcar una nota como completada, use el recuadro a la izquierda de la nota. La nota se moverá al principio o al final de la lista, dependiendo de los filtros activos (lea más adelante).

También puedes cambiar de contexto de ventana fácilmente presionando el ícono de menú de arriba a la izquierda. Podrás ver las ventanas que tengan notas, siempre y cuando pertenezcan al mismo ejecutable. Si quieres cambiar hacia otra ventana con distinto ejecutable, tendrás que regresar a la página principal.

![Elemento de nota seleccionado](images/Pantalla%20Notas%20(elemento%20selec).png)

> [!WARNING]
> Las notas se eliminan 24 horas después de haber sido marcadas como eliminadas.

Para crear una nota dale click al botón "Crear nota". Puedes crear rápidamente una nota presionando **Ctrl + N** mientras la ventana esté enfocada.
Para regresar a la pantalla principal, presiona el icono de hogar ubicado arriba a la izquierda.

#### Filtros

![Filtros](images/Filtros%20Notas.png)

Se pueden filtrar las notas usando el botón a la derecha, debajo del botón para crear una nota. Los filtros disponibles se basan en ordenar por fecha de creación y por fecha de modificación, además de mostrar al principio o al final notas que hayan sido marcadas como completadas.

Alternativamente, existe el orden personalizado, donde tu puedes crear el orden de tus notas tan solo arrastrandolas por la lista.

> [!NOTE]
> La opción de "notas terminadas primero" estará deshabilitada en este modo.
> Al aplicar el filtro personalizado en una aplicación, en otras aplicaciones que no tenga un orden previo ordenará por notas más antiguas.

### Editar una nota

![edición](images/Pantalla%20edicion.png)

Aquí es donde editas una nota.
Las notas deben tener obligatoriamente un título, pero el contenido es opcional. Para guardar la nota, abre el menú "Archivo" y dale click a la opción guardar,  o presiona Ctrl + S.

Puedes salir de la ventana presionando Shift + Esc.

### Configuración

![configuracion](images/Pantalla%20Configuración.png)

En esta pantalla podrás cambiar los parámetros de la aplicación, como el tema, el puerto de ejecución del servidor y el atajo para abrir la aplicación.
El tema por defecto es el tema claro, y puedes cambiarlo a modo oscuro.
Para poder capturar los nombres de las ventanas activas, la aplicación debe de montar un servidor local. Si tienes un firewall, deberás darle permisos para acceder a la red local. Cambia el puerto por si es que cuentas con una aplicación que también ocupe el mismo puerto. (recomendado: 16000).
Puedes cambiar el atajo con el que activas la aplicación, pero estás restringido a usar la tecla Windows (o Super para Linux) y limitado para seleccionar una letra o número del teclado. No podrás seleccionar caracteres especiales ni ninguna otra tecla. Por defecto, el atajo es Super + O.
