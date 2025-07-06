# Yield Curve Interpolation With Cubic Splines

This project implements a cubic spline interpolation method to estimate interest values for different tenors, even if they are not found within the original data. 
My script is designed to take a set of tenors (X) and their corresponding interest values (Y, for this example the TIIE), and calculate the coefficients of the cubic polynomials that connect the points. 
To facilitate the calculations, the 'Tenor' column expresses the date as a numerical value. This format is essential for the interpolation algorithm to work correctly with the data.



Este proyecto implementa un método de interpolación cúbica para estimar valores de interés para distintos plazos, incluso si no se encuentran dentro de los datos originales. 
Mi script está diseñado para tomar un conjunto de plazos (X) y sus correspondientes valores de interés (Y, para el ejemplo la TIIE) y calcular los coeficientes de los polinomios cúbicos que conectan a los puntos. 
Para facilitar los cálculos, la columna 'Plazo' expresa la fecha como un valor numérico. Este formato es indispensable para que el algoritmo de interpolación funcione correctamente con los datos.
