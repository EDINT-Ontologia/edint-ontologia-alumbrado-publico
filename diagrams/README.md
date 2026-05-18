# Recursos de conceptualización de la ontología

Esta carpeta contiene todos los **recursos relacionados con la fase de conceptualización y diseño** de la ontología.

# Propósito

El objetivo de este directorio es almacenar **materiales visuales y estructurales** que apoyen la comprensión y definición de los conceptos, relaciones y estructura de la ontología **de su implementación formal** (por ejemplo, en OWL o RDF).

# Contenido

## Diagramas

### Diagrama del modelo conceptual (`edint-ontologia-alumbrado-publico.drawio`)

- **Formato**: draw.io (editable) y PNG (visualización)
- **Descripción**: Diagrama que muestra las clases principales de la ontología de Alumbrado Público y sus relaciones.
- **Clases propias mostradas**: Farola, Poste, Brazo, Luminaria, Lámpara, Caja, CentroDeMando, SuministroElectrico, ConsumoEnergetico, ReductorFlujo, ModeloLuminaria, Fabricante
- **Clases reutilizadas**: UrbanElement, UtilitySupplyPoint, UtilityContract, UtilityConsumption, DireccionPostal
- **Clasificaciones SKOS**: tipo de soporte, tipo de luminaria, tipo de lámpara, tipo de alumbrado, tipo de alimentación, tipo de iluminación, tipo de cable, estado de conservación, zona de alumbrado, clase luminotécnica, período tarifario
- **Relaciones principales**: poste, luminaria, caja, tieneLampara, centroDeMando, tieneSuministro, tieneConsumo, fabricadoPor, modeloLuminaria, direccion

# Formatos aceptados

Almacena los recursos en uno de los siguientes formatos:
- `.svg` — Gráficos vectoriales escalables
- `.png` — Capturas de imagen de diagramas
- `.drawio` — Diagramas editables creados con [diagrams.net (draw.io)](https://app.diagrams.net/)

Otros formatos (por ejemplo, `.pdf`, `.jpg`, `.pptx`) pueden incluirse si son relevantes para discusiones conceptuales.

# Notas

- Mantén versiones de los diagramas cuando ocurran cambios conceptuales importantes.
- Esta carpeta **no** contiene código de ontología ni archivos OWL/RDF — esos pertenecen a la carpeta de implementación.
- Asegura que todos los diagramas sean consistentes con las especificaciones más recientes de la ontología.
