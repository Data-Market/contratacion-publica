# Datasets de Contratación Pública

<a href="https://datamarket.es">
  <img src="https://datamarket.es/media/banners/contratacion-publica-banner.png">
</a>

## Descripción

Todas las __ofertas de contratación públicas__, tanto licitaciones como contratos menores, emitidas por el __gobierno central de España y sus autonomías.__

Las características de este dataset son las siguientes:

* __Frecuencia de actualización__: diariamente
* __Volumen estimado__: 1000 registros cada día
* __Histórico__: desde julio de 2021 en adelante

El dataset completo se puede adquirir en [DataMarket](https://datamarket.es/#contratacion-publica-dataset), plataforma de referencia de datos externos en España. 

Este repositorio contiene los siguientes recursos:

* La documentación completa del dataset.
* Una muestra representativa del mismo disponible para su evaluación y uso gratuito.

## Muestra

La muestra se encuentra disponible para descarga en el siguiente [link](https://github.com/Data-Market/contratacion-publica/blob/main/contratacion-publica-sample.csv).

## Documentación

A continuación se muestran las columnas de las que consta el dataset junto con su descripción.

| nombre | tipo | descripción | ejemplo |
|--------|------|-------------|---------|
| adjudicatario | str | Nombre de la empresa que ha ganado la adjudicación de la oferta de contratación pública. | DKV SERVICIOS SAU |
| codigo_cpv | str | Código identificativo de la temática de la oferta de contratación pública. | {85147000-Servicios de sanidad de las empresas.} |
| descripcion | str | Breve descripción de la oferta de contratación pública. | Contratación del servicio médico de urgencias en el puerto de la Bahía de Algeciras |
| estado | str | Estado en el que se encuentra la oferta de contratación pública. | Adjudicada |
| expediente | str | Código identificativo correspondiente a una oferta de contratación pública. | 2021-039 |
| insert_date | datetime | Fecha de extracción de la información. | 21/08/2021 1:17:20 |
| last_update | datetime | Última fecha de actualización de la oferta de contratación pública. | 20/08/2021 11:22:25 |
| limite_presentacion | datetime | Fecha límite para poder inscribirse a la oferta de contratación pública. | 16/06/2021 14:00:00 |
| lugar_ejecucion | str | Localización donde se realizará las actividades pertinentes a la oferta de contratación pública. | España - Cádiz - ALGECIRAS |
| organo_contratacion | str | Órgano público competente que emite la oferta de contratación pública. | Presidencia de la Autoridad Portuaria de la Bahía de Algeciras |
| pliego_link | str | Url de la documentación de los pliegos de la oferta de contratación pública. | https://contrataciondelestado.es/wps/wcm/connec... |
| pliego_link_admin | str | Url a la documentación en pdf de las cláusulas administrativas de la oferta de contratación pública. | https://contrataciondelestado.es//wps/wcm/conne... |
| pliego_link_tech | str | Url a la documentación en pdf de las prescripciones técnicas de la oferta de contratación pública. | https://contrataciondelestado.es//wps/wcm/conne... |
| presupuesto_base | int | Presupuesto de la oferta de contratación pública. | 160000 |
| procedimiento_contratacion | str | Tipo de procedimiento por el que se opta a la oferta de contratación pública. | Abierto |
| publication_date | datetime | Fecha de publicación de la oferta de contratación pública. | 31/05/2021 10:14:53 |
| tipo_contrato | str | Modalidad del contrato de la oferta de contratación pública. | Servicios |
| url | str | Url de la contratación pública. | https://contrataciondelestado.es/wps/poc?uri=de... |
| valor_estimado | int | Presupuesto máximo disponible para la realización del pliego y sus posibles extensiones en el caso de que existan. | 400000 |
