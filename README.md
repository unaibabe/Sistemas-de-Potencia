# Sistemas de Potencia (UF1)

Aplicación web interactiva de estudio y simulación para la **Unidad Formativa 1: Introducción a los Sistemas de Potencia** . Diseñada para comprender de manera visual, práctica y dinámica el comportamiento de los materiales eléctricos, la resistencia, la intensidad, la caída de tensión en líneas y la resolución de circuitos.

## Fórmulas Clave de Referencia Rápida

| Magnitud / Concepto | Expresión Matemática | Unidad (SI) | 
| ----- | ----- | ----- | 
| **Intensidad Eléctrica** | $I = \frac{Q}{t}$ | Amperio ($\text{A}$) | 
| **Resistencia de un Conductor** | $R = \rho \cdot \frac{l}{S}$ | Ohmio ($\Omega$) | 
| **Variación con la Temperatura** | $R_{T2} = R_{T1} \cdot [1 + \alpha \cdot (T_2 - T_1)]$ | Ohmio ($\Omega$) | 
| **Ley de Ohm** | $I = \frac{V}{R} \quad \Rightarrow \quad V = I \cdot R$ | Voltio ($\text{V}$) / Amperio ($\text{A}$) | 
| **Caída de Tensión en Línea** | $\text{c.d.t.} = V_0 - V = I \cdot R_{\text{cable}}$ | Voltio ($\text{V}$) | 
| **Potencia Eléctrica** | $P = V \cdot I = I^2 \cdot R = \frac{V^2}{R}$ | Vatio ($\text{W}$) | 
| **Efecto Joule (Calorías)** | $E_{(\text{cal})} = 0.24 \cdot I^2 \cdot R \cdot t$ | Calorías ($\text{cal}$) | 
| **Densidad de Corriente** | $J = \frac{I}{S}$ | $\text{A/mm}^2$ | 
| **Energía en Condensador** | $W = \frac{1}{2} \cdot C \cdot V^2$ | Julio ($\text{J}$) | 

## Demo en Vivo (GitHub Pages)

Puedes acceder al laboratorio interactivo directamente desde el navegador a través del enlace de **GitHub Pages** de este repositorio.

## Módulos Interactivos Incluidos

La plataforma está dividida en **5 módulos prácticos** basados en el temario oficial y en la actividad de feedback:

### 1. Materiales, Resistividad y Temperatura

* **Clasificación interactiva:** Conductores, aislantes, semiconductores y superconductores.

* **Simulador 3D de conductor cilíndrico:** Ajusta en tiempo real el material (Plata, Cobre, Oro, Aluminio, Wolframio, Níquel, Hierro, Platino, Estaño), la longitud ($l$), la sección normalizada ($S$) y la temperatura ($T$).

* **Cálculo automático:** Resistencia a $20\text{ }^\circ\text{C}$, variación térmica con el coeficiente $\alpha$, conductancia ($G$) y conductividad ($\sigma$).

### 2.  Intensidad, Caída de Tensión y Efecto Joule

* **Simulador de línea de transporte (**$\text{c.d.t.} = V_0 - V$**):** Visualiza cómo afecta la resistencia propia del cable al voltaje que llega finalmente a la carga.

* **Métricas en tiempo real:** Caída de tensión en voltios y porcentaje, pérdida de potencia en la línea ($P_p = I^2 \cdot R$), densidad de corriente ($J = I / S$) y calor disipado por efecto Joule en kilocalorías ($\text{kcal}$).

* **Simulador de cortocircuito y sentido de la corriente:** Compara el sentido convencional ($+$ a $-$) frente al sentido real de los electrones ($-$ a $+$) y observa qué ocurre ante un cortocircuito ($R \approx 0\text{ }\Omega$).

### 3.  Circuitos, Divisor de Tensión y Puente de Wheatstone

* **Serie vs. Paralelo:** Comparativa dinámica de las Leyes de Kirchhoff, resistencia equivalente ($R_{eq}$) y reparto de tensiones e intensidades.

* **Divisor de Tensión con Reóstato/Potenciómetro:** Simulación interactiva con cursor móvil para calcular los rangos mínimo y máximo de $V_{out}$.

* **Puente de Wheatstone + Sonda PT-100:** Simulador térmico para observar cómo varía $R_x$ según la temperatura y cómo se desequilibra el puente generando la tensión diferencial $\vert{}V_{out}\vert{}$.

### 4. Código de Colores, Condensadores y Bobinas

* **Calculadora visual de resistencias (4 bandas):** Representación SVG en tiempo real con cálculo de valor nominal, tolerancia y rango óhmico permitido. Incluye accesos rápidos a todas las resistencias del **Ejercicio 10**.

* **Calculadora de Condensadores:** Cálculo de carga almacenada ($Q = C \cdot V$) y energía electrostática ($W = \frac{1}{2}CV^2$).

* **Resumen técnico:** Resistencias dependientes (NTC, PTC, LDR, VDR) y tipos de bobinas/inductores según su núcleo (aire, hierro, ferrita).

### 5. Entrenador Paso a Paso: Retos PDF (Actividad Feedback)

* Incluye los **10 ejercicios oficiales** de la Unidad Formativa 1.

* Verificador automático de respuestas numéricas con pistas y desarrollo matemático desplegable paso a paso.

## 

*Desarrollado como herramienta de aprendizaje interactivo para Sistemas de Potencia (UF1).*
