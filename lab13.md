#### Tiziano Pirez 4to 4ta

# Laboratorio 1: Clonación de Máquinas Virtuales

## Objetivo:
Clonar una máquina virtual para crear una copia exacta.

## Pasos:

### Crear una máquina virtual base:
1. Crear una nueva máquina virtual con una instalación de un sistema operativo (ej: Ubuntu).
2. Realizar configuraciones iniciales básicas (ej: instalación de actualizaciones, herramientas de desarrollo).

### Clonación de la VM:
1. Apagar la máquina base.
2. En el menú de VirtualBox, hacer clic derecho sobre la VM -> Opción "Clonar".
3. Seleccionar "Clonación Completa" para una copia completa o "Clonación Enlazada" si se desea ahorrar espacio en disco (pero compartiendo discos virtuales).

![image](https://github.com/user-attachments/assets/70e2074c-55bb-43e1-b478-d620fafbede0)

### Verificación:
1. Iniciar ambas máquinas (la original y la clonada) para verificar que ambas funcionan correctamente de manera independiente.

### Informe esperado:
- Captura de pantalla de ambas máquinas corriendo de forma simultánea.
- Comandos que verifiquen que tienen configuraciones de red y hostname diferentes.

![image](https://github.com/user-attachments/assets/8a323da5-5de8-4cff-8968-2ee1ac5333aa)

# Laboratorio 2: Uso de Guest Additions

## Objetivo:
Instalar y utilizar Guest Additions para mejorar la integración entre el sistema host y las máquinas virtuales.

## Pasos:

### Instalar Guest Additions:
1. Iniciar la máquina virtual.
2. Desde el menú de VirtualBox, ir a "Dispositivos" -> "Insertar imagen de CD de las Guest Additions".
3. Dentro de la VM, abrir un terminal y ejecutar el siguiente comando:
    ```bash
    sudo sh /media/cdrom/VBoxLinuxAdditions.run
    ```
4. Reiniciar la VM.

### Verificación:
1. Probar la redimensión automática de la pantalla.
2. Habilitar y probar la opción de compartir portapapeles y arrastrar y soltar archivos.

### Informe esperado:
- Capturas de pantalla del cambio de tamaño dinámico de la ventana.
- Una demostración de arrastrar un archivo entre el host y la VM.

![image](https://github.com/user-attachments/assets/70fa4fbe-2282-4f49-bd64-d28a908066e6)
![image](https://github.com/user-attachments/assets/671b6d21-13e5-41f0-92d8-374aa4bbd1bb)


