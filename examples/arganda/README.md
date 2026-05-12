# Ejemplos: Arganda del Rey

## Origen de los datos

**Dataset**: Consumo eléctrico de alumbrado público  
**Fuente**: [Ayuntamiento de Arganda del Rey — Datos Abiertos](https://datos.gob.es/es/cataloga/avance/ayuntamiento-arganda-del-rey)  
**Año**: 2016  
**Registros**: 11 zonas del municipio con consumo desglosado por período tarifario  
**Archivo original**: `arganda-consumo-alumbrado-2016.csv`

## Dataset

El dataset de Arganda **no contiene datos de farolas individuales ni de centros de mando técnicos**. Solo publica consumo eléctrico agregado por zona. Por ello, cada zona se modela como un `CentroDeMando` con su `SuministroElectrico` y `ConsumoEnergetico`, pero sin farolas asociadas.

El consumo se representa como un conjunto de observaciones SOSA.