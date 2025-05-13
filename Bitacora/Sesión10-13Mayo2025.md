#Sesion 10 

Notas de Mariana de la conversación: 
Redefinimos el propósito del reto, o los pendientes que nos quedan por hacer: 

- Terminar los detalles que les falten a las ecuaciones, se definió la clase pasada (BErny y Mariana)
junto con el profe, la sumatoria de fuerzas. De aquí saldrá nuestra segunda ecuación para el sistema
de ecuaciones.
Se tenía ya la ecuación que se obtuvo de la sumatoria de torques:

$I_t \frac{d^2 \theta}{dt} = \tau_M - b\frac{d\theta}{dt} r\sin(\psi)$

Donde $I_t = I_{disco} + I_{cuchillas} = I_d + 2m_c r(\theta)^2 $

- Generar un código, probablemente con Runge Kutta 4, para modelar las trayectorias de $\phi$
y $\theta$ y evaluarlas para graficarlas. Este será el modelo inicial que presentaremos.
Lograr que estas gráficas tengna sentido con el comportamiento del sistema. 

- Buscar la velocidad terminal dependiendo del torque, esto es algo que buscaba John Deere y podría
ser un buen complemento al entregable. 

Berny: termino de escribir en límpio la ecuación que se planteó la clase pasada de sumatoria de fuerzas. 

$\psi = \tan{-1} (\frac{m\dot{\theta} r'}{b} )$
