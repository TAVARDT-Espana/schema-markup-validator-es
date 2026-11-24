# Validador de Schema Markup y Datos Estructurados

[![Validador Schema](https://img.shields.io/badge/TAVARDT-Schema.org%20Validator-5b3cf5.svg)](https://tools.tavardt.com/es/validador-schema-markup/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Inspeccion tecnica de marcado Schema.org JSON-LD y Microdatos, deteccion de tipos semanticos, validacion de atributos y fragmentos enriquecidos.

Desarrollado y mantenido por el equipo de ingenieria semantica y SEO tecnico de **TAVARDT**.

***

## Capacidades de Validacion Semantica

* **Extraccion de Marcado Estructurado**: Analisis automatizado de bloques JSON-LD (`application/ld+json`) y atributos Microdatos.
* **Identificacion de Entidades Schema.org**: Deteccion de esquemas fundamentales como Organization, LocalBusiness, WebSite, Article, Product, FAQPage y BreadcrumbList.
* **Control de Sintaxis y Propiedades Requeridas**: Deteccion de errores sintacticos, campos obligatorios omitidos e inconsistencias de datos.
* **Indice de Calidad Semantica**: Puntuacion objetiva de 0 a 100 con guia técnica de optimizacion para fragmentos enriquecidos.

***

## Instalacion y Uso

Requiere Python 3.8 o superior sin dependencias adicionales.

```bash
git clone https://github.com/TAVARDT-Espana/schema-markup-validator-es.git
cd schema-markup-validator-es
python schema_validator.py ejemplo.es
```

Para emitir la evaluacion en formato JSON:

```bash
python schema_validator.py ejemplo.es -json
```

***

## Plataforma Web de Diagnostico

Para auditorias continuas y validacion directa de URLs en la nube:

* **Validador de Schema Markup Oficial**
* **[Portal Corporativo TAVARDT](https://ag.tavardt.com/es/)**

***

## Consultoria en Arquitectura de Datos y Marcado

Para planes de implementacion de datos semanticos bajo Estandares W3C y Directrices Tecnicas Europeas, consulte con los especialistas de **TAVARDT**.

***

## Enlaces Útiles

* **Portal Corporativo:** https://ag.tavardt.com/es/
* **Suite de Diagnósticos:** https://tools.tavardt.com/es/
* **Contacto Técnico:** https://ag.tavardt.com/es/contacto/

***

© 2026 TAVARDT. Todos los derechos reservados.
