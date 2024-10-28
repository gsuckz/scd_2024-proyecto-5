# Sistemas de Comunicaciones Digitales - Proyecto 5

## Introduccion
Se exponen resultados basicos de transformada de Fourier de señales de energia finita. Se resuelven algunas transformadas importantes en el contexto de las modulaciones digitales, *pulso rectangular*, *pulso conseno elevado* y *pulso raiz de coseno de elevado*. Se desarrollan los conceptos de ancho de banda necesario, condicion de *cero interferencia entrer simbolos* y se analiza esta ultima para una señal 2-PAM, con *filtro adaptado* y filtro LP de 1° Orden con pulsos de las formas resueltas.

## Resumen 

## Desarrollo

### Transformada de Fourier de Señales de energía finita
Se dice que la señal es de energía finita cuando la siguiente integral impropia existe:

$$ E_f = \int_{-\infty}^{\infty}{|f(t)|^2 dt} $$
En este caso al valor de $E_f$ se le llama *"Energía de la señal"*. (Oppenheim, Alan y Willsky, Alan (1996). Capitulo 1.Signals and Systems, Prentice Hall)

Una señal de energía finita es aquella que es limitada en tiempo y amplitud, es decir:
$$\text{Sea f una funcion que describe la señal, f es de energia finita } \iff \exist a \in \real, X \subset \real :\forall \space x \in X, f(x) \leq a \land \forall x \notin X, f(x) = 0$$

Esta definicion excluye las señales infinitas en el tiempo (una sinusoidal eterna) y al impulso, todas las señales fisicas observadas son de energía finita.

Una señal de energía finita, al ser limitada en el tiempo, sera ilimitada en frecuencia (aunque el cuadrado de su tranformada de Fourier sea integrable), como el proceso de hallar la antitransformada es similar al de la transformada, podemos ver que las señales limitadas en frecuencia, no lo estan en el tiempo.


Es posible aproximar una fcion no limitada en frecuencia, por funcione que si lo esten.

Capitulo 4 Gallager

Plancherel aproximacion energia 





## Conclusiones

## Referencias

