# 📊 Dashboard Cadena de Suministro Panovo - Power BI

Este repositorio contiene un ejemplo real de implementación de un dashboard de Power BI conectado a SQL Server, orientado a brindar visibilidad integral del desempeño de abastecimiento.

---

## 📌 Objetivo

Brindar visibilidad integral del desempeño de abastecimiento mediante indicadores clave como OTIF, Fill Rate de Proveedores, Negociación de Proveedores y Calidad del Inventario (clasificado por niveles de stock), con el fin de identificar desviaciones, asegurar la disponibilidad de materiales y optimizar la eficiencia operativa de la cadena de suministro.

---

## 🛠️ Tecnologías Utilizadas

- Power BI Desktop (DirectQuery)
- SQL Server (Consultas a vistas y tablas en producción)
- DAX (Medidas complejas para disponibilidad, eficiencia, forecast, etc.)
- GitHub (para control de versiones y documentación técnica)

---

## 📁 Estructura del Repositorio

```plaintext
CadenaSuministro_Panovo/
├── pbix/                                   → Archivo PBIX del tablero
├── docs/
│   ├── Medidas_Dax.md                      → Medidas DAX documentadas
│   ├── Columnas_Calculadas.md              → DAX documentadas
│   ├── Tablas_Catalogo.md                  → DAX documentadas
│   └── Instructivo Dashboard OEE.docx      → Guía de uso del dashboard
├── img/
│   ├── preview_dashboard.png               → Captura del dashboard
│   └── Modelo_Datos.png                    → Relación entre tablas
├── README.md                               → Descripción general del repositorio
```

---

## 📷 Preview del Dashboard

![Preview](img/preview_dashboard.png)

---

## 📎 Cómo utilizarlo

1. Clona este repositorio.
2. Abre el archivo `pbix/DA_CadenaSuministro1.pbix` con Power BI Desktop.
3. Conecta tu fuente de datos o consulta en SQL Server.
4. Revisa la documentación en `/docs` para entender cada fórmula y estructura.

