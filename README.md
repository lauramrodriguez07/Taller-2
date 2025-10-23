# Taller-2

#### Elaborado por: Diana Bernal y Laura Rodriguez

## Simulación y Despliegue de Robots con Docker y PyBullet

### INtroducción 
ESte proyecto tiene como objetivo implementar y desplegar simulaciones de tres tipos diferentes de robots (Drones, Baxter y ATLAS) utilizando Docker y PyBullet. El trabajo se centra en la creación de entornos containerizados que permiten la ejecución consistente y reproducibles de simulaciones robóticas, facilitando el desarrollo y pruebas de algoritmos de control y navegación.

### Objetivos:
+ Desplegar simulaciones de drones en contenedores de Docker
+ Implementar la simulación del robot Baxter con PyBullet en docker
+ Configurar y ejecutar el robot ATLAS en un entorno containerizado con PyBullet
+ Estableecer una metodologia reproducible para simulaciones roboticas

#### Desarrollo:

##### 1. Despliegue de Drones en Docker:

Para el despliegue de drones se utilizó como base el repositorio de referencia proporcionado. Se configuró un entorno Docker que incluye todas las dependencias necesarias para la simulación de drones, permitiendo una ejecución consistente independiente del sistema host. 
###### Implementación:

+ Configuración del Dockerfile con las dependencias requeridas
+ Establecimiento de los volúmenes y puertos necesarios
+ Integración con el simulador de drones
###### Proceso en el terminal:

<img width="1113" height="148" alt="image" src="https://github.com/user-attachments/assets/510dcd82-c348-40d6-9658-6eff4ed6c2e0" />
<img width="1600" height="306" alt="image" src="https://github.com/user-attachments/assets/83f3285f-43c6-4085-8f51-a4104f10bcf3" />
<img width="1600" height="306" alt="image" src="https://github.com/user-attachments/assets/b3c4258f-9fb6-4d08-bdda-dc4241ebcd0b" />
<img width="1600" height="304" alt="image" src="https://github.com/user-attachments/assets/b072ef44-87b8-4438-9338-4e12db87b5cb" />
<img width="1600" height="31" alt="image" src="https://github.com/user-attachments/assets/d0e5f0db-a4e4-4aa0-b541-e59c770e24cf" />
<img width="1600" height="563" alt="image" src="https://github.com/user-attachments/assets/c808af2c-c802-4a16-bc29-dc2a56e757b2" />
<img width="1600" height="245" alt="image" src="https://github.com/user-attachments/assets/e72d8c0a-6e1f-4811-bb6d-ef9262e61b7a" />
<img width="1600" height="819" alt="image" src="https://github.com/user-attachments/assets/cd71b9fe-c875-4b4e-8e71-c852e3fdcb71" />
<img width="1600" height="697" alt="image" src="https://github.com/user-attachments/assets/cc0a8a1f-0f83-47ef-bded-ecc4bd8192d7" />
<img width="1600" height="258" alt="image" src="https://github.com/user-attachments/assets/6192f3a4-d5dc-4f03-9bd2-884e4840515e" />
<img width="1600" height="476" alt="image" src="https://github.com/user-attachments/assets/9cf190d8-55cc-4220-baa9-be55468ba28f" />

##### 2. Simulación de Baxter con PyBullet:

El robot Baxter fue simulado utilizando el motor de física PyBullet, aprovechando los ejemplos proporcionados en los repositorios de referencia. La implementación incluye el modelo completo del robot y su entorno de trabajo.

###### Caracteristicas implementadas:

+ Modelado preciso del robot Baxter en PyBullet
+ Configuración de los grados de libertad y articulaciones
+ Entorno de simulación físico realista

###### Proceso en el terminal:

<img width="1600" height="207" alt="image" src="https://github.com/user-attachments/assets/532c3240-7c21-43ba-8a50-93262f5c7cb5" />
<img width="1600" height="557" alt="image" src="https://github.com/user-attachments/assets/8ab870bc-abef-46a8-8e3e-6bd1e4d5a483" />
<img width="1600" height="450" alt="image" src="https://github.com/user-attachments/assets/98bd10bd-3887-470d-9235-e8db22ab349b" />
<img width="1600" height="258" alt="image" src="https://github.com/user-attachments/assets/e6676712-af7c-4e86-a71b-9dde74034f60" />
<img width="1600" height="621" alt="image" src="https://github.com/user-attachments/assets/f626110b-b8f7-4feb-8c2b-eb59110d675d" />

##### 3. Implementación de robot ATLAS en Docker:

Se desarrolló la simulación del robot humanoide ATLAS utilizando PyBullet dentro de un contenedor Docker. Esta implementación demuestra la capacidad de ejecutar simulaciones complejas de humanoides en entornos containerizados.

###### Aspectos tecnicos:

+ Integración del modelo ATLAS en PyBullet
+ Configuración de parámetros dinámicos y de control
+ Optimización del rendimiento en el contenedor Docker

###### Proceso en el terminal:

<img width="1081" height="782" alt="image" src="https://github.com/user-attachments/assets/5c7762a0-9838-4d32-a412-b888402e02d7" />
<img width="1084" height="663" alt="image" src="https://github.com/user-attachments/assets/b099a08a-2f2d-49f9-923c-1f525e7482be" />
<img width="1600" height="393" alt="image" src="https://github.com/user-attachments/assets/611283c8-c3d4-4117-bb4b-82fd3943bdcc" />
<img width="1600" height="258" alt="image" src="https://github.com/user-attachments/assets/7a8f2af8-c074-462f-a7b8-e3da0cf00536" />

##### Resultados y verificación:

###### Despliegue de Drones:

<img width="1600" height="476" alt="image" src="https://github.com/user-attachments/assets/0bf95439-e1ac-4480-a1e0-23ae670cb24e" />
<img width="1600" height="726" alt="image" src="https://github.com/user-attachments/assets/fc50a2d5-5793-41f8-9fd2-89ac06695565" />
<img width="1600" height="726" alt="image" src="https://github.com/user-attachments/assets/c87cc3a3-9c98-4f4f-b2c7-158df05f524e" />
<img width="1600" height="664" alt="image" src="https://github.com/user-attachments/assets/76a4377d-3f2b-4b10-971f-71225b597a9c" />

###### Simulación de Baxter:

<img width="1600" height="621" alt="image" src="https://github.com/user-attachments/assets/30524c77-5bf4-4dfd-a83a-47ff0e679e73" />
<img width="1600" height="859" alt="image" src="https://github.com/user-attachments/assets/f3026291-72be-4f71-8d62-71ee3e82193e" />
<img width="1600" height="913" alt="image" src="https://github.com/user-attachments/assets/acf2f07f-1d92-4eb7-8fc8-206bee2a99da" />
<img width="1600" height="913" alt="image" src="https://github.com/user-attachments/assets/93e7fe74-f0b6-4dc3-a2f3-d5b062353083" />

###### Robot ATLAS:

<img width="1600" height="257" alt="image" src="https://github.com/user-attachments/assets/78ec723e-d8e0-4e9a-806e-45e3f44e167e" />
<img width="1600" height="880" alt="image" src="https://github.com/user-attachments/assets/292d525c-cc11-4346-b318-751ce4214b30" />
<img width="1600" height="880" alt="image" src="https://github.com/user-attachments/assets/9c3ac0e5-0dec-43be-97c9-b13ca886e592" />
<img width="1600" height="784" alt="image" src="https://github.com/user-attachments/assets/a5fa3c01-0f1e-4dae-8b7b-d3dd1a8825c0" />
