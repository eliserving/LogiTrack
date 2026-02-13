\# 🤝 Guía de Contribución



\## Flujo de Trabajo



\### 1. Crear una rama nueva

```bash

git checkout main

git pull origin main

git checkout -b feature/nombre-descriptivo

```



\### 2. Hacer cambios

```bash

git add .

git commit -m "feat(scope): descripción del cambio"

```



\### 3. Subir cambios

```bash

git push origin feature/nombre-descriptivo

```



\## Convenciones de Commits



\- `feat(scope): nueva funcionalidad`

\- `fix(scope): corrección de bug`

\- `docs(scope): cambios en documentación`

\- `test(scope): agregar tests`



\## Scopes



\- `tracking`: Tracking Service

\- `order`: Order Service

\- `dispatch`: Dispatch Service

\- `notif`: Notification Service

