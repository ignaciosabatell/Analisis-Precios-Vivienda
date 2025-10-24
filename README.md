# Análisis de la relación entre el precio de la vivienda, los salarios, la inmigración y las hipotecas en España (2003–2022)

## Descripción del proyecto

Este proyecto analiza la evolución del mercado inmobiliario en España entre los años 2003 y 2022, centrándose en la relación entre los precios de la vivienda, los salarios, la inmigración y las hipotecas concedidas.  
El objetivo principal es observar cómo han evolucionado estas variables a lo largo del tiempo y detectar posibles desequilibrios entre el poder adquisitivo y el coste de la vivienda.

El trabajo incluye tanto un análisis a nivel nacional como por comunidades autónomas, con especial atención a la Comunidad de Madrid.

---

## Motivación

En un contexto donde los salarios han crecido a un ritmo mucho más lento que el precio de la vivienda, el acceso a un hogar se ha convertido en un reto creciente.  
Este proyecto busca cuantificar esa brecha y explorar cómo factores como la inmigración o la concesión de hipotecas han influido en la dinámica del mercado inmobiliario español.

---

## Estructura del proyecto

Analisis-Precios-Vivienda/
│
├── main.ipynb → Notebook principal con el análisis completo
├── Proyecto 3 IronHack.pdf → Documento resumen y presentación del proyecto
├── datos_unidos_meses.csv → Dataset combinado con información limpia
├── spain_salary_distribution.csv → Datos salariales por comunidad y año
├── ine.xlsx → Datos de vivienda, hipotecas e IPC
├── README.md → Descripción del proyecto
└── .gitignore → Exclusión de archivos innecesarios 

---

## Tecnologías utilizadas

- Python 3.10+  
- Pandas → limpieza y análisis de datos  
- Matplotlib / Seaborn → visualización  
- Jupyter Notebook → desarrollo y documentación  

---

## Principales resultados

- El precio medio de la vivienda ha aumentado de forma sostenida, con especial intensidad desde 2014.  
- Los salarios medianos han crecido de manera mucho más moderada, ampliando la brecha entre poder adquisitivo y coste de vivienda.  
- La población inmigrante se ha más que duplicado desde 2003 (+114%).  
- Las hipotecas concedidas se han reducido en torno a un 47%, reflejando un acceso más limitado al crédito.

---

## Conclusiones

Los resultados muestran una clara desconexión entre los salarios y el mercado inmobiliario, especialmente a partir de la recuperación posterior a la crisis financiera.  
El encarecimiento de la vivienda frente a un crecimiento salarial moderado ha reducido la capacidad de compra de los hogares.  
Además, el aumento de la inmigración y la disminución de las hipotecas indican un cambio estructural en la demanda y en las condiciones de acceso a la vivienda.

Este análisis puede servir como punto de partida para futuros estudios sobre accesibilidad, desigualdad económica y sostenibilidad del mercado inmobiliario en España.

---

## Cómo ejecutar el proyecto

Clona este repositorio:

```bash
git clone https://github.com/ignaciosabatell/Analisis-Precios-Vivienda
cd Analisis-Precios-Vivienda
```

Instala las dependencias:

```bash
pip install -r requirements.txt
```

Ejecuta los notebooks:

```bash
jupyter notebook notebooks/analisis_general.ipynb
```

---

## Autor

**Ignacio Sabatell López**  
Data Analytics · Ironhack  
Granada, España
