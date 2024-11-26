# Practica05SUnix

# Compilar Kernel

El kernel es el núcleo del sistema operativo. En el caso de Linux, el kernel es de código abierto, lo que significa que cualquiera puede descargarlo, modificarlo y distribuirlo

La compilación del kernel de Linux es un proceso en el que se toma el código fuente del kernel, se configura según las necesidades específicas del sistema y se transforma en un archivo binario ejecutable que el sistema operativo puede utilizar para gestionar el hardware y los procesos. El kernel es la parte central del sistema operativo y actúa como un intermediario entre el hardware del equipo y las aplicaciones de software.

La mayoría de las distribuciones de Linux vienen con un kernel precompilado que ya está configurado para funcionar en la mayoría de los sistemas.Sin embargo, hay varias razones para compilar un kernel personalizado, como lo son :

- Optimización del rendimiento: Puedes eliminar características no necesarias, reduciendo el tamaño del kernel y mejorando el rendimiento.
- Compatibilidad de hardware: Algunos controladores específicos de hardware pueden no estar incluidos en el kernel predeterminado y deben ser activados manualmente.
- Actualización a una versión más reciente: Puedes compilar una versión más nueva del kernel para aprovechar las últimas mejoras y correcciones de seguridad.
- Personalización avanzada: Puedes habilitar funciones experimentales o específicas que no están disponibles en los kernels precompilados.

# Intrucciones
Tenemos que verificar que nuestra maquina tenga al menos 30 GB de almacenamiento, para que no haya ningun problema 

Checamos la version del kernel 

![image](https://github.com/user-attachments/assets/d751bc37-e0e3-4ee7-a603-fd9f2556e93c)

Luego instalamos las dependencias necesarias para compilar el kernel 

![image](https://github.com/user-attachments/assets/923651b8-926f-40aa-acb7-3566b30efa16)

Descargamos el codigo fuente de debian 12 del kernel usando wget 

![image](https://github.com/user-attachments/assets/b871c04a-0f77-4072-ac9e-76cf4fba7324)

Ahora lo extraemos 

![image](https://github.com/user-attachments/assets/9dd8f9bb-21b4-4343-985f-294835d37f0b)






