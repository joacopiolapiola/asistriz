# 🏥 Guía Estética del Proyecto Asistriz
## Identidad Visual Médica y Hospitalaria

---

## Introducción

Asistriz es una plataforma de productos de salud y bienestar creados a encargo, diseñada con una estética médica profesional. El diseño visual comunica expertise, precisión, confianza científica y ambiente clínico, reflejando los estándares hospitalarios de calidad y cuidado.

---

## 📋 Paleta de Colores

### Colores Primarios

| Color | Código | Uso | Contexto Médico |
|-------|--------|-----|-----------------|
| **Blanco quirúrgico** | #FFFFFF | Fondo principal, tarjetas | Higiene, esterilidad |
| **Gris hospitalario** | #F5F5F5 | Fondo de la página | Paredes de clínica |
| **Azul médico** | #1E5A96 | Acentos, encabezados | Confianza, profesionalismo |
| **Verde esmeralda clínico** | #0D7B5C | Botones, acciones positivas | Salud, sanación |
| **Gris acero** | #2C3E50 | Textos principales | Autoridad médica |
| **Gris clínico suave** | #7F8C8D | Textos secundarios | Información complementaria |

### Paleta Extendida (Complementaria)

| Color | Código | Uso |
|-------|--------|-----|
| **Azul cielo clínico** | #3498DB | Información, detalles |
| **Teal hospitalario** | #16A085 | Énfasis, highlights |
| **Rojo médico (alerta)** | #E74C3C | Información importante, descuentos |
| **Beige quirúrgico** | #ECF0F1 | Bordes suaves, separadores |

### Tema Oscuro (Modo Noche Clínico)

| Elemento | Color | Contexto |
|----------|-------|---------|
| Fondo principal | #0F1419 | Ambiente hospitalario de noche |
| Encabezado/Tarjetas | #1A2332 / #1F2A39 | Paneles clínicos modernos |
| Texto principal | #ECEFF1 | Alto contraste para legibilidad |
| Texto secundario | #B0BEC5 | Información secundaria legible |
| Footer | #0A0F14 | Anclaje visual oscuro |
| Acento azul | #5DADE2 | Azul más luminoso para oscuridad |
| Acento verde | #48C9B0 | Verde más claro para oscuridad |

### Filosofía de Color Médica

- **Blanco + Gris neutral**: Evocan ambientes hospitalarios limpios y profesionales
- **Azul médico**: Color institucional de hospitales y consultorios, transmite confianza científica
- **Verde clínico**: Representa salud, recuperación y vida; contrasta perfectamente con azul
- **Ausencia de colores vibrantes**: Mantiene profesionalismo clínico
- **Alto contraste**: Cumple con estándares de accesibilidad hospitalaria

---

## 🔤 Tipografía Médica

### Familia Tipográfica Principal

```
Segoe UI, Roboto, "Helvetica Neue", sans-serif
```

- **Tipo**: Sans-serif geométrica y profesional
- **Razón**: Es la fuente estándar en sistemas médicos y hospitalarios
- **Accesibilidad**: Excelente legibilidad en informes clínicos digitales
- **Precisión**: Formas geométricas exactas comunican precisión médica

### Jerarquía Tipográfica Hospitalaria

#### Título Principal (Encabezado de Hospital)
- **Tamaño**: 40px
- **Peso**: 600 (Semibold)
- **Color**: #1E5A96 (Azul médico)
- **Espaciado de letras**: +0.5px (profesional)
- **Espaciado inferior**: 12px
- **Propósito**: Logo/nombre de la clínica

#### Subtítulo Descriptivo
- **Tamaño**: 16px
- **Peso**: 400 (Regular)
- **Color**: #7F8C8D (Gris clínico)
- **Espaciado de línea**: 1.7
- **Ancho máximo**: 680px
- **Propósito**: Descripción profesional de servicios

#### Nombres de Productos (Prescripción)
- **Tamaño**: 22px
- **Peso**: 600 (Semibold)
- **Color**: #1E5A96 (Azul médico)
- **Espaciado inferior**: 8px
- **Efecto**: Aparecen como títulos de sección médica

#### Descripciones Clínicas
- **Tamaño**: 14px
- **Peso**: 400
- **Color**: #7F8C8D (Gris clínico)
- **Espaciado de línea**: 1.6
- **Altura mínima**: 52px
- **Propósito**: Beneficios y especificaciones médicas

#### Precios/Valores
- **Tamaño**: 24px
- **Peso**: 700 (Bold)
- **Color**: #0D7B5C (Verde esmeralda clínico)
- **Efecto**: Destacan como valores de referencia
- **Propósito**: Información económica clara

#### Etiquetas y Tags (Nuevas)
- **Tamaño**: 12px
- **Peso**: 600
- **Color**: Blanco sobre fondo de color
- **Fondo**: #1E5A96 o #0D7B5C
- **Padding**: 4px 8px
- **Radio**: 4px
- **Propósito**: Categorías médicas (ej: "Urgente", "Promoción")

---

## 🏥 Componentes y Texturas Clínicas

### Tarjetas Médicas de Producto

#### Características Visuales
- **Forma**: Rectángulo con bordes muy suavizados
- **Radio de borde**: 8px (más clínico, menos lúdico)
- **Sombra**: `0 2px 8px rgba(30, 90, 150, 0.08)` (azul médico tintado)
- **Borde**: 1px sólido #E8EEF2 (línea de separación sutil)
- **Fondo**: Blanco puro (#FFFFFF)
- **Transición hover**: 0.3s elegante

#### Efectos de Interacción
- **Elevación al pasar**: Se desplaza 3px hacia arriba
- **Sombra mejorada**: `0 4px 16px rgba(30, 90, 150, 0.12)` (sombra médica mayor)
- **Borde**: Cambia a #1E5A96 (línea azul médica)
- **Propósito**: Interactividad clara pero profesional

### Galería de Imágenes Clínica (Carrusel)

#### Estructura
- **Altura**: 320px (más ample para fotografías médicas)
- **Relación**: Panorámica horizontal
- **Borde superior**: 1px #DAEAF5 (línea azul muy clara)
- **Área de fondo**: Gris hospitalario #F0F2F5

#### Navegación Médica
- **Botones**: Cuadrados redondeados (4px) con iconos `‹` y `›`
- **Tamaño**: 44px × 44px
- **Fondo**: `rgba(30, 90, 150, 0.75)` (azul médico semi-transparente)
- **Posición**: A los lados, centrados verticalmente
- **Efecto hover**: Color sólido #1E5A96, sin cambio de opacidad

#### Indicadores de Posición Hospitalarios
- **Puntos pequeños**: 8px de diámetro
- **Color inactivo**: #B0BEC5 (gris clínico claro)
- **Color activo**: #1E5A96 (azul médico)
- **Posición**: Abajo al centro
- **Separación**: 6px entre puntos
- **Borde**: 1px de borde en inactivos (define precisión)

### Botón de Acción Médica (Verde Clínico)

#### Diseño Profesional
- **Color de fondo**: Verde esmeralda clínico #0D7B5C
- **Color de texto**: Blanco (#FFFFFF)
- **Ancho**: 100% (ocupar tarjeta)
- **Relleno**: 14px vertical, 18px horizontal
- **Radio de borde**: 6px (más clínico)
- **Peso de fuente**: 600 (Semibold)
- **Tamaño de fuente**: 15px
- **Texto en mayúsculas**: "CONSULTAR POR WHATSAPP"
- **Espaciado de letras**: +0.3px

#### Efectos de Interacción
- **Hover - Color**: Verde más oscuro #0A5C47
- **Hover - Sombra**: `0 3px 12px rgba(13, 123, 92, 0.3)`
- **Transición**: 0.25s suave
- **Efecto de profundidad**: Genera sensación de presionar un botón clínico

#### Propósito Médico
- Invita a consulta profesional
- Verde representa salud y acciones positivas
- Mayúsculas comunican importancia

### Visualizador de Imagen Grande (Modal Clínico)

#### Modal
- **Fondo**: Negro semi-transparente `rgba(0, 0, 0, 0.75)` (más opaco para profesionalismo)
- **z-index**: 9999
- **Ancho de imagen**: Máximo 92% de pantalla
- **Alto de imagen**: Máximo 88% de altura

#### Borde y Presentación
- **Marco alrededor de imagen**: 2px #1E5A96 (azul médico)
- **Sombra interna**: Genera efecto de profundidad clínica
- **Radio**: 4px

#### Animación de Apertura
```
Duración: 0.3s
Efecto: fade-in suave (no demasiado rápido)
Transformación: zoom muy suave (0.98 → 1)
```

#### Botón de Cierre
- **Texto**: "✕" (equis más elegante)
- **Color**: #ECEFF1 (blanco clínico)
- **Tamaño**: 36px
- **Posición**: Esquina superior derecha con padding de 24px
- **Hover**: Cambia a #1E5A96 (interacción clara)
- **Fondo**: Pequeño círculo `rgba(30, 90, 150, 0.2)` al pasar

---

## 📐 Espaciado y Layout Hospitalario

### Márgenes y Relleno

#### Página General
- **Ancho máximo**: 1280px (espacioso como clínica)
- **Margen exterior superior/inferior**: 50px
- **Margen exterior lateral**: 24px
- **Padding tarjetas**: 24px (más respirable)
- **Línea separadora**: 1px #E8EEF2 entre secciones

#### Encabezado Clínico
- **Padding superior**: 50px
- **Padding inferior**: 40px
- **Borde inferior**: 2px sólido #DAEAF5 (línea azul clara, como cabecera de receta)
- **Ancho de texto**: Máximo 720px
- **Alineación**: Centrado

### Grid de Productos Médicos

| Dispositivo | Columnas | Brecha | Notas |
|-------------|----------|--------|-------|
| Escritorio | 3 columnas | 24px | Espaciado clínico equilibrado |
| Tablet | 2 columnas | 24px | Mantiene profesionalismo |
| Móvil | 1 columna | 20px | Stack lineal como historia clínica |

---

## 🌙 Tema Oscuro Clínico (Modo Noche)

### Intención Médica
- Simula ambiente de hospital por la noche
- Reduce fatiga visual en consultorios oscuros
- Mantiene profesionalismo en cualquier horario

### Implementación
- **Botón flotante**: Esquina superior derecha en icono de luna médica (🌙)
- **Posición fija**: Permanece visible al desplazarse
- **Tamaño**: 50px de diámetro
- **Borde**: 2px sólido #5DADE2 (azul claro en tema oscuro)
- **Sombra**: `0 4px 12px rgba(0, 0, 0, 0.4)`
- **Transición**: Todos los cambios en 0.35s suave

### Paleta Tema Oscuro
- Azules se vuelven más luminosos (#5DADE2, #82B8E8)
- Verdes más claros (#48C9B0)
- Fondos en tonos azul-gris (no puro negro)
- Mantiene líneas y bordes para estructura clínica

---

## ✨ Animaciones y Transiciones Médicas

### Principios de Movimiento
- **Velocidad moderada**: 0.25s a 0.35s (profesional, no juguetonas)
- **Easing**: `ease` o `ease-in-out` (movimiento natural)
- **Propósito**: Comunican interactividad de forma clara

### Tabla de Animaciones

| Interacción | Duración | Efecto | Contexto |
|------------|----------|--------|---------|
| Hover tarjetas | 0.3s | Elevación 3px + sombra azul | Respuesta profesional |
| Hover botones | 0.25s | Color más oscuro + sombra | Feedback tactil |
| Cambio de imagen | 0.35s | Deslizamiento suave | Navegación fluida |
| Apertura modal | 0.3s | Fade-in con zoom mínimo | Presentación seria |
| Cambio de tema | 0.35s | Transición de colores | Adaptación cómoda |
| Hover indicadores | 0.2s | Cambio de color sutil | Señalización clara |

---

## 📱 Adaptabilidad Hospitalaria (Responsive)

### Breakpoints Médicos

#### Tablet Médico (hasta 1024px)
- Grid pasa de 3 a 2 columnas
- Encabezado se comprime a 40px
- Separación entre tarjetas: 22px

#### Móvil Clínico (hasta 768px)
- Grid de 1 sola columna
- Encabezado principal: 32px
- Margen exterior: 16px
- Carrusel: Botones se ocultan, se usa swipe
- Altura carrusel: 300px

#### Móvil Pequeño (hasta 480px)
- Padding reducido: 16px
- Carrusel altura: 280px
- Fuentes se reducen 1-2px
- Botón tema: 44px

### Filosofía Responsive Médica
- **Fluida**: Adaptación sin saltos bruscos
- **Lectura vertical**: En móviles como historia clínica
- **Táctil optimizada**: Áreas de toque de 44-48px mínimo
- **Mantiene jerarquía**: Azul y verde siempre presentes

---

## 🎭 Personalidad Visual Hospitalaria

### Emociones que Transmite
- **Confianza científica**: Colores institucionales, tipografía profesional
- **Precisión médica**: Bordes definidos, espaciado exacto, geometría clara
- **Limpieza y esterilidad**: Blanco puro, espacios respirables
- **Profesionalismo**: Sin frivolidades, enfocado en la salud
- **Seguridad**: Azul transmite confianza, verde transmite sanación

### Tono Visual Clínico
- **Serio pero acogedor**: Profesional sin ser intimidante
- **Ordenado**: Estructura clara como en un consultorio
- **Transparente**: Información legible y accesible
- **Institucional**: Evoca autoridad médica

### Elementos que Evocan Hospital
- Líneas de separación sutiles (#DAEAF5) como en expedientes
- Paleta azul-verde de laboratorios médicos
- Tipografía sans-serif como en señalización hospitalaria
- Espaciado amplio como en salas de consulta
- Bordes suaves (no afilados, acogedores)

---

## 🔍 Detalles de Implementación Clínica

### Sombras Médicas
```
Sombra suave:        0 2px 8px rgba(30, 90, 150, 0.08)
Sombra estándar:     0 4px 16px rgba(30, 90, 150, 0.12)
Sombra de profundidad: 0 6px 24px rgba(30, 90, 150, 0.15)
Sombra de botón:     0 3px 12px rgba(13, 123, 92, 0.3)
```

### Bordes Clínicos
- **Tarjetas**: 1px #E8EEF2 + radio 8px
- **Elementos destacados**: 2px #DAEAF5 (azul muy claro)
- **Separadores**: 1px #ECF0F1 (beige quirúrgico)
- **Sin bordes negros**: Mantiene suavidad profesional

### Líneas y Estructura
- **Cabecera de página**: 2px #DAEAF5 (como membrete médico)
- **Divisores secciones**: 1px #E8EEF2
- **Bordes imágenes**: 1px #DAEAF5 en modal

### Opacidad y Transparencia
- **Navegación carrusel**: 75% (semi-transparencia profesional)
- **Fondo modal**: 75% (oscurecimiento significativo)
- **Elementos suaves**: 8-12% opacidad (muy sutiles)

---

## 🏥 Elementos Especiales Médicos

### Etiquetas de Estado (Nuevas)
```
Urgente:     Fondo #E74C3C, texto blanco, 12px, semibold
Promoción:   Fondo #0D7B5C, texto blanco, 12px, semibold
Disponible:  Fondo #3498DB, texto blanco, 12px, semibold
Consultar:   Fondo #1E5A96, texto blanco, 12px, semibold
```

### Indicadores de Confianza
- Pequeño escudo de verificación junto a nombre si aplica
- Estrella para calificación (opcional)
- Tick de confirmación en acciones completadas

### Información Complementaria
- Horarios de atención en gris clínico
- Especialidad médica en azul médico
- Datos de contacto en verde clínico

---

## 📋 Checklist de Consistencia Hospitalaria

Cuando añadas nuevos elementos:

- [ ] ¿Usa azul médico (#1E5A96) o verde clínico (#0D7B5C) como acentos?
- [ ] ¿Los colores evocan ambiente hospitalario?
- [ ] ¿Las sombras son sutiles y azul-tintadas?
- [ ] ¿Los bordes tienen 6-8px de radio (no puntiagudos)?
- [ ] ¿Las transiciones son 0.25-0.35s?
- [ ] ¿El espaciado sigue múltiplos de 4-8px?
- [ ] ¿Funciona en móvil/tablet/escritorio?
- [ ] ¿Tiene versión de tema oscuro clínico?
- [ ] ¿La tipografía es semibold para títulos?
- [ ] ¿El texto es legible en 14-16px?
- [ ] ¿Hay suficiente espaciado "respirable"?
- [ ] ¿Transmite profesionalismo médico?

---

## 🎨 Inspiración Médica

Este diseño se basa en:
- **Estándares hospitalarios**: Colores y espaciado de clínicas profesionales
- **Accesibilidad médica**: Fuentes claras, alto contraste, legibilidad prioritaria
- **Precisión científica**: Formas geométricas exactas, paleta controlada
- **Empatía clínica**: Profesional pero acogedor, no intimidante
- **Estética institucional**: Inspirado en portales de hospitales y laboratorios

---

## 🌡️ Casos de Uso Visual

### Producto Activo y Disponible
```
Borde: #E8EEF2 → #1E5A96 (más visible)
Sombra: Aumentada
Botón: Verde clínico activo
```

### Producto Fuera de Stock
```
Opacidad: 65%
Botón: Deshabilitado (gris)
Etiqueta: "Próximamente"
```

### Consulta en Proceso
```
Borde: Verde clínico #0D7B5C
Ícono: Checkmark en verde
Estado: "En revisión"
```

---

**Última actualización**: Agosto 2026 — Diseño Médico Profesional
