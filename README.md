# PWM-Variado-por-Voltaje
PWM que varia su ciclo útil variando el voltaje de entrada

El siguiente es la simulación en proteus de un PWM realizado en base al integrado tl494. Este PWM varia el ciclo de trabajo en función de la tensión que se aaplique a la entrada. Esta entrada debe estar regulada entre 0V y 3V.

![image](https://github.com/Sebax1901/PWM-Variado-por-Voltaje/assets/41446136/c86e4101-ee86-4844-a2c1-c584c378be7e)

**Especificaciones**

**Frecuencia**: La frecuencia está dada por los pines 6 (RT) y 5(CT), a los cuales se deberá conectar una resistencia y un condensador, respectivamente. La fórmula de la frecuencia está dada por: F = 1 / (RT * CT)

La amplitud del PWM está dada por la tensión del integrado, aplicada al pin 12 (VCC).
