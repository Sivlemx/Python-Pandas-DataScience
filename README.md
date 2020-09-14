![PsyPy](https://github.com/Sivlemx/Intro-Python-DataScience/raw/master/Python%20Course.png)

# Pandas Python para Psicólogos 🐼
## Javier Villanueva-Valle
<javier830409@gmail.com>

Para llegar a este curso deberás tomar este otro [Picale aquí](https://github.com/Sivlemx/Intro-Python-DataScience) de lo contrario tendrás dificultades para entender este curso. Si ya lo tomaste, ya la hiciste. 👍🏼

Para leer este documento con extensión *.md, te recomiendo usar
[**MacDown** para OS](https://macdown.uranusjr.com/), [**Typora** para Windows](https://typora.io/#windows) o [**Remarkable** para Linux y Windows](https://remarkableapp.github.io/linux.html)

~~~
	Saber que tenemos dentro de nuestro Anaconda
conda info --envs

	Crear ambientes
conda create --name "el-nombre-que-yo-quiera"
conda info --envs
conda activate "el-nombre-que-yo-quiera"

	Actualizar el ambiente
conda update conda
conda update anaconda
conda update --all -y

	Revisar que todo esté bien
conda list

	Liberías necesarias para hacer cositas
conda install pandas numpy matplotlib seaborn xlrd openpyxl -y
conda install -c conda-forge statsmodels notebook jupyterlab -y
pip install tqdm

	Para observar datos y generar reportes [Pandas Profiling](https://pandas-profiling.github.io/pandas-profiling/docs/master/)
conda install -c conda-forge pandas-profiling

	Para pruebas post hoc
pip install scikit-posthocs

	Revisión de nuestras librerías
conda list
~~~

### Manejo, manipulación y organización de listas, tuplas y diccionarios de bases datos tanto de creación propia como manipulación de bases reales.

#### Uso de funciones
* Para Estructura
	* DataFrame()
	* Series()
	* iloc[]
	* loc[]
	* columns
	* index
	* lambda()
	* def()
	* array()
	* nan()
	* ramdon()
	* arange()
	* groupby()([])

* Trabajar con dos o mas bases de datos
	* concat([])
	* merge()
	* append()

#### Estadística
* Descriptiva
	* mean()
	* std()
	* err()
	* median()
	* min()
	* max()
	* percentiles

* Inferencial
	* De acuerdo a la base de datos a analizar es la estadística a aplicar.

#### Visualización
* plt.plot()
* pd.plot()
* la mayoría de las diferentes gráficas a plotear.

Entre tantas otras funciones.