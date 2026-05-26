---
title: Construir cuestionario diagnóstico de divorcio
date: 2026-05-25
priority: high
---

## Objetivo

Agregar /divorcio a CalculaMX: cuestionario de 4-5 preguntas que genera una guía personalizada del proceso de divorcio en México.

## Preguntas del cuestionario

1. ¿En qué estado viven? (enfoque inicial: CDMX)
2. ¿Tienen hijos menores de edad?
3. ¿Tienen bienes en común (casa, coche, cuentas)?
4. ¿Ambos están de acuerdo con el divorcio?
5. ¿Llevan más o menos de 1 año casados?

## Output esperado

Ruta personalizada que incluye:
- Tipo de divorcio aplicable (voluntario / necesario / incausado)
- Pasos ordenados del proceso
- Documentos requeridos
- Tiempo estimado
- Costos aproximados (trámites, notaría, juzgado)
- Dónde tramitarlo (juzgado familiar, notaría, UACI CDMX)

## Stack

HTML/CSS/JS estático — sin backend, sin API. Misma arquitectura que calculadoras existentes.

## Integración

- Agregar a home page grid junto a las calculadoras
- Footer navigation
- Sitemap.xml
- AdSense en zonas laterales y entre secciones de resultado
