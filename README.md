# Planificador de Capacidad Industrial

Aplicación web para planificación de capacidad industrial con:

- **Máquinas**: Configuración de máquinas y cantidad disponible
- **Referencias**: Rutas de producción con fases, máquinas alternativas y tiempos
- **Pedidos**: Carga de trabajo con fechas de entrega
- **Cálculo automático**: Plan Maestro Industrial con algoritmo EDD + Lean
- **Integración Excel**: Importar/exportar plantillas para máquinas, referencias y pedidos
- **Análisis de cuellos de botella**: Identificación gráfica de sobrecargas
- **Supermercados FIFO**: Cálculo de buffers y colas entre fases
- **Plan de acción**: Sugerencias de turnos extra, máquinas adicionales, subcontratación
- **Informes**: Exportación a PDF y Excel

## Despliegue

Esta app es un archivo HTML estático que se despliega directamente en Vercel.

## Uso

1. Configura turnos (horas, días, turnos por semana)
2. Añade máquinas (manual o importando Excel)
3. Define referencias con sus fases y tiempos (manual o importando Excel)
4. Introduce pedidos con fecha de entrega (manual o importando Excel)
5. Pulsa "CALCULAR CAPACIDAD"
6. Revisa resultados, cuellos de botella y plan de acción
