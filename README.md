# SEO en 10 minutos – Arquitectura, On-Page y SEO Técnico

![SEO](https://img.shields.io/badge/SEO-Strategy-blue)
![Architecture](https://img.shields.io/badge/Web-Architecture-green)
![OnPage](https://img.shields.io/badge/SEO-OnPage-orange)
![Technical](https://img.shields.io/badge/SEO-Technical-purple)
![Status](https://img.shields.io/badge/Estado-Active-brightgreen)

> Guía rápida y práctica para comprender los **fundamentos del SEO moderno**: arquitectura web, optimización On-Page, rendimiento técnico, indexación y estrategias de contenido.

Este documento resume los principios básicos del **posicionamiento web en buscadores** y proporciona ejemplos aplicados para proyectos reales.

---

# Índice

1. Arquitectura SEO  
2. Estrategia de palabras clave  
3. Etiquetas HTML esenciales  
4. Optimización de imágenes y URLs  
5. WPO y Core Web Vitals  
6. JavaScript, SEO y PWA  
7. Rastreo e indexación  
8. Redacción SEO  
9. Herramientas SEO  
10. SEO en CMS  
11. Tendencias SEO 2025  
12. SEO técnico y auditoría  
13. Analítica y medición  
14. Experimentos SEO

---

# Arquitectura SEO

Una arquitectura correcta facilita el **rastreo de Google** y mejora la experiencia del usuario.

## Topic Clusters

Se recomienda organizar el contenido en **páginas pilares y artículos asociados**.

Ejemplo:

```
/blog/guias-preparacion/
/blog/tipos-cafe/
/blog/curiosidades/
```

Cada categoría actúa como **pilar de contenido**.

---

## Jerarquía de navegación

Regla habitual:

**Todo el contenido importante debería estar a menos de 3 clics desde la home.**

Estructura recomendada:

```
tuweb.com/categoria/subcategoria/articulo
```

Ejemplo:

```
/blog/tipos-de-cafe/arabica-vs-robusta
```

---

## Enlazado interno

Los enlaces internos transmiten autoridad entre páginas.

Flujo recomendado:

```
Home
 ↓
Páginas pilar
 ↓
Artículos específicos
 ↓
Conversión (producto o servicio)
```

Ejemplo de anchor text:

❌ haz clic aquí  
✅ comparativa de cafés de origen

---

# Estrategia de palabras clave

Las palabras clave se clasifican según su longitud.

| Tipo | Ejemplo | Objetivo |
|-----|-----|-----|
| Head | café | tráfico masivo |
| Mid-tail | tipos de café | página pilar |
| Long-tail | cómo hacer capuchino en casa | contenido especializado |

Los artículos long-tail generan tráfico cualificado y pueden dirigir al usuario hacia páginas transaccionales.

---

# Etiquetas HTML esenciales

Las etiquetas HTML indican a los buscadores la estructura y relevancia del contenido.

| Etiqueta | Función |
|------|------|
| `<title>` | título SEO principal |
| `<meta description>` | resumen mostrado en Google |
| `<h1>` | título principal de la página |
| `<img alt="">` | descripción de imágenes |

Ejemplo:

```
<title>Café en grano para espresso | Marca X</title>

<meta name="description" content="Descubre el mejor café para espresso. Origen, tueste y molienda.">

<h1>Café en grano para espresso</h1>
```

---

# Optimización de imágenes y URLs

## Imágenes

Buenas prácticas:

- usar formato **WebP**
- comprimir imágenes
- nombres descriptivos

Ejemplo correcto:

```
cafe-grano-etiopia.webp
```

Ejemplo incorrecto:

```
IMG_001.jpg
```

---

## URLs amigables

Las URLs deben ser claras y descriptivas.

Correcto:

```
tienda.com/zapatillas-running-nike
```

Incorrecto:

```
tienda.com/product.php?id=123
```

---

# WPO (Web Performance Optimization)

La velocidad de carga influye directamente en el ranking.

Google utiliza métricas llamadas **Core Web Vitals**.

| Métrica | Qué mide |
|------|------|
| LCP | tiempo de carga del contenido principal |
| FID | tiempo de respuesta al usuario |
| CLS | estabilidad visual |

Acciones rápidas de optimización:

- minificar CSS y JavaScript
- usar CDN
- activar caché
- optimizar imágenes

---

# JavaScript y SEO

Las aplicaciones modernas usan JavaScript para generar contenido dinámico.

Problema:

Google necesita **renderizar el JS**, lo que retrasa la indexación.

Soluciones:

| Técnica | Descripción |
|------|------|
| SSR | renderizado en servidor |
| Static generation | páginas estáticas |
| renderizado híbrido | combinación cliente + servidor |

---

# Rastreo e indexación

Los motores de búsqueda necesitan instrucciones para rastrear correctamente el sitio.

## Sitemap

Archivo que lista todas las páginas del sitio.

Ejemplo:

```
sitemap.xml
```

Se envía a:

```
Google Search Console
```

---

## robots.txt

Archivo que indica qué páginas **no deben rastrearse**.

Ejemplo:

```
User-agent: *
Disallow: /wp-admin/
Disallow: /search/
```

---

## Meta Noindex

Evita que una página aparezca en Google.

```
<meta name="robots" content="noindex">
```

---

# Redacción SEO

El contenido debe responder a la intención de búsqueda.

Buenas prácticas:

- keyword en los primeros 100 caracteres
- uso de sinónimos
- contenido escaneable
- párrafos cortos
- listas

---

# Herramientas SEO

Herramientas básicas para análisis y monitorización.

| Herramienta | Uso |
|------|------|
| Google Search Console | indexación y errores |
| Google Analytics | tráfico |
| Screaming Frog | auditoría técnica |
| Ahrefs | backlinks |
| SEMrush | análisis de competencia |

---

# SEO en CMS

El SEO varía según el gestor de contenidos utilizado.

| CMS | Característica |
|------|------|
| WordPress | flexible y extensible |
| Shopify | optimizado para e-commerce |
| Wix | sencillo para proyectos pequeños |

Plugins recomendados en WordPress:

- Rank Math
- Yoast SEO

---

# Tendencias SEO 2025

Principales tendencias actuales.

### E-E-A-T

Experiencia  
Expertise  
Autoridad  
Confianza

Google prioriza contenido creado por **expertos reales**.

---

### Búsqueda generativa

Los resultados generados por IA están cambiando las SERPs.

Optimización recomendada:

- contenido profundo
- datos estructurados
- autoridad temática

---

### Mobile First

Google indexa principalmente la versión móvil del sitio.

Si una web no funciona bien en móvil, perderá visibilidad.

---

# SEO técnico: checklist

Elementos técnicos fundamentales.

- títulos únicos
- meta descriptions optimizadas
- estructura H1-H3 correcta
- datos estructurados (Schema.org)
- sitemap.xml
- robots.txt
- página 404 personalizada
- Open Graph para redes sociales

---

# Analítica y medición

Para mejorar SEO es necesario medir resultados.

Métricas clave:

- tráfico orgánico
- páginas de entrada
- conversiones
- consultas en buscadores

Herramientas:

- Google Analytics
- Google Search Console
- Microsoft Clarity

---

# Experimentos SEO

Ejercicios útiles para aprendizaje práctico.

Ejemplos:

- cambiar un `<title>` y observar resultados
- crear páginas con diferente estructura
- probar enlazado interno vs sin enlazado
- comparar redirecciones 301 y 302

---

# Retos SEO

Ideas para proyectos o experimentos.

- posicionar una palabra inventada
- optimizar para búsquedas por voz
- analizar por qué una web peor posiciona mejor
- estudiar impacto de IA en SEO

---

# Recursos

Repositorio relacionado:

https://github.com/jesusninoc/SEOextension

---

# Autor

Jesús Niño  

https://www.jesusninoc.com
