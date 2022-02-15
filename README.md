# Laboratorio8

# 1. OBJETIVOS

**General**

-Aplicar los conocimientos teóricos adquiridos sobre las señales senoidales y el osciloscopios a la realización de un conjunto de medidas de diferentes casos prácticos además de conocer alguna de las funciones más importantes del osciloscopio mediante el uso de Multisim

**Específicos**


-Determinar directamente el periodo y el voltaje de una señal.

-Determinar indirectamente la frecuencia de una señal.


# 2. MARCO TEÓRICO


# 3. EXPLICACIÓN DEL PROCEDIMIENTO

**MATERIALES**


**CIRCUITO ANALIZADO**

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/1.png)

**PROCEDIMIENTO**

**Ajuste el generador de funciones, para que proporcione una señal de 20 Vpp a una frecuencia de 2.5 Khz.**

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/2.png)

Con estos valores ajustamos el generador de funciones:

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/3.png)

Se comprueba que la señal es la correcta con el mismo osciloscopio: 

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/4.png)

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/5.png)

Como se ve, la división de voltaje es de 5 V, por lo tanto, el voltaje pico es de 10 V.

**Conecte el osciloscopio al resistor de carga RL. Observe la señal que aparece en el osciloscopio.**

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/6.png)

Ajustar las perillas tanto de amplitud como de tiempo para que sea más fácil el análisis de la onda seno.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/7.png)

# 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

**CUESTIONARIO**

**Responda las siguientes preguntas:**

-	¿Cuántas divisiones por cuadro abarca la amplitud pico de la señal de salida?

La amplitud pico de la onda abarca aproximadamente 3.4 divisiones por cuadro.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/8.png)

-	¿En qué valor está posicionada la perilla VOLTS/DIV?

La perilla está ubicada en 2V (voltios) por división.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/9.png)

-	¿Cuántas divisiones por cuadro abarca un ciclo completo de la señal de salida?

Un ciclo completo de la onda seno abarca 4 divisiones por cuadro.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/10.png)

-	¿En qué valor está posicionada la perilla TIME/DIV?

La perilla está ubicada en 100us (micro segundos) por cada división. 

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/11.png)

**¿Cuál es la amplitud de voltaje y el periodo de la señal que aparece en la pantalla del osciloscopio?**

Con la función “Cursor” se mueve la perilla hasta colocarla en el pico de la onda seno.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/12.png)

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/13.png)

De esta manera se determina la amplitud de voltaje (Voltaje pico) que es de 6.82 V. 

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/14.png)

Con la misma función activa se selecciona el eje “x” y se coloca en el punto donde se completa un ciclo.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/15.png)

Así se determina que el periodo es de 392.48 us, recordando que hay que restar el valor que se encuentra en las divisiones por cuadro debido a que al inicio se colocó de manera que sea más fácil analizar la onda seno.

392.48 us-(-7.52 us) = 400 us  

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/16.png)

Para conocer los datos exactos se utiliza la función “Quick Meas” y seleccionamos los valores que se necesitan medir con la botonera de la parte inferior de la pantalla.

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/17.png)

Así se observa que los valores arrojados por el osciloscopio son:
Amplitud de voltaje: 6.83 V
Periodo: 400 us

**Determine la frecuencia natural (Hz) y la frecuencia angular (rad/s) de la señal de salida.**

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/18.png)

**Con el multímetro digital mida el voltaje de salida en RL:**

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/19.png)

El voltaje en RL es de 4.86 V

**Compare el voltaje medido por el osciloscopio y el obtenido en el multímetro ¿Coinciden? ¿Por qué?**

No coinciden, debido a que el voltaje que se muestra en el osciloscopio es el valor pico mientras que en el multímetro es el valor RMS (Valor efectivo), que se obtiene mediante la siguiente ecuación:

![](https://github.com/bavargas5/Laboratorio8/blob/main/IMG%20BV/20.png)

# 5. VIDEO


# 6. CONCLUSIONES

Tal y como hemos podido comprobar el osciloscopio que se encuentra en Multisim es básicamente un dispositivo de visualización gráfica que muestra señales eléctricas variables en el tiempo, en el eje vertical representa el voltaje; mientras que el eje horizontal representa el tiempo.

# 7. BIBLIOGRAFÍA
