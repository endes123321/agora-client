# Agora-web
[Preview](https://cdn4.telesco.pe/file/s_ErkvhxrhI1TObPrbo5ZX1QSgx8lnhrbsthrqHrzOL3SanWG3bw0GD_4iW3N0Kg8B7MQxTg3suNPFiG-wF0jJmOcr8oZImDWUC0DvJJbHPtRmCUQBfGTn-GWnJIcHMiNlB9vx-HnRs8V2OUHxq6N6jh_KBshGGd2uHe_Y_ji7dyPkiGUzI__NAXMvqhZLtrqjbd56jhwaCiXmHrvR_JanmRzIaERIRAkpUA7LJP5BR2ddKR7D5d1Np-lrlyf3Vp8Zq8Hetiyp-G9YaZh6U3zPEVHWOjcSjnqZs6pfok1D4LvGmMigeDrtm38WEDADPfKAPRRYjM0R7hRSB9_FtjAg.mp4)

Cliente para la red social Agora, la cual tiene como fin reflexionar y debatir. Aunque actualmente no lo es, pretende ser distribuida gracias a la tecnología blockchain. **Advertencia:** Abandonada (deprecated), en pos de [nagora](https://notabug.org/org/nagora/), una red social mas completa pero que usa xmpp para ser descentralizada.
## instalación
Una vez compilada puedes usarla abriendo el index.html dentro de `bin/web` o poner esa carpeta en cualquier servidor web y abrir la dirección de este en el navegador.
Ademas tendrás que conocer un [servidor Agora], el cual puedes ponerlo en el archivo `cfg/server.json`:
```json
{
  "name": "<nombre del servidor>",
  "host": "<dirección con puerto>",
  "secure": <true si el seervidor usa ssl o false de lo contrario>
}
```
Para crear un servidor de agora puede encontrar el código fuente [aquí](https://notabug.org/Agora/Agora-server).
## Compilación
Para compilarlo se requerirá `haxe` y las instalar las siguientes librerías a través del siguiente comando: `haxelib install tamina actuate ckeditor-externs`.
Después, se puede compilar ejecutando `haxe compile_web.hxml` para una versión de producción y `haxe compile_debug.hxml` para debugueo.
## Por hacer
- Ser distribuida a través de un blockchain.
- Pestaña para crear posts a traves de ckeditor.
- Pestaña Yo, para mostrar tu propio perfil y la configuración.
- Estilo propio para _semantic css_.
- Sistema de reporte.
- Algunas ideas que nunca implemente como un resaltador de argumentos con información de estos, un extractor y comparador de tesis(sentences en el protocolo), opiniones acerca de conceptos o actualidad, comentarios y post relacionados o post en contra de un post.
- Algunos por hacer (TODOS) sueltos por el código.
- Mejoras al código.

---
Por beartek, un hiperproyecto de [netalabtek](https://netalab.tk).
