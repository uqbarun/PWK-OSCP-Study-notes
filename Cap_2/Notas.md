# Capitulo 2

## Acostumbrándonos a Kali

Kali es creado y mantenido por Offensive Security, es una distribución Linux basada en Debian que contiene multiples herramientas de seguridad. Se recomienda dar un vistazo al curso gratuito [KLR/PEN-103](https://portal.offensive-security.com/courses/pen-103) que sirve como un complemento a la información presentada aquí.

## Arrancando Kali

*Offsec* recomienda descargar la imagen oficial de la VM (Para VMware o VirtualBox) desde su [sitio web](https://www.kali.org/get-kali/#kali-virtual-machines), recuerde [verificar el checksum](https://docs.hak5.org/hc/en-us/articles/360049922674-How-to-verify-the-SHA256-checksum-of-a-downloaded-file) del archivo de descarga antes de utilizarlo.

Las versiones comerciales de VMware (*Worksation Pro* y *Fusion*) y VirtualBox tienen la funcionalidad de snapshots que nos permite restaurar la maquina virtual a un estado previamente guardado por si algo falla de forma irreversible. Por defecto, la VM de *OffSec* tiene dos usuarios (*root* y *kali* ) y se recomienda iniciar con el usuario *kali*. Algunos comandos requieren privilegios elevados, para ello utilice el comando `sudo` antes de los otros comandos. 

Las credenciales por defecto de la VM de offsec son:

- User: **kali**
- Password: **kali**

> **Nota:** Recuerde cambiar la contraseña por defecto con el comando `passwd`

## Menu de Kali
