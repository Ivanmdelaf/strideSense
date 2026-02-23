# StrideSense

Plataforma para el análisis de sesiones de carrera y la detección de riesgo de lesiones, compuesta por dos aplicaciones independientes.

Cada aplicación dispone de su propio README detallado con instrucciones de instalación, configuración y uso.

También se incluye un `docker-compose.yml` en la raíz para levantar ambas aplicaciones conjuntamente.

```bash
docker compose up
```

---

## Aplicaciones

### `stridesense-backend`
API REST y capa de procesamiento de datos.

```bash
cd stridesense-backend
# Consulta stridesense-backend/README.md para las instrucciones completas
```

### `stridesense-frontend`
Interfaz web del cliente.

```bash
cd stridesense-frontend
# Consulta stridesense-frontend/README.md para las instrucciones completas
```
