# TAREA3

*******************************************************
******** PUNTO 1 - INSTALAR Y CORRER CÓDIGO ***********
*******************************************************

# TOMANDO EN CUENTA QUE SE TIENE ANACONDA O CONDA INSTALADO
# SI SE TIENE INSTALADO CON EL PATH INCLUIDO EN EL PATH DE
 WINDOWS SE PUEDE DESDE CMD
# SI EL PATH NO FUE INCLUIDO, ENTONCES ABRIR UNA CONSOLA
 DESDE LA INSTALACION DE CONDA/ANACONDA

# PRIMERO CREAR VIRTUAL ENV

	conda create -n tarea3
	
	# Se genera directorio
	 ../tarea3

# ACTIVAR V ENV

	conda activate tarea3

# INSTALAR LIBERERÍAS 

	conda install pip
	pip install gensim
	pip install matplotlib
	pip install nltk
	pip install pandas
	pip install typing
	pip install jupyter
	pip install notebook
	pip install "spacy[lookups]"

	# OPCIONAL / NO NECESARIO / TOMA MUCHO TIEMPO

	# python -m spacy download en_core_web_trf
	# python -m spacy download es_dep_news_trf

	# pip install -r requirements
	# pip install ipykernel # to use an existing jupytar installation
	# conda install -n base nb_conda_kernels

# INGRESAR AL DIRECTORIO DEL PROYECTO DE SCRAPY

	# cd C:\Users\chris\anaconda3\envs\tarea3
	cd ..\tarea3

# CORRER LOS NOTEBOOKS

	cd notebooks
	dir
	jupyter notebook sentimentAnalysis.ipynb

# FINALIZAR

	conda deactivate

# RETOMAR

	conda activate tarea3
