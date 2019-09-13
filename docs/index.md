---
title: "index"
author: "John A. G. M"
date: "13 de septiembre de 2019"
output:
  html_document: default
  pdf_document: default
---
# Perfil

Doctor en Tecnología Química de la Universidad Nacional del Litoral, con pregrado en ingeniería electrónica de la Universidad de Antioquia. Durante el proceso de formación académica ha participado en varios proyectos de investigación -tanto a nivel de pregrado como posgrado-, en lineas relativas a las telecomunicaciones, el control automático,matemáticas aplicadas y cálculo numérico. En 2012 obtuvó una beca para estudios doctorales con el Consejo Nacional de Investigaciones Científicas y Técnicas (CONICET),con la cual investigó en temas de control óptimo en aplicaciones a la industria química.Además, cuenta con experiencia en investigación, elaboración y desarrollo de proyectos, facilitación en la apropiación social de ciencia tecnología e innovación. Ha publicado cuatro artículos en revistas internacionales, con participación en siete congresos a nivel nacional  y  uno  a  nivel  internacional.  Además,  cuenta  con  experiencia  docente  en distintas  instituciones  (Universidad  Nacional  del  Litoral,  Universidad  de  Antioquia,Institución universitaria Pascual Bravo y la corporación de estudiante universitarios y profesionales de Marinilla), en los cuales ha impartido cursos de: Sistemas de control continuo, fabricación asistida por computadora, Álgebra lineal, Cálculo multivariable, Desarrollo de software, Electrónica, inteligencia artificial y big data. Los principales aportes y contribuciones se basan en una fundamentación teórica para calcular el control óptimo de sistemas con ciertas restricciones y la forma en que puede ser aplicado a diferentes procesos de ingeniería, con especial énfasis en la exploración del uso de computación en paralelo para el tratamiento numérico de problemas que surgen en las aplicaciones. En la generación y validación de resultados tanto para sistemas lineales como para sistemas no lineales que presentan limitaciones físicas en la variable de control.

Sumado  a  esto,  la  experiencia  en  la  ejecución  de  trabajos  de  ingeniería  como  la sistematización de la pinacoteca y el sistema de votación electrónica para la corporación concejo de Marinilla [github](https://github.com/GomezMunera/anderson).

## Objetivo General
 Describir los movimientos espaciales y demás atributos de manipuladores,  sus condiciones estáticas y dinámicas como máquinas, el diseño y la evaluación de algoritmos de control para que éstos realicen movimientos deseados con  fuerzas limitadas, observadas desde sensores y aplicadas de forma controlada en actuadores


!!! note "Objetivos Especificos:"
    • Conocer la cinemática y la dinámica de un manipulador.

    • Describir matemáticamente los movimientos espaciales y demás atributos de un manipulador.

    • Diseñar y evaluar algoritmos para realizar movimientos controlados en un manipulador.

    • Programar dispositivos para la ejecución de algunas tareas deseadas.


> Ojetivos especificos

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Pruebas de ecuaciones

When \(a \ne 0\), there are two solutions to \(ax^2 + bx + c = 0\) and they are
$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a}. $$

Se pretende minimizar un funcional de costo cuadrático para un problema de
horizonte finito con estados finales libres de la forma

\(x_{i} \)
$x_{i}$

$$ x_{i} $$

\begin{equation}
 \left(\frac{1}{n} \right)^2
\end{equation}

sujeto a la siguiente restricción dinámica
\begin{equation}
\dot{x}(t)=f(x(t),u(t)),\text{  }x(0)=x_{0},
\end{equation}

\begin{equation}
	\sum_{i=1}^n X_i
\end{equation}
			$\sum_{i=1}^n X_i$


\begin{eqnarray}
\dot{x} &=&\text{ }\frac{\partial H^{0}}{\partial \lambda }(x,\lambda )\text{
};\;x(0)=x_{0}\;,  \label{x-prime} \\
\dot{\lambda} &=&-\frac{\partial H^{0}}{\partial x}(x,\lambda )\text{ };\;\lambda (t_{f})={}{}{}{}\left( \frac{\partial \mathcal{K}}{\partial x}\right) ^{\prime }(x(t_{f})),  \label{l-prime}
\end{eqnarray}


## Primer programa

	#!c
	#include <stdio.h>

	void main()
	{
	    printf("Hola mundo!!!");
	}



## Variables

Las variables son contenedores que podemos utilizar en nuestro programa para guardar datos. Una variable solo puede guardar un dato de un determinado tipo. Utilizaremos tres tipos de datos básicos: números enteros, números con decimales y carácteres.

|Tipo de dato|Nombre    |Ejemplo|
|------------|----------|-------|
|entero      |int       |14     |
|fraccionario|float     |25.32  |
|carácter    |char      |'m'    |

Podemos utilizar cualquier nombre para las variables siguiendo las siguientes normas:


La estructura **if** consiste en la palabra clave **if** seguida de una expresión condicional entre paréntesis. A continuación viene un bloque de código entre llaves. Si la condición se cumple (es cierta) el bloque de código se ejecuta. Si la condición no se cumple (es falsa) el programa salta el bloque de código y continua.

	:::c
	if(condicion)
	{
		// Bloque si la condición se cumple
	}
	else
	{
		// Bloque si la condición no se cumple
	}


## Including Plots

You can also embed plots, for example:
