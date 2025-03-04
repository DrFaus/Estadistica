El siguiente dataset viene con la siguiente información:

About Dataset
This dataset captures various metrics from exercise sessions, including heart rate (pulse), maximum heart rate (maxpulse), duration, and calories burned. It is ideal for analyzing patterns in fitness performance, exploring relationships between heart rate and calorie expenditure, or building predictive models for health and exercise.

Attributes:

Duration: Length of the workout session (in minutes).
Pulse: Average heart rate during the session (in beats per minute).
Maxpulse: Maximum heart rate reached during the session (in beats per minute).
Calories: Estimated calories burned during the session.
Teniendo esto realiza lo siguiente:

a) Sube la base de datos a tu repositorio e importala a colab mediante pandas. Agrega una línea adicional:

df.dropna(inplace = True) 

para eliminar los registros con valores faltantes. Posteriormente, elige una variable dependiente y una independiente.

b) Realiza un gráfico con la dispersión y la recta de regresión ajustada. 

c) Calcula el coeficiente de correlación y el coeficiente de determinación e interpreta los resultados.

d) Obtén un intervalo de confianza de 98% para la pendiente e interpreta el resultado. Respalda tu conclusión usando ANOVA.

e) Verifica los supuestos. 



Nota: El examen debe estar en el orden que se enlista en los incisos. No debe mostrarse información de más o en un orden alternativo.
