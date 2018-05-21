
# Instalación del entorno de desarrollo
---

## Temario
---
* Virtualización.
* Preparación del entorno de desarrollo.
* Entorno de programación de algoritmos.
* Referencias.

## Virtualización 
---
Una [máquina virtual](https://es.wikipedia.org/wiki/Virtualizaci%C3%B3n), llamada Hypervisor o VMM (Virtual Machine Monitor), nos permite tener **varios ordenadores virtuales** ejecutándose sobre el mismo ordenador físico, esto quiere decir que la VMM **comparte recursos** de la maquina fisica (host).
La máquina virtual en general simula una plataforma de hardware autónoma incluyendo un sistema operativo completo que se ejecuta en paralelo. Típicamente varias máquinas virtuales operan en un computador central.
Ademas la virtualizacion permite la **evaluación de aplicaciones en distintos sistemas operativos**. En este sentido [Docker](https://www.docker.com/) es un proyecto de código abierto que automatiza el despliegue de aplicaciones dentro de **contenedores de software**, proporcionando una capa adicional de abstracción y automatización de virtualización a nivel de sistema operativo en Linux

### Instalación de Virtual Box (VB)

[Oracle VM VirtualBox](https://es.wikipedia.org/wiki/VirtualBox) es un **software de virtualización** que permite instalar sistemas operativos adicionales (guests), dentro de otro sistema operativo (host), cada uno con su propio ambiente virtual. Entre los sistemas operativos soportados se encuentran GNU/Linux, Mac OS X, OS/2 Warp , Microsoft Windows, y Solaris/OpenSolaris, y dentro de ellos es posible virtualizar los sistemas operativos FreeBSD, GNU/Linux, OpenBSD, OS/2 Warp, Windows, Solaris, MS-DOS y muchos otros.

En primero lugar y con el objetivo de **unificar los entornos de desarrollo** es necesario crear una maquina virtual con Linux y trabajar sin importar el sistema operativo que disponga cada usuario. Para lo cual es necesario instalar [Oracle VM VirtualBox](https://www.virtualbox.org/). Dependiendo del sistema operativo instalado en el host el procedimiento varia, en el caso de Windows solo se limita a descargar el [instalador](https://www.virtualbox.org/wiki/Downloads), pero en Linux es necesario pasos adicionales y depende mucho de la distribución, por este motivo es recomendable buscar en la red el procedimiento para la distribución de Linux deseada.

Alternativas: 
* [Boxes](https://wiki.gnome.org/Apps/Boxes) (solo para Linux)
* [Etcher](https://etcher.io/) (multiplataforma)

> **Tarea** - Instalar software de virtualización, descargando desde el website y siguiendo las recomendaciones oficiales.

### Sistemas operativos - Linux

Actualmente los desarrolladores utilizan como plataforma preferida las basadas en [Linux](https://insights.stackoverflow.com/survey/2018). Un caso especial de esto es [Raspbian](https://es.wikipedia.org/wiki/Raspbian).

#### Distribución Raspian

Una distribución del sistema operativo GNU/Linux y por lo tanto libre basado en Debian Jessie (Debian 8.0) para las single board computer o SBC [Raspberry Pi](https://www.raspberrypi.org/), orientado a la enseñanza de informática y prototipado. La eleccion de este sistema operativo se baso en que las aplicaciones preinstaladas serán de gran utilidad para este curso, ademas de ser una plataforma de desarrollo en pleno auge.

> **Tarea** - Descargar la ultima version de [Raspberry Pi Desktop](https://www.raspberrypi.org/downloads/raspberry-pi-desktop/).

A continuación se procede a virtualizar el sistema operativo descargado, para lo cual se procede como se recomienda a continuación:

> **Tarea** - Instalar la imagen descargada en una VMM siguiendo los pasos destallados en la siguiente [web](https://www.luisllamas.es/raspberry-pi-virtualbox/).

## Preparación del entorno de desarrollo

Iniciar la VMM recientemente generada.

![](imagenes/vmm.png)

Unas vez iniciada la WMM, se abre una ventana con el sistema operativo corriendo.

![](imagenes/raspbian.png)

### Modificar la resolución de pantalla

Antes de coment


Some basic Git commands are:

```shell
foo@bar:~$ whoami
```
