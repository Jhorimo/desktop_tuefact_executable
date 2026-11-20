# Brain Tech para Windows

Instalador de la aplicación de escritorio de Brain Tech.

## Descargar

[Descargar la última versión](https://github.com/Jhorimo/desktop_tuefact_executable/releases/latest/download/Brain-Tech-Setup.exe)

Las versiones anteriores están en [Releases](https://github.com/Jhorimo/desktop_tuefact_executable/releases).

## Requisitos

- Windows 10 u 11 de 64 bits
- Conexión a internet

## Instalación

1. Descarga `Brain-Tech-Setup.exe`.
2. Ábrelo con doble clic. Se instala solo y crea un acceso directo en el escritorio.
3. Inicia sesión con tu usuario de Brain Tech.

Si Windows muestra **"Windows protegió su PC"**, pulsa **Más información** y luego **Ejecutar de todas formas**.

## Actualizaciones

La aplicación se actualiza sola. Cuando haya una versión nueva, la descarga en segundo plano y te pregunta si quieres reiniciar para instalarla. Si eliges **Más tarde**, se instala al cerrar la aplicación.

## Desinstalar

1. Abre **Configuración → Aplicaciones → Aplicaciones instaladas**.
2. Busca **Brain Tech**.
3. Pulsa los tres puntos **⋯** y luego **Desinstalar**.

También puedes hacerlo desde **Panel de control → Programas y características**.

Al desinstalar se conservan tus datos de inicio de sesión. Si vuelves a instalar, entras sin escribir tu usuario otra vez.

## Si no se puede desinstalar

Úsalo solo si al desinstalar aparece un error, por ejemplo **"Installer integrity check has failed"**, y no puedes instalar la versión nueva. Si tienes dudas, pide ayuda a soporte.

### 1. Cierra Brain Tech

Ciérrala por completo. Si sigue abierta, abre el **Administrador de tareas** con **Ctrl + Shift + Esc** y finaliza **Brain Tech**.

### 2. Borra la carpeta del programa

1. Pulsa **Windows + R**.
2. Escribe `%LOCALAPPDATA%\Programs` y pulsa **Enter**.
3. Borra la carpeta **brain-tech-desktop**.

No borres la carpeta `%APPDATA%\brain-tech-desktop`, porque ahí está tu sesión.

### 3. Quita Brain Tech de la lista de programas

1. Pulsa **Windows + R**, escribe `regedit` y pulsa **Enter**. Acepta el aviso de Windows.
2. En la barra de arriba pega esta ruta y pulsa **Enter**:
   `HKEY_CURRENT_USER\Software\Microsoft\Windows\CurrentVersion\Uninstall`
3. Haz clic en la carpeta `0c4eb65b-1b87-5ec2-9088-9ecffe3ce112`. A la derecha, **DisplayName** debe decir **Brain Tech**. Si no dice eso, no la borres.
4. Clic derecho sobre esa carpeta → **Eliminar** → **Sí**.
5. Pega esta otra ruta y pulsa **Enter**:
   `HKEY_CURRENT_USER\Software\0c4eb65b-1b87-5ec2-9088-9ecffe3ce112`
6. Clic derecho sobre esa carpeta → **Eliminar** → **Sí**.
7. Cierra el Editor del Registro.

### 4. Instala de nuevo

Descarga e instala la [última versión](https://github.com/Jhorimo/desktop_tuefact_executable/releases/latest/download/Brain-Tech-Setup.exe).
