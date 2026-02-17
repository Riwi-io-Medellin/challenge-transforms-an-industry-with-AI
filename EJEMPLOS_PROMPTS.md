# Ejemplos de Prompts para Lovable

Esta guía te ayudará a comunicarte efectivamente con la IA para crear tu interfaz en tiempo récord.

---

## Estructura de un Buen Prompt

```
[CONTEXTO] + [LAYOUT] + [FUNCIONALIDAD] + [ESTILO] + [DETALLES]
```

---

## Opción A: Logística

### Prompt Inicial (Mega-Prompt)

```
Crea un dashboard profesional para una empresa de logística moderna.

CONTEXTO:
Es una aplicación de control de envíos que usa IA para predecir problemas y optimizar rutas.

LAYOUT:
- Header superior con logo y notificaciones
- Sidebar izquierda con navegación: Dashboard, Envíos, Rutas, Alertas, Reportes
- Área principal dividida en 3 secciones:
  * Izquierda (40%): Mapa interactivo con marcadores de camiones
  * Centro (30%): Lista de envíos activos con estados
  * Derecha (30%): Panel de alertas de IA

FUNCIONALIDAD:
- Mapa debe mostrar rutas con líneas de colores según prioridad
- Alertas deben tener iconos según tipo: clima, retraso, daño
- Cada alerta muestra nivel de confianza de la IA (ej: 87%)

ESTILO:
- Tema oscuro (fondo #0f172a, texto claro)
- Colores de alerta: Rojo (#ef4444), Amarillo (#f59e0b), Verde (#10b981)
- Tipografía: Inter o similar, moderna y limpia
- Bordes redondeados sutiles (8px)
- Sombras suaves para profundidad

DETALLES:
- Animación sutil en alertas nuevas (fade in)
- Badges con números para notificaciones
- Gráfico de barras pequeño mostrando eficiencia semanal
```

### Prompts de Iteración

```
"Agrega un widget en la parte superior que muestre 4 KPIs: 
   Envíos Hoy, En Ruta, Retrasados, Completados. 
   Usa números grandes (32px) y colores según estado"

"Haz que cada alerta tenga un botón 'Ver Detalles' que expanda 
   información adicional con animación smooth"

"Agrega un filtro dropdown arriba del mapa para seleccionar 
   región: Norte, Sur, Este, Oeste, Todas"

"Incluye timestamps en cada alerta con formato relativo 
   (hace 5 min, hace 2 horas)"

"Agrega iconos de Lucide para cada tipo de alerta: 
   CloudRain para clima, Clock para retrasos, Package para daños"
```

---

## Opción B: Legal

### Prompt Inicial (Mega-Prompt)

```
Crea una aplicación web de análisis de contratos con IA.

CONTEXTO:
Abogados suben PDFs de contratos y la IA identifica riesgos automáticamente.

LAYOUT:
- Header con logo y menú de usuario
- Área principal dividida en 2 columnas:
  * Izquierda (50%): Zona de upload de PDF con drag & drop
  * Derecha (50%): Panel de resultados del análisis

FUNCIONALIDAD:
- Zona de upload debe mostrar icono de documento y texto "Arrastra tu contrato aquí"
- Después de "analizar", mostrar:
  * Semáforo de riesgo general (círculo grande: Rojo/Amarillo/Verde)
  * Lista de cláusulas encontradas con nivel de riesgo
  * Porcentaje de confianza de la IA en cada detección
- Botón para "Hacer una pregunta sobre el contrato"

ESTILO:
- Tema claro profesional (fondo blanco, acentos azul corporativo #2563eb)
- Tipografía serif para títulos (elegante), sans-serif para cuerpo
- Semáforo con animación de pulso sutil
- Cards con sombra para cada cláusula detectada

DETALLES:
- Iconos: FileText para documentos, AlertTriangle para riesgos
- Progress bar durante el "análisis" (simulado)
- Badges de colores para nivel de riesgo: Alto (rojo), Medio (amarillo), Bajo (verde)
```

### Prompts de Iteración

```
"Agrega una sección de 'Resumen Ejecutivo' arriba de las cláusulas 
   que muestre 3 bullet points con los hallazgos principales"

"Haz que cada cláusula sea expandible para mostrar el texto exacto 
   del contrato y la explicación de la IA"

"Incluye un chat flotante en la esquina inferior derecha donde 
   puedo hacer preguntas sobre el contrato"

"Agrega un botón 'Exportar Reporte' que simule generar un PDF 
   con los resultados"

"Muestra estadísticas del documento: número de páginas, 
   fecha de análisis, tiempo de procesamiento"
```

---

## Opción C: Retail

### Prompt Inicial (Mega-Prompt)

```
Crea una interfaz de Personal Shopper con IA para e-commerce de moda.

CONTEXTO:
Los usuarios describen lo que necesitan en lenguaje natural y la IA 
recomienda outfits completos con explicaciones.

LAYOUT:
- Header con logo de tienda y carrito
- Área principal dividida:
  * Izquierda (40%): Chat conversacional con la IA
  * Derecha (60%): Grid de productos recomendados

FUNCIONALIDAD:
- Chat debe tener:
  * Mensajes del usuario (alineados derecha, fondo azul)
  * Respuestas de la IA (alineados izquierda, fondo gris claro)
  * Input de texto abajo con botón de enviar
- Grid de productos debe mostrar:
  * Imagen del producto
  * Nombre y precio
  * Badge de "Por qué te lo recomendamos" (tooltip)
  * Botón "Agregar al carrito"

ESTILO:
- Tema moderno y fresco (fondo blanco, acentos rosa #ec4899)
- Tipografía sans-serif moderna (Poppins o similar)
- Cards de productos con hover effect (elevación)
- Avatar de IA en el chat (icono de robot o sparkles)

DETALLES:
- Animación de "escribiendo..." cuando la IA está "pensando"
- Badges de categoría en cada producto (Casual, Formal, Deportivo)
- Indicador de stock limitado si aplica
- Sugerencias de preguntas iniciales: "Necesito un outfit para...", 
  "Busco algo para el clima..."
```

### Prompts de Iteración

```
"Agrega un carrusel de 'Outfits Completos' arriba del grid 
   que muestre combinaciones de 3-4 prendas juntas"

"Incluye filtros rápidos arriba del grid: Precio, Categoría, Color. 
   Deben ser chips clickeables"

"Haz que la IA muestre su 'razonamiento' en el chat, por ejemplo: 
   'Considerando: clima cálido + ocasión formal + tu estilo'"

"Agrega un botón de 'Sorpréndeme' que genere una recomendación 
   aleatoria con animación"

"Incluye ratings de estrellas en cada producto y número de reviews"
```

---

## Prompts para Mejorar el Diseño

### Colores y Tema

```
"Cambia el esquema de colores a un tema oscuro con acentos neón 
   (cyan #06b6d4 y magenta #ec4899)"

"Usa un gradiente sutil de fondo que vaya de azul oscuro a púrpura"

"Agrega modo claro/oscuro con un toggle en el header"
```

### Tipografía

```
"Cambia la fuente principal a 'Space Grotesk' para un look más tech"

"Haz los títulos más grandes (36px) y bold, con letter-spacing amplio"

"Usa una fuente monoespaciada para números y datos técnicos"
```

### Animaciones

```
"Agrega una animación de fade-in cuando aparecen nuevos elementos"

"Haz que los botones tengan un efecto de scale al hacer hover (1.05x)"

"Incluye una animación de skeleton loading mientras carga la data"
```

### Componentes

```
"Agrega tooltips informativos en los iconos con hover"

"Incluye un breadcrumb de navegación en la parte superior"

"Agrega un footer con links de contacto y redes sociales"
```

---

## Errores Comunes a Evitar

### Prompts Demasiado Vagos

```
MAL: "Haz un dashboard bonito"
BIEN: "Crea un dashboard con tema oscuro, 3 columnas, y gráficos de barras"

MAL: "Agrega colores"
BIEN: "Usa azul #2563eb para botones primarios y gris #64748b para secundarios"

MAL: "Mejora el diseño"
BIEN: "Aumenta el padding de las cards a 24px y agrega sombras sutiles"
```

### Pedir Demasiado a la Vez

```
MAL: "Agrega un mapa, un chat, gráficos, filtros, y un sistema de notificaciones"
BIEN: Divide en pasos:
   1. "Agrega un mapa interactivo en el centro"
   2. "Ahora agrega un panel de chat a la derecha"
   3. "Incluye un gráfico de barras debajo del mapa"
```

### No Ser Específico con Elementos de IA

```
MAL: "Muestra que usa IA"
BIEN: "Agrega un badge que diga 'Confianza: 94%' junto a cada predicción"
BIEN: "Incluye un tooltip que explique cómo la IA llegó a esa conclusión"
```

---

## Tips Pro

### 1. **Usa Referencias Visuales**
```
"Haz el header similar al de Notion: minimalista, con iconos pequeños"
"El estilo debe ser como Stripe: limpio, espaciado, profesional"
```

### 2. **Especifica Interacciones**
```
"Al hacer click en una alerta, debe expandirse con animación smooth 
y mostrar un modal con detalles completos"
```

### 3. **Pide Responsive Design**
```
"Asegúrate de que en mobile el sidebar se convierta en un menú hamburguesa"
```

### 4. **Solicita Estados**
```
"Muestra 3 estados: loading (spinner), success (data), error (mensaje amigable)"
```

---

## Checklist de Elementos de IA

Para que tu interfaz realmente parezca "potenciada por IA", incluye:

- [ ] **Niveles de confianza** (ej: "87% seguro")
- [ ] **Explicaciones** ("Recomendado porque...")
- [ ] **Predicciones** ("Estimado: 2 horas")
- [ ] **Análisis visual** (resaltado de áreas importantes)
- [ ] **Sugerencias proactivas** ("También podrías...")
- [ ] **Procesamiento en tiempo real** (animaciones de "analizando")
- [ ] **Insights automáticos** ("Detectamos un patrón...")

---

## Prompt Final de Pulido

Antes de entregar, usa este prompt:

```
Revisa toda la interfaz y:
1. Asegúrate de que todos los espaciados sean consistentes
2. Verifica que los colores sigan una paleta coherente
3. Agrega micro-interacciones en botones y cards (hover, active)
4. Incluye estados de loading donde sea necesario
5. Optimiza para que se vea profesional y moderno
6. Agrega un favicon y título apropiado a la página
```

---

**¡Ahora tienes todo para crear una interfaz increíble en 30 minutos!**
