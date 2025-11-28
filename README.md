# Undersounds: Microservicio de Usuarios

## Requisitos
* Docker
* Docker Compose

## Ejecución del servicio
1. Clona el proyecto.
2. Ejecuta el comando `docker compose up` desde la raíz del proyecto.
3. Espera a que el servicio esté listo.
4. ¡Listo! El microservicio estará disponible en:
   * API: `http://localhost:8082`
   * BD: `localhost:5434`

## Detención del servicio
Ejecuta `docker compose down` si quieres mantener los cambios en la BD, y `docker compose down -v` si quieres borrar el volumen de datos.
