# 🏠📊 Análisis de la relación entre el precio de la vivienda, los salarios, la inmigración y las hipotecas en España (2003–2022)

## 📘 Descripción del proyecto

Este proyecto analiza la evolución del mercado inmobiliario en España entre los años **2003 y 2022**, centrándose en la relación entre **los precios de la vivienda**, **los salarios**, **la inmigración** y **las hipotecas concedidas**.  
El objetivo principal es observar cómo han evolucionado estas variables a lo largo del tiempo y detectar posibles **desequilibrios entre el poder adquisitivo y el coste de la vivienda**.

El trabajo incluye tanto un análisis **a nivel nacional** como **por comunidades autónomas**, con un enfoque especial en la Comunidad de Madrid.

---

## 🧠 Motivación

En un contexto donde los salarios han crecido de forma más moderada que el precio de la vivienda, el acceso a la vivienda se ha convertido en un reto creciente.  
Este proyecto busca **cuantificar esa brecha**, además de explorar cómo otros factores como la inmigración o la concesión de hipotecas influyen en la dinámica económica del país.

---

## 📂 Estructura del proyecto

## 🧰 Tecnologías utilizadas

- **Python 3.10+**
- **Pandas** → limpieza y análisis de datos  
- **Matplotlib / Seaborn** → visualización de resultados  
- **Jupyter Notebook** → desarrollo y documentación del análisis  

---

## 📈 Principales resultados

- 📊 **El precio medio de la vivienda** ha aumentado de forma constante, especialmente tras 2014.  
- 💶 **Los salarios medianos** muestran un crecimiento mucho más moderado, lo que ha ampliado la brecha entre poder adquisitivo y coste de vivienda.  
- 🧍‍♂️ **La población inmigrante** se ha más que duplicado desde 2003 (+114%).  
- 🏦 **Las hipotecas concedidas** se han reducido en torno a un **47%**, evidenciando un endurecimiento del acceso al crédito.  

### Ejemplo de gráfico generado:

```python
plt.title('Evolución nacional del precio de la vivienda y del salario mediano')
plt.xlabel('Año')
plt.ylabel('Valor medio (€)')

📊 Conclusiones

La evidencia obtenida refleja una desconexión entre los salarios y el mercado inmobiliario, agravada tras la crisis financiera y la recuperación posterior.
El crecimiento del precio de la vivienda supera con creces el de los ingresos, reduciendo la capacidad de compra de los hogares.
Además, el aumento de la inmigración y la caída de las hipotecas apuntan a un cambio estructural en la demanda y el acceso a la vivienda.

Este proyecto busca servir como punto de partida para futuros análisis sobre accesibilidad, desigualdad económica y sostenibilidad del mercado inmobiliario en España.


🚀 Cómo ejecutar el proyecto

Clona este repositorio:

git clone [https://github.com/ignaciosabatell/Analisis-Precios-Vivienda[
cd proyecto_vivienda


Instala las dependencias:

pip install -r requirements.txt


Ejecuta los notebooks:

jupyter notebook notebooks/analisis_general

👨‍💻 Autor
Ignacio Sabatell López
