🚚 LogiTrack - Sistema de Paquetería de Última Milla



Sistema de rastreo en tiempo real de paquetes con arquitectura de microservicios.



📋 Descripción



LogiTrack es una plataforma que permite:

\- Rastreo GPS en tiempo real de conductores

\- Asignación inteligente de paquetes

\- Notificaciones push instantáneas

\- Gestión completa del ciclo de vida del pedido



🏗️ Arquitectura



El sistema está compuesto por 4 microservicios:



Tracking Service(Go): Ingesta masiva de coordenadas GPS

Order Service(Node.js): Gestión del estado del paquete

Dispatch Service(Python): Asignación inteligente de rutas

Notification Service(Node.js): Push notifications





📁 Estructura del Proyecto

```

logitrack/

├── services/           # Microservicios

├── infrastructure/     # IaC (Terraform, K8s)

├── shared/            # Código compartido

└── docs/              # Documentación

```



👥 Contribuir



Lee \[CONTRIBUTING.md](CONTRIBUTING.md) para detalles del proceso de desarrollo.



📄 Licencia

