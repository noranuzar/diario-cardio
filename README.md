# Diario Cardioprotector

Aplicación web personal para el seguimiento de una dieta cardioprotectora orientada a reducir el colesterol LDL, basada en el método Portfolio (Dr. David Jenkins) y la dieta mediterránea avanzada.

## Qué hace

- **Registro diario** de comidas, vasos de agua y síntomas (mareo, tensión).
- **Panel de fase del día** en vivo: en qué franja estás y cuánto queda para la hora tope de cena.
- **Barra de situación del día**: vistazo rápido de comidas anotadas, agua y cobertura de fibra/grasas buenas.
- **Planificador**: planifica cualquier día y el registro lo trae prellenado para confirmar o editar.
- **Banco de recetas** por ingrediente y por momento del día, con técnica de preparación y su beneficio.
- **Método Portfolio** y sección de horarios (cronobiología) con base científica.
- **Mi progreso**: adherencia semanal y ventana recomendada para el análisis de sangre (6–8 semanas).
- **Informe** para llevar a la Unidad de Lípidos.

## Cómo funciona técnicamente

- Una sola página HTML, sin dependencias ni servidor.
- Los datos se guardan en el navegador (`localStorage`): son privados y locales a ese dispositivo.
- Incluye exportación/importación a JSON como copia de seguridad.

## Importante

- Los datos viven solo en el navegador donde se usan. **Exportar el JSON periódicamente** es la única copia de seguridad.
- Esta herramienta organiza información y no sustituye la valoración médica. Las decisiones clínicas corresponden a la Unidad de Lípidos.

## Despliegue

Proyecto estático. Se despliega en Vercel importando el repositorio (Framework Preset: *Other*, sin build command).
