# Gadolinium
Análisis de los datos experimentales de la temperatura y la magnetización espontáneas del Gadolinio en comparación con los datos test para diferentes momentos magnéticos para así, encontrar el momento magnético del Gadolinio Gd3+. Teóricamente sabemos que debe ser J=7/2.
##
Primero utilizaremos el Método Curve-Fitting comparando las curvas test con la curva del Gd3+ y comprobamos que nuestra muestra coincide con el momento magnético teórico(J=7/2).[gadolinio_cf]
##
Después utilizaremos un Análisis de Regresión de los sets de datos test con el del Gadolinio para ver cuál se ajusta mejor. Comprobaremos que, al no haber una relación lineal entre las variables, los modelos de regresiones lineales no darán buenos resultados(coeficientes de correlación r^2<0.9).[gadolinium_ra]
##
Por último utilizaremos un Análisis de Regresión Polinómica de los sets de datos test, estos datos predichos por el modelo se compararán con el del Gadolinio para ver cuál se ajusta mejor. Obtendremos mejores resultados que con las regresiones lineales.[gadolinio_rp]
