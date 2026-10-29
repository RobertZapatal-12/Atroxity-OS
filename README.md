# Atroxity-OS
- git
https://education.github.com/git-cheat-sheet-education.pdf

- C/C++ Fundamentos
  
  https://www.youtube.com/watch?v=D7lEnQeK-CQ&list=PL7yh-TELLS1HSmBcqYk9LhPYSWp31FWH2

  https://www.learncpp.com/

  https://www.youtube.com/watch?v=2fSBLH-ISaE&list=PL7yh-TELLS1GafZOVHhCPaCQUt8HrfCZE

- Lo que debes saber sobre memoria
https://docs.google.com/spreadsheets/d/145RvpkXPHngCk-VL-F5otTAlWMJ04OhPl2zks7_HwRI/edit?gid=0#gid=0

- OS 
https://dokumen.pub/operating-systems-three-easy-pieces.html

- Arquitectura computacional.

https://alg.manifoldapp.org/projects/computer-organization?utm_source=chatgpt.com

## Estructura inicial del proyecto
Esta estructura simplificada esta sujeta a cambios.

```text
Atroxity-OS/
├── kernel/
│   ├── arch/
│   │   └── i386/
│   │       └── boot.s
│   ├── kernel.cpp
│   ├── terminal.c
│   └── linker.ld
├── include/
│   └── kernel/
│       ├── kernel.h
│       └── terminal.h
├── Makefile
├── iso/
│   └── boot/
│       └── grub/
│           └── grub.cfg
└── README.md
```

## Requisitos previos
Antes de instalar el proyecto asegurate de tener:

- Algun compilador de C/C++ (MINGW u otros)
- GNU Assembler (GAS)	Ensambla archivos Assembly (.s)
- GNU LD	Enlaza los archivos para generar el kernel
- GRUB	Carga el kernel al arrancar
- QEMU	Emula una computadora para probar tu OS
- Make	Automatiza el proceso de compilación

## Instalacion
### 1. Clonar el repositorio

```text
git clone https://github.com/RobertZapatal-12/Atroxity-OS
cd Atroxity-OS
```




