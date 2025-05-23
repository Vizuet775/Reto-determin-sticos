# Avance para Modelo de la Cortadora
Partiendo de las Ecuaciones

$I_t\ddot{\theta} = \tau_M - b\dot{\theta}rsin(\pi-\phi)$

$\phi = arctan(\frac{b}{m\dot{\theta}l})$

Se hizo un codigo que permitiese resolver las ecuaciones con sistemas de ecuaciones diferenciales, permitiendo obtener los resultados visuales de las graficas de
los angulos $\theta$, $\omega$ y $\phi$

## Observaciones
![texto](https://github.com/Vizuet775/Reto-determin-sticos/blob/main/Bitacora/Fotos/imagen_2025-05-23_114417592.png)
En esta gráfica de $\theta$ respecto al tiempo observamos que theta aumenta linealmente después de un poco de tiempo
![texto](https://github.com/Vizuet775/Reto-determin-sticos/blob/main/Bitacora/Fotos/imagen_2025-05-23_114439110.png)
En la gráfica de $\omega$ respecto al tiempo observamos que se estabiliza después de un tiempo
![texto](https://github.com/Vizuet775/Reto-determin-sticos/blob/main/Bitacora/Fotos/imagen_2025-05-23_114459454.png)
Finalmente en la gráfica de $\phi$ respecto al tiempo vemos que tiende a 0 después de un tiempo.

Respecto a algunas conclusiones que se han llegado, tiene sentido que $\theta$ aumente linealmente, ya que $\omega$ llega a ser constante despues de un tiempo. 
La velocidad angular llega a ser constante y varía con el torque, en la simulación usada el torque era suficientemente pequeño y entre más grande el torque más grande es la velocidad angular. Y cuando la velocidad angular aumente el angulo de $\phi$ va a tender a 0 (cabe recalcar que nuestro angulo $\phi$ es un angulo de desface respecto al disco) 

En el argumento del arcotangente nuestra unica variable (no constante) es $\dot{\theta}$. Observando la
grafica de la funcion arcotangente:


## Codigo
![texto](https://github.com/Vizuet775/Reto-determin-sticos/blob/main/Bitacora/Fotos/imagen_2025-05-23_115128351.png)
![texto](https://github.com/Vizuet775/Reto-determin-sticos/blob/main/Bitacora/imagen_2025-05-23_114939745.png)
