# Práctica del curso de DevOps (KeepCoding)
___
## Despliegue Aplicación "Nodepop":

#### Descripción: 
* Utilizar Node como servidor de aplicación y **PM2** como ***gestor de procesos*** Node para que siempre esté en ejecución. La aplicación Node deberá reiniciarse automáticamente al arrancar el servidor.
* Utilizar **Nginx** como ***proxy Inverso*** que se encargue de recibir las peticiones HTTP y derivárselas a Node.
* Los *archivos estáticos* de la aplicación (imágenes, css...) deberán ser servidos por Nginx (no por Node). Para poder diferenciar quién sirve estos estáticos, se deberá añadir una **cabecera HTTP personalizada** cuando se sirvan estáticos cuyo nombre sea *X-Owner* y cuyo valor sea el nombre de la cuenta de usuario en github o bitbucket del alumno.

#### Enlace Repositorio Aplicación Nodepop
[`https://github.com/agdwm/06_KC_Backend_Avanzado`](https://github.com/agdwm/06_KC_Backend_Avanzado)


#### Enlace Despliegue Aplicación Nodepop:
[`http://nodepop.almudenaguerras.com`](http://nodepop.almudenaguerras.com)

## Despliegue de CV:
#### Enlace Repositorio Currículum Vitae:
[`https://github.com/agdwm/02_KC_Frotend_Basico_Entrega`](https://github.com/agdwm/02_KC_Frotend_Basico_Entrega)

#### Enlace Despliegue Currículum Vitae:
Se puede acceder a dicha página a través de:

* IP: [`54.175.6.229`](54.175.6.229)
* Dominio: [`https://cv.almudenaguerras.com`](https://cv.almudenaguerras.com)