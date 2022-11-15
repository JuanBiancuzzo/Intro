### **Postulado:**
---
_"El teorema de máxima transferencia de potencia establece que, dada una fuente, con un [[resistor]] de fuente fijado de antemano, el resistor de carga que maximiza la transferencia de potencia es aquel con un valor igual al resistor de fuente."_
Es decir, se toma un circuito equivalente como en el [[Teorema de Thevenin]], en donde el resistor de carga para maximizar la potencia que disipa, debe cumplir que:
$$
\begin{align}
R_\text{Th} = R_\text{carga}
\end{align}
$$

#### **Esquematizacion:**
---
![[Pasted image 20221114214118.png]]

#### **Analisis:**
---
Calculo la potencia entregada a la carga con la formula de [[potencia disipada]]:
$$
\begin{align}
P_\text{carga} = V_\text{carga} \cdot I_\text{carga}
\end{align}
$$
Sabiendo que, por [[divisor de tension]] y por [[resistores equivalentes]]:
$$ 
\left\{ 
\begin{array}{ l } 
V_\text{carga} = \frac{V_\text{Th} \cdot R_\text{carga}}{R_\text{Th} + R_\text{carga}} \\
I_\text{carga} = \frac{V_\text{Th}}{R_\text{Th} + R_\text{carga}}\\
\end{array} \right.
$$
Entonces:
$$
\begin{align}
P_\text{carga} &= \frac{V_\text{Th} \cdot R_\text{carga}}{R_\text{Th} + R_\text{carga}} \cdot \frac{V_\text{Th}}{R_\text{Th} + R_\text{carga}}\\
P_\text{carga} &= \frac{V_\text{Th}^2 \cdot R_\text{carga}}{(R_\text{Th} + R_\text{carga})^2}
\end{align}
$$
Y como el teorema establece que:
$$
\begin{align}
R_\text{Th} = R_\text{carga}
\end{align}
$$
Se concluye que:
$$
\begin{align}
P_\text{carga} &= \frac{V_\text{Th}^2}{4 \cdot R_\text{Th}}
\end{align}
$$
