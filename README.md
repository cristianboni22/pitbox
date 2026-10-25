# Pitbox

**[Español](#español) · [English](#english)**

> **App no oficial. Sin relación con PiBoSo ni con gpb-mods.com.**
> *Unofficial app. Not affiliated with PiBoSo or gpb-mods.com.*

---

## Español

**Pitbox** es un launcher para **GP Bikes**: ves las salas online, te instala el circuito y las motos que te faltan
y te mete en la sala con un clic. Trae además el **Asistente de reglaje** dentro del juego (tecla F8), el ranking
mundial de vueltas y GP Bikes en tu idioma.

### Descargar

| Sistema | Descarga |
|---|---|
| Windows 10 / 11 | **[Pitbox-Windows.zip](https://github.com/cristianboni22/pitbox/releases/latest/download/Pitbox-Windows.zip)** |
| Linux | **[Pitbox-Linux.tar.gz](https://github.com/cristianboni22/pitbox/releases/latest/download/Pitbox-Linux.tar.gz)** |

Estos enlaces siempre bajan la última versión. Todas las versiones y sus novedades:
[página de descargas](https://github.com/cristianboni22/pitbox/releases/latest).

### Instalar en Windows

1. Descarga **Pitbox-Windows.zip**.
2. Clic derecho en el .zip → **Extraer todo…** en una carpeta fija, por ejemplo `C:\Juegos`. Dentro queda la
   carpeta **Pitbox**. (No lo abras desde dentro del .zip ni lo pongas en una carpeta que vayas a borrar: el acceso
   directo apunta ahí.)
3. Cierra GP Bikes, entra en la carpeta **Pitbox** y haz doble clic en **Instalar.bat**.
4. Si sale «Windows protegió su PC» (ventana azul): **Más información → Ejecutar de todas formas**. Sale porque el
   programa no está firmado por una empresa; es normal en programas hechos por la comunidad.
5. Revisa las carpetas que ha encontrado, elige el idioma del juego y pulsa **Instalar**. Tendrás un acceso directo
   «Pitbox» en el escritorio.

### Instalar en Linux

Necesitas `python3`, `python3-venv`, `python3-gi` y `gir1.2-webkit2-4.1`. Descarga **Pitbox-Linux.tar.gz**,
descomprímelo, entra en la carpeta **Pitbox** y ejecuta `./instalar.sh`.

### Actualizaciones

Pitbox se actualiza solo al abrirlo. Cada actualización está firmada (Ed25519) y Pitbox comprueba la firma y la
huella SHA-256 del paquete antes de instalar nada: lo que no esté firmado por el autor se rechaza, venga de donde
venga. Si tu operadora bloquea el servidor de Pitbox (pasa con algunas operadoras españolas durante los partidos de
LaLiga), Pitbox descarga la actualización de aquí, de GitHub.

### Qué hay en este repositorio

Solo los **archivos publicados y firmados** de cada versión (en [Releases](https://github.com/cristianboni22/pitbox/releases)):
los paquetes de Windows y Linux (con versión y con nombre fijo) y `actualizacion.json` + `actualizacion.json.sig`,
el aviso de actualización firmado que lee Pitbox. **Aquí no hay código fuente.**

### Comunidad y apoyo

- Discord: **https://discord.gg/xJPBru6DR** (ayuda, salas, novedades)
- Si te gusta Pitbox, puedes invitarme a un café en Ko-fi: **https://ko-fi.com/cristianboni22**

Los archivos se ofrecen tal cual, sin garantía. GP Bikes es de PiBoSo; los mods son de sus autores.

---

## English

**Pitbox** is a launcher for **GP Bikes**: see the online rooms, install the track and bikes you're missing and
join the room in one click. It also brings the in-game **Setup Assistant** (F8 key), the world lap ranking and
GP Bikes in your language.

### Download

| System | Download |
|---|---|
| Windows 10 / 11 | **[Pitbox-Windows.zip](https://github.com/cristianboni22/pitbox/releases/latest/download/Pitbox-Windows.zip)** |
| Linux | **[Pitbox-Linux.tar.gz](https://github.com/cristianboni22/pitbox/releases/latest/download/Pitbox-Linux.tar.gz)** |

These links always get the latest version. All versions and release notes:
[downloads page](https://github.com/cristianboni22/pitbox/releases/latest).

### Install on Windows

1. Download **Pitbox-Windows.zip**.
2. Right-click the .zip → **Extract All…** into a permanent folder, e.g. `C:\Juegos` (or `C:\Games`). You'll get a
   **Pitbox** folder. (Don't run it from inside the .zip or from a folder you'll delete: the shortcut points there.)
3. Close GP Bikes, open the **Pitbox** folder and double-click **Instalar.bat**.
4. If "Windows protected your PC" (blue window) shows up: **More info → Run anyway**. It appears because the program
   isn't signed by a company; that's normal for community-made software.
5. Check the folders it found, pick the game language and press **Install**. You'll get a "Pitbox" shortcut on your
   desktop.

### Install on Linux

You need `python3`, `python3-venv`, `python3-gi` and `gir1.2-webkit2-4.1`. Download **Pitbox-Linux.tar.gz**,
extract it, open the **Pitbox** folder and run `./instalar.sh`.

### Updates

Pitbox updates itself when you open it. Every update is signed (Ed25519) and Pitbox checks the signature and the
package's SHA-256 before installing anything: anything not signed by the author is rejected, wherever it comes from.
If your ISP blocks the Pitbox server (some Spanish ISPs do during LaLiga matches), Pitbox downloads the update from
here, from GitHub.

### What's in this repository

Only the **published, signed files** of each version (under [Releases](https://github.com/cristianboni22/pitbox/releases)):
the Windows and Linux packages (versioned and with a fixed name) and `actualizacion.json` + `actualizacion.json.sig`,
the signed update notice Pitbox reads. **There is no source code here.**

### Community and support

- Discord: **https://discord.gg/xJPBru6DR** (help, rooms, news)
- If you like Pitbox, you can buy me a coffee on Ko-fi: **https://ko-fi.com/cristianboni22**

Files are provided as is, without warranty. GP Bikes belongs to PiBoSo; mods belong to their authors.
