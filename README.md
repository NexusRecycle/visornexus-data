# VISORNEXUS OF RECYCLE - Infraestructura de Datos

Repositorio central de datos para **VISORNEXUS OF RECYCLE**, plugin desarrollado para QGIS orientado al analisis territorial de infraestructura de reciclaje y flujos de residuos valorizables.

Este repositorio organiza datos espaciales y tabulares procesados para apoyar la lectura de rutas, potencial de generacion, brechas de cobertura e identificacion preliminar de candidatos de emplazamiento.

## Proposito

El repositorio tiene como objetivo reunir y documentar informacion territorial utilizada por el plugin, permitiendo:

- Identificar generadores y receptores asociados a flujos de residuos valorizables.
- Analizar rutas estimadas de transporte mediante red vial.
- Evaluar brechas entre infraestructura existente y areas potenciales de demanda.
- Apoyar la planificacion comunal de puntos verdes, puntos limpios y nueva infraestructura de reciclaje.

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

## Datos disponibles en esta version

- `sinader/gi_2024_cloud.csv`: muestra procesada de generacion industrial SINADER 2024, con coordenadas, comuna, LER, tratamiento y toneladas declaradas.
- `metadata/config.json`: archivo de configuracion inicial para documentar rutas internas y versionamiento del repositorio.

## Integracion con QGIS

El repositorio esta pensado para ser utilizado como fuente de datos del plugin **VISORNEXUS OF RECYCLE** en QGIS.

En esta etapa, los datos pueden ser descargados y cargados localmente en el plugin. La sincronizacion automatica con una fuente remota se considera una funcionalidad futura del sistema.

## Fuentes de Informacion

- Ministerio del Medio Ambiente, RETC/SINADER: https://retc.mma.gob.cl/
- IDE Chile, Infraestructura de Datos Geoespaciales: https://www.ide.cl/
- Censo 2017 y capas territoriales complementarias utilizadas para analisis urbano.

## Nota metodologica

Los resultados generados por el plugin corresponden a analisis preliminares de soporte a la decision. Los candidatos de localizacion no representan ubicaciones definitivas y deben ser validados mediante revision tecnica, normativa, municipal y trabajo de terreno.

## Desarrollo

Proyecto desarrollado como parte de **VISORNEXUS OF RECYCLE**, orientado a fortalecer herramientas de analisis territorial para la planificacion de infraestructura de reciclaje.
