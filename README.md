### Mentoria 2021

## Repositorio de la mentoría

# Selección de cripto activos para un cartera de inversión

En el mundo de las finanzas tradicionales, el desempeño de diferentes activos podría variar bajo diferentes condiciones de mercado. Es entonces cuando entra en juego la diversificación. El objetivo principal de la exposición a diferentes clases de activos es equilibrar el riesgo y el rendimiento de una cartera. 

Cuando hablamos de criptomonedas, la diversificación también podría ser una de las formas de gestionar la exposición al riesgo. Sin embargo, la alta correlación entre algunos activos dificulta la selección de una cartera equilibrada. A pesar de ello, con una cesta cuidadosamente seleccionada, de monedas alternativas, junto con algunas monedas estables, se podría invertir en el mercado de manera más efectiva con un riesgo manejable. Por lo cual, el objetivo principal de este proyecto es determinar una forma de seleccionar algunos activos para nuestra cartera, tomados de un conjunto más amplio, según los momentos de mercado.

En un mercado con una alta volatilidad, es necesario comprender los riesgos de la exposición y poder cubrirse de posibles pérdidas significativas. Además, contar con una cartera acorde a cada inversor (según su aversión al riesgo) permite una participación más heterogénea en este tipo de mercados. Desde el punto de vista de los datos, se trabajará con series de tiempo, y veremos que este tipo de datos requieren un tratamiento específico.

¡Espero que te interese el desafío y aprendamos mucho en el camino!

## Detalles

En el archivo [dataset.csv](https://github.com/sergiobuzzi/MentoriaDiplodatos2020/blob/master/dataset.csv) se proveen datos sobre los valores de cierre diario de 11 índices bursátiles (aproximadamente 19 años), y series de tipos de cambio para efectuar el análisis en una moneda común. Dicho dataset también contiene una serie de dolar "blue" para ajustar el tipo de cambio de Argentina en épocas de cepo cambiario.

Luego se presentan carpetas en las cuales se irán cargando los enunciados y soluciones de cada uno de los trabajos prácticos. A continuación se plantean los posibles contenidos generales a desarollar en los mismos:

#### TP1: Análisis y Visualización (29/6)

Exploración de la base de datos. Medidas de Estadística Descriptiva. Gráficos de evolución temporal. Identificación de outliers "comunes" vs. identificación de outliers temporales. Cálculo de correlaciones. Intuición básica del concepto de raíz unitaria.

#### TP2: Análisis y Curación de Datos (19/7)

Curación de la base de datos. Imputación de faltantes. Reconstrucción de serie de tipo de cambio de Argentina. Expresión de los índices en moneda común. Transformaciones de los datos.

#### TP3: Introducción al Machine Learning (16/8)

Separación de datos en entremamiento, validación y test. Aplicación de metodos simples de ML para regresión univariante. Selección de métrica. Selección de hiperparámetros. Comparación de resultados.

#### TP4: Aprendizaje Supervisado (13/9)

Estimación de modelos de serie temporales univariados y multivariados (ARMA y VAR). Estimación usando LSTM. Comparación. 

#### TP5: Aprendizaje No Supervisado (27/9)

Aplicacion de algoritmos de clustering de series de tiempo.

#### Presentación Final (6/11 - 7/11) 

Ideas: Combinación de modelos de la literatura específica de series temporales (ARMA - VAR - VECM) con LSTM. Presentación de los resultados de los prácticos.


