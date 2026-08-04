# VISORNEXUS OF RECYCLE - Infraestructura de Datos

Repositorio central de datos para **VISORNEXUS OF RECYCLE**, plugin desarrollado para QGIS orientado al análisis territorial de infraestructura de reciclaje y flujos de residuos valorizables.

Este repositorio organiza datos espaciales y tabulares procesados para apoyar la lectura de rutas, potencial de generación, brechas de cobertura e identificación preliminar de candidatos de emplazamiento.

## Propósito

El repositorio tiene como objetivo reunir y documentar información territorial utilizada por el plugin, permitiendo:

- Identificar generadores y receptores asociados a flujos de residuos valorizables.
- Analizar rutas estimadas de transporte mediante red vial.
- Evaluar brechas entre infraestructura existente y áreas potenciales de demanda.
- Apoyar la planificación comunal de puntos verdes, puntos limpios y nueva infraestructura de reciclaje.

## Estructura de Datos

```text
/cartografia
  Limites administrativos y capas territoriales base en formatos geoespaciales.

/sinader
  Datos procesados desde RETC/SINADER para generadores, receptores y flujos reciclables.

/infraestructura
  Puntos verdes, puntos limpios, paraderos, areas verdes y otras capas urbanas de apoyo.

/metadata
  Diccionario de datos, fuentes, fechas de actualizacion y criterios de procesamiento.

/outputs
  Tablas, capas procesadas y resultados exportados por comuna.
```

## Integración con QGIS

El repositorio está pensado para ser utilizado como fuente de datos del plugin **VISORNEXUS OF RECYCLE** en QGIS.

En esta etapa, los datos pueden ser descargados y cargados localmente en el plugin. La sincronización automática con una fuente remota se considera una funcionalidad futura del sistema.

## Fuentes de Información

- Ministerio del Medio Ambiente, RETC/SINADER: https://retc.mma.gob.cl/
- IDE Chile, Infraestructura de Datos Geoespaciales: https://www.ide.cl/
- Censo 2017 y capas territoriales complementarias utilizadas para análisis urbano.

## Nota metodológica

Los resultados generados por el plugin corresponden a análisis preliminares de soporte a la decisión. Los candidatos de localización no representan ubicaciones definitivas y deben ser validados mediante revisión técnica, normativa, municipal y trabajo de terreno.

## Desarrollo

Proyecto desarrollado como parte de **VISORNEXUS OF RECYCLE**, orientado a fortalecer herramientas de análisis territorial para la planificación de infraestructura de reciclaje.
