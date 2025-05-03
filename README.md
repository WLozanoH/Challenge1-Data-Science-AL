# 🛍️ Análisis de Desempeño de Tiendas y Ventas Geográficas

Este proyecto analiza el desempeño de cuatro tiendas ficticias con base en sus datos de ventas, calificaciones, productos vendidos y ubicación geográfica. Se aplicaron técnicas de análisis exploratorio, visualización y limpieza de datos con Python.

## 📌 Objetivos

- Comparar calificaciones promedio por tienda.
- Identificar los productos más y menos vendidos por tienda.
- Evaluar el costo promedio de envío por tienda.
- Analizar el desempeño de las ventas en función de la ubicación geográfica usando coordenadas (lat, lon).

## 📁 Estructura del proyecto

```
├── data/
│   ├── tienda1.csv
│   ├── tienda2.csv
│   ├── tienda3.csv
│   └── tienda4.csv
├── notebooks/
│   └── analisis_tiendas.ipynb
├── README.md
└── requirements.txt
```

## 🧪 Tecnologías y librerías utilizadas

- Python 3.10+
- Pandas
- Seaborn
- Matplotlib
- Plotly (opcional para mapas interactivos)
- Folium (opcional para análisis geoespacial)

## ⚙️ Instalación

1. Clona este repositorio:

```bash
git clone https://github.com/WLozanoH/Challenge1-Data-Science-AL.git
cd AluraStoreLatam
```

2. Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv env
source env/bin/activate  # En Windows usa: env\Scripts\activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

## 🚀 Cómo ejecutar el proyecto

Abre el notebook:

```bash
jupyter notebook notebooks/AluraStoreLatam.ipynb
```

Sigue las celdas para visualizar:

- Gráficos de barras de calificaciones promedio por tienda.
- Barras horizontales con productos más vendidos (top 5) por tienda.
- Análisis del costo de envío.
- Mapas de calor y gráficos de dispersión geográficos de las ventas.

## 📊 Principales análisis

- **Calificaciones promedio**: Visualización ordenada de las tiendas según desempeño de clientes.
- **Productos top y flop**: Agrupación de los productos más y menos vendidos por tienda, con subgráficos.
- **Costo de envío**: Comparación clara entre tiendas y su logística.
- **Análisis geográfico**: Mapas que revelan concentración de ventas según latitud y longitud.


## 👨‍💻 Autor

**Wilmer Lozano** – [LinkedIn](https://www.linkedin.com/in/wilmerlozanohuaman/) | [GitHub](https://github.com/WLozanoH)

---

Este README está diseñado para que reclutadores o colaboradores entiendan rápida y fácilmente el propósito y ejecución del proyecto.