k8s-soc-lab
Laboratorio para la detección de amenazas en entornos Kubernetes utilizando Suricata y Minikube.

Descripción
Este proyecto permite desplegar un entorno de análisis de tráfico de red con Suricata como IDS (sistema de detección de intrusos) dentro de un clúster Kubernetes local. Incluye:

Despliegue de Suricata como Deployment y como DaemonSet.

Pod atacante para generar tráfico malicioso (nmap, ping, etc.).

Recolección y análisis de logs generados por Suricata.

Requisitos
Ubuntu con Minikube y Docker instalados.

kubectl configurado y apuntando al clúster local.

Visual Studio Code u otro editor para modificar archivos del proyecto.

Instalación
Clonar el repositorio:

bash
Copiar
Editar
git clone https://github.com/dekapala/k8s-soc-lab.git
cd k8s-soc-lab
Desplegar el entorno siguiendo los manifiestos disponibles en la carpeta manifests/.
