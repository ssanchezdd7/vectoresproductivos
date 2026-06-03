# 📊 Vectores productivos provinciales y proveedores locales en mineria

Dashboard ejecutivo en HTML para analizar la matriz productiva provincial argentina, la capacidad proveedora relativa y los posibles encadenamientos con la mineria.

El proyecto esta pensado como una pagina estatica: no requiere backend, instalacion ni proceso de compilacion.

## 🌐 Demo online

Ver el dashboard publicado en GitHub Pages:

[https://ssanchezdd7.github.io/vectoresproductivos/](https://ssanchezdd7.github.io/vectoresproductivos/)

## 💻 Demo local

Abrir el archivo:

```text
index.html
```

Tambien puede publicarse directamente con GitHub Pages si `index.html` queda en la raiz del repositorio.

## ✨ Caracteristicas

- 🧭 Dashboard interactivo de una sola pagina.
- 🔎 Filtros por provincia, periodo, vector proveedor y perfil de impacto.
- 📌 Indicadores KPI para VAB seleccionado, capacidad proveedora, comparacion contra el maximo anual y participacion minera provincial.
- 📈 Graficos de estructura productiva, evolucion temporal, ranking provincial y principales ramas economicas.
- 📚 Glosario metodologico con conceptos, formulas, vectores, ramas y fuentes.
- 🌎 Interfaz multilingue en espanol, ingles y portugues.
- 📦 Datos embebidos en el propio HTML para facilitar su distribucion.

## 🛠️ Tecnologias

- 🧱 HTML, CSS y JavaScript vanilla.
- 📊 Chart.js para visualizacion de graficos.
- 🧮 MathJax para renderizar formulas metodologicas.

Las librerias externas se cargan desde CDN, por lo que se necesita conexion a internet para ver correctamente los graficos y formulas la primera vez.

## 🗂️ Estructura sugerida del repositorio

```text
.
+-- index.html
`-- README.md
```

## 🚀 Uso

1. 📥 Clonar o descargar el repositorio.
2. 🌐 Abrir `index.html` en un navegador moderno.
3. 🔎 Seleccionar provincia, rango de anos, vector proveedor y perfil de impacto.
4. 🌎 Cambiar el idioma desde el control de idioma disponible en el dashboard.
5. 📚 Consultar el glosario metodologico para ver definiciones, formulas y correspondencias sectoriales.

## 📖 Fuentes

- CEPAL y Ministerio de Economia de la Argentina (2022). "Desagregacion provincial del valor agregado bruto de la Argentina, base 2004".
- Schteingart, D. y Allerand, M. (2021). "El impacto de la mineria argentina en los proveedores locales".
- Archivo de trabajo: Jurisdiccion 52 sectores CEPAL-IIEE.

## 🧪 Nota metodologica

La capacidad proveedora es un indicador sintetico experimental que aproxima la capacidad relativa de una provincia para capturar demanda minera mediante proveedores locales.

Los vectores productivos son agregados analiticos de ramas CEPAL-MECON. No constituyen una clasificacion estadistica oficial, sino una homologacion funcional para lectura de politica publica y analisis comparativo.

## 👤 Autoria

Elaboracion analitica de Silvana Sanchez Di Domenico.

LinkedIn: [Silvana Sanchez Di Domenico](https://www.linkedin.com/in/silvana-s%C3%A1nchez-di-domenico/)

## ⚖️ Licencia

Creative Commons Zero v1.0 Universal
