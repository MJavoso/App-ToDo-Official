# App-ToDo-Official

Una aplicación que te ayuda a organizar tus notas por cada ventana que utilizes. Para las personas que colocan sus recordatorios en el bloc de notas
y guardan su archivo raápidamente en alguna carpeta, y que después se olvidan de donde lo guardaron.

## Instalación
Ve a la pestaña de "Releases" o da click [aquí](https://github.com/MJavoso/App-ToDo-Official/releases) y descarga la versión más reciente de la aplicación.
Los sistemas operativos soportados son:
- Windows 10/11
- Linux (Distros basadas en Debian y con sistema de ventanas X11)
Las instrucciones de instalación se muestran primero antes que los archivos a descargar

## Uso
Para Windows 10 y 11, si instalaste la aplicación dentro de los directorios "Archivos de programa" o "Archivos de programa (x86)" entonces necesitarás ejecutar con permisos administrativos.
En Linux no se requiere ejecutar con "sudo", siempre y cuando se instale la aplicación con el ejecutable "install" y no manualmente con el comando "dpkg".

### Pantalla principal
![Pantalla principal](https://github.com/user-attachments/assets/a7ea6a16-43a9-445b-b464-1aab0699604f)

Aquí podrás ver todas las aplicaciones capturadas que hayas hecho. Para abrir las notas asociadas a determinada aplicación, dale click al botón de enlace a la derecha del nombre de la aplicación.
También se cuenta con el botón "Ver notas comunes", por si necesitas escribir notas que no estén asociadas a una ventana en específico.

Presiona el ícono de engranaje para acceder a la configuración.
Presiona el ícono de enchufe para apagar el servidor de escucha. Esto implica que al apagarlo, se cerrará la aplicación y dejará de funcionar hasta que la vuelvas a abrir.

### Pantalla de notas
![Notas](https://github.com/user-attachments/assets/84c12da3-06ea-4279-91c6-02e52a1831b0)

En esta pantalla podrás ver todas tus notas asociadas a una aplicación. Para ver una nota o editarla, dale doble click al elemento.
Si deseas borrar la nota, dale click al botón rojo a la derecha.
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
Puedes cambiar el atajo con el que activas la aplicación, pero estás restringido a usar la tecla Windows (o Super para Linux) y limitado para seleccionar una letra o número del teclado. No podrás seleccionar caracteres especiales ni ninguna otra tecla. Por defecto, el atajo es Super + O
