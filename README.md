# 🏠 Airbnb Madrid: Análisis Exploratorio y Dashboard

---

## 📖 Descripción del Proyecto

Este proyecto realiza un análisis exploratorio del mercado de alquiler turístico a corto plazo en Madrid, utilizando datos reales de [Inside Airbnb](http://insideairbnb.com/get-the-data). El objetivo es comprender la estructura del mercado identificando patrones de precios, tasas de ocupación e ingresos estimados por distrito y tipo de alojamiento, con especial foco en detectar oportunidades de inversión inmobiliaria por zonas.

El análisis incluye limpieza y transformación de datos, análisis descriptivo a nivel de distrito y barrio, y la construcción de un dashboard interactivo con segmentaciones dinámicas.

---

## 🗂️ Estructura del Proyecto

```
├── Mercado_Airbnb_en_Madrid_Analisis_exploratorio_y_dashboard.xlsx
│   ├── DDBB_AirBnB_Madrid        # Dataset limpio con columnas calculadas
│   ├── Contadores                # Control de calidad y resumen del dataset
│   ├── Limpieza y vista general  # Estadísticos principales y parámetros de limpieza
│   ├── Distrito y barrio         # Análisis por distrito y barrio
│   ├── Tipo de alojamiento       # Análisis por tipo de alojamiento
│   ├── Analisis de demanda       # Ocupación, ingresos y perfil de estancia
│   ├── Graficos y tablas DB      # Tablas empleadas para el dashboard
│   └── DashBoard                 # Dashboard interactivo con slicers
├── README.md                     # Descripción del proyecto
```

---

## 🛠️ Instalación y Requisitos

Este proyecto está desarrollado íntegramente en **Microsoft Excel** y no requiere instalación de software adicional.

**Requisitos:**
- Microsoft Excel 2016 o superior (para compatibilidad con slicers y tablas dinámicas)
- Los datos provienen de http://insideairbnb.com/get-the-data — archivo `listings.csv` de Madrid (2025)

**Para abrir el proyecto:**
1. Descarga el archivo `.xlsx`
2. Ábrelo con Microsoft Excel
3. Habilita el contenido si aparece un aviso de seguridad
4. Navega a la pestaña `DashBoard` para ver el análisis interactivo

---

## 📊 Resultados y Conclusiones

### Dataset
- **Registros originales:** 25.094
- **Registros tras limpieza:** 18.684
- **Cobertura:** 21 distritos, 128 barrios de Madrid

### Hallazgos principales

**Mercado general:**
- Precio medio por noche: **133€** — mediana: **110€**
- Tasa de ocupación media estimada: **41,7%**
- Ingreso mensual medio estimado: **1.633€**

**Por tipo de alojamiento:**

| Tipo | Listings | % Total | Precio medio |
|---|---|---|---|
| Vivienda completa | 13.537 | 72,5% | 159€ |
| Habitación privada | 4.961 | 26,6% | 67€ |
| Otros | 186 | 1,0% | 63€ |

> 7 de cada 10 listings son viviendas completas — el mercado está orientado al alquiler de inmueble entero.

**Top 5 distritos por ingreso mensual estimado:**

| Distrito | Precio medio | Ocupación | Ingreso mensual |
|---|---|---|---|
| Salamanca | 178€ | 42,9% | 2.303€ |
| Centro | 156€ | 43,7% | 1.991€ |
| Chamberí | 137€ | 40,0% | 1.618€ |
| Retiro | 128€ | 39,3% | 1.418€ |
| Chamartín | 127€ | 36,4% | 1.388€ |

**Por perfil de estancia:**

| Perfil | Listings | % Total | Precio medio |
|---|---|---|---|
| Turismo (1–6 noches) | 14.674 | 78,5% | 139€ |
| Mensual (30+ noches) | 2.597 | 13,9% | 108€ |
| Estancia media (7–29 noches) | 1.413 | 7,6% | 119€ |

### Conclusiones

1. **Centro concentra el 42,8% de la oferta** con 7.988 alojamientos. Demanda de perfil turístico con una ocupación del 43,7%.
2. **Salamanca es el distrito más rentable** — combina el precio más alto (178€/noche) con una sólida ocupación (42,9%).
3. **Barajas destaca por rotación** — precio bajo (107€) pero 137 reseñas de media por listing y 4,93 reseñas/mes (casi 3x la media de la ciudad), impulsado por la proximidad al aeropuerto.
4. **Moratalaz tiene la mayor ocupación** (55%) pero ingresos moderados (1.110€) por precio contenido.
5. **El mercado es fundamentalmente turístico** — el 78,5% de los listings admite estancias de hasta 6 noches.

---

## 🔄 Próximos Pasos

- Incorporar datos de precio de compra por distrito (fuente: Idealista €/m²) para calcular la rentabilidad bruta real de inversión
- Ampliar el análisis con datos históricos de Inside Airbnb para capturar variación estacional
- Comparar el mercado de Madrid con otras ciudades españolas (Barcelona, Sevilla, Valencia)
- Desarrollar un índice de atractivo inversor por barrio combinando precio, ocupación y competencia

---

## 🤝 Contribuciones

Las contribuciones son bienvenidas. Si deseas mejorar el análisis o el dashboard, puedes contactar con el autor o abrir una sugerencia en el repositorio.

---

## ✒️ Autor

- **Dani Asencio Roig** — Análisis, limpieza de datos y dashboard


