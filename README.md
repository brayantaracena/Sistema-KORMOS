# 🪵 Sistema Presupuesto Ebanistería RD

Sistema de presupuestación dinámica para talleres de ebanistería en República Dominicana. Calcula costos de materiales, mano de obra y genera cotizaciones profesionales en pesos dominicanos (RD$).

## ✨ Características

- **Calculadora de Pies Tablares**: Convierte dimensiones a pies tablares automáticamente
- **Base de Datos de Materiales**: Precios actualizados de maderas, adhesivos, lacas y herrajes
- **Cálculo de Costos**: Materiales + Mano de obra + Margen de ganancia
- **Exportación Profesional**: Genera cotizaciones en PDF y Excel
- **Almacenamiento Local**: Guarda tus precios personalizados

## 🚀 Inicio Rápido

1. Abre `index.html` en tu navegador
2. Agrega los materiales de tu proyecto
3. Configura la mano de obra y margen de ganancia
4. Exporta o imprime tu cotización

## 📁 Estructura del Proyecto

```
Kormos Sistema/
├── index.html          # Página principal
├── css/
│   └── styles.css      # Estilos y temas
├── js/
│   ├── main.js         # Lógica principal
│   ├── boardfeet.js    # Calculadora pies tablares
│   ├── storage.js      # Persistencia de datos
│   └── export.js       # Exportación PDF/Excel
├── data/
│   └── materials.json  # Base de datos de precios
└── lib/
    ├── jspdf.umd.min.js   # Librería PDF
    └── xlsx.full.min.js   # Librería Excel
```

## 📐 Fórmula de Pies Tablares

```
Pies Tablares = (Grosor" × Ancho" × Largo") / 12
```

### Ejemplo
Una tabla de Caoba de 1½" × 9" × 96":
```
(1.5 × 9 × 96) / 12 = 108 pies tablares
```

## 💰 Precios de Referencia (RD$)

| Material | Precio | Unidad |
|----------|--------|--------|
| Caoba Fiji KD | ~13,800 | Pieza |
| Roble Americano | ~8,989 | Pieza |
| Cedro | ~22 | Pie tablar |
| Cola Blanca Lanco | ~481 | Galón |
| Laca Natural A1 | ~1,394 | Galón |

> **Nota**: Precios basados en el mercado dominicano 2024-2025

## 🛠️ Tecnologías

- HTML5 / CSS3
- JavaScript (ES6+)
- [jsPDF](https://github.com/parallax/jsPDF) - Generación de PDF
- [SheetJS](https://sheetjs.com/) - Exportación a Excel
- LocalStorage - Persistencia de datos

## 📄 Licencia

Este proyecto es de uso privado para talleres de ebanistería.

---

Desarrollado para el mercado de ebanistería de República Dominicana 🇩🇴
