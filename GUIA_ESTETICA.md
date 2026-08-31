# 🎨 Guía Estética del Proyecto Asistriz

## Introducción

Asistriz es una plataforma de productos de salud y bienestar creados a encargo. Su diseño visual ha sido concebido para transmitir confianza, profesionalismo y accesibilidad, reflejando los valores de calidad y cuidado del sector salud.

---

## 📋 Paleta de Colores

### Colores Principales

| Color | Código | Uso |
|-------|--------|-----|
| **Blanco** | #FFFFFF | Fondo principal, tarjetas, encabezado |
| **Gris claro** | #F7F7F7 | Fondo de la página en tema claro |
| **Gris oscuro** | #222222 | Textos principales, footer |
| **Verde WhatsApp** | #25D366 | Botón de acción (consultas) |
| **Gris medio** | #666666 | Textos secundarios, descripciones |

### Tema Oscuro (Modo Noche)

| Elemento | Color |
|----------|-------|
| Fondo principal | #121212 |
| Encabezado/Tarjetas | #1C1C1C / #1E1E1E |
| Texto principal | #FFFFFF |
| Texto secundario | #BDBDBD |
| Footer | #080808 |

### Filosofía de Color

- **Colores neutros y limpios**: Los grises y blancos crean un ambiente profesional y seguro, ideal para un proyecto de salud
- **Punto focal verde**: El verde WhatsApp en los botones es la única nota de color vibrante, guiando al usuario hacia la acción principal
- **Contraste accesible**: Las combinaciones mantienen alto contraste para legibilidad óptima
- **Tema oscuro disponible**: Reduce la fatiga visual en ambientes con poca luz

---

## 🔤 Tipografía

### Familia Tipográfica Principal

```
Arial, Helvetica, sans-serif
```

- **Tipo**: Sans-serif moderna y accesible
- **Razón**: Transmite modernidad, limpieza y profesionalismo
- **Accesibilidad**: Excelente legibilidad en pantallas

### Jerarquía Tipográfica

#### Títulos
- **Tamaño**: 38px (encabezado principal)
- **Peso**: Normal
- **Color**: #222222 (tema claro) / #FFFFFF (tema oscuro)
- **Espaciado inferior**: 10px

#### Subtítulos / Descripción de marca
- **Tamaño**: 17px
- **Color**: #666666 (tema claro) / #BDBDBD (tema oscuro)
- **Espaciado de línea**: 1.6
- **Propósito**: Explicar la propuesta de valor

#### Nombres de productos
- **Tamaño**: 21px
- **Peso**: Normal
- **Color**: #222222 (tema claro) / #FFFFFF (tema oscuro)
- **Espaciado inferior**: 10px

#### Descripciones de producto
- **Tamaño**: 15px
- **Color**: #666666 (tema claro) / #BDBDBD (tema oscuro)
- **Espaciado de línea**: 1.5
- **Altura mínima**: 48px (garantiza espacio visual)

#### Precios
- **Tamaño**: 21px
- **Peso**: Bold (negrita)
- **Color**: #222222 (tema claro) / #FFFFFF (tema oscuro)
- **Propósito**: Destacar el valor del producto

---

## 🎯 Componentes y Texturas

### Tarjetas de Producto

#### Características visuales
- **Forma**: Rectángulo redondeado
- **Radio de borde**: 14px
- **Sombra**: `0 5px 20px rgba(0, 0, 0, 0.08)`
- **Fondo**: Blanco sólido (#FFFFFF)
- **Transición hover**: 0.25s con efecto suave

#### Efectos de interacción
- **Elevación al pasar cursor**: Se desplaza 5px hacia arriba
- **Sombra mejorada**: `0 10px 28px rgba(0, 0, 0, 0.12)`
- **Propósito**: Indicar interactividad sin agresividad

### Galería de imágenes (Carrusel)

#### Estructura
- **Altura**: 280px (escritorio) / 300px (móvil)
- **Relación**: Panorámica horizontal
- **Área de fondo**: Gris suave (#EEEEEE) cuando no hay imagen

#### Navegación
- **Botones**: Círculos semi-oscuros con iconos `‹` y `›`
- **Tamaño**: 42px diámetro
- **Fondo**: `rgba(0, 0, 0, 0.55)` (semi-transparente)
- **Posición**: A los lados, centrados verticalmente
- **Efecto hover**: Oscurecimiento a `rgba(0, 0, 0, 0.8)`

#### Indicadores de posición
- **Puntos pequeños**: 9px de diámetro
- **Color inactivo**: `rgba(255, 255, 255, 0.55)` (semi-transparente)
- **Color activo**: Blanco sólido con ligero aumento de tamaño
- **Posición**: Abajo al centro
- **Separación**: 7px entre puntos

### Botón de Acción (WhatsApp)

#### Diseño
- **Color de fondo**: Verde WhatsApp (#25D366)
- **Color de texto**: Blanco
- **Ancho**: 100% (ocupar tarjeta)
- **Relleno**: 13px vertical, 18px horizontal
- **Radio de borde**: 8px
- **Peso de fuente**: Bold
- **Tamaño de fuente**: 15px

#### Efectos
- **Hover - Color**: Verde más oscuro (#1ebe5d)
- **Hover - Escala**: Aumenta 2% (1.02x)
- **Transición**: 0.2s suave

#### Propósito
- Es la llamada a la acción principal
- El verde es universal para WhatsApp (confianza)
- Invita al usuario a consultar de forma directa

### Visualizador de Imagen Grande

#### Modal
- **Fondo**: Negro translúcido `rgba(0, 0, 0, 0.88)`
- **z-index**: 9999 (por encima de todo)
- **Ancho de imagen**: Máximo 95% de la pantalla
- **Alto de imagen**: Máximo 90% de alto de ventana

#### Animación de apertura
```
Duración: 0.2s
Efecto: fade-in con escala suave (0.95 → 1)
```

#### Botón de cierre
- **Texto**: "×" (equis)
- **Color**: Blanco (#FFFFFF)
- **Tamaño**: 40px
- **Posición**: Esquina superior derecha
- **Hover**: Suavización a gris claro (#DDD)

---

## 📐 Espaciado y Layout

### Márgenes y Padding

#### Página general
- **Ancho máximo**: 1200px (contenedor principal)
- **Margen exterior**: 45px arriba/abajo, 20px lados
- **Padding tarjetas**: 22px

#### Encabezado
- **Padding superior**: 45px
- **Padding inferior**: 35px
- **Ancho de texto**: Máximo 650px (mejora legibilidad)

### Grid de Productos

| Dispositivo | Columnas | Brecha |
|-------------|----------|--------|
| Escritorio | 3 columnas | 28px |
| Tablet | 2 columnas | 28px |
| Móvil | 1 columna | 28px |

---

## 🌙 Tema Oscuro (Dark Mode)

### Intención
- Reducir fatiga visual en ambientes oscuros
- Mejorar accesibilidad
- Opción de preferencia del usuario

### Implementación
- **Botón flotante**: Esquina superior derecha (🌙 ☀️)
- **Posición fija**: Permanece visible al desplazarse
- **Tamaño**: 48px de diámetro
- **Transición**: Todos los cambios en 0.3s suave

### Cambios de paleta
- Fondos claros → Oscuros
- Textos oscuros → Claros
- Mantiene legibilidad y contraste

---

## ✨ Animaciones y Transiciones

### Elementos interactivos

| Interacción | Duración | Efecto |
|------------|----------|--------|
| Hover tarjetas | 0.25s | Elevación + sombra mejorada |
| Hover botones | 0.2s | Cambio de color + escala |
| Cambio de imagen | 0.4s | Deslizamiento suave |
| Apertura modal | 0.2s | Fade-in con zoom |
| Cambio de tema | 0.3s | Transición de colores |

### Principios
- **Suavidad**: Todas las transiciones usan `ease` o `ease-in-out`
- **Velocidad**: Entre 0.2s y 0.4s (rápidas pero notables)
- **Claridad**: Las animaciones comunican interactividad

---

## 📱 Adaptabilidad (Responsive)

### Breakpoints

#### Tablet (hasta 900px)
- Grid pasa de 3 a 2 columnas
- Espaciado se mantiene consistente

#### Móvil (hasta 600px)
- Grid de 1 sola columna
- Encabezado más compacto: 30px de tamaño (antes 38px)
- Botón de tema se reduce a 42px
- Carrusel: botones se ocultan (se usa swipe/toque)
- Imagen modal: 100% de ancho disponible

### Filosofía responsive
- **Fluida**: El diseño se adapta sin saltos bruscos
- **Funcional**: Toda interactividad funciona en móviles
- **Táctil**: Eliminación de botones pequeños en móviles

---

## 🎭 Personalidad Visual

### Emociones que transmite
- **Confianza**: Colores neutros, profesionales
- **Cuidado**: Espaciado generoso, tipografía legible
- **Modernidad**: Borde redondeado, animaciones suaves
- **Accesibilidad**: Alto contraste, textos grandes, tema oscuro

### Tono visual
- No agresivo: Sombras suaves, colores apagados
- No minimalista extremo: Hay suficiente espaciado y jerarquía
- Caliente y acogedor: Verde natural del WhatsApp, fondos claros

---

## 🔍 Detalles de implementación

### Sombras
```
Sombra estándar:     0 5px 20px rgba(0, 0, 0, 0.08)
Sombra de hover:     0 10px 28px rgba(0, 0, 0, 0.12)
Sombra de botón:     0 4px 12px rgba(0, 0, 0, 0.2)
```

### Bordes
- **Tarjetas**: 14px de radio (suavidad moderna)
- **Botones**: 8px o 50% (circular para iconos)
- **Sin bordes lineales duros**: Se prefieren transiciones suaves

### Opacidad
- Elementos semi-transparentes se usan estratégicamente (controles en imágenes)
- Mejora la legibilidad sin eliminar el contenido de fondo

---

## 📋 Checklist de consistencia

Cuando añadas nuevos elementos, verifica:

- [ ] ¿Usa Arial/Helvetica como tipografía base?
- [ ] ¿Los colores son de la paleta establecida?
- [ ] ¿Las sombras siguen el patrón (0 5px 20px...)?
- [ ] ¿Las transiciones son 0.2-0.4s con ease?
- [ ] ¿El radio de borde está entre 8-14px?
- [ ] ¿El espaciado es múltiple de 5-10px?
- [ ] ¿Funciona en móvil/tablet/escritorio?
- [ ] ¿Tiene versión de tema oscuro?

---

## 🎨 Inspiración general

Este diseño se basa en principios de:
- **Diseño limpio**: Menos es más, pero con suficiente espacio respiratorio
- **Accesibilidad primero**: Todo debe ser legible y usable
- **Funcionalidad visual**: Las formas comunican propósito
- **Sector salud**: Confianza, profesionalismo, calidez

---

**Última actualización**: Agosto 2026

