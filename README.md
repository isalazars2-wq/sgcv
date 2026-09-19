# Sistema de Gestión Comercial Vértice (SGCV) - Entregable DevOps 1

## Descripción
Sistema web monolítico (PHP + MySQL) para la gestión de clientes, cotizaciones y catálogo de Vértice Arquitectos.

## Estructura del Repositorio
- `/src`: Código fuente de la aplicación (Frontend y API PHP).
- `/docs`: Documentación técnica y entregables PDF.
- `/docker`: Archivos de configuración para contenedores.
- `/tests`: Scripts de pruebas unitarias y de integración.

## Requisitos previos
- Docker y Docker Compose instalados.

## Instrucciones de ejecución (Entorno Local)
1. Clonar el repositorio.
2. Copiar `.env.example` a `.env` y configurar las variables de entorno.
3. Ejecutar el entorno con Docker: `docker compose up -d`
4. Acceder a la aplicación en `http://localhost:8080`