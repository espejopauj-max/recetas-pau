# 🍳 RecetasFáciles.com — Documentación del Proyecto
## Web monetizable con AdSense + SEO avanzado

---

## 📁 ESTRUCTURA DE ARCHIVOS

```
recetas/
├── index.html              ← Página principal (Home) con grid de 10 recetas
├── receta-tortilla.html    ← Receta completa: Tortilla española ✅ COMPLETA
├── receta-carbonara.html   ← Receta completa: Pasta carbonara ✅ COMPLETA
├── receta-gazpacho.html    ← Receta completa: Gazpacho andaluz ✅ COMPLETA
├── receta-pollo-ajillo.html      ← Duplicar plantilla y adaptar
├── receta-pizza.html             ← Duplicar plantilla y adaptar
├── receta-lentejas.html          ← Duplicar plantilla y adaptar
├── receta-ensalada-cesar.html    ← Duplicar plantilla y adaptar
├── receta-arroz-leche.html       ← Duplicar plantilla y adaptar
├── receta-croquetas.html         ← Duplicar plantilla y adaptar
├── receta-paella.html            ← Duplicar plantilla y adaptar
├── receta-huevos-rotos.html      ← Duplicar plantilla y adaptar
│
├── css/
│   └── style.css           ← CSS completo (todo el diseño)
│
└── js/
    └── main.js             ← JavaScript (UX, animaciones, navbar)
```

---

## 🚀 CÓMO USAR

### 1. Arrancar localmente
Abre `index.html` directamente en el navegador.
Para mejor experiencia, usa un servidor local:
```bash
# Con Python 3:
cd recetas/
python -m http.server 8080

# Con Node.js (npx):
npx serve .
```

### 2. Crear las recetas restantes
Copia `receta-gazpacho.html` (la más limpia como plantilla) y cambia:
- `<title>` y `<meta name="description">`
- El `og:image` 
- El Schema.org JSON-LD (nombre, tiempos, ingredientes, pasos)
- La imagen del hero
- El H1 con keyword
- Los stats rápidos (tiempo, personas, calorías)
- Introducción (500-800 palabras con keywords)
- Ingredientes
- Pasos detallados
- Consejos
- FAQ (mínimo 5 preguntas)
- Sección de variaciones

---

## 💰 INTEGRACIÓN CON GOOGLE ADSENSE

### Pasos para activar AdSense real:
1. Crea cuenta en https://adsense.google.com
2. Verifica tu sitio web
3. Sustituye los `<div class="ad-block">` por los snippets reales de AdSense:

```html
<!-- ANTES (placeholder) -->
<div class="ad-block ad-recipe">
  <i class="bi bi-megaphone me-2"></i> Publicidad – AdSense 728×90
</div>

<!-- DESPUÉS (AdSense real) -->
<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-XXXXXXXXXXXXXXXX"
     data-ad-slot="XXXXXXXXXX"
     data-ad-format="auto"
     data-full-width-responsive="true">
</ins>
<script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
```

### Posiciones de anuncios (ya implementadas):
| ID clase CSS      | Posición              | Formato ideal   |
|-------------------|-----------------------|-----------------|
| `.ad-top`         | Encima del fold       | 728×90 (Leaderboard) |
| `.ad-inline`      | Entre tarjetas home   | 728×90 o responsive |
| `.ad-recipe`      | Entre pasos receta    | 728×90 o responsive |
| `.ad-recipe-mid`  | Antes del FAQ         | 300×250 (Rectangle) |
| `.ad-sidebar`     | Columna lateral       | 300×250 o 300×600 |
| Pie de página     | Footer                | 728×90 |

### Código de verificación AdSense (en `<head>` de cada página):
```html
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-XXXXXXXXXXXXXXXX" crossorigin="anonymous"></script>
```

---

## 🔍 SEO IMPLEMENTADO

### Técnico:
- ✅ Meta title optimizado (keyword principal + marca)
- ✅ Meta description con CTA y keywords
- ✅ Meta keywords
- ✅ Open Graph (og:title, og:description, og:image, og:type)
- ✅ Schema.org Recipe (JSON-LD) en cada receta
- ✅ Breadcrumbs (navegación + SEO)
- ✅ H1 único con keyword principal
- ✅ H2, H3 estructurados
- ✅ Alt text en imágenes
- ✅ Lazy loading de imágenes
- ✅ URLs descriptivas (receta-tortilla.html)
- ✅ Internal linking (footer, "otras recetas", breadcrumbs)
- ✅ FAQ con Schema implicit (accordion)
- ✅ Texto largo (500-800+ palabras por receta)
- ✅ Keywords en negrita (`<strong>`)

### Schema.org por receta incluye:
- name, image, author, datePublished
- prepTime, cookTime, totalTime
- recipeYield, recipeCategory, recipeCuisine
- nutrition (calories)
- aggregateRating (ratingValue + reviewCount)
- recipeIngredient (array)
- recipeInstructions (HowToStep)

---

## ⚡ OPTIMIZACIÓN UX (más tiempo en página = más ingresos)

### Implementado:
- ✅ Barra de progreso de lectura (fija arriba)
- ✅ Navbar sticky con efecto scroll
- ✅ Jump links (saltar a secciones)
- ✅ Botón "volver arriba"
- ✅ Sticky CTA bar (aparece al llegar a los pasos)
- ✅ Sección "otras recetas que te pueden gustar"
- ✅ Newsletter (retención de usuarios)
- ✅ Animaciones de entrada en cards (scroll reveal)
- ✅ Hover effects en todas las tarjetas
- ✅ Imágenes con zoom suave en hover
- ✅ Scroll largo con contenido bien dividido
- ✅ Acordeón FAQ (mantiene al usuario activo)
- ✅ Categorías clickables en home

---

## 📊 MÉTRICAS A MONITORIZAR

### Google Analytics 4 (añadir a `<head>`):
```html
<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

### KPIs principales:
- **CTR anuncios**: objetivo >1.5% para display
- **Tiempo en página**: objetivo >3 min por receta
- **Páginas por sesión**: objetivo >2.5
- **Bounce rate**: objetivo <65%
- **Posición orgánica**: palabras clave objetivo <20

---

## 🛠 PRÓXIMOS PASOS PARA MAXIMIZAR INGRESOS

1. **Completar las 7 recetas restantes** (copiar plantilla gazpacho)
2. **Activar Google AdSense** y pasar la verificación
3. **Instalar Google Analytics 4**
4. **Subir a hosting** (Netlify gratis, o Hostinger para dominio propio)
5. **Registrar en Google Search Console**
6. **Enviar sitemap.xml** a GSC
7. **Conseguir backlinks** (redes sociales, Pinterest, foros)
8. **Crear contenido nuevo semanalmente** (blog de recetas)
9. **Optimizar Core Web Vitals** (PageSpeed Insights)
10. **Añadir vídeos** (YouTube embed = más tiempo en página)

---

## 💻 TECNOLOGÍAS USADAS

| Tecnología | Versión | Uso |
|------------|---------|-----|
| HTML5 | - | Estructura semántica |
| CSS3 | - | Diseño y animaciones |
| JavaScript ES6+ | - | Interactividad UX |
| Bootstrap | 5.3.3 | Grid y componentes |
| Bootstrap Icons | 1.11.3 | Iconografía |
| Google Fonts | - | Playfair Display + DM Sans |
| Schema.org | - | Rich snippets (JSON-LD) |

---

## 🎨 PALETA DE COLORES

```css
--primary:    #e05c1a  /* Naranja principal */
--primary-dk: #b84910  /* Naranja oscuro */
--accent:     #f5a623  /* Amarillo dorado */
--dark:       #1a1208  /* Marrón muy oscuro */
--light:      #fffbf5  /* Crema claro */
--text:       #2d2010  /* Marrón texto */
--muted:      #7a6a55  /* Gris cálido */
```

---

Desarrollado con ❤️ para maximizar SEO + AdSense revenue
