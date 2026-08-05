# Diccionario de Datos

## sinader/gi_2024_cloud.csv

| Campo | Descripcion |
|---|---|
| region | Region del establecimiento generador. |
| comuna | Comuna del establecimiento generador. |
| latitud | Coordenada de latitud del generador. |
| longitud | Coordenada de longitud del generador. |
| trazabilidad__region | Region asociada al destino o trazabilidad declarada. |
| trazabilidad__comuna | Comuna asociada al destino o trazabilidad declarada. |
| LER | Codigo y descripcion del residuo declarado. |
| tratamiento_n1_name | Tipo general de tratamiento declarado. |
| cantidad_toneladas | Cantidad declarada en toneladas. |

## Observaciones

- Las coordenadas deben revisarse antes de cualquier analisis definitivo.
- Los datos pueden contener registros fuera de la Region Metropolitana si la fuente original corresponde a una descarga nacional.
- Los campos de trazabilidad permiten vincular generadores con receptores, pero requieren validacion y limpieza previa.
