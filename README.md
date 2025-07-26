# Mini-IRCap 2.5

⚙️ Objetivo del Proyecto

Mini-IRCap busca recrear la esencia del IRC clásico, respetando su estética retro pero aprovechando la eficiencia y flexibilidad de los lenguajes modernos. No pretende ser un reemplazo de mIRC, sino una alternativa minimalista y sin scripting que concentra solo lo esencial para disfrutar del IRC sin distracciones.

🧩 Descripción del Software y 🛰️ Características principales

Cliente de IRC en español para Windows, inspirado en el script para mIRC, IRcap. Desarrollado en VB.NET utilizando la librería SmartIrc4net de Meebey.

Aplicación ligera y ejecutable de 506 KB (no requiere instalación). Compatible con la mayoría de servidores del IRC, está especialmente optimizada para chatear en las principales redes hispanohablantes: IRC-Hispano, ChatZona y Chateamos. Ofrece soporte para conexión cifrada mediante SSL (en IRC-Hispano) y admite la mayoría de eventos y comandos, con opciones de Operador ("@") en menú, decodificación de texto con formato decorativo, fuente personalizable, tamaño de texto ajustable y cuatro colores de fondo disponibles. Cuenta con numerosos detalles refinados que la convierten en una aplicación de chat intuitiva, fácil de usar y, sobre todo, práctica.

🖥️ Interfaz:

![cap](https://github.com/user-attachments/assets/eba349d5-1b3e-4262-947e-ad6496a32b66)

🌐 Web: https://www.mini-ircap.com

🎬 YouTube: [Video Mini-IRCap 2.5](https://www.youtube.com/watch?v=canENWhkpyU)

🛡️ Seguridad y recomendaciones

La librería [SmartIrc4net](https://github.com/meebey/SmartIrc4net) (.dll) ha sido integrada en el ejecutable mediante [ILRepack](https://github.com/ravibpatel/ILRepack.Lib.MSBuild.Task) (MSBuild), lo que podría generar falsos positivos en algunos antivirus, especialmente en aquellos de dudosa reputación. Asimismo, el archivo ha sido firmado digitalmente con un certificado autofirmado (cosmos89.pfx) usando SignTool, lo cual no evita las advertencias de SmartScreen, ni asegura reconocimiento por parte del sistema operativo. Si tu navegador bloquea el acceso, también está disponible una versión base comprimida en "Mini-IRCap.2.5.rar", que incluye la DLL por separado.

Dado que me presento como un programador amateur y aún desconocido, sugiero analizar Mini-IRCap en [VirusTotal](https://www.virustotal.com/) antes de su ejecución, como medida de transparencia y para brindar mayor tranquilidad. Adicionalmente, también pueden ejecutar la aplicación dentro de un entorno aislado, como una máquina virtual o sandbox, para evaluar su comportamiento de forma segura.

Invito a cada usuario a revisar los resultados y a contrastar la información con fuentes confiables, por cuenta propia o con el apoyo de un experto.

En última instancia, si desean obtener el proyecto en VB.NET con el código fuente, no duden en contactarme a través de mi correo electrónico.

Gracias por su atención. — cosmos89
