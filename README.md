# Burgers1D_PD
En este repositorio presentamos un ejemplo de aplicación de redes neuronales informadas por la física (PINNs) en un problema directo asociado a la ecuación de Burges en una dimensión.  
La formulación matemática es la siguiente:

$
 \frac{\partial u}{\partial t} + u \frac{\partial u}{\partial x} = \nu \frac{\partial^2 u}{\partial x^2},
$
Para  $(x,t) \in (0,1)\times(0,1]$. Sujera a la condición inicial,

 $
 u(x,0) = u_{0}(x), \qquad  x \in [-1,1],
 $

 y a condiciones de forntera tipo Dirichlet,
$
u(t,0) = u(t,1) = 0, \qquad  t \in [0,T]
$


Aquí, $\nu > 0$ representa la viscosidad cinemática del medio  y la condición  $u(x,0) = u_{0} (\cdot)$ define un perfil el instante inicial
