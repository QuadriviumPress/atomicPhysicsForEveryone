---
title: 10. Isotope Shifts, Radioactive Decay, and the Nuclear Forces
short_title: "Ch. 10 — Isotope Shifts"
label: ch-10
doi: 10.1007/978-3-031-69507-0_10
---

## Abstract

In this chapter, we explore the nucleus, focusing on how the number of neutrons in a nucleus influences transition frequencies and the stability of atoms. We begin by examining the effect of neutrons on transition frequencies, then shift into detailed discussions of the nuclear forces and principles governing atomic stability and radioactive decay. Various modes of radioactive decay, including neutron and proton emission, $\alpha$ decay, spontaneous fission, $\beta ^-$ decay, $\beta ^+$ decay, and electron capture, are investigated, with an emphasis on the conditions under which each occurs. Additionally, we explore the nuclear shell model to understand the energetics behind different types of decays and the stability of isotopes.

**Keywords:** Isotope shifts, Normal mass shift, Radioactive decay, Half-life, Nuclear forces, Strong nuclear force, Weak nuclear force, Nuclear shell model

## Learning Goals

By the end of this chapter, you should be able to understand:

- that the number of neutrons in the nucleus can
  - cause a small shift in the spectrum,
  - make an isotope unstable.
- that unstable atoms undergo radioactive decay characterized by a time called the half-life.
- that a system always seeks to reach its lowest energy state.
- that the daughter system of a decay has lower energy than the parent system.
- that the table of isotopes is similar to the periodic table but includes all isotopes.
- that the strong nuclear force is the force that holds the nucleus together.
- that the weak nuclear force is the force that facilitates the annihilation and creation of particles during radioactive decay.
- the nuclear shell model and the energy arguments behind radioactive decay.

(sec-10-1)=
## 10.1 Isotope Shifts

**Definitions:**

- **Mass number:** The number of neutrons plus protons in an element, represented by the variable *A*.
- **Nucleon:** A general word for either a neutron or a proton.
- **Isotope shift:** The change in the resonance frequency of a transition between two states in an atom caused by changing the number of neutrons in the nucleus.

Different isotopes of a particular element have different numbers of neutrons. For example, europium-151 has 63 protons and 88 neutrons. The ’151’ in the name of the isotope indicates the total number of protons and neutrons in the nucleus: $63+88 = 151$. Europium-153 has 63 protons and 90 neutrons: $63+90 = 153$. The element name europium is just a placeholder for ‘the atom with 63 protons.’ To display all the information at once, we often write an isotope as follows: 

```{math}
:label: eq-10-1
{}^{A}_{Z}\text{X}^{}_{N}
```

where *Z* is the proton number, *N* is the neutron number, $A=Z+N$ is the mass number, and $\text{X}$ is the element symbol. See Appendix B for a full list of element symbols. For example, europium-153 would be written as ${}^{153}_{63}\text{Eu}^{}_{90}$

**Quick Quiz**

Use Appendices A or B to find the proton number for the following atoms:

1. How many neutrons does oxygen-17 have?
2. How many neutrons does hydrogen-2 have?
3. How many neutrons does beryllium-9 have?

The answers are in the footnotes.[^1]

The number of neutrons in the nucleus slightly affects the energy of the states in an atom. Neutrons affect the energy of the states in two ways: they change the mass of the nucleus and slightly alter the charge distribution within the nucleus (how the protons are distributed in the nucleus). For a given isotope, the energy of each state in the atom will shift a different amount because each state has a different electron configuration and term symbol (i.e. different angular momentum and different distance from the nucleus). To study how changing the number of neutrons affects the energy of a state, we typically select the same transition and measure how the transition frequency changes as a function of neutron number. Since the energy of each state in an atom shifts a different amount, the transition frequency between those two states also changes. That shift is called the isotope shift.

Table [](#tbl-10-1) shows experimental results from my research group for three transitions for two different isotopes of europium. The transitions are from the $4\text{f}^7 6\text{s}^2~{ }^{8}\text{S}_{7/2}$ ground state to the $4\text{f}^7({ }^{8}\text{S}^\circ )6\text{s}6\text{p}({ }^{1}\text{P}^\circ )~{ }^{8}\text{P}_{J}$ states, where $J = 5/2$, $7/2$, or $9/2$. In the above electronic configurations, I did not write out the closed subshells (e.g., $1\text{s}^2 2\text{s}^2 \ldots$). Notice that adding two neutrons to the nucleus decreased the transition frequency for all three transitions. Because the two isotopes have a different number of neutrons, all of the states in europium-151 have a different energy than the states in europium-153. The difference in energy between the ground states of the two isotopes is different from the difference in energy between, say, the $J = 5/2$ excited states. Therefore, the transition frequency from the ground state to the $J=5/2$ excited state is slightly different for the two isotopes; this is the isotope shift for this transition. Similarly, the difference in energy between the $J = 7/2$ excited states for the two isotopes is different from the difference in energy between the $J = 5/2$ excited states, so the isotope shift for this transition is different from the isotope shift for the $J=7/2$ state. In the end, every transition in the atom will have a different isotope shift. 

(tbl-10-1)=
**Table 10.1** The isotope shifts for three transitions in the europium atom. All of the transitions are from the atomic ground state. The labels for the excited state column are the total electronic angular momentum quantum number *J* for the excited state: $4\text{f}^7({ }^{8}\text{S}^\circ )6\text{s}6\text{p}({ }^{1}\text{P}^\circ ){ }^{8}\text{P}_{J}$. $f_r$ is the frequency for the transition between the center of gravity of the ground state and the center of gravity for an excited state. The numbers come from references [3] and [4]

| Excited state | $f_r\,(\text{MHz})\text{ for }{}^{151}_{63}\text{Eu}^{}_{88}$ | $f_r\,(\text{MHz})\text{ for }{}^{153}_{63}\text{Eu}^{}_{90}$ | Isotope Shift (MHz) |
| --- | --- | --- | --- |
| $J=9/2$ | 652,389,757.16$\pm$0.34 | 652,386,593.2$\pm$0.5 | 3163.8$\pm$0.6 |
| $J=7/2$ | 647,708,930.6$\pm$0.6 | 647,705,958.4$\pm$2.6 | 2972.8$\pm$0.5 |
| $J=5/2$ | 642,894,493.3$\pm$0.4 | 642,891,693.3$\pm$0.9 | 2799.54$\pm$0.20 |

**Important Comment**

Isotope shifts are measured with respect to the center of gravity of a state. This is because each isotope for an element can have a different nuclear spin. Studying the effects of neutron number is much more convenient after removing hyperfine splitting. We accomplish this using Eq. [](#eq-9-5). When you read studies of isotope shifts from scientific papers, the numbers you are reading have already accounted for hyperfine structure.

While experimentalists measure the frequency difference between isotopes, mathematically we break down the isotope shift into three expressions: the normal mass shift $\delta f_{\text{NMS}}^{AA'}$, the specific mass shift $\delta f_{\text{SMS}}^{AA'}$, and the field shift $\delta f_{\text{FS}}^{AA'}$. The formula for the isotope shift is: 

```{math}
:label: eq-10-2
\delta f^{AA'}=\delta f_{\text{NMS}}^{AA'}+\delta f_{\text{SMS}}^{AA'}+\delta f_{\text{FS}}^{AA'}, 
```

where *A* is the mass number for one isotope and $A'$ is the mass number of the other isotope. Both the normal mass shift and the specific mass shift come about because the two isotopes have different masses. The field shift comes about because the nuclei for the two isotopes have a slightly different size. The different sizes change the charge distribution (the distribution of protons) inside the nucleus and this leads to a small shift in the energy levels.

The easiest way to think about normal mass shift is a classical analogy. The moon orbiting the earth implies that the moon is orbiting about the center of the earth and the earth is not orbiting around the moon. This is a bit of a misnomer. The moon and the earth are actually orbiting around a point somewhere along a line between the center of the earth and the center of the moon. Because the earth has so much more mass than the moon, that point happens to be very close to the center of the earth. If the moon and the earth had the same mass, they would both be orbiting about a point directly between them. That point is called the center of mass. Analogously, the electron is not orbiting around the center of the nucleus. Instead, the nucleus and the electron are orbiting around the center of mass point. That point moves if we change the mass of the nucleus. Accounting for this shift in the center of mass point is the normal mass shift. The specific mass shift is present in atoms with more than 1 electron. It comes about because the electrons are moving and interacting with one another. Changing the mass of the nucleus has a small effect on those interactions.

Out of the 3 contributions, only the normal mass shift has a simple formula: 

```{math}
:label: eq-10-3
\delta f_{\text{NMS}}^{AA'}=\frac{m_e}{m_p}\frac{A'-A}{AA'}f_r,
```

where $A'$ is the mass number of an isotope (for example the 151 in europium-151), *A* is the mass number of a different isotope (for example the 153 in europium-153), $\delta f_{\text{NMS}}^{AA'}$ is the isotope shift of the isotope with mass number $A'$ with respect to the isotope with mass number *A* due to the normal mass shift, $m_e$ is the mass of an electron, $m_p$ is the mass of a proton, and $f_r$ is the transition frequency from the center of gravity from the lower energy state to the center of gravity of the higher energy state.[^2]

**Example**

Rubidium, an element with 37 protons, has two naturally occurring isotopes: rubidium-85 and rubidium-87.[^3] There is a transition from the ground state to an excited state with a center of gravity transition frequency of $377.107\,\text{THz}$. What is the normal mass shift between the two isotopes?

For this example, let’s make $A'=87$ and $A=85$:

```{math}
:label: eq-10-4
\begin{array}{rcl} \delta f_{\text{NMS}}^{AA'}&=&\frac{m_e}{m_p}\frac{A'-A}{AA'}f_r \\ &=&\frac{9.11\times 10^{-31}\,\text{kg}}{1.67\times 10^{-27}\,\text{kg}}\frac{87-85}{(85)(87)}(377.107\times 10^{12}\,\text{Hz}) \\ &=&55.6\,\text{MHz} \end{array}
```

Since we made $A'=87$ and $A=85$, a positive result means that rubidium-87 would have a larger transition frequency, at least before we account for the specific mass shift or the field shift.

The experimental value of the isotope shift between rubidium-87 and rubidium-85 for this transition is $(77.583\pm 0.012)\,\text{MHz}$, see reference [1]. We found the normal mass contribution was 55.6 MHz. The remaining shift comes from the other two contributions that are, unfortunately, difficult to calculate. However, we can try to extract information about the nucleus by measuring a large number of isotopes for a particular element.

To visually compare different isotopes, we can make a plot of the isotope shifts for a particular transition as a function of neutron number. This plot is called a King plot[^4] and is a nice way to visualize how changing the number of neutrons in a nucleus affects the spectrum. Figure [](#fig-10-1) shows an example of experimentally measured isotope shifts for a transition in the krypton atom that is excited using a laser near 760 nm. It was collected by Keim et al. in 1995, see reference [2]. All of the isotope shifts are measured with respect to krypton-86. Notice there is a “kink” in the graph at $A'=86$. As physicists, we want to know why! If we truly understand the system, we should be able to calculate the isotope shifts using Eq. [](#eq-10-2) and predict such a graph. The reason for the “kink” at $A'=86$ is that nucleons fill shells in the nucleus just like electrons fill shells. We discuss nuclear shells in Sect. [](#sec-10-6). There is a nuclear shell for neutrons that fills at 50 neutrons. Since krypton has 36 protons, this neutron shell fills at $A'=86$. The “kink” at $A'=75$ is not from a shell filling. That “kink” is thought to come from the nucleus itself beginning to deform due to lack of neutrons. There is so much one could ask and explore with this data. What questions would you ask? The wonderful thing about physics is that if we understand the system, we can interpret the data. If there is something we don’t understand, this sort of data gives us a starting point to explore and learn more.
```{figure} ../images/ch-10/541577_1_En_10_Fig1_HTML.png
:label: fig-10-1
:alt: The isotope shift of a transition in krypton near 760 nm using data from reference [2]. The isotope shifts are measured with respect to the isotope with mass number A = 86

The isotope shift of a transition in krypton near 760 nm using data from reference [2]. The isotope shifts are measured with respect to the isotope with mass number $A=86$

```

(sec-10-2)=
## 10.2 Radioactive Decay
Inside the nucleus are neutrons and protons. Experimental evidence shows that if the neutron-to-proton ratio isn’t “correct,” the nucleus becomes unstable and will undergo radioactive decay. Radioactive decay is often written in the form of an equation. The left hand side of the equation is the unstable isotope. We will call this the parent system. The right hand side shows all of the decay particles. We will call this the daughter system.[^5] The equation looks something like this: 

```{math}
:label: eq-10-5
\text{parent } \rightarrow \text{ daughter}
```

There are a number of decays that can happen:

**Neutron Emission**

The nucleus will eject a neutron. An example of an isotope that undergoes neutron emission is helium-5 (2 protons and 3 neutrons), which decays to helium-4 (2 protons and 2 neutrons) and a neutron:

```{math}
{}^{5}_{2}\text{He}^{}_{3}\rightarrow {}^{4}_{2}\text{He}^{}_{2}+\text{n}
```

In the above equation, helium-5 is called the parent nucleus and helium-4 is called the daughter nucleus. The general formula for neutron emission is:

```{math}
:label: eq-10-6
{}^{A}_{Z}\text{X}^{}_{N}\rightarrow {}^{A}_{Z}\text{X}^{}_{N-1}+\text{n}
```

**Proton Emission**

The nucleus will eject a proton. An example of an isotope that undergoes proton emission is scandium-39 (21 protons and 18 neutrons), which decays to calcium-38 (20 protons and 18 neutrons) and a proton:

```{math}
{}^{39}_{21}\text{Sc}^{}_{18} \rightarrow {}^{38}_{20}\text{Ca}^{}_{18} + \text{p}
```

In the above equation, scandium-39 is called the parent nucleus and calcium-38 is called the daughter nucleus. The general formula for proton emission is:

```{math}
:label: eq-10-7
{}^{A}_{Z}\text{X}^{}_{N}\rightarrow {}^{A}_{Z-1}\text{X}^{}_{N}+\text{p}
```

**$\beta ^{-}$ Decay (Beta Minus Decay)**

A neutron will transform into a proton, an electron, and a particle called an “anti-electron neutrino” (which has the label $\bar {\nu }_e$). We haven’t talked about neutrinos, but you can find more information about them with a quick internet search. For our purposes, neutrinos are very light particles with no electric charge. Both the electron and the anti-electron neutrino are ejected while the proton remains in the nucleus. The electron that is ejected from the nucleus usually has a ton of energy and is called a $\beta ^{-}$ particle. An example of an isotope that undergoes $\beta ^{-}$ decay is carbon-14:

```{math}
{}^{14}_{6}\text{C}^{}_{8}\rightarrow {}^{14}_{7}\text{N}^{}_{7}+\beta^-+\bar{\nu}_e
```

In the above equation, carbon-14 (6 protons and 8 neutrons) is called the parent nucleus and nitrogen-14 (7 protons and 7 neutrons) is called the daughter nucleus. The general formula for $\beta ^-$ decay is:

```{math}
:label: eq-10-8
{}^{A}_{Z}\text{X}^{}_{N}\rightarrow {}^{A}_{Z+1}\text{X}^{}_{N-1}+\beta^-+\bar{\nu}_e
```

**$\beta ^+$ Decay (Beta Plus Decay or Positron Decay)**

A proton will transform into a neutron, a positron,[^6] and an electron neutrino (which has the label $\nu _e$). Both the positron and the electron neutrino are ejected while the neutron remains in the nucleus. Like the electron in $\beta ^{-}$ decay, the positron has a ton of energy and is called a $\beta ^{+}$ particle. An example of an isotope that undergoes $\beta ^{+}$ decay is potassium-40, which is found in bananas and decays to argon-40:

```{math}
{}^{40}_{19}\text{K}^{}_{21} \rightarrow {}^{40}_{18}\text{Ar}^{}_{22} + \beta^{+} + \nu_e
```

The general formula for $\beta ^+$ decay is:

```{math}
:label: eq-10-9
{}^{A}_{Z}\text{X}^{}_{N}\rightarrow {}^{A}_{Z-1}\text{X}^{}_{N+1}+\beta^++\nu_e
```

**Electron Capture**

The nucleus will steal an electron from the atom. That electron and a proton in the nucleus transform into a neutron and an electron neutrino. The electron neutrino is ejected while the neutron stays in the nucleus. An example of an isotope that undergoes electron capture is beryllium-7, which decays to lithium-7:

```{math}
{}^{7}_{4}\text{Be}^{}_{3} + e \rightarrow {}^{7}_{3}\text{Li}^{}_{4} + \nu_e
```

The general formula for electron capture is:

```{math}
:label: eq-10-10
{}^{A}_{Z}\text{X}^{}_{N}+e\rightarrow {}^{A}_{Z-1}\text{X}^{}_{N+1}+\nu_e
```

**$\alpha$ Decay (Alpha Decay)**

Heavy nuclei can emit a cluster of two protons and two neutrons known as an $\alpha$ particle. This usually happens when a pair of protons is far enough away from the other protons that the Coulomb force from all the other protons is larger than the strong nuclear force (discussed in Sect. [](#sec-10-4)), which keeps those protons attached to the nucleus. As we will see in Sect. [](#sec-10-6), an $\alpha$ particle is a super-stable combination of protons and neutrons. An example of an isotope that undergoes $\alpha$ decay is radon-222, which is a gas that leaks into some basements and decays to polonium-218:

```{math}
{}^{222}_{86}\text{Rn}^{}_{136}\rightarrow {}^{218}_{84}\text{Po}^{}_{134}+\alpha
```

The general formula for $\alpha$ decay is:

```{math}
:label: eq-10-11
{}^{A}_{Z}\text{X}^{}_{N}\rightarrow {}^{A-4}_{Z-2}\text{X}^{}_{N-2} + \alpha
```

**Spontaneous Fission**

While most heavy nuclei undergo $\alpha$ decay, superheavy atoms can emit nuclei of other elements. For example, californium-252 (98 protons and 154 neutrons) can break apart into xenon-140 (54 protons and 86 neutrons), ruthenium-108 (44 protons and 64 neutrons), and 4 neutrons (notice that $140+108+4=252$). This is called spontaneous fission:

```{math}
{}^{252}_{98}\text{Cf}^{}_{154}\rightarrow {}^{140}_{54}\text{Xe}^{}_{86}+{}^{108}_{44}\text{Ru}^{}_{64}+4\,\text{n}
```

In the above equation, both xenon-140 and ruthenium-108 are considered daughters.

If the balance between neutrons and protons deviates too far from a stable equilibrium, the nucleus will undergo radioactive decay. Some isotopes can undergo two or more forms of decay. For example, francium-220 undergoes $\alpha$ decay 99.65% of the time and $\beta ^{-}$ decay for the remaining 0.35%. Radium-226 almost always undergoes $\alpha$ decay, but $3.2\times 10^{-9}$% of the time it will undergo spontaneous fission by emitting a carbon-14 nucleus. Exploring the physics behind the balance between neutrons and protons is the topic of Sect. [](#sec-10-6).

**Will’s Rant**

It is important to understand that during $\beta ^{-}$ decay, $\beta ^{+}$ decay, and electron capture, particles cease to exist and new particles come into existence. Some books imply, for example, that a neutron is composed of a proton, an electron, and an anti-electron neutrino, as if you could look inside the neutron and find those three particles squished together. This is incorrect and drives me a little crazy, hence the rant ☺. The neutron is actually composed of three smaller particles called quarks, a topic in Chap. [](#ch-11). What is important here is that during $\beta ^{-}$ decay, the neutron ceases to exist. The neutron is present one moment and gone the next. The proton, electron, and anti-electron neutrino did not exist before the decay; these particles are created during the decay. In contrast, no new particles are created or destroyed in neutron emission, proton emission, or $\alpha$ decay.

There is a general rule about whether or not an isotope will undergo radioactive decay. In fact, this rule is more general than radioactive decay. As a general rule of nature, things try to get to the place of lowest energy.

**A General Rule of Nature**

A system always seeks to reach a state of lower energy.

As an analogy, think about a ball that is sitting halfway up a bowl. When released, the ball will try to get to the lowest point in the bowl and, with friction present, will eventually settle at this lowest point. The reason the ball settled at the lowest point is because this is the place of lowest energy.

Consider the radioactive decay of carbon-14: 

```{math}
{}^{14}_{6}\text{C}^{}_{8}\rightarrow {}^{14}_{7}\text{N}^{}_{7}+\beta^-+\bar{\nu}_e
```

The daughter nucleus, nitrogen-14, has lower energy than the parent, carbon-14. The decay happens because carbon-14 is a higher energy state than nitrogen-14, see Fig. [](#fig-10-2). The higher energy state has a lifetime of about 5700 years. After that characteristic time, it will decay to nitrogen-14. We will discuss the mechanisms behind radioactive decay in Sects. [](#sec-10-4), [](#sec-10-5) and [](#sec-10-6).
```{figure} ../images/ch-10/541577_1_En_10_Fig2_HTML.png
:label: fig-10-2
:alt: An example of how to think about why carbon-14 decays to nitrogen-14

An example of how to think about why carbon-14 decays to nitrogen-14

```

All unstable isotopes have a characteristic time for decay, known as the half-life, represented by the parameter $t_{1/2}$. Radioactive decay is a random process, but we can state probabilities for whether an isotope has decayed. Half-life is defined as the time it takes for there to be a 50% probability that the isotope has decayed. If the radioactive sample is large enough, the half-life can also be thought of as the time it takes for half of the parent nuclei to decay to the daughter nucleus. The number of remaining parents as a function of time is given by the formula: 

```{math}
:label: eq-10-12
N(t)=N_0 \Bigl(\frac{1}{2}\Bigr)^{\frac{t}{t_{1/2}}},
```

where $N_0$ is the number of radioactive atoms we start with, *t* is the time elapsed, and $t_{1/2}$ is the half-life. For example, rubidium-84 has a half-life of $t_{1/2}=32.82$ days. If we had a sample of 1,000,000,000 rubidium-84 atoms, half would decay after 32.82 days leaving about 500,000,000 rubidium-84 atoms. Of those remaining atoms 500,000,000 rubidium-84 atoms, half of those will decay in the next 32.82 days. This continues until there are no radioactive atoms remaining, see Table [](#tbl-10-2). 

(tbl-10-2)=
**Table 10.2** How radioactive rubidium-84 atoms decay over time

| $t_{1/2}$ | Days | $N(t)$ |
| --- | --- | --- |
| 0 | 0 | 1,000,000,000 |
| 1 | 32.82 | 500,000,000 |
| 2 | 65.64 | 250,000,000 |
| 3 | 98.46 | 125,000,000 |
| 4 | 131.28 | 62,500,000 |
| 5 | 164.10 | 31,250,000 |
| 6 | 196.92 | 15,625,000 |
| 7 | 229.74 | 7,812,500 |
| 8 | 262.56 | 3,906,250 |
| 9 | 295.38 | 1,953,125 |

**Extra Fun**

Carbon-14 is a radioactive isotope of carbon with a half-life of about 5700 years. It is created in the atmosphere when high energy neutrons from space, also known as cosmic rays, slam into the stable isotope nitrogen-14. The high energy neutron basically crashes into a proton in the nitrogen-14 nucleus, pushing the proton out while remaining behind. This radioactive carbon-14 attaches to an oxygen molecule to form radioactive carbon dioxide. Since there is a source (cosmic rays hitting nitrogen-14) and a sink (radioactive decay), the atmosphere reaches an equilibrium between the carbon-12 (the stable isotope) and carbon-14 forms of carbon dioxide. This equilibrium results in a constant isotopic abundance. If you collected a bunch of carbon dioxide from the air, about 1 molecule in every $10^{12}$ is radioactive. Living organisms in contact with the atmosphere breathe in, absorb, or ingest this radioactive carbon dioxide, thereby reaching equilibrium with the atmosphere. If the organism ceases interaction with the atmosphere,[^7] the isotopic abundance decreases (the radioactive carbon decays without being replaced). If sometime later you dig up the formally living being and you know the starting isotopic abundance, you can quickly calculate how long that being has been removed from the atmosphere. This process is known as radiocarbon dating. There are other types of radioactive dating including radioargon dating and radiokrypton dating.

(sec-10-3)=
## 10.3 The Table of Isotopes

The table of isotopes, also known as the table of nuclides, is similar to the periodic table, but includes all known elements and isotopes. Figure [](#fig-10-3) is a screenshot of the table of isotopes from a website maintained by the International Atomic Energy Agency (IAEA).[^8] Figure [](#fig-10-4) is a zoom in for the lighter elements. The vertical axis represents the number of protons in the isotope, while the horizontal axis represents the number of neutrons in the isotope. The entire row with 2 protons consists of helium isotopes; the entire row with 63 protons consists of europium isotopes. The black boxes indicate stable isotopes, and the colors representing the various types of radioactive decay are shown as insets in both Figs. [](#fig-10-3) and [](#fig-10-4). The interactive table is a lot of fun to play with.
```{figure} ../images/ch-10/541577_1_En_10_Fig3_HTML.png
:label: fig-10-3
:alt: A screenshot of the entire table of isotopes from the Live Chart of Nuclides maintained by the IAEA: [https://www-nds.iaea.org/relnsd/vcharthtml/VChartHTML.html](https://www-nds.iaea.org/relnsd/vcharthtml/VChartHTML.html) Note: I added the axes and the legend. Some isotopes have more than one type of decay. The legend shows the dominate decay

A screenshot of the entire table of isotopes from the Live Chart of Nuclides maintained by the IAEA: [https://www-nds.iaea.org/relnsd/vcharthtml/VChartHTML.html](https://www-nds.iaea.org/relnsd/vcharthtml/VChartHTML.html) Note: I added the axes and the legend. Some isotopes have more than one type of decay. The legend shows the dominate decay

```
```{figure} ../images/ch-10/541577_1_En_10_Fig4_HTML.png
:label: fig-10-4
:alt: A zoom in screenshot of the lighter elements from the table of isotopes. Note: I added the axes and the legend

A zoom in screenshot of the lighter elements from the table of isotopes. Note: I added the axes and the legend

```

(sec-10-4)=
## 10.4 The Strong Nuclear Force

**Important Reminder**

When two particles are interacting, there is a force between them. For example, an electron and a proton are attracted to each other because they have opposite charges. That attractive force is called the Coulomb force, which is also known as the electrostatic force.

We learned in Sect. [](#sec-10-2) that an imbalance in the ratio of protons to neutrons results in radioactive decay. If the balance is “good”, the atom is stable. If there is an imbalance, there will exist a daughter system that has a lower energy than the parent system, see Fig. [](#fig-10-2) for an example. To fully explore the nucleus and atomic stability, we will first study the strong nuclear force (this section). The strong nuclear force is an attractive force that keeps the nucleons in the nucleus. In Sect. [](#sec-10-5) we will explore the weak nuclear force, which is the force that facilitates $\beta ^-$ decay, $\beta ^+$ decay, and electron capture. Basically, if a process involves the annihilation and creation of particles, the weak nuclear force is involved. Finally, we will tie everything together in Sect. [](#sec-10-6) using energy principles to explore why some isotopes are stable and some are not.

The helium-4 nucleus has 2 protons and 2 neutrons. Since both protons have positive charge, they repel each other due to the Coulomb force. The protons in helium-4 are separated by about $1\times 10^{-15}$ m. This incredibly small distance is called a femtometer, which is given the unit fm: $1 \times 10^{-15}\,\text{m} = 1\,\text{fm}$. The repulsive Coulomb force between the two protons has a magnitude of about 230 newtons (about 50 pounds of force). Considering each proton has a mass of only $1.67\times 10^{-27}\,\text{kg}$, this is huge!! If we took a free proton and acted on it with 230 Newtons of force, the proton would accelerate at $1\times 10^{29}\,\text{m}/\text{s}^2$!!!! For comparison, freefall on earth is only about $9.8\,\text{m}/\text{s}^2$. The relative comparison is so enormous, I have absolutely no idea how to convey how large that repulsive force is.

However, the protons inside a helium-4 nucleus do not fly apart.[^9] Therefore, there must be some other attractive force that is larger than the repulsive Coulomb force to stop the protons from being pushed out of the nucleus. An intuitive guess is that maybe gravity is keeping the protons in the nucleus. After all, gravity is the attractive force that we interact with everyday. Remarkably, gravity is an extremely weak force. You will explore just how weak gravity is in Problem [](#prob-10-6). In addition, neutrons have no charge, so they don’t feel any Coulomb force. What is keeping neutrons in the nucleus?

The force keeping the nucleons “glued” to one another is the strong nuclear force.[^10] The strong nuclear force acts on both neutrons and protons, and it can be either an attractive or repulsive force. At a distance of 1 femtometer, the strong nuclear force is attractive and approximately 100 times stronger than the repulsive Coulomb force. Figure [](#fig-10-5) shows a graph of both the Coulomb force and the strong nuclear force.[^11] At short distances, both the strong nuclear force and the Coulomb force are repulsive. Somewhere around 0.85 fm, the nucleons start to be attracted by the strong nuclear force. The really important thing to take from this graph is that at around 1 fm, the strong nuclear force is more attractive than the Coulomb force is repulsive. The total force is the sum of the two, which for small distances, is attractive. Outside of about 5 fm, the strong nuclear force is basically 0 and the Coulomb force will dominate, pushing the protons away from each other.
```{figure} ../images/ch-10/541577_1_En_10_Fig5_HTML.png
:label: fig-10-5
:alt: An illustrative plot showing the forces between nucleons inside the nucleus. The strong nuclear force is attractive (negative force) above about 0.85 fm but falls off very quickly. The Coulomb force between two protons, which is increased by a factor of 10 for visibility, is always repulsive (positive force)

An illustrative plot showing the forces between nucleons inside the nucleus. The strong nuclear force is attractive (negative force) above about 0.85 fm but falls off very quickly. The Coulomb force between two protons, which is increased by a factor of 10 for visibility, is always repulsive (positive force)

```

Figure [](#fig-10-5) is also useful for understanding why we cannot have a stable atom with more than about 200 nucleons. A proton near the edge of a large nucleus is far away from the nucleons that are on the other side of the nucleus. Because the strong nuclear force goes to zero so quickly, that proton does not feel any attractive strong nuclear force from the distant nucleons. It does, however, still feel the repulsive Coulomb force from all the other protons. Consequently, this proton near the edge will be repelled away. This is why the periodic table does not have any stable elements above lead-208. The next atom on the periodic table is bismuth. Bismuth has no stable isotopes, although bismuth-209 is super long-lived with a half-life of $2\times 10^{19}$ years.

**An Analogy**

The Coulomb force is a long-range force. Two protons will weakly repel each other even if they are 10 meters apart. The strong nuclear force is similar to a contact force such as two pieces of Velcro. When the two pieces of Velcro are touching, they stick together really well. The moment they are no longer touching, the force between the two is zero.

So, why do we need neutrons for a stable nucleus? Neutrons add additional attractive strong nuclear force to the nucleus without adding any additional repulsive Coulomb forces. A nucleus with only 2 protons, which would be helium-2, is extremely unstable. The Coulomb force, while small compared to the strong nuclear force, is still large enough to push the two protons apart. So, the decay of helium 2 would be two protons flying away in different directions. Adding a neutron to the nucleus adds additional strong nuclear force (attractive) without adding any additional repulsive Coulomb forces. Both helium-3 (2 protons and 1 neutron) and helium-4 (2 protons and 2 neutrons) are stable. Helium-5 (2 protons and 3 neutrons) is unstable. But why is helium-5 unstable? An extra neutron should just add additional attractive strong nuclear force with no additional repulsive Coulomb force. In the end, it comes down to the energy analogy: there is a daughter system with lower energy than helium-5. We will explore this more in Sect. [](#sec-10-6).

**Strong Nuclear Force Summary**

Inside the nucleus, the strong nuclear force is the mechanism that keeps nucleons in the nucleus. It is a short-range force. Neutrons add additional attractive strong nuclear force without adding any additional repulsive Coulomb force. If there are too many protons compared to neutrons or the nucleus is too large, proton emission or $\alpha$ decay may occur.

**Fun Fact**

If the strong nuclear force were only 2% larger, helium-2 could undergo $\beta ^-$ decay to hydrogen-2 (also known as deuterium or heavy hydrogen) instead of breaking apart into 2 protons.[^12]

(sec-10-5)=
## 10.5 The Weak Nuclear Force

The strong nuclear force holds nucleons in the nucleus. If the balance between protons and neutrons is not correct, the nucleus will be unstable and undergo radioactive decay (more on this in Sect. [](#sec-10-6)). We have hinted at possible mechanisms behind proton emission and $\alpha$ decay (the Coulomb force overwhelms the strong nuclear force), but nothing we have talked about so far explains the forces behind the annihilation or creation of particles (i.e., $\beta ^-$, $\beta ^+$, and electron capture; see the beginning of Sect. [](#sec-10-2) for a recap of the types of radioactive decays). To explore those decays, we need to understand the weak nuclear force.

**Important**

If the radioactive decay process involves the annihilation and creation of particles, the weak nuclear force is involved.

Let’s start by reviewing a few important concepts. The Coulomb force acts only on charged particles. It is a long-range force and can be either an attractive force (opposite charges) or a repulsive force (same charges). The strong nuclear force acts on protons and neutrons but not on electrons. It is a short-range force with a range on the order of a few femtometers and is, for our purposes, an attractive force.

The weak nuclear force, sometimes referred to simply as “the weak force,” acts on electrons, protons, and neutrons. Like the Coulomb force, it can be either attractive or repulsive. However, unlike the Coulomb force, it is an *extremely* short-range force. While the strong nuclear force has a range on the order of a few femtometers, the weak nuclear force has a range on the order of $1\times 10^{-18}\,\text{m}$, or about 0.1% of the diameter of a proton. This distance is called an attometer (am): $1\times 10^{-18}\,\text{m}=1\,\text{am}$.

As you can probably guess from the name, the weak nuclear force is weak compared to the strong nuclear force and the Coulomb force. Consider two protons about 1 fm apart. The weak nuclear force is about 1 million times weaker than the strong nuclear force. For stable atoms, the strong nuclear force dominates the weak nuclear force, but for atoms with a few too many neutrons or protons, the weak nuclear force can play an important role.

To explore the importance of the weak nuclear force, let’s discuss the neutron. A neutron outside of a nucleus, called a free neutron, will undergo radioactive decay with a half-life of about 10.2 minutes according to the equation: 

```{math}
:label: eq-10-13
n \rightarrow p +\beta^{-}+\bar{\nu}_e,
```

where *n* is the neutron that decays into a proton *p*, a $\beta ^{-}$ particle (a high energy electron), and an anti-electron neutrino $\bar {\nu }_e$.

**A Reminder of an Important Rule and an Analogy from Sect. [](#sec-10-2)**

**A General Rule of Nature**

A system always seeks to reach a state of lower energy.

**The Analogy**

Think about a ball that is sitting half way up a bowl. When released, the ball will try to get to the lowest point in the bowl and, with friction present, will eventually settle at this lowest point. The reason the ball settled at the lowest point is because this is the place of lowest energy. Both gravity and friction were the mechanisms (forces) that got the ball to settle at the bottom of the bowl. Gravity pulled the ball down, and friction dissipated the extra energy into heat. The ball went from a higher energy state to a lower energy state.

The proton, $\beta ^-$ particle, and anti-electron neutrino (i.e., the daughter system) have lower energy than the free neutron (the parent system). Something had to facilitate this system going from higher energy to lower energy. The force behind this interaction is the weak nuclear force. So, according to the general rule of nature, a free neutron “wants” to get to a place of lower energy, and the weak nuclear force is the force that helps it get there.

A free neutron will undergo radioactive decay facilitated by the weak nuclear force. For a neutron inside a nucleus, there is also the strong nuclear force from other nucleons interacting with the neutron. The question to ask is, “Is there a place of lower energy for the system to go?” If the answer is yes, the weak nuclear force will eventually get the system to a lower energy. If the answer is no, then the weak force has no place to push the system. So, the weak nuclear force will cause the free neutron to cease existing and create a proton, $\beta ^-$ particle, and anti-electron neutrino. In contrast, there is no place of lower energy for, for example, a helium-4 nucleus. So, the helium-4 nucleus is stable.

If a neutron in a helium-4 nucleus were to undergo $\beta ^-$ decay, the equation would be: 

```{math}
\begin{array}{c} {}^{4}_{2}\text{He}^{}_{2} \rightarrow {}^{4}_{3}\text{Li}^{}_{1}+\beta^-+\bar{\nu}_e \\ \text{This does not happen!} \end{array}
```

The system on the right of this equation (the lithium-4 atom, the $\beta ^-$ particle, and the anti-electron neutrino) has a higher energy than the helium-4 atom. Therefore, this process does not occur.

**Current Summary**

As a general rule of thumb:

- If there are way too many neutrons in the nucleus, a neutron will escape (more on this in Sect. [](#sec-10-6)) to get the system to a point of lower energy.
- If there are a few too many neutrons in the nucleus, the weak nuclear force will facilitate $\beta ^{-}$ decay to get the system to a point of lower energy.
- If there are way too many protons in the nucleus, the Coulomb force will push a proton out of the nucleus to get the system to a point of lower energy.

A free proton is stable[^13] because a free proton is already the system of lowest energy. However, a proton can decay inside the nucleus. How?!? The answer always goes back to the energy argument: a system wants to get to the place of lowest energy. If a nucleus has a few too many protons, the weak nuclear force will find a way to that place of lower energy. In this case, a proton can transform into a neutron, a positron (more on positrons in Chap. [11]), and an electron neutrino. This is called $\beta ^+$ decay. As an example, consider the following decay for oxygen-15: 

```{math}
:label: eq-10-14
{}^{15}_{8}\text{O}^{}_{7}\rightarrow {}^{15}_{7}\text{N}^{}_{8}+\beta^{+}+\nu_e
```

This decay, which has a half-life of about 2 minutes, is used in Positron Emission Tomography (PET) scans to measure blood flow and oxygen metabolism.[^14] A proton in the oxygen-15 nucleus transforms into a neutron, a $\beta ^+$ particle (positron), and an electron neutrino. The right-hand side of that equation is lower energy than the left-hand side, so the weak nuclear force will make this decay happen.

The daughter particle, nitrogen-15, is the lowest energy state for this system, so it does not undergo any further type of decay. Therefore, neither of the following occurs: 

```{math}
\begin{array}{c} {}^{15}_{7}\text{N}^{}_{8}\rightarrow {}^{15}_{6}\text{C}^{}_{9}+\beta^{+}+\nu_e \\ {}^{15}_{7}\text{N}^{}_{8}\rightarrow {}^{15}_{8}\text{O}^{}_{7}+\beta^-+\bar{\nu}_e \\ \text{Neither of these happen!} \end{array}
```

Both of these processes have daughter systems with higher energy than the parent system, so they will never occur.

There is one more process in which the weak nuclear force plays an important role. For some atoms, the electrons “orbiting” the nucleus can come too close. If that happens **and** there is a daughter system with a lower energy, that electron and a proton in the nucleus will transform into a neutron and an electron neutrino. This is called electron capture. The weak nuclear force, once again, is the force that is facilitating this process. I want to emphasize that the proton and electron do not combine to form a neutron. The proton and electron literally stop existing, and a neutron and an electron neutrino start existing (see Will’s rant in Sect. [](#sec-10-2)). An atom that undergoes electron capture decay is the beryllium-7 atom, which has a half-life of about 53 days. The equation to describe beryllium-7 decay is: 

```{math}
:label: eq-10-15
{}^{7}_{4}\text{Be}^{}_{3}+e\rightarrow {}^{7}_{3}\text{Li}^{}_{4} + \nu_e,
```

where ${ }^{7}_{3}\text{Li}_{4}$ is the daughter lithium-7 atom. Once again, this process can only occur because the daughter system has lower energy than the parent system.

**Summary for the Weak Nuclear Force**

If particles are going to be annihilated and created to get the system to a place of lower energy, the weak nuclear force is the force that facilitates the process.

**Current Summary**

As a general rule of thumb:

- If there are way too many neutrons in the nucleus, a neutron will escape (more on this in Sect. [](#sec-10-6)) to get the system to a point of lower energy.
- If there are a few too many neutrons in the nucleus, the weak nuclear force will facilitate $\beta ^{-}$ decay to get the system to a point of lower energy.
- If there are a few too many protons in the nucleus, the weak nuclear force will facilitate either $\beta ^{+}$ decay or electron capture to get the system to a point of lower energy.
- If there are way too many protons in the nucleus, the Coulomb force will push a proton out of the nucleus to get the system to a point of lower energy.

(sec-10-6)=
## 10.6 The Nuclear Shell Model and Energetics

When we talked about the strong nuclear force, we had an unanswered question: “Why is a nucleus with too many neutrons unstable?” After all, neutrons only add an attractive force to the system. There was an explanation about the existence of a lower energy state, but that explanation, at least to me, felt unsupported. In this section, we will explore what happens when more and more nucleons are added to a nucleus. We will also see why, from an energy viewpoint, different types of decays occur and why stable lighter atoms have about equal numbers of protons and neutrons while stable heavier atoms have more neutrons than protons, see the black boxes in Fig. [](#fig-10-3). To do so, we will rely on the general rule of nature and the Pauli Exclusion Principle, see Chap. [](#ch-8), Sect. [](#sec-8-5) for a review of the Pauli Exclusion Principle.

**Important Reminder**

**Pauli Exclusion Principle**

Two fermions cannot simultaneously occupy the same quantum state; that is, no two fermions can have the same set of quantum numbers within a quantum system. Electrons, protons, and neutrons are all fermions with spin quantum number 1/2.

In Chap. [](#ch-8), we learned that electrons fill shells. The $1\text{s}$ subshell can hold two electrons. Using the ket notation $|{n~\ell ~m_\ell ~s~m_s}\rangle$, the two electrons have quantum numbers $|{1~0~0~\frac {1}{2}~\frac {1}{2}}\rangle$ and $|{1~0~0~\frac {1}{2}\,\text{-} \frac {1}{2}}\rangle$. Notice they have different quantum numbers as required by the Pauli Exclusion Principle. All six electrons in a filled $2\text{p}$ subshell also have different quantum numbers. The $1\text{s}$ electrons are in a lower energy state than the $2\text{p}$ electrons, but the Pauli Exclusion Principle prevents any more electrons from being in the $1\text{s}$ subshell. The dominant interaction between the electrons and the nucleus is the electromagnetic force, so this force determines how many subshells there are for a particular shell. Table [](#tbl-10-3) shows the maximum number of electrons that can fit into each subshell and shell. I want to emphasize that every electron has a unique set of quantum numbers. Neon has a total of ten electrons to completely fill the $n=1$ and $n=2$ shells. Each of those ten electrons has a unique set of quantum numbers. As a reminder, electrons do not have to completely fill a shell before starting to fill the next shell (see Fig. [](#fig-8-3)). For example, potassium has a single electron in the 4s subshell with no electrons in the 3d subshell. This ordering is determined by the electromagnetic force. 

(tbl-10-3)=
**Table 10.3** Electron configuration for shells and subshells

| Shell | Subshell | Subshell max electrons | Shell max electrons |
| --- | --- | --- | --- |
| 1 | 1s | 2 | 2 |
| 2 | 2s | 2 | 8 |
|  | 2p | 6 |  |
| 3 | 3s | 2 | 18 |
|  | 3p | 6 |  |
|  | 3d | 10 |  |
| 4 | 4s | 2 | 32 |
|  | 4p | 6 |  |
|  | 4d | 10 |  |
|  | 4f | 14 |  |

Protons and neutrons are also fermions with a spin quantum number of $1/2$. Therefore, they also fill nuclear shells and subshells. Since protons and neutrons are different particles, they fill individual nuclear shells; protons fill the proton shells and neutrons fill the neutron shells. Isotopes with filled nuclear shells and subshells tend to be more stable. This stability occurs at so-called “magic numbers.” The magic numbers for protons indicate how many protons are in the nucleus when this extra stability occurs. The magic numbers for protons are 2, 8, 20, 28, 50, 82, and 114. The magic numbers for neutrons are 2, 8, 20, 28, 50, 82, and 126. Oxygen-16 (8 protons and 8 neutrons) is called doubly magic because it has both a filled proton shell and a filled neutron shell. Oxygen-16 is an extra stable nucleus.

The configuration of the nuclear shells is very different from the electron shells because the nuclear shells are determined by both the strong nuclear force and the electromagnetic force. However, every proton (or neutron) in the nucleus has a unique set of quantum numbers and fills the proton (or neutron) shells. The last magic number for protons (114) is smaller than the last magic number for neutrons (126). This is because protons have an additional Coulomb force acting on them, and that additional force causes a different structure for the shells. I want to emphasize that these are not electron shells! Protons and neutrons do not fill up their nuclear shells according to the Madelung rule (see Fig. [](#fig-8-3)).

Let’s use this as a starting point to understand nuclear stability. Figure [](#fig-10-6) shows a planetary model for protons and neutrons filling their respective shells. As a reminder, the planetary model is not correct. Protons and neutrons are quantum mechanical particles that have wave-like properties. Nonetheless, this nuclear shell model can help us understand the stability of the nucleus.
```{figure} ../images/ch-10/541577_1_En_10_Fig6_HTML.png
:label: fig-10-6
:alt: The nuclear shells for protons and neutrons. Starting from the left, helium-4 is a stable isotope. The system is in its lowest energy state. The middle diagram is an example of beta-minus decay. The right diagram is an example of proton emission

The nuclear shells for protons and neutrons. Starting from the left, helium-4 is a stable isotope. The system is in its lowest energy state. The middle diagram is an example of $\beta -$ decay. The right diagram is an example of proton emission

```

The number of nucleons that can occupy a subshell is indicated on the left. The lowest energy proton shell can hold two protons (one spin up and one spin down) and the lowest energy neutron shell can hold two neutrons. This is the first magic number, 2. The next shell can hold a total of six nucleons distributed among two subshells. The sum of all protons (or neutrons for the neutron shells) that completely fill the first two shells is the second magic number, $2+6=8$. The third grouping of subshells holds a total of twelve nucleons, a magic number of $2+6+12=20$, and so on. Notice that as the energy increases, the neutron shells are lower in energy than the proton shells. This is because the Coulomb force acts on the protons, but not on the neutrons, and also because neutrons have a slightly larger mass than protons. It should be noted that the energy spacings are not correct; they are greatly simplified for us to explore concepts. There are also higher energy shells that are not shown in these diagrams.

Starting from the left diagram in Fig. [](#fig-10-6), we see that helium-4 is a stable isotope. In fact, this is a super-stable, doubly magic nucleus because it perfectly fills the lowest nuclear shell for both the protons and the neutrons. There isn’t any place of lower energy for any of the nucleons. The helium-4 nucleus is also the $\alpha$ particle from $\alpha$ decay. The middle diagram is an example of $\beta ^-$ decay. The system has a place of lower energy if the highest-energy neutron transforms into a proton (plus a $\beta ^-$ particle and anti-electron neutrino). One could ask the question, “Why is this $\beta ^-$ decay and not neutron emission?” The answer always come back to energy. For this scenario, it is energetically more favorable for the weak nuclear force to facilitate $\beta ^-$ decay than the neutron to just leave the nucleus. The right diagram is an example of proton emission. The highest-energy proton has a place to go to bring the system to a point of lower energy. It can leave the nucleus or undergo $\beta ^+$ decay. In this scenario, the Coulomb force makes proton emission energetically more favorable than $\beta ^+$ decay, so that is what happens. Finally, the left diagram in Fig. [](#fig-10-7) shows an example of $\beta ^+$ decay. In this scenario, it is energetically more favorable for the weak nuclear force to facilitate the decay of scandium-41 to calcium-41. And this is the essence of stable versus unstable nuclei. If there is a state of lower energy, the system will try to get there. Sometimes the mechanism is proton emission, neutron emission, $\alpha$ decay, or spontaneous fission. Other times, the weak nuclear force facilitates the annihilation and creation of particles. In the end, if there is a state of lower energy, the nucleus will decay to this lower state.
```{figure} ../images/ch-10/541577_1_En_10_Fig7_HTML.png
:label: fig-10-7
:alt: Starting from the left, scandium-41 is an example of beta-plus decay. The middle diagram and right diagram are examples of stable nuclei. Oxygen-16 is stable and has 8 protons and 8 neutrons. Germanium-72 is also stable, but it needs 40 neutrons to balance the energy of the 32 protons. The three dots on the subshell that can hold 8 nucleons are indicating the shell is filled; I couldn’t fit 8 nucleons on the line

Starting from the left, scandium-41 is an example of $\beta ^+$ decay. The middle diagram and right diagram are examples of stable nuclei. Oxygen-16 is stable and has 8 protons and 8 neutrons. Germanium-72 is also stable, but it needs 40 neutrons to balance the energy of the 32 protons. The three dots on the subshell that can hold 8 nucleons are indicating the shell is filled; I couldn’t fit 8 nucleons on the line

```

There is another interesting concept I’d like to explore with you. For smaller mass, stable nuclei, there are roughly equal numbers of neutrons and protons. This can be seen by the black boxes (stable nuclei) in Fig. [](#fig-10-3), which make a linear line with a slope of one for smaller mass nuclei. This is because, for smaller masses, the nuclear energy levels for the protons and neutrons are about the same. This is shown in the left diagram in Fig. [](#fig-10-6) for helium-4 and the middle diagram in Fig. [](#fig-10-7) for oxygen-16. However, as more protons are packed into the nucleus, the Coulomb force becomes larger and larger, increasing the nuclear energy levels for the protons. As such, more neutrons are needed to balance the energy of the protons and neutrons. This is an equivalent way of saying more neutrons are needed to provide a larger strong nuclear force to overcome this increase in the Coulomb force repulsion. An example of a heavier nucleus is shown in the right diagram of Fig. [](#fig-10-7). Germanium-72 needs eight more neutrons than protons to create a stable balance between the total proton energy and the total neutron energy. In fact, germanium-70, -72, -73, and -74 are all stable.[^15] Notice how the diagrams for all the stable nuclei have approximately equal energy for the highest-energy neutrons and protons while the unstable nuclei do not.

If the nucleus gets too big, there is always a state of lower energy. The largest mass nucleus that is stable is lead-208. Lead-208 has a proton number of 82 and a neutron number of 126, which are both magic numbers. There are also isotopes that have two or more decay paths to states of lower energy. This is more likely for larger mass nuclei. For example, bismuth-212 can undergo both $\alpha$ decay (36% of the time) and $\beta ^-$ decay (64% of the time). For the heaviest of atoms, the dominant decay is not the annihilation and creation of particles, but particles simply leaving the nucleus to reach a lower energy state, see Fig. [](#fig-10-3) or the online table of isotopes.

The nucleus is an amazing and wonderful system to study. It is such a rich system to explore and is needed to understand the world of the super small. Atomic physicists tend to use lasers to excite electrons to higher energy atomic states. We care about the nucleus, but usually in the context of how the structure of the nucleus affects electronic energy levels, for example, isotope shifts discussed in Sect. [](#sec-10-1).

Nuclear physicists conduct similar experiments on nuclei with the goal of understanding the internal forces at play. Just like electrons, protons and neutrons can be excited to higher energy states. Compared to the Coulomb force and the mass of the electron, the strong nuclear force and the mass of the nucleons are much larger! This results in nuclear excited states with much higher energies than atomic energy levels. For the most part, we can’t use lasers to excite nucleons to higher energy states. Thorium-229 is the one exception. The lowest energy nuclear excited state of thorium-229 requires a laser with a wavelength $\lambda = 150\,\text{nm}$, or a frequency of $2.00 \times 10^{15}\,\text{Hz}$. That laser isn’t easy to make or use, but it is possible! The next isotope with the lowest lying nuclear excited state is protactinium-234, which would require a laser with $\lambda = 16.8\,\text{nm}$ ☹. However, nuclear physicists are clever and use other methods to study nuclear excited states. For example, nuclear physicists can use accelerators and high-energy collisions to excite a nucleus and then measure the energy of the high-energy photons that are emitted. They also use radioactive decay. For this technique, some parent systems decay to excited nuclear levels that then decay via high-energy photons. If you find the nucleus as fascinating as I do, nuclear physics might be the field for you!

(sec-10-7)=
## 10.7 Problems

```{exercise}
:label: prob-10-1
:enumerator: 10.1

Consider the transition in the beryllium atom $1\text{s}^2 2\text{s}^2~{ }^{1}\text{S}_{0}\rightarrow 1\text{s}^2 2\text{s}2\text{p}~{ }^{1}\text{P}_{1}$. The resonance frequency for this transition is $f_r=1,276,080,100$ MHz.

(a) Calculate the normal mass shift as a function of mass number for $A'=7$ to $A'=12$ with respect to the stable isotope beryllium-9.

(b) Make a (modified) King plot of the normal mass shift versus $A'$.
```

```{exercise}
:label: prob-10-2
:enumerator: 10.2

Write the decay equation for the following radioactive decays:

- $\beta ^-$ decay:
  - Potassium-40 $({ }^{40}_{19}\text{K}_{21})$: Potassium-40 is the largest source of natural radioactivity in animals, including humans. About 89% of all potassium-40 decay is $\beta ^-$ decay.
  - Rubidium-87 $({ }^{87}_{37}\text{Rb}_{50})$: Rubidium-87 is used in rubidium-strontium dating, a radiometric dating technique used to determine the age of rocks and minerals.
- $\beta ^+$ decay:
  - Sodium-22 $({ }^{22}_{11}\text{Na}_{11})$: Sodium-22 is used as a calibration source for positron emission tomography (PET) scans.
  - Carbon-11 $({ }^{11}_{6}\text{C}_{5})$: Carbon-11 is used in PET scans to detect sites of prostate cancer.
- Electron capture:
  - Potassium-40 $({ }^{40}_{19}\text{K}_{21})$: Potassium-40 is used in potassium-argon dating. About 11% of all potassium-40 decay is $\beta ^-$ decay.
  - Beryllium-7 $({ }^{7}_{4}\text{Be}_{3})$: Beryllium-7 is used in cosmogenic isotope studies to understand solar activity and atmospheric processes. It is also the lightest element to undergo electron capture.
- Alpha decay:
  - Uranium-238 $({ }^{238}_{92}\text{U}_{146})$: Uranium-238 produces about 40% of the radioactive heat produced in the earth.
  - Thorium-232 $({ }^{232}_{90}\text{Th}_{142})$: Thorium-232 is used in thorium reactors and in dating geological formations through thorium-lead dating.
```

```{exercise}
:label: prob-10-3
:enumerator: 10.3 (Carbon Dating)

The current atmospheric isotopic abundance is $\frac {\text{carbon-14}}{\text{carbon-12}}=10^{-12}$.

(a) Using the table of isotopes or online resources, find the half-life of carbon-14.

(b) A mummy was recently found in what was the ancient city of Memphis. The egyptologist who led the expedition sends a sample of the mummy to a radiocarbon dating specialist for carbon dating. The results came back as isotopic abundance, and not a date. The isotopic abundance of the sample is $\frac {\text{carbon-14}}{\text{carbon=12}}=5.8 \times 10^{-13}$. Assuming the atmospheric isotopic abundance stays constant in time,[^16] estimate how long ago the individual who is now a mummy died?
```

```{exercise}
:label: prob-10-4
:enumerator: 10.4

Locate rubidium-84 in the table of isotopes. Given a sample of 1 billion rubidium-84 atoms, determine the composition of atoms remaining after 100 days.

Hint: Rubidium-84 decays into both krypton-84 and strontium-84.
```

````{exercise}
:label: prob-10-5
:enumerator: 10.5

A decay chain is a series of radioactive decays that shows the sequential process of decays. It is also known as a “radioactive cascade.” For example, oxygen-20 undergoes $\beta ^-$ decay to fluorine-20, which then undergoes $\beta ^-$ decay to neon-20, which is stable. So, the decay chain is:

```{math}
{}^{20}_{8}\text{O}^{}_{12}\xrightarrow{\beta^-}{}^{20}_{9}\text{F}^{}_{11}\xrightarrow{\beta^-}{}^{20}_{10}\text{Ne}^{}_{10}
```

Construct a decay chain for thorium-232, considering only the dominant decay mode at each step. When reaching bismuth-212, follow the decay path to thallium-208. The decay chain should terminate at lead-208.
````

````{exercise}
:label: prob-10-6
:enumerator: 10.6

Newton’s law of universal gravitation is a model of the gravitational force between two objects with mass. Mathematically, the force between two objects with mass $m_1$ and $m_2$ is:

```{math}
:label: eq-10-16
F_G=\frac{G m_1 m_2}{r^2},
```

where $G=6.674\times 10^{-11}~\frac {\text{N}\,\text{m}^2}{\text{kg}^2}$ is a constant of nature, known as the gravitational constant, and *r* is the distance between the two objects. The gravitational force between two objects is always attractive.

Coulomb’s law is a model of the force between two objects with charge. Mathematically, the force between two objects with charge $q_1$ and $q_2$ is:

```{math}
:label: eq-10-17
F_C=\frac{k q_1 q_2}{r^2},
```

where $k=8.988\times 10^{9}~\frac {\text{N}\,\text{m}^2}{\text{C}^2}$ is a constant of nature, known as the Coulomb constant, *r* is the distance between the two objects, and the unit $\text{C}$ stands for Coulomb. A proton has a charge of $+1.602\times 10^{-19}\,\text{C}$ and an electron has the same magnitude charge but opposite sign, $-1.602\times 10^{-19}\,\text{C}$.

(a) Consider two protons in a nucleus. How much larger is the Coulomb force compared to the gravitational force?

Hint: Take the ratio of the two forces first. The distance between the two protons will cancel out.

(b) For an object with mass $m_1$ at the surface of the earth, Newton’s law of universal gravitation is:

```{math}
:label: eq-10-18
F_G=\frac{G m_1 m_E}{R_E^2},
```

where $m_E=5.972\times 10^{24}\,\text{kg}$ is the mass of the earth, $R_E=6.378\times 10^6\,\text{m}$ is the radius of the earth. This formula can be simplified to:

```{math}
:label: eq-10-19
F_G=m_1 g,
```

where $g = \frac {G m_E}{R_E^2}$. What is the numerical value of *g*? The units should simplify to $\text{m}/\text{s}^2$.Hint: A newton $\text{N}$ is the same thing as $\frac {\text{kg}\,\text{m}}{\text{s}^2}$.

(c) Calculate the force of gravity between you and the earth. The conversion between pounds and kilograms is $1\,\text{kg} = 2.205\,\text{lbs}$.

(d) Find the ratio of the Coulomb force of two protons separated by $1\,\text{fm}$ to your answer in part (c). For context, you are much, much more massive than a proton!

(e) The magnitude of the strong nuclear force between two nucleons separated by $1\,\text{fm}$ is about $24{,}000\,\text{N}$. Find the ratio of this strong nuclear force compared to your answer in part (c).
````

```{exercise}
:label: prob-10-7
:enumerator: 10.7 (Advanced Math Problem: Connecting Half-Life to Lifetime)

Equation [](#eq-10-12) is the formula most everyone uses for radioactive decay. However, it can be useful to convert this equation to one of exponential decay: $N(t) = N_0 e^{-t/\tau }$, where $\tau$ is the lifetime. This is the same form we used to model the probability that an electron in an excited state decays to a lower energy state, see Sect. [](#sec-3-3)!

(a) Carbon-14 has a half-life of 5700 years. What is the lifetime?

(b) Make a graph of both equations. If your answer to part (a) is correct, the two functions should graph identically.
```

## References

1. Barwood, G.P., Gill, P., Rowley, W.R.C.: Frequency measurements on optically narrowed Rb-stabilised laser diodes at 780 nm and 795 nm. Appl. Phys. B 53 , 142–147 (1991). [https://doi.org/10.1007/BF00330229](https://doi.org/10.1007/BF00330229)
2. Keim, M., Arnold, E., Borchers, W., Georg, U., Klein, A., Neugart, R., Vermeeren, L., Silverans, R.E., Lievens, P.: Laser-spectroscopy measurements of 72–96Kr spins, moments and charge radii. Nucl. Phys. A 586 (2), 219–239 (1995). [https://doi.org/10.1016/0375-9474(94)00786-M](https://doi.org/10.1016/0375-9474(94)00786-M)
3. Reid, R.V.: Local phenomenological nucleon-nucleon potentials. Ann. Phys. 50 (3), 411–448 (1968). [https://doi.org/10.1016/0003-4916(68)90126-7](https://doi.org/10.1016/0003-4916(68)90126-7)
4. Bradford, R.A.W.: The effect of hypothetical diproton stability on the universe. J. Astrophys. Astron. 30 , 119–131 (2009). [https://doi.org/10.1007/s12036-009-0005-x](https://doi.org/10.1007/s12036-009-0005-x)

[^1]: $A=Z+N\rightarrow N=A-Z$: 1. Oxygen-17 has 8 protons, so $17-8=9$ neutrons 2. Hydrogen-2 has 1 proton, so $2 - 1 = 1$ neutron 3. Beryllium-9 has 4 protons, so $9 - 4 = 5$ neutrons.

[^2]: If you are paying close attention, you might ask the question, “Does $f_r$ refer to the transition frequency for the isotope with mass number *A* or $A'$?” The answer is neither. $f_r$ is a calculated transition frequency assuming a nucleus with infinite mass. However, in practice, you can use $f_r$ for either isotope or the calculated value for a nucleus with infinite mass. We can do this because isotope shifts are usually on the order of MHz to a few GHz, which is typically more than 100,000 times smaller than $f_r$. The formula to calculate the transition frequency assuming a nucleus with infinite mass is $\frac {m_e+M}{M}f_r$, where *M* is the mass of a nucleus for a particle isotope and $f_r$ is the transition frequency for that isotope. That fraction is very close to 1.

[^3]: On earth, about 72% of rubidium is rubidium-85 and about 28% is rubidium-87.

[^4]: Named after the British physicist William H. King.

[^5]: Historically, parent and daughter are the names used to describe radioactive decay. The terminology also shows up in biology during cell division (parent cell and daughter cells). Sometimes the daughter system is called the decay system.

[^6]: A positron is the antimatter partner to the electron. Antimatter is a topic in Chap. [](#ch-11).

[^7]: RIP ☹.

[^8]: I consider the Live Chart of Nuclides website one of three essential tools for an atomic and nuclear physicist: [https://www-nds.iaea.org/relnsd/vcharthtml/VChartHTML.html](https://www-nds.iaea.org/relnsd/vcharthtml/VChartHTML.html). The other two are the IAEA app for your phone, known as ‘Isotope Browser’, and the NIST spectral database, [https://www.nist.gov/pml/atomic-spectra-database](https://www.nist.gov/pml/atomic-spectra-database).

[^9]: This is a good thing!

[^10]: In Chap. [](#ch-11), we are going to talk about quarks, which are the subparticles that make up protons and neutrons. The strong nuclear force is also what keeps the quarks glued to one another inside the nucleon. However, the strong nuclear force extends outside of a nucleon to interact with other nucleons. The force that extends out of the nucleon is often called the “strong residual force”. Technically, it is still the same strong nuclear force, but there are subtle and important differences for how it behaves inside a nucleon and how it behaves between nucleons. Figure [](#fig-10-5) is an illustrative plot for the strong residual force between nucleons.

[^11]: This strong nuclear force plot is calculated from the Reid potential, see Reference [3], which was developed and named after American physicist Roderick V Reid Jr. This is a popular model for the strong nuclear force first used in 1968.

[^12]: See reference [4].

[^13]: As far as we know.

[^14]: Due to its short half-life, it is made in an accelerator on site (usually in the basement of the hospital) and brought immediately to the patient.

[^15]: Germanium-71 decays via electron capture, which is facilitated by the weak nuclear force.

[^16]: It is not constant, but we have ways to calibrate how the ratio has changed in times as well as geographical variations.
