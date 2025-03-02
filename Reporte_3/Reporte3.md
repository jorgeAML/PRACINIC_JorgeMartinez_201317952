Universidad de San Carlos de Guatemala

Facultad de Ingeniería

Escuela de ciencias y sistemas

Prácticas iniciales

Ing. Floriza Avila

# Informe No.1 / Manual de instalación servidor Apache

Jorge Anibal Martínez Letona

Carné: 201317952

## Introducción
El sistema operativo linux es un software libre que ofrece una variedad de aplicaciones y alto rendimiento para la instalación de servidores locales y en la nube, este manual se enfocará en la instalación de un servidor apache en ubuntu WSL, proporcionando los comandos utilizados durante su ejecución.

### Versión recomendada
Para esta instalación se llevo a cabo desde el sistema operativo Ubuntu WSL, pero el usuario queda libre de usar cualquier distribución de su gusto.

### Requisitos previos a la instalación
Para tener una instalación exitosa del sistema operativo linux, se aconseja tener conocimiento del computador donde se instalará, ya que este puede tener o no una unidad óptica sino la instalación deberá hacerse por medio de USB, pero por experiencia aconsejamos que se realice usando CD o DVD para la instalación, teniendo cuidado del sistema operativo si es X32 o x64.

### Requisitos del sistema
#### Especificaciones mínimas y recomendadas
- 4GB Ram
- 32GB almacenamiento
- Puertos USB
- Unidad óptica (opcional)
- Procesador Intel, AMD
- Tarjeta gráfica

#### Requisitos de software
- si es instalación por medio de USB, cambiar la configuración del BIOS, arrancar desde USB.
- Tener una imagen de Linux en USB, CD o DVD.

### Descarga de la imagen ISO
Para poder descargar la imagen debemos de ir al sitio original de la distribución así como para [Linux Mint](https://www.linuxmint.com/) podemos visitar el sitio web y navegar entre las distintas variantes que ofrece la distribución, o así como [Ubuntu WSL](https://ubuntu.com/desktop/wsl) también podemos visitar su sitio web y podemos verificar su atenticidad y especiales usos que ofrece la distribución.

### Creación del medio de instalación
- Uso de herramientas para crear un USB bootable:
- Windows: Rufus
- Linux: Ventoy
- Mac: terminal, BalenaEtcher

### Configuración del BIOS/UEFI
- Acceder al BIOS
- Habilitar secure boot
- Configurar orden de arranque
- Modo de arranque: Legacy y UEFI.

### Instalación del sistema operativo
- Arranque desde USB Bootable
- Escoger un modo de instalación(mínima, completa, live)
- Partición de disco, automática o SWAP
- Creación de usuario y configuración básica
- Instalación GRUB.

### Primer inicio y Configuración iniciales
Para poder comenzar a utilizar ubuntu debemos de actualizar los paquetes de aplicación de nos ofrece Ubuntu para ello debemos de asegurarnos de estar conectados a internet para inicializar la descarga de paquetes con el siguiente comandos:

> sudo apt update

este comando actualizará los paquetes y software a los más recientes.
![sudo apt update](./imagenes/sudoaptupdate.png)
