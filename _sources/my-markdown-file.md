# Here's my sample title

This is some sample text.

(section-label)=
## Here's my first section

Here is a [reference to the intro](intro.md). Here is a reference to [](section-label).

## Planet Jupiter

 ```{figure} https://solarsystem.nasa.gov/system/resources/detail_files/2486_stsci-h-p1936a_1800.jpg
 ---
 height: 300px
 name: jupiter-figure
 ---
 The beautiful planet Jupiter!
 ```

 Jupiter is the fifth planet from the Sun and the largest in the Solar System. It is a gas giant with a mass more than two and a half times that of all the other plantes in the Sorlar Sustem combined, but slightly less than one-thousandth the mass of the Sun.

 In {numref}`jupiter-figure`, you can see an image of the planet Jupiter captured by the Hubble Space Telescope on June 27, 2019. This image is obtained from [NASA's website](https://solarsystem.nasa.gov/resources/2486/hubbles-new-protrait-of-jupiter/?category=planets_jupiter).

Jupiter has a mass of $m_{j} \approx 1.9 \times 10^{27} \: \text{kg}$.
Let's show this as a code block as well:

$$
  m_{j} \approx 1.9 \times 10^{27} \: \text{kg}
$$

Another way is to have named equations so you can cross-reference them later:

```{math}
:label: eq_label
m_{j} \approx 1.9 \times 10^{27} \: \text{kg}
```

Equation {eq}`eq_label` is an example of a named equation.

```{margin} Did you know?
Jupiter is 11.0x larger than Earth!
```

```{note}
I'm a note!
```

:::{warning}
I'm a warning!
:::

```{tip}
I'm a tip!
```

:::{danger}
I'm a danger!
:::

::::{grid}
:gutter: 3

:::{grid-item-card} Python
Python is super popular!
+++
Is it obvious that I'm a Python fan?
:::

:::{grid-item-card} PJulia
But Julia is incredibly fast...
+++
Switch to Julia in future?
:::
::::

```{dropdown} What is the capital of Canada (dropdown option)?
Ottawa! Correct!
```

```{admonition} What is the capital of Canada (admonition option)?
:class: tip, dropdown
Ottawa! Correct!
```