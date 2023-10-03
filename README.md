# Review tecnica

Juan trabaja en una empresa de software y es un experto en Java. Se le solicitó crear una aplicación Spring Boot que se desplegará en un clúster de Kubernetes.

Aunque Juan es experto en Java, no tiene conocimiento de Docker e incluso desconoce que es Kubernetes. Por esta razón, El generó un servicio demo y lo envió al equipo de DevOps para que se encargara de la creación de la imagen Docker, así como de la creación de los manifiestos necesarios para desplegar el código en un clúster de Kubernetes.

Juan salio de vacaciones y como "buen" dev no dejo ninguna documentacion de la version o la forma de compilar, segun el jefe de juan nos indico que el codigo funciona devuelve un OK via Http y que el puerto se encuentra en un archivo properties

## Retos

- Que Juan pueda generar una imagen de docker, desde un archivo Dockerfile
- Generar el o los manifiestos necesarios para que la imagen pueda ser desplegada en un cluster kubernetes, la misma va a ser un deployment.
- Documentar como realizar el proceso de la creacion de imagen y como aplicar el manifiesto en kubernetes para que juan despliegue la imagen docker en el cluster
- Subir los documentos creados a un repositorio 
  
### Extra Ball

- El archivo Dockerfile debe cumplir con las mejores practicas
- Generar un solo manifiesto que permita la creacion de todos los recursos
- Generar un script para que se desplegue automaticamente