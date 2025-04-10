# k8s-soc-lab

Laboratorio de detección de amenazas en Kubernetes utilizando Suricata y Minikube.

## Descripción

Este laboratorio simula un entorno básico de detección de intrusos (IDS) usando Suricata en un clúster de Kubernetes. El objetivo es generar tráfico malicioso y capturarlo en tiempo real mediante Suricata desplegado en distintos formatos.

## Componentes

- Suricata desplegado como Deployment y como DaemonSet
- Un pod atacante que simula tráfico sospechoso (nmap, curl, ping, etc.)
- Visualización de logs generados por Suricata

## Requisitos

- Ubuntu
- Docker
- Minikube
- kubectl
- Visual Studio Code

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/dekapala/k8s-soc-lab.git
cd k8s-soc-lab
´´´

Estado del proyecto
Actualmente el entorno permite:

Detectar tráfico básico de red entre pods

Visualizar logs generados por Suricata directamente en la terminal

Experimentar con diferentes formas de despliegue de Suricata

En futuras versiones se planea integrar Elasticsearch y EveBox para análisis avanzado.

Copiar
Editar
