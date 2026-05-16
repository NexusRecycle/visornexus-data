# VISORNEXUS OF RECYCLE - Infraestructura de Datos 🌍♻️

Bienvenido al repositorio central de datos de **VISORNEXUS OF RECYCLE**. Este espacio funciona como el "cerebro en la nube" para el plugin de QGIS, permitiendo un análisis territorial dinámico de las redes de reciclaje en Chile.

## 🚀 Propósito
Este repositorio aloja información procesada y optimizada proveniente de sistemas oficiales como **SINADER**, con el objetivo de:
- Identificar nodos estratégicos de generación y recepción de residuos.
- Detectar desarticulaciones territoriales en la gestión de recursos.
- Fortalecer los sistemas barriales de circularidad urbana.

## 📂 Estructura de Datos
El repositorio está organizado para ser consumido automáticamente por el plugin VisorNexus:

*   **/cartografia**: Límites administrativos oficiales de Chile (Regiones y Comunas) en formato GeoJSON.
*   **/sinader**: Registros de Generación Industrial (GI) y Destino Final (DF) optimizados para análisis espacial.
*   **/metadata**: Archivos de configuración y versiones de los datasets.

## 🔌 Integración con QGIS
Para conectar tu plugin **VisorNexus** con este repositorio:
1. Copia la URL base de este repositorio (en modo `raw`).
2. Abre el plugin en QGIS y ve a **Configuración Nexus Cloud**.
3. Pega la URL y sincroniza los datos.

## 🛡️ Fuentes de Información
Los datos contenidos en este visor provienen de:
- [Ministerio del Medio Ambiente (RETC/SINADER)](https://retc.mma.gob.cl/ )
- [IDE Chile (Infraestructura de Datos Geoespaciales)](https://www.ide.cl/ )

---
**Desarrollado por Nexus Team & Manus AI**  
*Impulsando la inteligencia territorial para un futuro circular.*
