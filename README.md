# Acerca del proyecto:  
Este proyecto consiste en clasificar una transacción electronica como "Fraude" o "No fraude". Para resolver este problema se usaron datos en que sus clases están desbalanceadas. Por lo tanto, se deberán aplicar métodos apropiados para este contexto, como undersampling, oversamplig utilizando un muestreo aleatorio con repetición y SMOTE(un método que genera artificialmente nuevos datos de la clase minoritaria). Además, se usaron algoritmos de ML enfocados en este tipo de problemas como random forest y SVC para datos desbalanceados entre otros. Los atributos que se tienen para resolver este problema son:
- intervalo de tiempo,
- cliente,  
- edad cliente,  
- sexo,  
- ubicación cliente,
- vendedor,
- ubicación vendedor,
- área de servicio o producto,
- monto de transacción,
- y obviamente, si es fraude o no la transacción.

Para este problema se hicieron estudios de los datos, se eliminaron "variables independientes" que no explicaban la variable dependiente y se aplicaron distintos métodos de machine learning.  

Fuente data:  
https://www.kaggle.com/datasets/ealaxi/banksim1?select=bs140513_032310.csv

# Nota importante:  
Este proyecto fue generado a partir de Python v3.11 y se utilizaron las librerias que están en el archivo last_requirements.txt. Para el código del proyecto se debe generar un entorno, a continuación se muestra como:  

Paso 1) Abrir una terminal (powershell):

Paso 2) Crear un entorno virtual en cierto lugar:  
```bash
python3.11 -m venv NombreEnv
```

Paso 3) Para cargar el entorno debe ejecutar el archivo activate que está en la siguiente dirección:
```bash
.\NombreEnv\Scripts\Activate
```

Paso 4) Una vez cargardo el entorno debe instalar las librerias necesarias, estas están en el archivo last_requirements.txt.
Para instalar las librerias del archivo last_requirements.txt debe estar en el directorio del archivo y ejecutar:  
```bash
 pip install -r requirements.txt
```

Paso 5) Para que el sistema reconozca el kernel creado debe ejecutar los siguientes comandos:  
```bash
pip install ipykernel
python -m ipykernel install --user --name=NombreEnv
```

Paso 6) Luego, puede ejecutar jupyter notebook y listo.
```bash
 jupyter notebook
```
