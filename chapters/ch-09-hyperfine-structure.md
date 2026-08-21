---
title: 9. Hyperfine Structure
short_title: "Ch. 9 — Hyperfine Structure"
label: ch-9
doi: 10.1007/978-3-031-69507-0_9
---

## Abstract

In this chapter, we explore hyperfine structure, which occurs in atoms with a nucleus that has angular momentum. We will discuss the theoretical framework, including key equations for calculating hyperfine energy shifts, and apply this knowledge through practical examples involving cesium, europium, and oxygen. This chapter aims to provide a comprehensive understanding of hyperfine structure and its significance in atomic physics.

**Keywords:** Hyperfine structure, Nuclear spin, Magnetic dipole hyperfine constant, Electric quadrupole hyperfine constant, Hyperfine splitting, Hyperfine levels, Hyperfine transition amplitudes

## Learning Goals

By the end of this chapter, you should be able to understand:

- why hyperfine structure exists and identify the conditions under which hyperfine splitting occurs.
- the difference between fine structure and hyperfine structure.
- how to interpret spectroscopic data to extract hyperfine constants.

(sec-9-1)=
## 9.1 Hyperfine Structure

The nucleus contains protons and neutrons, each of which has intrinsic angular momentum. In addition to their intrinsic spins, nucleons (protons and neutrons) can also have orbital angular momentum due to their motion within the nucleus. When discussing the angular momentum of the nucleus as a whole, we primarily refer to the combination of the intrinsic spins of the nucleons and their orbital angular momentum. This combined angular momentum should be called the “total nuclear angular momentum,” but it is commonly referred to as “**nuclear spin**.” Despite the terminology, neither the nucleus nor the protons and neutrons in the nucleus are literally spinning or orbiting in the classical sense. Nuclei with both an even number of protons and an even number of neutrons tend to have zero nuclear spin because the individual spins pair up (one spin-up and one spin-down) and cancel each other out. Nuclei with an odd number of protons and/or neutrons generally have a non-zero nuclear spin.

When an atom has a non-zero nuclear spin, the nucleus interacts with the magnetic fields produced by the electrons. More specifically, because the nucleus has both charge and angular momentum (*I*), and the electrons have both charge and angular momentum (*J*), there is an additional internal torque between the nucleus and the electrons. This interaction leads to the splitting of atomic energy levels into closely spaced sub-levels known as hyperfine levels, analogous to the interaction between an electron’s spin and its orbital angular momentum, which results in fine structure splitting. I want to point out that atomic physicists use **hyperfine levels** and hyperfine states interchangeably. We tend to use hyperfine levels when thinking about energy splittings and hyperfine states when using quantum numbers, but the two terms mean the same thing.

Table [](#tbl-9-1) is a copy of a table from Chap. [](#ch-7) that summarizes all of the angular momentum vectors and angular momentum quantum numbers for the system of electrons and the atom as a whole. Let’s look at some examples. Oxygen has three stable isotopes: oxygen-16 (99.76% of all oxygen on earth is oxygen-16), oxygen-17 ($\sim$0.04%), and oxygen-18 ($\sim$0.20%). Isotopes are elements with the same number of protons but different numbers of neutrons. Oxygen-16 has 8 electrons, 8 protons, and 8 neutrons. Oxygen-17 has 8 electrons, 8 protons, and 9 neutrons. Oxygen-18 has 8 electrons, 8 protons, and 10 neutrons. Since each isotope has a different number of neutrons, the transition frequencies are slightly different. This small shift, called an isotope shift, will be discussed in Chap. [](#ch-10).

(tbl-9-1)=
**Table 9.1** This table summaries all of the angular momentum quantum numbers

| Type | QN | Rule | Formula |
| --- | --- | --- | --- |
| Orbital | *L* | Zero or positive integer | Magnitude: $\sqrt {L(L+1)}\hbar$ |
|  | $m_{L}$ | $-L$ to $+L$ in integer steps | Cone height: $m_{L}\hbar$ |
| Spin | *S* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {S(S+1)}\hbar$ |
|  | $m_{S}$ | $-S$ to $+S$ in integer steps | Cone height: $m_{S}\hbar$ |
| Total electronic | *J* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {J(J+1)}\hbar$ |
|  | $m_{J}$ | $-J$ to $+J$ in integer steps | Cone height: $m_{J}\hbar$ |
| Nuclear spin | *I* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {I(I+1)}\hbar$ |
|  | $m_{I}$ | $-I$ to $+I$ in integer steps | Cone height: $m_{I}\hbar$ |
| Total atomic | *F* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {F(F+1)}\hbar$ |
|  | $m_{F}$ | $-F$ to $+F$ in integer steps | Cone height: $m_{F}\hbar$ |

**Important Reminders**

- We can represent the energy difference between two states using energy units, wavelength units, or frequency units. For hyperfine structure, frequency units are the most convenient unit because the energy spacing between hyperfine levels is small.
- When adding two angular momentum vectors together, both the magnitude and orientation of the individual angular momentum vectors will affect the magnitude and orientation of the resulting vector. Each possible magnitude of the composite angular momentum vector will have an effect on the energy of a state.
- **Center of gravity:** The energy of a state if there was no nuclear spin.

The nuclear spin quantum number for oxygen-17 is $I=5/2$. The nuclear spin quantum number for both oxygen-16 and oxygen-18 is $I=0$. Therefore oxygen-17 will have hyperfine structure while the other two isotopes do not. All isotopes of oxygen have a ground state term symbol of ${ }^{3}\text{P}_{2}$, or $S=1$ ($2S+1=3$), $L=1$, and $J=2$. However, the ground state of oxygen-17 looks different compared to the other two isotopes, see Fig. [](#fig-9-1). If oxygen-17 had no nuclear spin, it would have a single level precisely at 0. Nuclear spin “splits” this single level into 5 hyperfine levels. For example, the level labeled $F=7/2$ has a slightly smaller energy than the center of gravity while the $F=5/2$ state has a higher energy. Both oxygen-16 and oxygen-18 have no nuclear spin, so they have a single ground state that would be labeled 0 energy and have no F quantum number designation.

```{figure} ../images/ch-09/541577_1_En_9_Fig1_HTML.png
:name: fig-9-1

The hyperfine structure of the ground state of oxygen-17. The hyperfine levels are shown with respect to the center of gravity of the ground state
```

Adding together nuclear spin, represented by the quantum number *I*, and the total electronic angular momentum, represented by the quantum number *J*, results in a new angular momentum vector that we call the total angular momentum of the atom, represented by the quantum number *F*. Hyperfine structure generally has a much smaller energy splitting compared to fine structure. Like every angular momentum vector we have encountered, the *F* vector can also point in different orientations. For example, an $F=3/2$ state has four possible orientations described by the quantum numbers $m_F=$3/2, 1/2, $-$1/2, and $-$3/2. All four of those orientations have the same energy.

**Compatibility with Energy**

We often care about what observables are compatible with energy. At the end of Chap. [](#ch-7), we used the ket $|{n~\ell ~s~j~m_j}\rangle$ to represent the states of the hydrogen atom (one electron). All the different quantum numbers in this ket represent observables that are compatible with energy.

**Important Reminder**

The observables represented by $m_\ell$ and $m_s$ are not compatible energy.

Let’s update our ket with information we have learned from this chapter. When we add together nuclear spin and total electronic angular momentum, the cones representing those angular momenta are tilted with respect to the total atomic angular momentum (F). Just like when we added orbital and electron spin, the cone heights of I and J, which are represented by the quantum numbers $m_I$ and $m_J$, are no longer compatible with energy. Therefore, our new ket is $|{n~\ell ~s~j~I~F~m_F}\rangle$.

```{math}
:label: eq-9-1
\begin{array}{l l} |{n~\ell~s~j~m_j}\rangle & \text{Energy state with no nuclear spin} \\ |{n~\ell~s~j~I~F~m_F}\rangle & \text{Energy state with nuclear spin} \end{array}
```

The nucleus of a hydrogen atom has a nuclear spin represented by $I=1/2$. The atomic ground state of hydrogen has the electronic configuration $1\text{s}$, or $s=1/2$, $\ell =0$, and $j=1/2$. Because the nucleus has spin, there will be two hyperfine levels represented by $F=0$ ($m_F=0$) and $F=1$ ($m_F=1$, 0, and $-$1). Therefore, the four hyperfine levels for the ground state have kets:

```{math}
:label: eq-9-2
\begin{array}{l} |{1~0~\frac{1}{2}~\frac{1}{2}~\frac{1}{2}~1~1}\rangle \\ |{1~0~\frac{1}{2}~\frac{1}{2}~\frac{1}{2}~1~0}\rangle \\ |{1~0~\frac{1}{2}~\frac{1}{2}~\frac{1}{2}~1~{\text{-} 1}}\rangle \\ |{1~0~\frac{1}{2}~\frac{1}{2}~\frac{1}{2}~0~0}\rangle \end{array}
```

The three hyperfine levels with $F=1$ are degenerate and have the same energy. The hyperfine level with $F=0$ has a different energy.

So, the ground state of hydrogen has two hyperfine levels represented by the quantum numbers $F=1$ and $F=0$. For something a bit more complicated, let’s look at the ground state of europium. Europium has 7 electrons in its last, unfilled subshell. All isotopes of europium have a ground state term symbol ${ }^{8}\text{S}_{7/2}$, or $S=7/2$ ($2S+1=8$), $L=0$, and $J=7/2$. If europium had no nuclear spin, that would be the end of the story. We would define the ground state:

```{math}
:label: eq-9-3
1\text{s}^2 2\text{s}^2 2\text{p}^6 3\text{s}^2 3\text{p}^6 3\text{d}^{10} 4\text{s}^2 4\text{p}^6 4\text{d}^{10} 5\text{s}^2 5\text{p}^6 6\text{s}^2 4\text{f}^7~{}^{8}\text{S}_{7/2}
```

to have 0 energy. However, both stable isotopes of europium have nuclear spin: europium-151 (63 electrons, 63 protons, 88 neutrons, and $I=5/2$) and europium-153 (63 electrons, 63 protons, 90 neutrons, and $I=5/2$). Other isotopes of europium will have different nuclear spin. For example, europium-152, which is radioactive with a half-life of 13.5 years, has a nuclear spin quantum number of $I=3$. Each of these europium isotopes have hyperfine levels.

**Summary**

If an isotope has no nuclear spin, there would be 1 ground state. If it does have nuclear spin, there are multiple ground states. This is because the angular momentum from the nucleus exerts a torque on the electrons, which results in a small splitting and shift of the state’s energy.

There is a single exception to the above summary that we will discuss more in Sect. [](#sec-9-2). If the state has no total electronic angular momentum ($J=0$), there is still only a single state; the single state does not split into multiple hyperfine levels. However, that single state will still have an *F* quantum number as a label.

(sec-9-2)=
## 9.2 Math

We can find the possible values of F by using the largest to smallest in integer steps rule. The rule is:

```{math}
:label: eq-9-4
\begin{array}{l l} F=(I+J),\dots,|I-J| & \quad  \text{in integer steps}. \end{array}
```

Let’s do a few examples.

**Example 1**

Hydrogen-1 has a nuclear spin quantum number of $I=1/2$ and the ground state has a total electronic angular momentum quantum number of $J=1/2$ (also $j=1/2$ since hydrogen has a single electron). Therefore, the possible *F* values for the ground state range from $1/2+1/2=1$ to $|1/2-1/2|=0$ in integer steps. Thus, there are 2 hyperfine levels for the ground state of hydrogen-1.

**Example 2**

Oxygen-17 has a nuclear spin quantum number of $I=5/2$ and the ground state has a total electronic angular momentum quantum number of $J=2$. Therefore, the possible F values for the ground state range from $5/2+2=9/2$ to $|5/2-2|=1/2$ in integer steps. Thus, there are 5 hyperfine levels for the ground state of oxygen-17. Those values, which are shown in Fig. [](#fig-9-1), are $F=$9/2, 7/2, 5/2, 3/2, and 1/2.

**Example 3**

Let’s consider the two stable isotopes of europium: europium-151 and europium-153. Both stable isotopes of europium have the same nuclear spin quantum number of $I=5/2$. The ground state has a total electronic angular momentum quantum number of $J=7/2$. Therefore, the possible values for *F* range from $5/2+7/2=6$ to $|5/2-7/2|=1$ in integer steps, resulting in $F=$6, 5, 4, 3, 2, or 1.

**Quick Quiz**

1. The radioactive isotope europium-152 has a nuclear spin quantum number of $I=3$. How many hyperfine levels will the ground state have, and what are their *F* quantum numbers?
2. Beryllium-9 has a nuclear spin quantum number of $I=3/2$ with a ground state total electronic angular momentum quantum number of $J=0$. How many hyperfine levels will the ground state have, and what are their F quantum numbers? The answers are below the maze shown in Fig. [](#fig-9-2).

```{figure} ../images/ch-09/541577_1_En_9_Fig2_HTML.png
:name: fig-9-2

A fun maze to separate the quiz from the answers
```

The answers are:

1. 7 levels: $F=$13/2, 11/2, 9/2, 7/2, 5/2, 3/2, or 1/2
2. 1 level: $F=$3/2.

Notice that beryllium-9 still has a single ground state even though the nucleus has spin. This is because $(I+J)=|I-J|$, so the range of possible *F* values is 3/2 to 3/2. This always happens when $J=0$. However, the nucleus still has angular momentum, so we include $F=3/2$ in the description of the state.

Using quantum mechanics, we can derive the energy splitting of a hyperfine level with respect to the center of gravity:

```{math}
:label: eq-9-5
\begin{array}{c} \Delta E = \frac{1}{2} K A+ \frac{\frac{3}{2} K(K+1)-2I(I+1)J(J+1)}{2I(2I-1)2J(2J-1)} B \\ K=F(F+1)-I(I+1)-J(J+1) \\ A=0 \text{ unless both } I>0 \text{ and } J>0 \\ B=0 \text{ unless both } I>1/2 \text{ and } J>1/2 \end{array}
```

where *A* is called the magnetic dipole hyperfine constant and *B* is called the electric quadrupole hyperfine constant. Notice that everything else in the above equation apart from *A* and *B* is a quantum number. Theorists can calculate the hyperfine constants *A* and *B* while experimentalists measure them. When we perform spectroscopy on an atom with hyperfine structure, we can measure the energy spacing between all of the hyperfine levels and use the above equation to back out experimental values of *A* and *B*. Some hyperfine constants were measured many years ago while others have yet to be measured. For example, the ground state hyperfine constants for europium-151 and europium-153 were measured for the first-time way back in 1960 by P.G.H. Sandars and G.K. Woodgate and published in the journal *Proceedings of the Royal Society A*.[^1] Sandars and Woodgate found that the magnetic dipole hyperfine constant and the electric quadrupole hyperfine constant for the ground state of europium-151 is $A=-20.0523\pm 0.0002$ MHz and $B=-0.7012\pm 0.0035$ MHz. To convert those numbers into energy, just plug the hyperfine constants into the above equation and multiply the result by Planck’s constant, *h*. If someone already measured those numbers, we can use those as a starting point for our fitting algorithms. If not, we have to determine them ourselves.

For every state in an atom, the electrons have different quantum numbers. States with higher *n* tend to be farther from the nucleus while the angular momentum quantum numbers represent different orbitals. Therefore, for an atom with nuclear spin, every state in that atom will have different hyperfine constants resulting in a different hyperfine splitting. Even the same state in two different isotopes that happen to have the same nuclear spin will have different hyperfine constants because the nuclei of the two isotopes are slightly different.

**Summary**

The “splitting” of the center of gravity into hyperfine levels is described by Eq. [](#eq-9-5). The magnetic dipole hyperfine constant *A* is zero unless both $I>0$ and $J>0$. The magnetic quadrupole hyperfine constant *B* is zero unless both $I>1/2$ and $J>1/2$.

**One Final Thing**

The magnetic dipole term (the term with *A*) in Eq. [](#eq-9-5) tends to be larger than the electric quadrupole term (the term with *B*). For example, the $F=6$ ground hyperfine state of europium-151 has a splitting $\Delta E = (-175.458\,\text{MHz}) + (-0.175\,\text{MHz})=-175.633\,\text{MHz}$. The first term in parentheses is from the magnetic dipole term and the second is from electric quadrupole term. There are additional terms to Eq. [](#eq-9-5), but they are very small compared to the electric quadrupole term. The next term in the formula is the magnetic octupole term, which contains quantum numbers and the magnetic octupole hyperfine constant *C*. This term is generally unnecessary unless you have exceptionally good data. The magnetic octupole constant is zero unless both $I>1$ and $J>1$.

(sec-9-3)=
## 9.3 Transition Frequencies

Suppose we have an atom with a nuclear spin quantum number of $I = 3/2$. To help distinguish between the lower and upper states, we will use primes on the quantum numbers for the excited states. In this example, the lower state has a total angular momentum quantum number of $J = 1/2$ and the upper state has $J' = 1/2$. Our goal is to write an equation for the transition frequency between two hyperfine levels. We first need to find the possible values for F, which can range from $3/2 + 1/2 = 2$ to $|3/2 - 1/2| = 1$ in integer steps, giving $F = 1$ and $F = 2$. Since $J' = 1/2$ as well, the possible values for $F'$ are $F' = 1$ and $F' = 2$, see Fig. [](#fig-9-3). In this hypothetical example, the $F=1$ hyperfine level has a smaller energy than the $F=2$ hyperfine level while the order is reversed in the excited state; the ordering of the quantum number all depends upon the interaction with the nucleus.

```{figure} ../images/ch-09/541577_1_En_9_Fig3_HTML.png
:name: fig-9-3

A simple Grotrian diagram for a made-up atom
```

Next, we want to find the transition frequency from the $F=2$ hyperfine level to the $F'=1$ hyperfine level. Using Eq. [](#eq-9-5), we can calculate the hyperfine energy splitting. We will use “LS” for lower state and “US” for upper state. Note that since $J=1/2$ and $J'=1/2$, both $B_{\text{LS}}=0$ and $B_{\text{US}}=0$. Evaluating Eq. [](#eq-9-5) with the given quantum numbers, we find $\Delta E_{\text{LS},F=2}=\frac {3}{4} A_{\text{LS}}$ and $\Delta E_{\text{US},F'=1}=-\frac {5}{4}A_{\text{US}}$. According to Fig. [](#fig-9-3), the $F=2$ state has more energy than the center of gravity for the lower level, meaning $\Delta E_{\text{LS},F=2}>0$. Since $\Delta E_{\text{LS},F=2}=\frac {3}{4} A_{\text{LS}}$, we also learn that $A_{\text{LS}}>0$. For the upper state, the hyperfine energy splitting is also positive. For this state, the formula is $\Delta E_{\text{US},F'=1}=-\frac {5}{4} A_{\text{US}}$, which implies that $A_{\text{US}}<0$ in order to make $\Delta E_{\text{US},F'=1}>0$.

**Quick Quiz**

Suppose an electron in our made up atom is in the $F=2$ lower hyperfine level. What is the formula to calculate the transition frequency from the $F=2$ lower hyperfine level to the $F'=1$ upper hyperfine level? Your answer should contain the center of gravity frequency $f_{\text{cog}}$ and the two magnetic dipole hyperfine constants $A_{\text{LS}}$ and $A_{\text{US}}$. The answer is in the footnotes.[^2]

The general formula to calculate the transition frequency between two hyperfine levels is

```{math}
:label: eq-9-6
f_{r}=f_{\text{cog}}-\Delta E_{\text{LS}}(A_{\text{LS}},B_{\text{LS}})+\Delta E_{\text{US}}(A_{\text{US}},B_{\text{US}}).
```

For many learners, the signs of the shifts can be confusing, so let’s explore the signs with our toy example. Let’s start with the minus sign in front of $\Delta E_{\text{LS}}(A_{\text{LS}},B_{\text{LS}})$. According to Fig. [](#fig-9-3), the $F=2$ hyperfine state reduces the transition frequency compared to $f_{\text{cog}}$. Since $\Delta E_{\text{LS}}(A_{\text{LS}},B_{\text{LS}})>0$ for that state, the minus sign makes sense. What about if we wanted the transition frequency from the $F=1$ lower hyperfine level? For that state, $\Delta E_{\text{LS}}(A_{\text{LS}},B_{\text{LS}}) < 0$, so that minus sign turns into a plus sign, increasing the frequency needed compared to $f_{\text{cog}}$. This is a subtle but important point, so take some time to convince yourself the transition frequency from any lower hyperfine level to any upper hyperfine level is given by Eq. [](#eq-9-6). Using this same logic, convince yourself that the plus sign in front of $\Delta E_{\text{US}}(A_{\text{US}},B_{\text{US}})$ makes sense.

(sec-9-4)=
## 9.4 Example with Cesium-133

Figure [](#fig-9-4) shows a spectrum from a paper we published in 2018,[^3] in which we performed saturated absorption spectroscopy on cesium-133. Cesium-133 has a nuclear spin quantum number of $I=7/2$. The first five shells of cesium are completely filled, leaving a single electron in the 6s subshell. The ground state has the term symbol ${ }^{2}\text{S}_{1/2}$ while the excited state has a term symbol ${ }^{2}\text{P}_{3/2}$. So, the ground state has two hyperfine levels, $F=3$ and $F=4$, while the excited state has four hyperfine levels, $F'=$ 2, 3, 4, and 5. The $F=3$ and $F=4$ ground hyperfine levels are well separated from each other ($\sim$9.192 GHz), which is much larger than the Doppler width for transitions from either state. Therefore, we will not have any $\Lambda$ crossovers despite having two lower states.

```{figure} ../images/ch-09/541577_1_En_9_Fig4_HTML.png
:name: fig-9-4

Experimental spectroscopic results of the transition in neutral cesium-133. This is an experimental result from my research group, see reference [1]. A simplified Grotrian diagram for the transition can be found in Fig. [](#fig-5-12)
```

We performed spectroscopy from the $F=4$ ground hyperfine level, which has an energy approximately 4.021 GHz above the center of gravity for the ground state. Given The Rule (Eq. [](#eq-3-15)) $\Delta F= -1$, 0, or 1 with the exception $F=0 \not \rightarrow F=0$, we can excite an atom from the ground state hyperfine level with $F=4$ to the excited state hyperfine levels with $F'=$3, 4, or 5.[^4] Each of these three real transitions has a Lorentzian lineshape. We also have three V crossovers. For a review of crossovers, see Chap. [](#ch-5), Sect. [](#sec-5-2). The first crossover comes from the two real transitions $F=4 \rightarrow F'=3$ and $F=4 \rightarrow F'=4$. We often write this crossover in shorthand form: $F=4 \rightarrow F'=3/4$. The other two crossovers are the $F=4 \rightarrow F'=4/5$ and $F=4 \rightarrow F'=3/5$ crossovers. Despite having 6 spectroscopic features, the frequencies of all 6 features depend on only five parameters: the two hyperfine constants for the ground state, the two hyperfine constants for the excited state, and the transition frequency between the center of gravity for the ground state and the center of gravity for the excited state, see Eq. [](#eq-9-6). I should point out that the width and amplitude of each peak are also free parameters, but we didn’t really care about those. Our main goal was to measure the center of gravity frequency and the hyperfine constants. Having 5 parameters to determine the position of all spectroscopic features is typical. The experimental data from our group on a transition in europium-151 had up to 77 spectral features in that spectrum![^5] Even still, the center of each feature is determined by only 5 free parameters.

Let’s apply Eq. [](#eq-9-6) using numbers from cesium-133. The spectrum in Fig. [](#fig-9-4) is from the $J=1/2$, $F=4$ ground state. The excited state has $J'=3/2$ and $F'=$3, 4, and 5.[^6] Let’s find $\Delta E$ for all of the features.

(sec-9-4-1)=
### 9.4.1 Real Transitions

There are three real transitions in the spectrum. They are

1. $F=4 \rightarrow F'=3$
2. $F=4 \rightarrow F'=4$
3. $F=4 \rightarrow F'=5$

Let’s calculate the shift from the center of gravity for the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state for each real transition. Since these are shifts for the excited state, we will use the primed values in Eq. [](#eq-9-5). We will also need Eq. [](#eq-9-6) to find the transition frequency between two hyperfine levels. Since the hyperfine splitting for the ground state is so large, we will perform our spectroscopy with respect to the $F=4$ ground hyperfine level. For ease of reference, here are those equations:

```{math}
:label: eq-9-7
\begin{array}{c} \Delta E = \frac{1}{2} K A_{\text{US}}+ \frac{\frac{3}{2} K(K+1)-2I(I+1)J'(J'+1)}{2I(2I-1)2J'(2J'-1)} B_{\text{US}} \\ K=F'(F'+1)-I(I+1)-J'(J'+1) \\ ~\\ f_{r}=f_{F=4 \rightarrow \text{cog}}+\Delta E_{\text{US}}(A_{\text{US}},B_{\text{US}})\\ \end{array}
```

where $f_{F=4 \rightarrow \text{cog}}=f_{\text{cog}}-\Delta E_{\text{LS,F=4}}$ is the frequency of light needed to go from the $F=4$ ground hyperfine level to the center of gravity of the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state. I also replaced the quantum numbers with primed values and the hyperfine constants with “US” subscripts.

Let’s do the math for the $F=4\rightarrow F'=3$ real transition. First, let’s find K:

```{math}
\begin{array}{rcl} K&=&F'(F'+1)-I(I+1)-J'(J'+1) \\ &=& 3(3+1)-\frac{7}{2} (\frac{7}{2}+1)-\frac{3}{2} (\frac{3}{2}+1)\\ &=&-\frac{15}{2} \end{array}
```

Now we can find the hyperfine splitting for the $F'=3$ state from the center of gravity for the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state.

```{math}
\begin{array}{rcl} \Delta E &=& \frac{1}{2} K A_{\text{US}} + \frac{\frac{3}{2} K(K+1) - 2I(I+1)J'(J'+1)}{2I(2I-1)2J'(2J'-1)} B_{\text{US}} \\ &=& \frac{1}{2} \left(-\frac{15}{2}\right) A_{\text{US}} + \frac{\frac{3}{2} \left(-\frac{15}{2}\right)\left(\left(-\frac{15}{2}\right)+1\right) - 2\left(\frac{7}{2}\right)\left(\frac{7}{2}+1\right)\left(\frac{3}{2}\right)\left(\frac{3}{2}+1\right)}{2\left(\frac{7}{2}\right)\left(2\left(\frac{7}{2}\right)-1\right)2\left(\frac{3}{2}\right)\left(2\left(\frac{3}{2}\right)-1\right)} B_{\text{US}} \\ &=& -\frac{15}{4}A_{\text{US}} + \frac{\left(-\frac{45}{4}\right)\left(-\frac{13}{2}\right) - 7\left(\frac{9}{2}\right)\left(\frac{3}{2}\right)\left(\frac{5}{2}\right)}{7(6)(3)(2)} B_{\text{US}} \\ &=& -\frac{15}{4}A_{\text{US}} + \frac{\left(\frac{585}{8}\right) - \left(\frac{945}{8}\right)}{252} B_{\text{US}} \\ &=& -\frac{15}{4}A_{\text{US}} + \frac{\left(-\frac{360}{8}\right)}{252} B_{\text{US}} \\ &=& -\frac{15}{4}A_{\text{US}} + \left(\frac{-45}{252}\right) B_{\text{US}} \\ &=& -\frac{15}{4} A_{\text{US}} - \frac{5}{28} B_{\text{US}} \\ \end{array}
```

Table [](#tbl-9-2) shows the results of the math. The hyperfine constants for the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state are kept as unknowns that we find while fitting the data. If there weren’t any crossovers, we would be done. Our fitting function would be the sum of three Lorentzian functions[^7] whose centers are taken from the above table:

```{math}
:label: eq-9-8
\begin{array}{rcl} g(f)&=&\frac{C_1}{1+\frac{\big(f-(f_{F=4 \rightarrow \text{cog}}-\frac{15}{4} A_{\text{US}}-\frac{5}{28} B_{\text{US}})\big)^2}{\gamma_1^2}}+\frac{C_2}{1+\frac{\big(f-(f_{F=4 \rightarrow \text{cog}}+\frac{1}{4} A_{\text{US}}-\frac{13}{28} B_{\text{US}})\big)^2}{\gamma_2^2}}\\ &&\quad  +\frac{C_3}{1+\frac{\big(f-(f_{F=4 \rightarrow \text{cog}}+\frac{21}{4} A_{\text{US}}+\frac{1}{4} B_{\text{US}})\big)^2}{\gamma_3^2}}. \end{array}
```

(tbl-9-2)=
**Table 9.2** The energy shifts for the hyperfine levels with respect to the center of gravity for the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state in cesium-133. All of the real transitions in this example are from the $6\text{s}~{ }^{2}\text{S}_{1/2}~F=4$ ground hyperfine level

| Transitions | $K=F'(F'+1)-I(I+1)-J'(J'+1)$ | $\Delta E$ |
| --- | --- | --- |
| $F=4 \rightarrow F'=3$ | $3(3+1)-\frac {7}{2} (\frac {7}{2}+1)-\frac {3}{2} (\frac {3}{2}+1)=-\frac {15}{2}$ | $-\frac {15}{4} A_{\text{US}}-\frac {5}{28} B_{\text{US}}$ |
| $F=4 \rightarrow F'=4$ | $4(4+1)-\frac {7}{2} (\frac {7}{2}+1)-\frac {3}{2} (\frac {3}{2}+1)=+\frac {1}{2}$ | $+\frac {1}{4} A_{\text{US}}-\frac {13}{28} B_{\text{US}}$ |
| $F=4 \rightarrow F'=5$ | $5(5+1)-\frac {7}{2} (\frac {7}{2}+1)-\frac {3}{2} (\frac {3}{2}+1)=+\frac {21}{2}$ | $+\frac {21}{4} A_{\text{US}}+\frac {1}{4} B_{\text{US}}$ |

where $f_{F=4 \rightarrow \text{cog}}$ is the frequency of light needed to go from the $F=4$ ground hyperfine level to the center of gravity of the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state. To avoid accidentally mixing up the magnetic dipole hyperfine constant of the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state and the amplitude of the Lorentzian functions, I changed the variable for amplitude to *C*. If we wanted to write the transition frequencies in terms of the actual center of gravity frequency, we would replace $f_{F=4 \rightarrow \text{cog}}$ with $f_{\text{cog}}-\Delta E_{LS,F=4}$.

(sec-9-4-2)=
### 9.4.2 Crossover Transitions

For this spectrum, there are three V crossovers: $F=4 \rightarrow F'=3/4$, $F=4 \rightarrow F'=4/5$, and $F=4 \rightarrow F'=3/5$. The center of the spectral feature due to the $F=4 \rightarrow F'=3/4$ crossover is found using the same procedures we learned about in Chap. [](#ch-5), which is adding the two real transitions and dividing by 2:

```{math}
:label: eq-9-9
\begin{array}{rcl} \Delta E_{F'=3/4} = \frac{\Delta E_{F'=3}+\Delta E_{F'=4}}{2} &=& \frac{\big(-\frac{15}{4} A_{\text{US}}-\frac{5}{28} B_{\text{US}}\big)+\big(\frac{1}{4} A_{\text{US}}-\frac{13}{28} B_{\text{US}}\big)}{2}\\ &=&-\frac{7}{4}A_{\text{US}}-\frac{9}{28}B_{\text{US}} \end{array}
```

The same procedure can be done for the other two crossovers. In the end, the fit function is a sum of 6 Lorentzian functions. From the fit, we find $A_{\text{US}}$, $B_{\text{US}}$, and $f_{F=4 \rightarrow \text{cog}}$, all with uncertainty. You will get to practice this in a homework problem.

(sec-9-5)=
## 9.5 Optional: Amplitudes

A common question I am asked is if there is a way to calculate the amplitudes of the Lorentzian functions. Finding the absolute amplitude is possible, but quite difficult. However, if the spectral features aren’t overlapping (we often use the phrase “well-separated features”), we can find the relative amplitudes for the real transitions. It uses a mathematical symbol you may not have seen before, but you should think of it as a placeholder for a lot of hidden algebra. Not many people do the hidden algebra themselves—that’s what Mathematica is for—but if you search the internet for “Wigner 6-j,” you can find all the math behind the symbol. The scaled amplitudes of the real transitions are given by the following formula:

```{math}
:label: eq-9-10
I_r = (2F + 1)(2F' + 1) \begin{Bmatrix} J & I & F \\ F' & 1 & J' \end{Bmatrix}^2,
```

where the primed quantum numbers are for the excited state. That last symbol is called the Wigner 6-j symbol (it is squared in the above equation). Also, the second element of the second row is the number 1 (lots of folks accidentally read that as the nuclear spin quantum number *I*). In Mathematica, you would type `SixJSymbol[{J,I,F},{Fp,1,Jp}]`$^2$ (Mathematica doesn’t allow J’ or F’ as variable names, so I replaced them with Jp and Fp). There are also online calculators you can find by searching the internet for “Wigner 6-j symbol calculator”. Notice this formula has no units. We use this formula to take ratios to find relative amplitudes.

Let’s find $I_r$ for all three real transitions in the cesium-133 example we have been studying. To make things a bit easier, I included a copy of Fig. [](#fig-9-4) on this page. As a reminder, the ground state has quantum numbers $J=1/2$ and $F=4$, the excited state has $J'=3/2$ and $F'=3,~4,\,\text{and}~5$, and the nuclear spin is $I=7/2$.

1. $F=4 \rightarrow F'=3:~I_r=(2(4)+1)(2(3)+1) \begin {Bmatrix} \frac {1}{2} & \frac {7}{2} & 4 \\ 3 & 1 & \frac {3}{2} \end {Bmatrix}^2 = \frac {7}{16} = 0.4375$
2. $F=4 \rightarrow F'=4:~I_r=(2(4)+1)(2(4)+1) \begin {Bmatrix} \frac {1}{2} & \frac {7}{2} & 4 \\ 4 & 1 & \frac {3}{2} \end {Bmatrix}^2 = \frac {21}{16} = 1.3125$
3. $F=4 \rightarrow F'=5:~I_r=(2(4)+1)(2(4)+1) \begin {Bmatrix} \frac {1}{2} & \frac {7}{2} & 4 \\ 5 & 1 & \frac {3}{2} \end {Bmatrix}^2 = \frac {11}{4} = 2.75$

From this math we see that the $F=4 \rightarrow F'=5$ is the largest transition. Using this largest transition as the reference, we can compare the size of the other two transitions to it. The $F=4 \rightarrow F'=4$ transition, which is the peak around 5 MHz in Fig. [](#fig-9-5), is $\frac {21/16}{11/4}=\frac {21}{44}=0.47$ times smaller than the $F=4 \rightarrow F'=5$ transition. Finally, the $F=4 \rightarrow F'=3$ transition is $\frac {7/16}{11/4}=\frac {7}{44}=0.16$ times smaller than the $F=4 \rightarrow F'=5$ transition. If you look at the amplitudes of the real transitions, you’ll see that these estimates are pretty close to what was measured experimentally.

```{figure} ../images/ch-09/541577_1_En_9_Fig5_HTML.png
:name: fig-9-5

Experimental spectroscopic results of the transition in neutral cesium-133. This is an experimental result from my research group. A simplified Grotrian diagram for the transition can be found in Fig. [](#fig-5-12)
```

While it is possible to calculate the amplitudes of the crossovers, it is much more complicated. One reason is that the number of atoms with a particular velocity, which creates the crossovers, depends on the temperature of your vapor cell. However, we at least have a fairly straightforward way of finding the relative amplitudes of the real transitions.

(sec-9-6)=
## 9.6 Example with Oxygen-16

Oxygen-16 has no nuclear spin, so there is no hyperfine structure. Shortest section ever!

(sec-9-7)=
## 9.7 Example with Oxygen-17

Oxygen-17 has a nuclear spin quantum number of $I=5/2$, so there will be hyperfine structure. Below is a table of the seven lowest energy states for atomic oxygen.

(tbl-9-3)=
**Table 9.3**

| Electron configuration | Term symbol | Energy ($\text{cm}^{-1}$) | f (Hz) |
| --- | --- | --- | --- |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{3}\text{P}_{2}$ | 0 |  |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{3}\text{P}_{1}$ | 158.265 | $4.74\times 10^{12}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{3}\text{P}_{0}$ | 226.977 | $6.80\times 10^{12}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{1}\text{D}_{2}$ | 15,867.862 | $4.76\times 10^{14}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{1}\text{S}_{0}$ | 33,792.583 | $1.01\times 10^{15}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^3 3\text{s}$ | ${ }^{5}\text{S}_{2}$ | 73,768.200 | $2.21\times 10^{15}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^3 3\text{s}$ | ${ }^{3}\text{S}_{1}$ | 76,794.978 | $2.30\times 10^{15}$ |

For oxygen isotopes with no nuclear spin, such as oxygen-16, this table provides all the information about their atomic states. There is a single ground state with electronic configuration and term symbol $1\text{s}^2 2\text{s}^2 2\text{p}^4~{ }^{3}\text{P}_{2}$. However, due to hyperfine structure, the table does not tell the whole story for oxygen-17. Let’s examine the ground state of oxygen-17. For this state, the total electronic angular momentum quantum number is $J=2$ and the nuclear spin quantum number is $I=5/2$. The possible values for the total atomic angular momentum quantum number are:

```{math}
:label: eq-9-11
F= \left(2+\frac{5}{2}\right), \dots, \left|2-\frac{5}{2}\right|=\frac{9}{2},~\frac{7}{2},~\frac{5}{2},~\frac{3}{2},~\frac{1}{2}
```

We can also calculate the energy splitting using the hyperfine splitting formula. For convenience, here is the hyperfine splitting formula:

```{math}
:label: eq-9-12
\begin{array}{c} \Delta E = \frac{1}{2} K A+ \frac{\frac{3}{2} K(K+1)-2I(I+1)J(J+1)}{2I(2I-1)2J(2J-1)} B \\ K=F(F+1)-I(I+1)-J(J+1) \\ A=0\text{ unless both }I>0\text{ and }J>0\\ ~B=0\text{ unless both }I>1/2\text{ and }J>1/2. \end{array}
```

The first thing to notice is that for the ${ }^{3}\text{P}_{2}$ ground state, both $I>1/2$ and $J>1/2$, so we will need both the magnetic dipole term (the term with A) and the electric quadrupole term (the term with B). For example, the hyperfine splitting for the $F=9/2$ hyperfine level is:

```{math}
:label: eq-9-13
\begin{array}{c} K = F(F+1) - I(I+1) - J(J+1) = \frac{9}{2}\left(\frac{11}{2}\right) - \frac{5}{2}\left(\frac{7}{2}\right) - 2(3) = 10 \\\\ \Delta E_{F=9/2} = 5A_{\text{gs}} + \frac{1}{4} B_{\text{gs}} \end{array}
```

where $A_{\text{gs}}$ and $B_{\text{gs}}$ are the hyperfine constants for the ${ }^{3}\text{P}_{2}$ ground state. Each energy level in the above table will have different hyperfine constants.

Next, let’s explore the ${ }^{3}\text{P}_{0}$ state, which has an energy of $226.977\,\text{cm}^{-1}$ above the ground state and a total electronic angular momentum quantum number of $J=0$. Using the rule to find F, we find a single possible value: $F = (J+I),\dots, |J-I| = (0+I),\dots, |0-I| = I \rightarrow F=I=5/2$. This only happens when a state has quantum number $J=0$. With the constraint $F=I$, we find

```{math}
:label: eq-9-14
\begin{array}{rcl} K &=& F(F+1) - I(I+1) - J(J+1) \\ &=& I(I+1) - I(I+1) - 0(0+1) \\ &=& 0 \\ \rightarrow \Delta E &=& 0 \end{array}
```

Even though the nucleus has angular momentum, there is no energy shift when $J=0$. This hyperfine level has the same energy as the center of gravity. However, we will still label this state with the *F* quantum number: $1\text{s}^2 2\text{s}^2 2\text{p}^4~{ }^{3}\text{P}_{0}~F=\frac {5}{2}$. You will explore the hyperfine structure of oxygen-17 more in Problem [](#prob-9-3).

(sec-9-8)=
## 9.8 Problems

```{exercise}
:label: prob-9-1
:enumerator: 9.1

Table [](#tbl-9-2) shows the energy shifts for the hyperfine levels with respect to the center of gravity for the $7\text{p}~{ }^{2}\text{P}_{3/2}$ state in cesium-133. All of the real transitions in this problem are from the $6\text{s}~{ }^{2}\text{S}_{1/2}~F=4$ ground hyperfine level.

(a) In Sect. [](#sec-9-4-1), we found $\Delta E$ for the $F=4\rightarrow F'=3$ real transition. Confirm $\Delta E$ for the other two real transitions.
(b) Find $\Delta E$ for the three V crossovers, similar to what we did in Sect. [](#sec-9-4-2).
```

```{exercise}
:label: prob-9-2
:enumerator: 9.2

Below is table for four states in europium.[^8] The first row represents the ground state, and the three subsequent rows are excited states. Europium has two stable isotopes, europium-151 and europium-153.

(tbl-9-4)=
**Table 9.4**

| Electron configuration | $A_{151}$ (MHz) | $B_{151}$ (MHz) | $A_{153}$ (MHz) | $B_{153}$ (MHz) |
| --- | --- | --- | --- | --- |
| $4\text{f}^7 6\text{s}^2~{ }^{8}\text{S}_{7/2}$ | $-$20.0523$\pm$0.0002 | $-$0.7012$\pm$0.0035 | $-$8.8532$\pm$0.0002 | $-$1.7852$\pm$0.0035 |
| $4\text{f}^7 6\text{s} 6\text{p}~{ }^{8}\text{P}_{5/2}$ | $-$157.01$\pm$0.03 | 74.5$\pm$0.4 | $-$69.43$\pm$0.14 | 191$\pm$2.6 |
| $4\text{f}^7 6\text{s} 6\text{p}~{ }^{8}\text{P}_{7/2}$ | $-$218.66$\pm$0.04 | $-$293.4$\pm$0.8 | $-$97.15$\pm$0.13 | $-$750$\pm$3 |
| $4\text{f}^7 6\text{s} 6\text{p}~{ }^{8}\text{P}_{9/2}$ | $-$228.84$\pm$0.02 | 226.9$\pm$0.5 | $-$101.87$\pm$0.06 | 575.4$\pm$1.5 |

(a) Select either the 151 or 153 isotope and one of the three excited states from the table above. Use the largest to smallest in integer steps rule to find the possible *F* values for the ground state and your chosen excited state.
(b) Using the hyperfine splitting equation, calculate the energy splitting for the ground state. Don’t worry about the uncertainties.
(c) Using the hyperfine splitting equation, calculate the energy splitting for the excited state. Don’t worry about the uncertainties.
(d) Determine the transition frequency from a single ground hyperfine level (your choice) to a single excited state hyperfine level (your choice). Report your answer in MHz. Your final answer should include $f_{\text{cog}}$ in it.

Note: $f_{\text{cog}}$ is different for the two isotopes. This small difference is called an isotope shift, which we will explore in Chap. [](#ch-10).
```

```{exercise}
:label: prob-9-3
:enumerator: 9.3

Oxygen-17 has a nuclear spin quantum number of $I=5/2$, resulting in hyperfine structure. Sect. [](#sec-9-7) contains a table that lists the seven lowest energy states.

(a) Find the possible *F* quantum numbers for all seven states. Hint: There are only three calculations here!
(b) For the $1\text{s}^2 2\text{s}^2 2\text{p}^4~{ }^{3}\text{P}_{1}$ state, calculate the hyperfine energy shift $\Delta E$ for each hyperfine level in terms of the hyperfine constants. Label your hyperfine constants $A_{3P1}$ and $B_{3P1}$.
(c) Suppose you were to excite an oxygen atom from the $1\text{s}^2 2\text{s}^2 2\text{p}^4~{ }^{3}\text{P}_{1}~F=7/2$ state to the $1\text{s}^2 2\text{s}^2 2\text{p}^3 3\text{s}~{ }^{3}\text{S}_{1}~F'=5/2$ state. What is the transition frequency? Your answer should look something like $f=f_{\text{cog}}+\#A_{3P1}+\#B_{3P1}+\#A_{3S1}+\#B_{3S1}$.
(d) Suppose you performed saturated absorption spectroscopy across all hyperfine levels for the $1\text{s}^2 2\text{s}^2 2\text{p}^4~{ }^{3}\text{P}_{1} \rightarrow 1\text{s}^2 2\text{s}^2 2\text{p}^3 3\text{s}~{ }^{3}\text{S}_{1}$ transition. Write the fit function for this spectrum, assuming we have no crossovers.
(e) Challenge: Include crossovers!
(f) Optional: Find the relative intensities of all the real hyperfine transitions for the spectrum in part (d). The relative intensities should be with respect to the largest amplitude transition.
```

````{exercise}
:label: prob-9-4
:enumerator: 9.4

Consider the $3\text{s}~{ }^{2}\text{S}_{1/2}\rightarrow 3\text{p}~{ }^{2}\text{P}_{3/2}^{\circ }$ transition in sodium-23. The little circle on the excited state term symbol is the parity of the state, a topic we don’t cover in this book. Parity is an advanced topic that is easy to say in words, but hard to understand.[^9] Fig. [](#fig-9-6) is a Grotrian diagram that shows the hyperfine structure of both states. We will call the hyperfine constants for the ground state $A_{2S}$ and $B_{2S}$ and the hyperfine constants for the excited state $A_{2P}$ and $B_{2P}$.

```{figure} ../images/ch-09/541577_1_En_9_Fig6_HTML.png
:name: fig-9-6

A Grotrian diagram for a transition in sodium-23
```

(a) What is the nuclear spin quantum number for sodium-23?
(b) What is $B_{2S}$?
(c) Write the formula for the transition frequency between the $3\text{s}~{ }^{2}\text{S}_{1/2}~F=1$ state and the $3\text{p}~{ }^{2}\text{P}_{3/2}~F'=2$ state. Leave the hyperfine constants as $A_{2S}$, $A_{2P}$, and $B_{2P}$. You will find their values in parts (d) and (e).
(d) Determine the hyperfine constants for the $3\text{s}~{ }^{2}\text{S}_{1/2}$ state.
(e) Determine the hyperfine constants for the $3\text{p}~{ }^{2}\text{P}_{3/2}$ state.
(f) The center of gravity frequency is $f_{\text{cog}}=508,848,717.1\,\text{MHz}$. Determine the numerical value for the transition frequency for the $3\text{s}~{ }^{2}\text{S}_{1/2}~ F=1 \rightarrow 3\text{p}~{ }^{2}\text{P}_{3/2}~F'=2$ transition.
(g) Optional: Find the relative amplitudes of the real transitions between the $3\text{s}~{ }^{2}\text{S}_{1/2}~F=2$ state and the allowed excited states.
````

## References

1. Williams, W.D., Herd, M.T., Hawkins W.B.: Spectroscopic Study of the $7\text{p}_{1/2}$ and $7\text{p}_{3/2}$ States in Cesium-133. Laser Phys. Lett. **15**(9), 095702 (2018). [https://doi.org/10.1088/1612-202X/aac97](https://doi.org/10.1088/1612-202X/aac97)
2. Sandars P.G.H., Woodgate G.K.: Hyperfine structure in the ground state of the stable isotopes of europium. Proc. R. Soc. Lond. A. **257**, 269–276 (1960). [https://doi.org/10.1098/rspa.1960.0149](https://doi.org/10.1098/rspa.1960.0149)
3. Maruko, C., Cölmek, N., Herd, M.T., Ahrendsen, K., Cabrales, B., Cannon, G., Davis, E., Guo, X., Karani, T., Wallace, A., Wisnauckas, K., Williams, W.D.: Spectroscopic study of the $4\text{f}^{7}6\text{s}^{2}~{ }^{8}\text{S}_{7/2}^{\circ } - 4\text{f}^{7}({ }^{8}\text{S}^{\circ })~6\text{s}6\text{p}({ }^{1}\text{P}^{\circ })~{ }^{8}\text{P}_{5/2,7/2}$ transitions in neutral europium-151 and europium-153: absolute frequency and hyperfine structure. J. Opt. Soc. Am. B. **41**, 1217–1223 (2024). [https://doi.org/10.1364/JOSAB.521181](https://doi.org/10.1364/JOSAB.521181)
4. Herd, M.T., Maruko, C., Herzog, M.M., Brand, A., Cannon, G., Duah, B., Hollin, N., Karani, T., Wallace, A., Whitmore, M., Williams, W.D.: Spectroscopic study of the $4\text{f}^{7}6\text{s}^2~{ }^{8}\text{S}_{7/2}^{\circ }-4\text{f}^7({ }^{8}\text{S}^{\circ })6\text{s}6\text{p}({ }^{1}P^{\circ }){ }^{8}\text{P}_{9/2}$ transition in neutral europium-151 and europium-153: absolute frequency and hyperfine structure. J. Opt. Soc. Am. B. **39**, 2596–2602 (2022). [https://doi.org/10.1364/JOSAB.467968](https://doi.org/10.1364/JOSAB.467968)

[^1]: How cool of a journal name is that?! See reference [2] for the full citation.

[^2]: $f_{F=2\rightarrow F'=1}=f_{\text{cog}}-\frac {3}{4} A_{\text{LS}}-\frac {5}{4} A_{\text{US}}$.

[^3]: Reference [1].

[^4]: A full list of the rules that need to be satisfied for an electron to transition between two atomic states is given in Appendix [](#app-c).

[^5]: See Reference [4] for the full citation.

[^6]: There is also an $F'=2$ excited hyperfine level, but we cannot excite an atom from the $F=4$ ground hyperfine level to this state.

[^7]: There are many subtleties that we are glossing over here. Spectra sometimes have an offset, a sloped offset, or a Gaussian pedestal for various reasons. When you fit data, sometimes you have to add something to your fit function. However, you should always have a reason for why you are adding something to your fit function.

[^8]: Ground state citation: Reference [2]. ${ }^{8}\text{P}_{5/2}$ and ${ }^{8}\text{P}_{7/2}$ citation: Reference [3]. ${ }^{8}\text{P}_{9/2}$ citation: Reference [4].

[^9]: You should, of course, do an internet search for “parity physics” if you’d like to learn more.
