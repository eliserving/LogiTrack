\# 🚚 LogiTrack - Sistema de Paquetería de Última Milla



Sistema de rastreo en tiempo real de paquetes con arquitectura de microservicios.



\## 📋 Descripción



LogiTrack es una plataforma que permite:

\- Rastreo GPS en tiempo real de conductores

\- Asignación inteligente de paquetes

\- Notificaciones push instantáneas

\- Gestión completa del ciclo de vida del pedido



\## 🏗️ Arquitectura



El sistema está compuesto por 4 microservicios:



1\. \*\*Tracking Service\*\* (Go): Ingesta masiva de coordenadas GPS

2\. \*\*Order Service\*\* (Node.js): Gestión del estado del paquete

3\. \*\*Dispatch Service\*\* (Python): Asignación inteligente de rutas

4\. \*\*Notification Service\*\* (Node.js): Push notifications



\## 🚀 Stack Tecnológico



\- \*\*Backend\*\*: Node.js, Python, Go

\- \*\*Databases\*\*: PostgreSQL, TimescaleDB, MongoDB

\- \*\*Message Queue\*\*: RabbitMQ

\- \*\*Container Orchestration\*\*: Kubernetes

\- \*\*CI/CD\*\*: GitHub Actions

\- \*\*Monitoring\*\*: Prometheus + Grafana



\## 📁 Estructura del Proyecto

```

logitrack/

├── services/           # Microservicios

├── infrastructure/     # IaC (Terraform, K8s)

├── shared/            # Código compartido

└── docs/              # Documentación

```



\## 👥 Contribuir



Lee \[CONTRIBUTING.md](CONTRIBUTING.md) para detalles del proceso de desarrollo.



\## 📄 Licencia

