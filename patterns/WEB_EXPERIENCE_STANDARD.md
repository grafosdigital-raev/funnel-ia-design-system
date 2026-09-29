# WEB EXPERIENCE STANDARD

**Funnel-IA Design System**  
**Versión:** 0.1  
**Fecha:** 2026-09-29  
**Estado:** Principio aprobado; checklist operativo en construcción.

## Regla maestra

### Funnel-IA Experience Rule — Ningún estado es neutro

> Todo punto de contacto visible —incluidos estados técnicos, legales, vacíos, errores y confirmaciones— debe expresar claridad, humanidad y coherencia de marca.  
> La sofisticación no se añade con decoración; se percibe en la atención al detalle.

Este estándar convierte el Brand OS y el Design System en comportamiento visible. No basta con que hero, tipografía y paleta “se vean Funnel-IA”; también deben sentirse Funnel-IA los estados que normalmente quedan delegados al navegador, framework, plugin o componente genérico.

## Principio de traducción

**Función técnica → significado humano → expresión de marca.**

Ejemplo:
- Genérico: “Registro guardado correctamente.”
- Experiencia: **“Tu proyecto ya existe.”**

La redacción final siempre debe depender del contexto real. No usar lenguaje ceremonial cuando el evento no lo justifique.

## Microexperience Agent

### Misión
Detectar cualquier punto visible que todavía parezca software genérico y convertirlo, sin sacrificar claridad, accesibilidad, cumplimiento legal ni rendimiento, en una experiencia coherente con Funnel-IA.

### Pregunta obligatoria
> **¿Hay algún momento de esta experiencia que todavía parezca software genérico en lugar de nuestra marca?**

## Superficie mínima de revisión

Cookies y consentimiento; modales; alerts; hover; focus; estados vacíos; errores; loading; success; formularios; validación; botones deshabilitados; tooltips; 404; footer; navegación móvil; favicon; metadata/share preview; scrollbars; selección de texto; feedback posterior a una acción; teclado; y `prefers-reduced-motion`.

## Criterios de aceptación

Una microexperiencia se aprueba cuando:
- comunica con claridad qué ocurrió y qué puede hacer la persona;
- respeta voz, nomenclatura y tono de Funnel-IA;
- no oculta ni manipula decisiones legales o de consentimiento;
- funciona con teclado y estados de focus visibles;
- conserva contraste y legibilidad;
- tiene comportamiento móvil coherente;
- contempla loading, vacío, error y success cuando apliquen;
- respeta `prefers-reduced-motion`;
- evita decoración innecesaria y complejidad gratuita;
- no introduce patrones genéricos si existe un patrón aprobado del sistema.

## Relación con el Harness Web

```text
LANDING REQUEST
→ Discovery
→ Brand
→ Narrative / Conversion
→ UX Architecture
→ Visual System
→ Motion
→ Microexperience
→ Accessibility / Responsive
→ SEO / Performance
→ QA
→ Release
```

El Microexperience Agent no reemplaza Accessibility/Responsive ni QA. Su responsabilidad es la coherencia de marca en los estados pequeños; los agentes posteriores validan cumplimiento integral y liberación.

## Regla de escalamiento

Si mejorar la experiencia entra en conflicto con accesibilidad, consentimiento, privacidad, claridad o rendimiento, el agente no “embellece” el conflicto: conserva el requisito funcional y lo escala para decisión humana cuando no exista una solución aprobada.

## Pendiente de la sesión de construcción

Convertir este documento en una checklist verificable y en contratos de entrada/salida para el Microexperience Agent, incluyendo severidad, evidencias, criterios pass/fail y ejemplos aprobados.
