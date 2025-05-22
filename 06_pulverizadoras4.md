---
title: "06. Problemas integradores de regulación y calibración de pulverizadoras"
autor: "José Juarez"
version: "21/05/25"
---

<span hidden>Local path of the file: "H:/cfr/mye5/"</span>
<span hidden>Local path of images: "H:/cfr/mye5/_i/"</span>


<br><br>


### Problema 1: Regulando y calibrando en el campo

Un operario va a realizar una aplicación con una **pulverizadora de arrastre** que tiene **21 boquillas**, separadas entre sí por **0,5 metros**. El técnico recomienda trabajar con **3 bar de presión**, boquillas de **110° de ángulo** y mantener una **altura de 50 cm sobre el blanco**.

Después de ajustar la máquina, se realiza una calibración siguiendo este procedimiento:

1. Se cronometra y se registra que tarda **12 segundos en recorrer 50 metros**.

2. Se recoge el líquido de **3 boquillas** durante ese tiempo, obteniendo un total de **180 cm³**.

3. Se quiere saber **cuántos litros por hectárea está aplicando** la máquina.

**Preguntas:**

a) ¿Cuál es el **ancho de labor** de la pulverizadora?

b) ¿Qué volumen promedio entrega cada boquilla en esos 12 segundos?

c) ¿Cuánto líquido arroja el equipo al recorrer 50 metros?

d) ¿Qué superficie se cubre al recorrer esos 50 metros?

e) ¿Cuántos litros por hectárea aplica el equipo?


> 💡 *Recordar:*
>
> * 1 litro = 1000 cm³
> * 1 ha = 10.000 m²
> * Superficie cubierta = largo recorrido × ancho del equipo
> * Regla de 3 para obtener litros por hectárea


<br><br>


### **Problema 2: Comparando dos velocidades**

Una pulverizadora autopropulsada tiene **30 metros de ancho** y trabaja con **60 boquillas**.

Se hacen dos pruebas:

- En la primera, tarda **10 segundos en recorrer 50 metros** y las jarras recogen **0,18 litros** en total de 3 boquillas.

- En la segunda, tarda **8 segundos en recorrer 50 metros** y las jarras recogen **0,15 litros** de las mismas boquillas.

**Preguntas:**

a) ¿Cuánto líquido aplica por hectárea en **cada una** de las dos pruebas?

b) ¿Cómo influye la **velocidad** en la cantidad aplicada?

c) ¿Cuál de las dos velocidades sería preferible si se quiere evitar **deriva**?

<div hidden>

## **Soluciones – Problema 1**

**a) Ancho de labor:**

Ancho = cantidad de boquillas × separación
Ancho = 21 × 0,5 m = **10,5 metros**

**b) Volumen promedio por boquilla en 12 s:**

Volumen por boquilla = 180 cm³ ÷ 3 = **60 cm³**

**c) Total de líquido que aplica el equipo en 12 s (recorriendo 50 m):**

Cada boquilla: 60 cm³ → 21 boquillas →
Total = 60 × 21 = **1260 cm³ = 1,26 litros**

**d) Superficie cubierta en 50 m de avance:**

Superficie = largo × ancho
Superficie = 50 × 10,5 = **525 m²**

**e) Litros por hectárea (L/ha):**

Sabemos:

* Aplica 1,26 L en 525 m²
* 1 ha = 10.000 m²
  → Regla de 3:

$$
\frac{1,26 \text{ L}}{525 \text{ m}^2} = \frac{x \text{ L}}{10.000 \text{ m}^2}
$$

$$
x = \frac{1,26 \times 10.000}{525} = 24 \text{ L/ha}
$$

✅ **Respuesta final: 24 litros por hectárea**

---

## ✅ **Soluciones – Problema 2**

**Primera prueba:**

* 10 s en 50 m
* 0,18 L en 3 boquillas
* Por boquilla: 0,18 ÷ 3 = **0,06 L**
* Total de boquillas: 60
  → Total = 0,06 × 60 = **3,6 L**
* Ancho de labor = 30 m
  → Superficie = 50 × 30 = **1500 m²**

L/ha:

$$
\frac{3,6 \text{ L}}{1500 \text{ m}^2} = \frac{x}{10.000}
\Rightarrow x = \frac{3,6 \times 10.000}{1500} = 24 \text{ L/ha}
$$

---

**Segunda prueba:**

* 8 s en 50 m
* 0,15 L en 3 boquillas → 0,05 L/boquilla
  → Total: 0,05 × 60 = **3 L**
  → Misma superficie: 1500 m²

L/ha:

$$
\frac{3 \times 10.000}{1500} = 20 \text{ L/ha}
$$

---

**b) ¿Cómo influye la velocidad?**

→ Al aumentar la velocidad, **disminuye el tiempo de aplicación**, por lo tanto **se aplica menos líquido por hectárea**.

---

**c) ¿Qué velocidad es preferible para evitar deriva?**

→ Es preferible la **más baja** (primera prueba, 10 s), ya que:

* Permite gota más grande (más tiempo para caer)
* Menor velocidad del equipo = menor riesgo de arrastre del viento

✅ **Respuesta: La velocidad más baja ayuda a evitar deriva.**

</div>

<!-- HTML style definitions -->
<style>
/* Colors */
.grey1 {color: #b3b3b3;} /* my light-grey */
.grey2 {color: #999999;} /* my middle-grey */
.grey3 {color: #808080;} /* my dark-grey */
.blue1 {color: #6495ed;} /* nvim blue */
.blue2 {color: #276cdf;} /* Andrew Ng Blue */
.sky1 {color: #7dbed8;} /* nvim sky */
.sky2 {color: #27a2db;}   /* my sky */
.green {color: #81b524;} /* my green */
.red1 {color: #ec5469;} /* my coral-red */
.red2 {color: #f44336;} /* my red */
.rose {color: #ec9998:} /* nvim rose */
.gold {color: #df9d43;} /* Andrew Ng gold */
.orange1 {color: #fda556;} /* nvim orange */
.orange2 {color: #ff9505;} /*Andrew Ng orange */
.purple1 {color: #ff40ff;} /* Andrew Ng purple */
.purple2 {color: #d164d7;} /* Andrew Ng purple */
/* Font Size */
.size90 {font-size: 0.9em;}
.size85 {font-size: 0.85em;}
.size80 {font-size: 0.8em;}
.size70 {font-size: 0.7em;}
/* Document General Font Size */
body {font-size: 1.3em;}
</style>
<!-- Use <span> inline and <div> with several lines --->
