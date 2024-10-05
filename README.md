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
![Pantalla principal](https://github.com/user-attachments/assets/be8b85d0-376d-4773-9fb4-0c60a4f75408)

Aquí podrás ver todas las ventanas (junto con su ejecutable y su ruta) que has abierto al menos una vez.

Para abrir las notas asociadas a determinada aplicación, primero expande la lista de ventanas de un ejecutable, y después, usa el botón de abrir documento ubicado a la derecha para abrir las notas de la ventana.

![Ejecutables expandidos](https://github.com/user-attachments/assets/58024a3a-26c9-453a-bff7-5496528a57fb)

Los ejecutables se caracterizan por el ícono binario, mientras que las ventanas son distinguidas por un logo de ventana estilo mac.
También se cuenta con el botón "Ver notas comunes", por si necesitas escribir notas que no estén asociadas a una ventana o ejecutable en específico.

Presiona el ícono de engranaje para acceder a la configuración.
Presiona el ícono de enchufe para apagar el servidor de escucha. Esto implica que al apagarlo, se cerrará la aplicación y dejará de funcionar hasta que la vuelvas a abrir.

### Pantalla de notas
![Notas](https://github.com/user-attachments/assets/acf71faf-390b-485c-82e2-679396d7c5df)

En esta pantalla podrás ver todas tus notas asociadas a una aplicación. Para ver una nota o editarla, dale doble click al elemento.
Si deseas borrar la nota, dale click al botón rojo a la derecha. Si deseas marcar una nota como completada, use el recuadro a la izquierda de la nota. La nota se moverá al principio o al final de la lista, dependiendo de los filtros activos (lea más adelante).

> [!WARNING]
> Las notas se eliminan 24 horas después de haber sido marcadas como eliminadas.

![Filtros](https://github.com/user-attachments/assets/bf3dae37-fa0f-4ac0-ad72-0cc30282bbde)

Se pueden filtrar las notas usando el botón a la derecha, debajo del botón para crear una nota. Los filtros disponibles se basan en ordenar por fecha de creación y por fecha de modificación, además de mostrar al principio o al final notas que hayan sido marcadas como completadas.

Para crear una nota dale click al botón "Crear nota". Puedes crear rápidamente una nota presionando Ctrl + N mientras la ventana esté enfocada.
Para regresar a la pantalla principal, presiona el icono de hogar ubicado arriba a la izquierda.

### Editar una nota
![edición](https://github.com/user-attachments/assets/d48a490e-cba8-4a51-9ad9-69ba6f87b910)

Aquí es donde editas una nota.
Las notas deben tener obligatoriamente un título, pero el contenido es opcional. Para guardar la nota, dale click al botón "Guardar" o presiona Ctrl + S. Al guardar la nota, se cerrará auomáticamente la ventana.

Puedes salir de la ventana presionando Esc.

### Configuración
![image](https://github.com/user-attachments/assets/45717f01-57ca-4c1c-a4ff-8b633afc0d0d)

En esta pantalla podrás cambiar los parámetros de la aplicación, como el tema, el puerto de ejecución del servidor y el atajo para abrir la aplicación.
El tema por defecto es el tema claro, y puedes cambiarlo a modo oscuro.
Para poder capturar los nombres de las ventanas activas, la aplicación debe de montar un servidor local. Si tienes un firewall, deberás darle permisos para acceder a la red local. Cambia el puerto por si es que cuentas con una aplicación que también ocupe el mismo puerto. (recomendado: 16000).
Puedes cambiar el atajo con el que activas la aplicación, pero estás restringido a usar la tecla Windows (o Super para Linux) y limitado para seleccionar una letra o número del teclado. No podrás seleccionar caracteres especiales ni ninguna otra tecla. Por defecto, el atajo es Super + O.
