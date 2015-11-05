# emulacion-kids
Portal o plataforma para iniciar juegos de atari, nes, snes y nintendo 64 y reproductor de vídeos sencillo en la misma plataforma; Utilizando el joystic como mouse y dirigido a niños mayores de 4 años.

Se esta desarrollando en GAMBAS3 como Aplicación gráfica GTK+ por el momento...
En el camino, dependiendo de con qué problemas nos encontremos, podrá ser necesario cambiar de plataforma de desarrollo, por cuanto estamos abiertos a recomendaciones de la comunidad, apoyo, etc.

Por el momento, hay configuraciones manuales que hay que hacer:
- SO soportado (probado): XUBUNTU 14.04
- Configuración para Autenticación automática (sin necesidad de iniciar sesión en el sistema). https://distrosimple.wordpress.com/2011/12/12/manipula-lightdm-manualmente-en-xubuntu/
- Configuración a nivel de SO para usar el Joystick como Mouse. http://www.ubunturoot.com/2012/07/control-mouse-with-your-gamepadjoystick.html
- Las configuraciones del joystick en los emuladores es manual (hay configuraciones recomendadas pero no se han probado en diversas plataformas). Las configuraciones están en la carpeta conf de éste proyecto.
- Se debe modificar (configurar) el archivo sudoers de tal manera que el usuario que se autentica automáticamente no requiera ingresar contraseña para ejecutar comandos con sudo. http://www.formandome.es/linux/configuracion-fichero-sudoers-en-ubuntu/

Gracias por leer esto! Saludos!

Atte.
Team SkrDz-Sv
