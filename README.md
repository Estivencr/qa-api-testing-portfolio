![API Tests](https://github.com/Estivencr/qa-api-testing-portfolio/actions/workflows/api-tests.yml/badge.svg)

# QA API Testing 

Colección de pruebas de API desarrolladas con Postman
como parte de mi formación como QA Engineer.

## API Probada
**Airport Gap API** — https://airportgap.com
Sistema de aeropuertos y gestión de favoritos.

## Cobertura de pruebas

| Módulo | Tests | Positivos | Negativos |
|--------|-------|-----------|-----------|
| Aeropuertos | 3 | 2 | 1 |
| Autenticación | 2 | 1 | 1 |
| Favoritos | 5 | 3 | 2 |
| Distancia | 2 | 1 | 1 |
| **Total** | **24** | **16** | **8** |

## Status codes verificados
- 200 OK
- 201 Created
- 204 No Content
- 401 Unauthorized
- 404 Not Found
- 422 Unprocessable Entity

## Cómo ejecutar las pruebas

1. Instalar [Postman](https://postman.com)
2. Importar `airport-gap-tests.json`
3. Importar `airport-gap-environment.json`
4. Crear cuenta en https://airportgap.com
5. Ejecutar POST /tokens y guardar el token en el environment
6. Ejecutar la colección completa con Collection Runner

## Técnicas aplicadas
- Variables de entorno para baseUrl y token
- Encadenamiento de requests con pm.environment.set()
- Tests automáticos en JavaScript
- Casos positivos y negativos
- Exploración de comportamiento con datos inválidos

## Autor
**ESTIVENCR** — QA Engineer en formación
https://www.linkedin.com/in/estivencr/
