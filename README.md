# k8s-soc-lab

Laboratorio de detección de amenazas en Kubernetes con Suricata y Minikube.

## 🔍 Descripción

Este laboratorio simula un entorno básico de detección IDS usando Suricata en Kubernetes. Incluye:

- Suricata desplegado como **Deployment** y como **DaemonSet**
- Un pod atacante para simular tráfico malicioso (`nmap`, `ping`, etc.)
- Captura y visualización de logs desde los pods de Suricata

## ⚙️ Requisitos

- Ubuntu + Minikube + Docker instalados
- `kubectl` configurado
- VSCode para edición del proyecto

## 🚀 Instalación

1. Clonar el repositorio:

```bash
git clone https://github.com/dekapala/k8s-soc-lab.git
cd k8s-soc-lab
´´´