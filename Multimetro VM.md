### **Definicion:**
---
"El multimetro de valor medio es un tipo de [[multímetro]] que “sólo sabe” calcular valor medio"

#### Modos:
---
- Modo DC:
Se utiliza la formula de la [[tension promedio]]:
$$
\begin{align}
V_\text{DC} = \frac{1}{T} \cdot \int_{0}^{T} v(t) \cdot dt
\end{align}
$$
- Modo AC:
Como solo puede hacer calculos de valor medio, se debe hacer lo siguiente:
1. Se quita la tension continua:
$$
\begin{align}
v(t) - V_\text{DC}
\end{align}
$$
2. Se rectifica:
$$
\begin{align}
|v(t) - V_\text{DC}|
\end{align}
$$
3. Se computa el valor medio:
$$
\begin{align}
\frac{1}{T} \cdot \int_{0}^{T} |v(t) - V_\text{DC}| \cdot dt
\end{align}
$$
4. Se multiplica por el valor de forma senoidal (que tiene un valor de $1.11$):
$$
\begin{align}
V_{AC} = 1.11 \cdot \frac{1}{T} \cdot \int_{0}^{T} |v(t) - V_\text{DC}| \cdot dt
\end{align}
$$