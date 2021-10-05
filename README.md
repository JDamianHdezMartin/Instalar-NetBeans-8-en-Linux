# Instalar-NetBeans-8-en-Linux
Guía rápida y sencilla para la instalación de NetBeans en Linux

## Pasos
### Paso 1
Descargar la versión deseada en este [enlace](https://www.oracle.com/technetwork/java/javase/downloads/jdk-netbeans-jsp-3413139-esa.html).
Hemos de descargar la versión jdk-8u111-nb-8_2-linux-x64.sh, aceptando los acuerdos de licencia.

![Captura de pantalla de 2021-10-04 19-59-44](https://user-images.githubusercontent.com/91153503/135997132-29d2500e-438e-4bbb-810e-71a23cabf7c3.png)

### Paso 2
Al finalizar la descarga, debemos ir hasta el directorio donde se ha descargado el instalador de NetBeans IDE y ejecute el siguiente comando para hacer ejecutable el script del instalador y comenzar a instalarlo.
Debería mostraste como la imagen siguiente:
```bash
chmod +x jdk-8u111-nb-8_2-linux-x64.sh
./jdk-8u111-nb-8_2-linux-x64.sh
```

![Captura de pantalla de 2021-10-04 20-00-39](https://user-images.githubusercontent.com/91153503/135997856-88affd65-4382-4fc0-a365-30af351c5337.png)

### Paso 3
Se mostrará la "pantalla de bienvenida", lo único que falta por hacer es seleccionar el lugar de instalación de NetBeans,seleccionar el lugar de instalación del servidor GlassFish, activar la actualizaciones automáticas y hacer click en instalar. Al finalizar debería mostrarse una ventana como la siguiente:

![Captura de pantalla de 2021-10-04 20-02-48](https://user-images.githubusercontent.com/91153503/135998390-b24edf14-2a94-426c-9093-3de4cb560943.png)

### Paso 4
Reiniciar la máquina y comprobar que NetBeans está instalado

![Captura de pantalla de 2021-10-05 10-39-48](https://user-images.githubusercontent.com/91153503/135999208-713184de-eba4-431f-8780-0dd54ed1570e.png)
