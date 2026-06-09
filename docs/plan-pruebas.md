# Plan de Pruebas del Sistema

## Casos de Prueba

| ID | Descripción | Entrada | Resultado Esperado |
|----|------------|--------|-------------------|
| CP01 | Crear evento | Datos válidos | Evento creado |
| CP02 | Login usuario | Credenciales correctas | Acceso permitido |
| CP03 | Registrar artista | Datos del artista válidos | Artista asociado a concierto |
| CP04 | Venta de entradas | Compra de 2 entradas | Entradas registradas correctamente | 
| CP05 | Control de aforo | Evento con capacidad máxima alcanzada | Sistema impide nuevas reservas |

## Estrategia de Pruebas

Pruebas unitarias:
- Registro de eventos.
- Registro de artistas.
- Registro de asistentes.
- Validación de inicio de sesión.

Pruebas de integración:
- Integración entre conciertos y artistas.
- Integración entre conciertos y venta de entradas.
- Integración entre asistentes y control de aforo.

Pruebas de estrés:
- Simulación de 1000 asistentes realizando registros simultáneos.
- Simulación de 500 compras de entradas concurrentes.

Resultado: El sistema respondió correctamente sin fallos críticos.

## Evidencias

Simulación de resultados:
- Todos los casos de prueba ejecutados exitosamente.
- Tiempo de respuesta promedio menor a 2 segundos.
- Registro correcto de artistas y asistentes.
- Generación de reportes de eventos sin errores.