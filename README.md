<p align="center"><img src="assets/icon.svg" width="96" alt=""></p>

<h1 align="center">ad video</h1>

<p align="center">Graba tu pantalla y tu cámara en Windows. Todo se queda en tu equipo.</p>

<p align="center">
  <a href="https://github.com/ing-alvarodm92/ad-video-descargas/releases/latest/download/ad-video-Setup.exe"><b>⬇ Descargar para Windows</b></a>
</p>

## Qué hace

- **Pantalla + cámara**: graba tu pantalla con tu cámara en una burbuja flotante que puedes
  mover y cambiar de tamaño mientras grabas.
- **Solo pantalla** o **solo cámara**.
- Borde de la burbuja **blanco, arcoíris, cambio de color** o **un color** con efecto de luz.
- Micrófono y sonido del ordenador, pausa, silencio y cuenta atrás.
- Biblioteca con tus vídeos para verlos, renombrarlos y descargarlos en MP4.

Los vídeos **nunca salen de tu ordenador**: la app no se conecta a internet.

## Instalación

1. Descarga **`ad-video-Setup.exe`** con el botón de arriba.
2. Ábrelo. Windows mostrará **«Windows protegió su PC»** porque el instalador no tiene firma
   digital: pulsa **Más información → Ejecutar de todas formas**. Si el navegador avisa al
   descargarlo, elige **Conservar**.
3. Se instala solo (sin permisos de administrador) y crea el icono **ad video** en el escritorio
   y en el menú Inicio.

Para actualizar, descarga e instala la versión nueva: tus vídeos se conservan.
Para desinstalar: **Configuración → Aplicaciones → ad video**.

## Requisitos

- Windows 10 (versión 2004 o posterior) u 11, de 64 bits.
- Si la cámara o el micrófono no aparecen: **Configuración → Privacidad → Cámara / Micrófono →
  «Permitir que las aplicaciones de escritorio accedan»**.

## Comprobar que el archivo es el original

Cada versión publica su huella **SHA-256** en la página de
[versiones](https://github.com/ing-alvarodm92/ad-video-descargas/releases). En PowerShell:

```powershell
Get-FileHash "$env:USERPROFILE\Downloads\ad-video-Setup.exe"
```

Si el resultado coincide, el archivo es idéntico al publicado.
