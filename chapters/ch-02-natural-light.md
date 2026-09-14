---
title: "2. “Natural Light”"
short_title: "Ch. 2 — Natural Light"
label: ch-2
doi: 10.1007/978-3-031-69507-0_2
---

## Abstract

In this chapter, we explore how light from sources such as the sun or a lamp can be dispersed into its spectral components. We discuss various dispersive elements, including gratings and prisms, and the phenomena of refraction and diffraction that allow these elements to spatially separate light. The chapter explores blackbody radiation and the historical significance of the ultraviolet catastrophe. Additionally, we introduce the concepts of absorption and emission lines, which provide insights into atomic and molecular energy levels.

**Keywords:** Spectrum · Blackbody radiation · Diffraction · Refraction · Gratings · Absorption spectroscopy · Spectral analysis

## Learning Goals

By the end of this chapter, you should be able to understand:

- the concept of spectral components and how white light is composed of various wavelengths of light.
- the function and importance of dispersive elements like prisms and gratings in spectroscopy.
- the difference between refraction and diffraction.
- blackbody radiation and the ultraviolet catastrophe.
- the principles of emission and absorption lines in spectroscopy and their significance in understanding atomic structure.
- the Stefan-Boltzmann law and Wien’s displacement law in the context of blackbody radiation, and how to determine temperature from the blackbody spectrum.
- how light collected from the sun gave us our first evidence of atomic energy levels.

(sec-2-1)=
## 2.1 Breaking Light into a Spectrum

**Definitions**

- **Spectral component:** “White” light is made up of many different wavelengths of light. Even light from the sun, which looks yellow, is made up of many different wavelengths of light. A single wavelength of light that makes up a broader spectrum of light is called a spectral component.
- **Dispersive element:** Anything that spatially separates light into its spectral components.
- **Spectrometer:** Any tool that allows us to separate out and measure the amount of each spectral component.
- **Refraction:** the redirection of a wave as it passes from one medium to another medium (like air to water).
- **Diffraction:** when waves bend around the corners of an obstacle.

A spectrometer only needs two items: a dispersive element and a screen. A dispersive element is anything that takes light and spatially separates it into its spectral components. A common dispersive element is a prism, as shown in [](#fig-2-1), which works due to refraction. If you send white light into a dispersive prism, you will see a rainbow exiting because each spectral component refracts at a different angle. For a prism, the smaller the wavelength of light, the larger the refraction angle. So, blue light ($\lambda _{\text{b}} =$ 400–490 nm) refracts at a larger angle than red light ($\lambda _{\text{r}} =$ 620–750 nm). If you calibrate the prism so that you know at what angle each wavelength refracts, you can send in an unknown wavelength, measure the angle of refraction, and use math to determine the wavelength of the light. You can also send in light from, for example, a hydrogen lamp and see what wavelengths or spectral components are in that light. Knowing how each wavelength refracts allows you to determine what wavelengths make up the hydrogen lamp spectrum.
```{figure} ../images/ch-02/541577_1_En_2_Fig1_HTML.jpg
:label: fig-2-1
:alt: A dispersive prism takes white light, which enters the prism from the left, and makes a rainbow. Each wavelength is refracted at a different angle. The white light source I used to make this picture is a tungsten lamp

A dispersive prism takes white light, which enters the prism from the left, and makes a rainbow. Each wavelength is refracted at a different angle. The white light source I used to make this picture is a tungsten lamp


```

In spectroscopy, the most common dispersive element is an optical grating, which works due to diffraction. Optical gratings commonly come in two types: transmission and reflection, see [](#fig-2-2). Either way, the optical grating is a dispersive element that will spatially separate light into its spectral components because each spectral component diffracts at a different angle.
```{figure} ../images/ch-02/541577_1_En_2_Fig2_HTML.png
:label: fig-2-2
:alt: (**a**) An example of white light, which is composed of many spectral components, reflecting off a reflection grating. For illustrative purposes, *d*, which is usually very small, is greatly enlarged. We also only show one order to keep the example a little cleaner. (**b**) An example of white light diffracting through a transmission grating. Again, *d* is greatly enlarged and we only show one order. (**c**) An example of blue light with hitting perpendicular to the transmission grating and being diffracted. In this example, we show all diffraction orders. The angles of diffraction are calculated using [](#eq-2-1)

(**a**) An example of white light, which is composed of many spectral components, reflecting off a reflection grating. For illustrative purposes, *d*, which is usually very small, is greatly enlarged. We also only show one order to keep the example a little cleaner. (**b**) An example of white light diffracting through a transmission grating. Again, *d* is greatly enlarged and we only show one order. (**c**) An example of blue light with $\lambda =455\,\text{nm}$ hitting perpendicular to the transmission grating and being diffracted. In this example, we show all diffraction orders. The angles of diffraction are calculated using [](#eq-2-1)


```

To create the diffraction, both types of gratings have small structures separated by a distance *d*. A reflection grating has a bunch of small tilted mirrors called rulings while a transmission grating has a bunch of small slits. The only physical criterion for a grating is that $d>\lambda$. The size of *d* in [](#fig-2-2) has been greatly enlarged for visual purposes. While *d* must be larger than $\lambda$, in practice we also make sure that *d* is typically less than about $5 \lambda$ to ensure suitable diffraction angles.

We will start with the equations that describe how spectral components are diffracted through a transmission grating; we will find that each spectral component can be diffracted at multiple, but well defined, angles. The math behind the next equation is a little complicated, but the end result is really what we care about. Let’s start by keeping things simple and assume the incoming light is perpendicular to the grating, see [](#fig-2-2)c. The light diffracts through the grating according to the equation:

```{math}
:label: eq-2-1
\begin{array}{c} d \sin \theta_{m} =m\lambda \\ \text{for incident light perpendicular to a transmission grating} \end{array}
```

In this equation, *d* is the distance between the slits, *m* is an integer known as the diffraction order (the fact that a spectral component diffracts at multiple but well defined angles is mathematically represented by *m*), $\lambda$ is the wavelength of a spectral component of the light, and $\theta _{m}$ is the angle of diffraction for order *m*. *m* can be a negative integer, zero, or a positive integer. If you know *d* and *m*, you can then measure $\theta _{m}$ and use that to calculate $\lambda$.

**Example**

A transmission grating has $d = 1~\mu \text{m}$. There are three laser pointers: a blue laser pointer with $\lambda _{b} = 450\,\text{nm}$, a green laser pointer with $\lambda _{g} = 532\,\text{nm}$, and a red laser pointer with $\lambda _{r} = 650\,\text{nm}$. All three lasers hit the grating perpendicular. What angles do the three lasers diffract for *m* = +1, 0, $-$1, and +2?

First, we use the diffraction equation to solve for $\theta _{m}$: $\theta _{m}=\sin ^{-1}{(m\lambda /d)}$, where $\sin ^{-1}$ is the inverse sine function. For $m=0$, we plug in numbers to find $\theta _{0,b}=0^{\circ }$, $\theta _{0,g}=0^{\circ }$, $\theta _{0,r}=0^{\circ }$. So, let’s not use the $m=0$ diffraction order since we can’t learn anything here!

For $m=+1$, we plug in numbers to find $\theta _{+1,b}=26.7^{\circ },\theta _{+1,g}=32.1^{\circ },\theta _{+1,r}=40.5^{\circ }$. That is a pretty big difference! Your light only needs to travel a short distance to separate out the three colors.

**Quick Math Aside**

Let’s put the screen $10\,\text{cm}$ from the grating. On the screen is a ruler that will serve as our z-axis. If the grating wasn’t in place, all spectral components would hit the screen at the same place. Let’s call this spot $z = 0\,\text{cm}$. With the grating in place and the white light hitting the grating perpendicular, the blue light, which diffracts at $26.7^\circ$, hits the screen at $z=(10 \,\text{cm})\tan 26.7^\circ =5.04\,\text{cm}$ while the green light hits the screen $z=6.28\,\text{cm}$. You could also skip the angle calculation and use the formula:

```{math}
:label: eq-2-2
\begin{array}{c} z=\pm\frac{L}{\sqrt{(\frac{d}{m \lambda})^2-1}} \\ \text{for incident light perpendicular to a transmission grating}, \end{array}
```

where *L* is the distance between the diffraction grating and the screen. *z* is positive for positive *m* and negative for negative *m*. You have the opportunity to derive this formula in problem 2.4. Notice that the diffraction order in the denominator is squared, so the sign of *m* only determines the sign of *z*.

For $m=-1$, we plug in numbers to find $\theta _{-1,b}=-26.7^{\circ }$, $\theta _{-1,g}=-32.1^{\circ }$, $\theta _{-1,r}=-40.5^{\circ }$.

For $m=+2$, we find something interesting when we plug numbers into a calculator: $\theta _{+2,b}=64.2^{\circ },\theta _{+2,g}=(90-20.4i)^{\circ },\theta _{+2,r}=(90-43.3i))^{\circ }$. Blue light diffracts at $64.2^\circ$, but the other two have weird looking answers that came out of my calculator. These numbers are called complex numbers. Complex numbers are a huge topic in both math and physics, but what it means for us is that green and red light cannot diffract into the $m=+2$ order. Experimentally, we would see blue light diffracted at $64.2^\circ$, but we would not see second order diffraction for red light and green light. They just wouldn’t be there. In general, whenever you calculate a number that is supposed to represent something physical and you get a complex number, that means this is something you cannot measure or it doesn’t exist.

From this example, we would want to design our spectrometer to use either $m=+1$ or $m=-1$ because all spectral components diffract with a real, measurable angle (i.e. not a complex number). In the end, it doesn’t matter which diffraction order we pick. As long as we know the angle at which a spectral component diffracts, we can use that information to determine the wavelength of an unknown spectral component.

A reflection grating does a similar job as a transmission grating, but the equation looks slightly different:

```{math}
:label: eq-2-3
\begin{array}{c} d \sin \theta_{m} =-m\lambda \\ \text{for incident light perpendicular to a reflection grating} \end{array}
```

All that is different is the minus sign on the righthand side. Finally, let’s suppose the incoming light isn’t perpendicular to the grating but hits the grating at an angle $\theta _{i}$ with respect to the perpendicular (in optics, the perpendicular is called the “normal”), see [](#fig-2-2)b. The formula describing the diffraction of a spectral component is:

```{math}
:label: eq-2-4
\begin{array}{c} d (\sin \theta_{m} -\sin \theta_{i} )=\pm m\lambda \\ \text{(use }+m\text{ for transmission and }-m\text{ for reflection)} \end{array}
```

While this formula is more complicated, it is important to note that the concept is far more important than the formula. The concept is simply this:

**Take Home Message**

If you know how your dispersive optic bends (diffracts or refracts) different wavelengths of light, you can use that information to determine the wavelength of an unknown spectral component from any light source.

**Fun History**

- The first known exploration of a diffraction grating was by the Scottish mathematician and astronomer James Gregory in the mid 1600s. He observed the diffraction of sunlight caused by light passing through a bird feather. The individual feathers acted like the small slits of a transmission grating. The German physicist Joseph von Fraunhofer made the first diffraction grating in 1814. He discovered something amazing, which is the topic of the next section.
- Diffracting light from a light bulb whose gas is a particular element like hydrogen, nitrogen, or oxygen is the topic of [](#sec-2-3). Classical physics had no way of explaining the observed spectral components, and this mystery was one of the puzzling experiments that led to quantum mechanics.

(sec-2-2)=
## 2.2 Blackbody Radiation

I pointed a commercial spectrometer at the sky, see [](#fig-2-3). Collecting this data was spectroscopy! A few important notes before we continue:
```{figure} ../images/ch-02/541577_1_En_2_Fig3_HTML.png
:label: fig-2-3
:alt: The spectral components of light from the sun after it passes through the atmosphere

The spectral components of light from the sun after it passes through the atmosphere


```

- This spectrometer has a dispersive element that was pre-calibrated, so the angle the light hits the detector is automatically converted to a wavelength.
- Spectrometers are not uniformly sensitive. This means that the detector you are using might be more sensitive to red light than blue light. Graphs like [](#fig-2-3) are useful for identifying the wavelengths present in the light, but unless the detector has been calibrated to correct for wavelength sensitivity, the shape may be incorrect. In fact, the real spectrum of the sky goes to far longer wavelengths, but this spectrometer is not sensitive to light at those frequencies.
- When this type of spectrum was first taken in the 1800s, those dips were a mystery, and physicists love a good mystery. Whenever a physicist is presented with data, the first thing they ask themselves is, “Why does the data look the way it does?” If we understand the concepts, we should be able to produce a mathematical model to describe (and predict) the data.
- For this data, there are, at least, two things that need to be thought through. The first is the overall shape. The second is, what are those dips?

Historically, it was a fun journey to figure out the overall shape. Physics known in the 1800s predicted a far different shape. In fact, when challenged with describing the overall shape, physics failed hard. When physicists tried to predict the spectrum in [](#fig-2-3), the model was close for large wavelengths but very, very wrong for small wavelengths. Starting at the larger wavelengths and moving to shorter wavelengths, the math says the spectrum should get larger and larger and larger instead of turning around and getting smaller, which would require infinite energy. The dramatic result of the math is this: the universe doesn’t exist. Whenever the model says the universe doesn’t exist, there is something we don’t understand.[^1] This result is now known as the “ultraviolet catastrophe.” It is a dramatic name, but the predictions from the mathematical model were also dramatic. We clearly needed a better model!

**A Short Aside**

Imagine you had a room with perfectly reflecting, parallel walls. Only light with particular wavelengths that create standing waves (perfect constructive interference like in [](#fig-1-7)) can exist in this room. Even though only certain wavelengths are allowed in the room, there are still an infinite number of them (you can always add one more loop to the standing wave). According to classical thermodynamics, a well tested and very successful theory, each standing wave has the same amount of energy. If you learned about heat capacity in high school chemistry, this classical thermodynamics model predicted an infinite heat capacity. Yikes!

According to the model, since each mode has the same energy, [](#fig-2-3) should keep going up and up at small wavelengths. As a practical example, this mathematical model says that if you stood in a closed room and lit a match, the entire room and everything in it would burst into flames due to the infinite energy density at short wavelengths. Ultraviolet catastrophe indeed!

In 1901, after a lot of thought and model development, German physicist Max Planck eventually figured out that if light was composed of photons, then there would be way fewer higher-energy photons than lower-energy ones, which solved the problem. In 1905, German born physicist Albert Einstein built upon this idea with the photoelectric effect. The mathematical result of this new model predicted the shape in [](#fig-2-3), which is modeled by the complicated formula:

```{math}
:label: eq-2-5
M(\lambda,T)=\frac{2\pi hc^2}{\lambda^5} \frac{1}{e^{\frac{hc}{\lambda \: k_B T}}-1},
```

where $h=6.626\times 10^{-34}\,\text{Js}$ is Planck’s constant, *c* is the speed of light, $k_{B}=1.38\times 10^{-23}\,\text{J/K}$ is a constant known as Boltzmann’s constant,[^2] and *T* is the temperature of the object. For temperature, we use the unit kelvin, which is named after British mathematician, physicist, and engineer Lord William Thomson. The unit for Boltzmann’s constant is joule/kelvin. Using this model to fit the data from the spectrometer, we can measure the temperature of the surface of the sun to be about 5800 kelvin. We call $M(\lambda ,T)$ “spectral radiant exitance”, and it tells us how much radiant energy per second is leaving the object per unit area per unit wavelength.[^3] The units for $M(\lambda ,T)$ are $\text{W}/\text{m}^{3}$. I should note that this equation is for a “perfect” blackbody, which doesn’t exist in real life. Not having a perfect blackbody is equivalent to saying there is no such thing as a room with perfectly parallel and reflective walls. However, it still does a pretty good job with modeling the spectrum emitted by objects.

It isn’t just the sun that emits a blackbody spectrum. A hot pan on the stove does, you do, and I do as well. The amount of light that is emitted as well as the peak wavelength of the blackbody spectrum only depends upon the temperature of the object. Remarkably, everything else in this model is either a constant or wavelength, which is our horizontal axis. [](#fig-2-4) shows a few different plots of the spectral radiant exitance for different temperatures. For objects near 5000 K, like the sun, they emit light that is visible to our human eye. For cooler objects, like us, the maximum spectral radiant exitance occurs more near $10{,}000\,\text{nm}$, which is $10\,\mu \text{m}$. There are special cameras that can see this wavelength of light. You may have seen thermal imaging or watched the Predator movies. I did not include the vertical scale in this plot because the numbers are big and hard to interpret without really digging into the spectral radiant exitance formula. But hotter objects do emit more light. The maximum spectral radiant exitance for a 6000 K object is about 3 million times larger than for a 310 K object.
```{figure} ../images/ch-02/541577_1_En_2_Fig4_HTML.png
:label: fig-2-4
:alt: Left: Blackbody spectrum for very hot objects. The surface of the sun is 5800 K. Right: Your blackbody spectrum, assuming you are human (310 K is about 98 F). Notice the horizontal axis is a very different scale

Left: Blackbody spectrum for very hot objects. The surface of the sun is 5800 K. Right: Your blackbody spectrum, assuming you are human (310 K is about 98 F). Notice the horizontal axis is a very different scale


```

**The Stefan–Boltzmann Law and Wien’s Displacement Law**

Imagine you have a blackbody with surface area *A*. Besides the spectrum of the blackbody, you can also measure the total power emitted by the object. The total power emitted is proportional to the area under a spectral radiant exitance graph. After some math (calculus), the total power emitted by a blackbody:

```{math}
:label: eq-2-6
\begin{array}{c} P=\sigma \epsilon A T^4, \\ \sigma=\frac{2\pi^5}{15}\frac{k_B^4}{c^2h^3} =5.67\times10^{-8} ~\frac{W}{m^2 K^4} \end{array}
```

where $\sigma$ is a constant known as the Stefan–Boltzmann constant,[^4] $\epsilon$ is the emissivity, and *A* is the surface area of the object. Emissivity is a number between 0 and 1 indicating how closely the object behaves like a blackbody. If it is a perfect blackbody, $\epsilon = 1$. For a sphere, like the sun, the surface area is $4\pi R^2$, where *R* is the radius of the sphere. The emissivity of the sun is about 0.99, so it is nearly a blackbody.

Several years before Max Planck solved the ultraviolet catastrophe, German physicist Wilhelm Wien experimentally noticed that the wavelength of the maximum spectral radiant exitance graph, see [](#fig-2-4), was inversely proportional to temperature. He discovered that a blackbody with a temperature of 6000 K had a maximum around $\lambda _{\text{peak}} = 484$ nm, 5000 K had a maximum around 580 nm, 4000 K around 725 nm, etc. After studying the trend between temperature and peak wavelength, he determined:

```{math}
:label: eq-2-7
\lambda_{\text{peak}}=\frac{b}{T},
```

where $b=2.898\times 10^{6}\,\text{nm K}.$ This formula was later derived from the spectral radiant exitance formula. If you have the calculus background to find the maximum of a function and want to derive this formula, you should know that, unfortunately, the resulting equation is a transcendental equation and thus does not have an analytical solution. However, you can find a numerical solution.

**What About Those Dips?**

Let’s return to the experimental data we took for the spectrum of the sky, see [](#fig-2-3). Blackbody radiation explains the overall shape, but what about the dips? What do you think is making those dips? The answer is below the fun little puzzle in [](#fig-2-5).
```{figure} ../images/ch-02/541577_1_En_2_Fig5_HTML.png
:label: fig-2-5
:alt: A fun little puzzle to separate the question from the answer

A fun little puzzle to separate the question from the answer


```

There are two sources of the dips: atoms and molecules in our atmosphere and the sun itself. For example, the dip near 750 nm is due to oxygen molecules in the atmosphere. There are photons coming from the sun that have the perfect energy to excite oxygen molecules. Because oxygen molecules absorb only photons with the perfect energy, some light is lost at very specific wavelengths before it reaches our spectrometer.

The second source for the dips is the sun itself. While the sun emits blackbody radiation, that light passes through gas at the surface of the sun. That gas absorbs light just like atoms and molecules in our atmosphere. If we wanted just the composition of the sun, we should collect this data from space!

This leads to one method of performing spectroscopy with a spectrometer. You take a light source, which can be a blackbody, a flashlight, or really any light source you want, and send it into your spectrometer. Record this spectrum. Next, place an atomic sample between the light source and the spectrometer and record this spectrum. Comparing the two spectra tells you which wavelengths got absorbed. Each wavelength that is lost from the light due to absorption is the same wavelength needed to excite the atom from one energy level to another. So measuring these absorption dips gives you information about the energy levels of the atoms.

(sec-2-3)=
## 2.3 Discharge Lamps

Another method of spectroscopy using a spectrometer is to point the spectrometer at a lamp filled with an element. [](#fig-2-6) shows the spectrum of a helium discharge lamp collected using a commercial spectrometer. The spectrum is not continuous like that of a blackbody. Instead, we observe individual spikes at very specific wavelengths. And, we already know the source of these spikes! Atoms have energy levels, and the atoms will only absorb and emit at specific wavelengths. Filling a lamp with a specific element, or the combination of a few elements, and collecting the emitted light with a spectrometer was the most common form of spectroscopy before the invention of the laser. After the spectrum was collected, physicists had to be very clever to back out the energy levels from all of those lines.
```{figure} ../images/ch-02/541577_1_En_2_Fig6_HTML.jpg
:label: fig-2-6
:alt: Spectrum collected from a helium discharge lamp collected using a spectrometer with an accuracy of 0.5 nm

Spectrum collected from a helium discharge lamp collected using a spectrometer with an accuracy of 0.5 nm


```

Whether you use a white light source and look for lost photons or you collect light from a discharge lamp, you gain the same information, which is the wavelengths of light needed to have an atom go from one energy level to another.

In the lab, spectrometers are still really useful tools, but they are not great for certain applications. Below are a few pros and cons to using spectrometers for spectroscopy.

Pros:

- You get lots of data all at once.
- You get lots of data very quickly.

Cons:

- The resolution is limited. You need to get different wavelengths far enough apart to distinguish between them. For example, let’s see how far apart 450.334 nm is from 450.335 nm using [](#eq-2-2) with $L=10\,\text{cm}$, $m=+1$, and $d=1000\,\text{nm}$:

  ```{math}
  \begin{array}{c} z(\lambda)=\pm\frac{L}{\sqrt{(\frac{d}{m \lambda})^2-1}} \\ z(450.335\,\text{nm})-z(450.334\,\text{nm})=140\,\text{nm}. \end{array}
  ```

  That is small! A possible solution is to make a bigger spectrometer, but then you will have to worry about thermal drifts, how well you can uniformly space the grating slits, and how well you can measure *d*. In short, it becomes really hard if you want really high resolution.

- The data can be hard to interpret. Getting all the data at once means you are getting all transitions from your atom or molecule all at once. A spectroscopist has to figure out what line comes from what transition (pair of energy levels), which is not an easy task!

For high precision spectroscopy, most spectroscopy groups use a laser to study a single transition instead of collecting light from many transitions at once. As we will find in [](#ch-4), having atoms moving around (i.e., a hot gas) is a bad thing if we want to measure something like the energy difference between two energy states to really high precision. Clever physicists developed a neat technique to still use hot atoms to measure properties to high precision, which is the topic of [](#ch-5), but we need multiple lasers to do so.

## Problems

```{exercise}
:label: prob-2-1
:enumerator: 2.1

Go through the chapter and write down all of the new fundamental constants. Don’t forget units.
```

```{exercise}
:label: prob-2-2
:enumerator: 2.2

Go through the chapter and write down each equation. For each equation, write a brief description about what the equation means.
```

```{exercise}
:label: prob-2-3
:enumerator: 2.3

What is the frequency difference between light that has a wavelength of 450.334 nm and light that has a wavelength of 450.335 nm? Express your answer in MHz. Your final answer should have 6 significant figures.
```

```{exercise}
:label: prob-2-4
:enumerator: 2.4

Derive [](#eq-2-2). Start by drawing a triangle.
```

```{exercise}
:label: prob-2-5
:enumerator: 2.5

When introducing gratings we stated, “The only physical criterion for a grating is that $d>\lambda$.” Looking at [](#eq-2-2), what would happen if $d<\lambda$?
```

```{exercise}
:label: prob-2-6
:enumerator: 2.6

[](#fig-2-6) shows the spectrum of a helium discharge lamp collected using a spectrometer. Below is a table of helium energy levels. Pick any three spectral lines from the Figure (except for the feature at 389 nm) and determine which transition produced each line. The lower level for each transition is listed in the third column. For example, the feature at 389 nm is due to an electron transitioning from level 8 to level 2:

```{math}
\begin{array}{c} 185,564.6\,\text{cm}^{-1}-159,856.0\,\text{cm}^{-1}=25708.6\,\text{cm}^{-1} \\ \rightarrow \lambda=\frac{1}{25708.6\,\text{cm}^{-1}}=0.0000388975\,\text{cm}=388.975\,\text{nm} \end{array}
```

(tbl-2-1)=
**Table 2.1** Helium energy levels

| Level # | Energy ($\text{cm}^{-1}$) | Lines with this lower level |
| --- | --- | --- |
| 1 | 0 |  |
| 2 | 159,856.0 | 389 nm |
| 3 | 166,277.4 | 502 nm |
| 4 | 169,086.8 | 447, 471, and 707 nm |
| 5 | 171,134.9 | 492 and 728 nm |
| 6 | 183,236.8 |  |
| 7 | 184,864.8 |  |
| 8 | 185,564.6 |  |
| 9 | 186,209.4 |  |
| 10 | 190,298.1 |  |
| 11 | 191,446.5 |  |
```

```{exercise}
:label: prob-2-7
:enumerator: 2.7

You want to design your own spectrometer to measure light collected from a lamp. You need to collect data for light with wavelengths between 1000 and 3000 nm. You have a number of different gratings that you can pick from, each with a different *d*. What are a few examples of a bad choice for *d*? What is an example of a good choice for *d*?
```

```{exercise}
:label: prob-2-8
:enumerator: 2.8

**(Solar Power)**

The sun has a surface temperature of $5772\,\text{K}$ with a radius of $r_{s}=696,340\,\text{km}$. The surface area of the sun is $A=4\pi r_{s}^2$. The emissivity of the sun is about 0.99.

- (a) Find the total power output of the sun.
- (b) The light from the sun spreads out radially in all directions. A small fraction of that light hits the earth. The earth is $d=1.496\times 10^{8}\,\text{km}$ from the sun. Assuming the earth is a solid disk with radius $r_{e}=6371\,\text{km}$, what fraction of the total power leaving the sun hits the earth?

  Hint: We first want to find the ratio of the area of the earth disk ($\pi r_{e}^2$) to the surface area of a sphere with the radius equal to the earth-sun distance: $\frac {\pi r_{e}^2}{4\pi d^2}$ That ratio tells us fraction of light emitted from the sun that hits the earth.

- (c) For solar energy, we care about how much power per area is hitting the solar panel. Power per area is called intensity. Find how much power from the sun is hitting a 1 square meter area of land. This is the intensity of sunlight on the earth.
- (d) You have a 10 cm by 10 cm solar panel. Determine the power of sunlight hitting that solar panel.
- (e) Your solar panel is 20% efficient at converting sunlight into usable electric power. What is the power output of your solar panel? Is it enough to power a 10 watt LED light bulb?
- (f) A refrigerator needs 200 watts of power to run. What area solar panel do you need to run the refrigerator? If the solar panel was a square, what are the dimensions of that square?
```

````{exercise}
:label: prob-2-9
:enumerator: 2.9

**(Numerical Problem)**

- (a) [](#fig-2-7) is an amazing figure made by Robert A. Rohde. It shows the spectrum from the sun collected using an amplitude corrected spectrometer. The vertical axis is the spectral irradiance.[^5] Included in the graph is a good approximation of what the sun would emit if it were a perfect blackbody. Using your favorite graphing program, estimate the temperature of the surface of the sun by plotting the spectral radiant exitance. Don’t worry about the vertical scale. What you are most concerned about is getting the spectral radiant exitance to be a maximum around 500 nm.

```{figure} ../images/ch-02/541577_1_En_2_Fig7_HTML.png
:label: fig-2-7
:alt: The spectrum from the sun both before the light enters the atmosphere (yellow) and at the surface of the earth (red). A perfect blackbody spectrum is shown by the black curve. Image Credit: Robert A. Rohde, CC BY-SA 3.0 via Wikimedia Commons

The spectrum from the sun both before the light enters the atmosphere (yellow) and at the surface of the earth (red). A perfect blackbody spectrum is shown by the black curve. Image Credit: Robert A. Rohde, CC BY-SA 3.0 via Wikimedia Commons
```

- (b) Use Wien’s displacement law to assess your answer. (In other words, does Wien’s displacement law confirm the peak of your graph in part (a)?)
````

```{exercise}
:label: prob-2-10
:enumerator: 2.10

**(Advanced Problem)**

- (a) Using your favorite numerical program, numerically find and plot the wavelength of maximum spectral wavelength ($\lambda _{\text{peak}}$) for temperatures between 3000 and 6000 K in steps of 100 K.[^6]
- (b) Fit your data to b/T to find b. Be sure to use the speed of light accurate to, at least, 5 digits.
```

```{exercise}
:label: prob-2-11
:enumerator: 2.11

**(Advanced Math Problem)**

Requires calculus.

- (a) Find the transcendental equation that you would need to numerically solve to find Wien’s displacement law.
- (b) Convert the spectral radiant exitance from a function of wavelength to a function of frequency. To do this, you need to use the formula. $M_{\lambda }(\lambda ,T)d\lambda =-M_{f}(f,T)df$, which guarantees that the same amount of total energy is in a spectral interval $d\lambda$ as in the corresponding interval *df*. The minus sign is because decreasing wavelength increases frequency.
- (c) Find the spectral radiant exitance as a function of wavenumber (inverse wavelength).
```

[^1]: I feel like this might be the understatement of the millennium.

[^2]: Boltzmann’s constant was named by Max Planck in honor of the Austrian physicist and philosopher Ludwig Boltzmann.

[^3]: The units are, admittedly, confusing! As a rough interpretation, you can think of these units as telling you how much light is being emitted from a blackbody at a given wavelength. If you look at [](#fig-2-3), there is more light being emitted at 500 nm than 700 nm, so the spectral radiant exitance is larger at 500 nm. This is what we mean by “per unit wavelength.”

[^4]: Named after the Carinthian Slovene physicist, mathematician, and poet Josef Stefan, who empirically found the relationship, and Austrian physicist and philosopher Ludwig Boltzmann, who derived the equation.

[^5]: Spectral radiant exitance is the radiant flux *emitted* by a surface per unit area per unit wavelength. Spectral irradiance is the radiant flux *received* by a surface per unit area per unit wavelength. You can think of spectral radiant exitance as what leaves the sun and spectral irradiance as what hits the earth.

[^6]: In python, you can use the code scipy.optimize.fmin from the scipy library. The code only finds the minimum, so you would multiply the spectral radiant exitance formula by -1 first. In Mathematica, the function is FindMaximum.
