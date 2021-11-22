![banner](bin/cropped-logo-fcfm-die-1.png)  
# Proyecto de clasificación supervisada de SuperNovas para el curso EL4106  
Integrantes : Joaquin Zepeda, Benjamin Irarrazabal  
Tutor : Pablo Montero   
**Instrucciones para ejecutar el código:**  
1.	Para la **extracción de características** se debe ejecutar el archivo SN_feature_extraction.ipynb  
  1.1.	Si se ejecuta utilizando jupyter notebook es necesario tener instaladas las librerías de Alerce, esto puede ser complicado si es que no se trabaja en un ambiente de Linux.  
  1.2.	Si se ejecuta utilizando Google Colab, se debe ejecutar el “Bloque inicial”, luego reiniciar el entorno de ejecución (Reiniciar el kernel) para luego ejecutar los bloques.            py```
          # pyarrow might be needed to read the data  
          !python -m pip install Cython  
          
          !python -m pip install -e git+https://git@github.com/alercebroker/turbo-fats#egg=turbofats
          
          !python -m pip install -e git+https://git@github.com/alercebroker/mhps#egg=mhps  
          
          !python -m pip install -e git+https://git@github.com/alercebroker/P4J#egg=P4J  
          
          !python -m pip install pyarrow
          
          !python -m pip install -e git+https://git@github.com/alercebroker/lc_classifier#egg=lc_classifier  
          ```

2.	Para la **clasificación de supernovas utilizando Random Forest** se debe ejecutar el archivo Clasificación de Supernovas RF.ipynb.   
    2.1.1.	 No se recomienda ejecutar los bloques de “Random Forest Hyperparameter tuning” pues estos toman mucho tiempo, pero es posible observar los resultados.
3.	Para la **clasificación de supernovas utilizando una red MLP** se debe ejecutar el archivo Clasificación de Supernovas MLP.ipynb.   
  
