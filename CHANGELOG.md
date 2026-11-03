# Cambios

## 1.1.0

- Agrega `integrantes.txt` con los integrantes del taller (#1).
- Ejercicio 5: una versión con una consulta lenta en el listado de reservas (#6) incumplió el SLO en el despliegue
  (p95 612 ms) y la reversión automática volvió a la versión anterior. El cambio se revirtió en #7.

## 1.0.0

- Versión inicial del taller: servicio de reservas con arquitectura hexagonal, pipeline de CI/CD con quality gates
  de seguridad, publicación firmada en GHCR, despliegue en el runner autohospedado y reversión.
