<<<<<<< HEAD
# Desafio11_kubernetes
=======
# Desafio12_Helm
El objetivo de este desafío es poner en práctica lo visto sobre helm y desarrollar nuestro propio helm chart, tomando como entrada lo visto en los desafíos 10 y 11.

Escenario:
Nuestro equipo identificó que Kubernetes agrega mucho valor a la hora de mantener los deployments de nuestra aplicación y ha estado analizando la manera en que gestionamos el código de estos deployments. Luego de varias reuniones, identificaron que los manifiestos duplican mucho código y que esto se puede resolver utilizando algún sistema de templates. Durante este sprint, se nos asignó la tarea de desarrollar un Helm chart para gestionar el deployment de la aplicación. Este chart debe desplegar la aplicación y el servicio de base de datos MongoDB para almacenar los datos de nuestra aplicación.


# Desafio14_Helm

El objetivo de este desafío es poner en práctica el despliegue del Helm Chart desarrollado en
el desafío #12 utilizando ArgoCD. Se debe automatizar la gestión del despliegue de la
aplicación y su base de datos MongoDB, siguiendo los principios de GitOps.

## Escenario:

Luego de haber desarrollado el Helm Chart en el desafío anterior para la aplicación y
MongoDB, el equipo ha decidido implementar una solución de despliegue continuo
utilizando ArgoCD. Esto permitirá automatizar y gestionar los despliegues de manera
eficiente, basándose en un repositorio Git.
El objetivo es desplegar el Helm Chart en el entorno de Kubernetes utilizando ArgoCD,
permitiendo que cualquier cambio realizado en el repositorio de código sea aplicado
automáticamente en el clúster de Kubernetes.
