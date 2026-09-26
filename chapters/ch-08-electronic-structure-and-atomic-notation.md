---
title: 8. Electronic Structure and Atomic Notation
short_title: "Ch. 8 — Electronic Structure"
label: ch-8
doi: 10.1007/978-3-031-69507-0_8
---

## Abstract

In this chapter, we explore the fundamental principles governing the electronic structure of atoms and the notation used to describe it. We begin by examining energy level spacings across various elements, highlighting how the number of electrons influences the complexity of these levels. The Coulomb interaction and electron shell filling patterns are introduced as key factors determining atomic state energies. Through detailed discussions on electronic configurations and term symbols, we illustrate how angular momentum, both in individual electrons and in atoms as a whole, impacts energy states. We also discuss fine structure splitting and hyperfine structure splitting. By the end of this chapter, readers will have a comprehensive understanding of the labels used by atomic physicists for electronic levels in atoms. Additionally, we differentiate between fermions and bosons, emphasizing their roles and significance in atomic and nuclear physics.

**Keywords:** Energy level spacings, Coulomb interaction, Electron shells, Electronic configuration, Term symbols, Fermions, Bosons, Pauli exclusion principle

## Learning Goals

By the end of this chapter, you should be able to understand:

- the Coulomb interaction and its role in determining the energy levels within an atom.
- describe how electrons fill shells and subshells according to quantum mechanical principles.
- the concept of angular momentum in the context of atomic physics and how it affects atomic energy states.
- the influence of Coulomb interactions, electron shell filling, and angular momentum on the energy of atomic states.
- interpret and describe electronic configurations and term symbols to understand the angular momentum of individual electrons and the overall atom.
- explain the difference between fine structure splitting and hyperfine structure splitting.
- distinguish between fermions and bosons and explain their significance in atomic and nuclear physics.

(sec-8-1)=
## 8.1 Energy Level Spacings

Figure [](#fig-8-1) shows the energy levels for hydrogen, helium, lithium, and europium. As a reminder, hydrogen has 1 electron, helium has 2, lithium has 3, and europium has 63. Notice how different the energy levels are! Hydrogen’s first excited state is over 80,000 $\text{cm}^{-1}$ above the ground state, while helium’s first excited state is around 160,000 $\text{cm}^{-1}$ above the ground state![^1] The hydrogen states seem to get closer and closer to each other as the energy increases, but helium seems to “clump” a bit more. And look at europium; there seems to be a big gap after the ground state before a really dense set of energy levels, a gap, and then even more! The red line on each element is the energy needed to rip an electron from the atom. We call this the **ionization threshold**.
```{figure} ../images/ch-08/541577_1_En_8_Fig1_HTML.png
:label: fig-8-1
:alt: The energy levels of hydrogen, helium, lithium, and europium. The red line at the top of each element is the ionization threshold, which is the energy required to remove an electron from the atom

The energy levels of hydrogen, helium, lithium, and europium. The red line at the top of each element is the ionization threshold, which is the energy required to remove an electron from the atom

```

Even though the energy levels are so densely packed, they are still discrete. The energy levels looking like a solid band is just an artifact of making a picture with many, many discrete energy levels (the europium diagram has 500 levels in it). Figure [](#fig-8-2) is a zoom in of the europium energy levels from 40,210 $\text{cm}^{-1}$ to 40,250 $\text{cm}^{-1}$, which is right in the middle of one of the dense patches. As you can see, these 7 levels are very close together, but still discrete. Plotting all 500 levels together really highlights the groupings.
```{figure} ../images/ch-08/541577_1_En_8_Fig2_HTML.png
:label: fig-8-2
:alt: A zoom in on some of the denser states in europium. Even though there are many states, they are still discrete

A zoom in on some of the denser states in europium. Even though there are many states, they are still discrete

```

**Guiding Question**

Why are the energy levels so different for each element?

Give it some thought and then read on.

(sec-8-2)=
## 8.2 The Coulomb Interaction and Electron Shells

**Definitions**

- **Coulomb force:** The force between two charged particles, described by $F = k_e \frac {q_1 q_2}{r^2}$, where $F$ is the force, $k_e = 8.987 \times 10^9 \ \text{N} \cdot \text{m}^2/\text{C}^{2}$ is Coulomb’s constant, $q_1$ and $q_2$ are the charges, and $r$ is the distance between them. It represents the attraction or repulsion between the charged particles.
- **Coulomb interaction:** The interaction between two charged particles due to their electric charges. It is governed by the Coulomb force and is fundamental in understanding the behavior of charged particles.

We use the phrase Coulomb interaction when we are thinking about general interactions between charged particles, such as how these interactions can affect energy levels. We use the phrase Coulomb force when we are specifically thinking about the force one charged particle exerts on the other.

There are many interactions that happen inside the atom. Each of these interactions affects where the discrete energy levels end up. If we, as physicists, understand all of these interactions we should be able to calculate properties of the atom like the energy of a particular state, the natural linewidth of each transition, and what would happen if we put the atoms in a particular situation such as inside an electric field, a magnetic field, or if we put a bunch of these atoms together so strongly compressed under gravity that the gravitational energy is converted into heat and eventually the atoms fuse together.[^2] While there are many interactions happening in the atom, the two biggest contributions that determine the energy of an atomic state are the Coulomb interaction and how electrons fill up “shells.”

The **Coulomb interaction** is how we describe the interaction between charged particles. For the hydrogen atom, there is only 1 Coulomb interaction. That interaction is between the single electron, which has negative charge, and the single proton, which has positive charge. In fact, this interaction is so simple we can exactly solve the Schrödinger equation to find the effect this interaction has on the energy levels. The helium atom has two electrons and two protons. The two protons are inside the nucleus and, while there is technically a Coulomb interaction between the two protons, that interaction is overwhelmed by the strong nuclear force, which is a topic in Chap. [](#ch-10). Therefore, we can think of the nucleus as a single particle with a charge of $+2$. The two electrons on the other hand are not confined tightly together like the two protons in the nucleus. For the helium atom, there are effectively 3 Coulomb interactions: one between the two electrons, one between one of the electrons and the nucleus, and one between the other electron and the nucleus. The increased number of interactions causes most of the dramatic difference between the energy levels of hydrogen and helium.

Lithium has 3 electrons and europium has 63. Like helium, we can think about the nucleus of lithium as 1 particle with a charge of +3. Even though europium has 63 protons in the nucleus, we can still think of the nucleus as 1 particle with a charge of +63.[^3] Now we have a lot of interactions. Each electron has a Coulomb interaction with every other electron and each electron has a Coulomb interaction with the nucleus. One of the homework problems for this chapter will have you count the number of Coulomb interactions for the first few atoms in the periodic table.

The second major contribution comes from something called **electron shells**, which are made up of **electron subshells**. The first shell is called 1, and it contains 1 subshell labelled 1s, see Fig. [](#fig-8-3). The second shell is 2 and has two subshells. The third shell is 3 and has 3 subshells and so on. In Fig. [](#fig-8-3), we stop showing all possible subshells on shell 5. There is a 5g subshell, 6f, 6g, 6h, etc. that is not shown. In quantum mechanics and atomic physics, the shell number $(1,~2,~3,~\dots )$ is a quantum number called the principal quantum number, represented by the letter *n*. This is the same quantum number *n* explored in Chap. [](#ch-6).
```{figure} ../images/ch-08/541577_1_En_8_Fig3_HTML.png
:label: fig-8-3
:alt: How electrons fill shells. This diagram is often called Madelung energy ordering rule, named after the German physicist Erwin Madelung. The top row is the n = 1 shell and has one subshell. The second row is the n = 2 shell and has two subshells. The third row is the n = 3 shell and has three subshells, and so on

How electrons fill shells. This diagram is often called Madelung energy ordering rule, named after the German physicist Erwin Madelung. The top row is the $n=1$ shell and has one subshell. The second row is the $n=2$ shell and has two subshells. The third row is the $n=3$ shell and has three subshells, and so on

```

The electron subshells come about because an electron in an atom can have orbital angular momentum and spin. The letter accompanying the principal quantum number is the orbital angular momentum quantum number for the electron in that subshell. The subshells use the historical letter designations discussed in Chap. [](#ch-7). As a reminder, if an electron has the label s, it has $\ell =0$. If it has a label p, it has $\ell =1$, and so on. For example, 3p tells us that $n=3$ and $\ell =1$. From solving the Schrödinger equation, we find that *n* is the upper limit on possible values for $\ell$. As a reminder, $\ell$ is a zero or a positive integer. From the math, we find $\ell _{\text{max}}=n-1$. For example, if $n=3$, then $\ell =0$, 1, or 2. That means the $n = 3$ shell has three subshells: 3s, 3p, and 3d. There is no 3f subshell since $\ell =n$, which is not allowed.

An s-subshell can hold 2 electrons in total; one will have spin up $(m_{s}=+1/2)$ and the other spin down $(m_{s}=-1/2)$. A p-subshell can hold 6 electrons in total: 3 spin up and 3 spin down. A d-subshell can hold 10 electrons (5 up and 5 down); an f-subshell can hold 14, a g-subshell can hold 18, etc. The subshells fill in a specific order roughly shown in Fig. [](#fig-8-3).

The first subshell to fill is the 1s subshell, which can hold 2 electrons. After the 1s subshell is filled, electrons start to fill the 2s subshell, which also holds 2 electrons. Once the 2s subshell is filled, electrons start to fill the 2p subshell, which holds 6 electrons. Next is 3s followed by 3p, 4s, 3d, 4p, etc.

**Why Can a p-Shell Hold 6 Electrons?**

An electron with the label p means that $\ell =1$. There are three possible orientations for this angular momentum vector: $m_\ell =-1$, 0, and 1. In addition, the electron can be either spin up or spin down. That means there are 6 orientations for an electron to have $\ell =1$. Using the notation ($m_\ell$, $m_s$), the possible orientations for a p-subshell are:

```{math}
\begin{array}{llllll}
\left(1, +\frac{1}{2}\right) & \left(1, -\frac{1}{2}\right) & \left(0, +\frac{1}{2}\right) & \left(0, -\frac{1}{2}\right) & \left(-1, +\frac{1}{2}\right) & \left(-1, -\frac{1}{2}\right)
\end{array}
```

An electron with the label *d* means that $\ell =2$. There are 5 possible orientations for this vector ($m_\ell$ = -2,-1,0,1,and 2). Including spin up and spin down for each $m_\ell$ gives 10 possible orientations. Using the notation ($m_\ell$, $m_s$), the possible orientations for a d-subshell are:

```{math}
\begin{array}{lllll}
\left(2, +\frac{1}{2}\right) & \left(1, +\frac{1}{2}\right) & \left(0, +\frac{1}{2}\right) & \left(-1, +\frac{1}{2}\right) & \left(-2, +\frac{1}{2}\right) \\
\left(2, -\frac{1}{2}\right) & \left(1, -\frac{1}{2}\right) & \left(0, -\frac{1}{2}\right) & \left(-1, -\frac{1}{2}\right) & \left(-2, -\frac{1}{2}\right)
\end{array}
```

Figure [](#fig-8-4) shows Bohr model pictures of hydrogen, helium, and lithium in their lowest energy state (the ground state). Remember that electrons are actually more like waves, but I like to draw them as little balls to explore this concept. Hydrogen has 1 electron so the 1s subshell is half filled. Helium has 2 electrons that fully fill this 1s subshell. If we move up the periodic table to lithium (3 electrons), 2 electrons fill the 1s shell while the last electron is in the 2s shell.
```{figure} ../images/ch-08/541577_1_En_8_Fig4_HTML.png
:label: fig-8-4
:alt: A Bohr model picture of hydrogen, helium, and lithium. Electrons will first fill the 1s subshell. Hydrogen half fills the 1s subshell, while Helium fills the 1s subshell completely. Lithium has 3 electrons that completely fill the 1s subshell leaving a single electron in the 2s subshell

A Bohr model picture of hydrogen, helium, and lithium. Electrons will first fill the 1s subshell. Hydrogen half fills the 1s subshell, while Helium fills the 1s subshell completely. Lithium has 3 electrons that completely fill the 1s subshell leaving a single electron in the 2s subshell

```

So, why does this affect the energy levels in the atom? The answer is every time we fill a shell, it is like creating a new nucleus with a reduced charge. For example, let’s look at a picture of lithium in Fig. [](#fig-8-4). I added a red dashed line between the 1s and 2s shells. Inside this red dashed line, the effective charge is +1 (2 electrons and 3 protons). For all it knows, that 1 electron sitting in the 2s subshell is all by itself interacting with a nucleus with charge +1. This is just like the hydrogen atom with a few key differences. The first is the nucleus of lithium has a lot more mass than the nucleus of hydrogen. The second is that the outermost electron in lithium is farther away from the nucleus. The reduced Coulomb force means the energy levels for lithium are not as widely spaced compared to hydrogen. This is why the hydrogen atom and the lithium atom energy levels look so similar, but the lithium energy levels are closer together, see Fig. [](#fig-8-5). All of the atoms in the first column of the periodic table (hydrogen, lithium, potassium, rubidium, cesium, and francium) have 1 electron sitting outside a closed shell. Therefore, the energy levels of these atoms are very similar to hydrogen.
```{figure} ../images/ch-08/541577_1_En_8_Fig5_HTML.png
:label: fig-8-5
:alt: The energy levels for the first column of the periodic table. Each of these elements has fully closed shells except for a single electron in an s-shell

The energy levels for the first column of the periodic table. Each of these elements has fully closed shells except for a single electron in an s-shell

```

We write the **electron configuration** with superscripts that tell us how many electrons are in a subshell; if there is no superscript present, there is only 1 electron in that subshell. For example, the electronic configuration for the ground state of helium is $1\text{s}^2$; there are 2 electrons in the 1s subshell. If we excite the atom so that 1 electron moves to the 3d subshell, the electronic configuration is 1s3d; 1 electron is in the 1s subshell and 1 is in the 3d subshell.

As we move through the periodic table, the atoms gain more and more electrons filling up shells according to Fig. [](#fig-8-3). I should note that while the chart does a really good job, particularly for lighter atoms, it messes up sometimes for heavier atoms. For example, the chart predicts that the ground state of silver (47 electrons) should have a filled 5s subshell and 9 electrons in the 4d subshell:

```{math}
1\text{s}^2 2\text{s}^2 2\text{p}^6 3\text{s}^2 3\text{p}^6 3\text{d}^{10} 4\text{s}^2 4\text{p}^6 5\text{s}^2 4\text{d}^9
```

However, the actual electronic configuration has a completely filled 4d subshell and a single electron in the 5s subshell:

```{math}
1\text{s}^2 2\text{s}^2 2\text{p}^6 3\text{s}^2 3\text{p}^6 3\text{d}^{10} 4\text{s}^2 4\text{p}^6 4\text{d}^{10} 5\text{s}
```

As physicists, we ask, “Why?” Why would silver decide that filling the 4d subshell is better than following that chart and keeping the 5s subshell filled? The short answer is that nature tends to try and get to a configuration with the lowest overall energy.

**A General Rule of Nature**

A system always seeks to reach a state of lower energy.

As an analogy, think about a ball in a bowl. The ball will want to hang out at the bottom of the bowl, which is the spot of lowest energy. Because there are so many electrons in silver and so many interactions, the electron configuration that fills the 4d shell has less energy than if the 5s shell was filled.

**Quick quiz:**

Considering the silver atom, how many electrons are in the 3d subshell? The answer is in the footnotes.[^4]

Here is the electron configuration for the ground state of europium, which has 63 electrons:

```{math}
1\text{s}^2 2\text{s}^2 2\text{p}^6 3\text{s}^2 3\text{p}^6 3\text{d}^{10} 4\text{s}^2 4\text{p}^6 4\text{d}^{10} 5\text{s}^2 5\text{p}^6 6\text{s}^2 4\text{f}^7
```

From this electronic configuration we can see which shells are filled. After the 6s subshell fills up, the 4f subshell starts to fill until we run out of electrons. There are 7 electrons in the unfilled 4f subshell. Combined with the Coulomb interactions, the end result is a pretty complicated energy level diagram, see Figs. [](#fig-8-1) and [](#fig-8-2). This is why I’m glad to be an experimentalist. I don’t have to try to calculate these levels, just measure them ☺.

**Summary**

The dominant interactions in atoms that determine the energy level locations are the Coulomb interaction and the way electrons fill shells.

(sec-8-3)=
## 8.3 Term Symbols

**Reminder Definition**

- **Torque:** A measure of how effective a force is in causing an object to rotate. Applying torque changes the angular momentum of an object. There is energy associated with that torque.

We spent almost all of Chap. [](#ch-7) studying angular momentum and emphasizing the orientation of the vectors. The theory of electricity and magnetism reveals an important fact: because electrons and the nucleus have charge, and the electrons have angular momentum, everything in the atom exerts a torque on everything else.

**A Brief Aside**

The Coulomb interaction is used to describe the interaction between charged particles, resulting in an electric field between the charges. This approach ignores the motion associated with their angular momentum. When we include angular momentum, it is more appropriate to use the electromagnetic interaction because moving charges create magnetic fields. Therefore, the interaction between moving charged particles involves both electric and magnetic forces, which is what the electromagnetic force describes.

**Definitions**

- **Electromagnetic force:** A fundamental force encompassing both electric and magnetic forces, including the Coulomb force and magnetic forces due to moving charges.
- **Electromagnetic interaction:** The interaction between charged particles due to both electric and magnetic forces, including interactions involving stationary charges (electrostatics) and moving charges.

The magnetic forces from the moving charges cause the internal torques. The magnitude of this internal torque depends on the orientation and size of the angular momentum vectors. In short, both the size and the orientation of the angular momentum vectors impact the energy of a state. That is so important, I’m going to give the sentence its own red box.

**Important**

Both the size and the orientation of the angular momentum vectors impact the energy of a state.

If we had a magic wand to change the orientation of an angular momentum vector, the energy of that state would change slightly. Now we can add a third property that affects where the energy levels end up: the Coulomb interaction, electron shells, and angular momentum.

The total orbital angular momentum of all the electrons, the total spin of all of the electrons, and total angular momentum of all of the electrons affect the energy of a state. Therefore, we need to include that information in the description of a state. By tradition, we combine these quantum numbers into a “term symbol”, which looks like this:

```{math}
:label: eq-8-1

{}^{2S+1}L_{J}
```

where *S* is the quantum number representing the total spin of all the electrons, *L* is the quantum number for the total orbital angular momentum of all the electrons, and *J* is the quantum number for the total angular momentum of all of the electrons. For example, suppose an energy level has a term symbol ${ }^{3}\text{D}_{2}$. That tells us that the spin of the electrons has quantum number $S=1$ $(2S+1=3)$, the orbital angular momentum of the electrons has quantum number $L=2$ (represented by the letter D), and the total electronic angular momentum of the electrons has quantum number $J=2$. We can use those numbers to calculate the magnitude of angular momentum.

**Two Important Reminders**

1. The term symbol is important not just because it tells us three quantum numbers for the electrons in an atom as a whole, but also because those three quantum numbers affect the energy of a state.
2. The observables represented by *S*, *L*, and *J* are all compatible with energy.

The shift of an energy level due to electrons having angular momentum is called fine structure splitting.[^5] The nucleus can also have angular momentum (often called nuclear spin), which is the topic of Chap. [](#ch-9). The shift in the energy of a state due to the nucleus having angular momentum is called hyperfine structure splitting.[^6]

**Definitions**

- **Fine structure splitting:** The shift in the energy of a state due to the electrons having orbital angular momentum and spin.
- **Hyperfine structure splitting:** The shift in the energy of a state due to the nucleus having angular momentum.

Table [](#tbl-8-1) shows the six lowest energy states of atomic oxygen (8 electrons, 8 protons, and 8 neutrons). This particular type of oxygen is known as oxygen-16. Oxygen-16 has no nuclear angular momentum, so the nucleus does not play a role in the following discussion. Notice that the first five energy states all have the same electronic configuration but different term symbols. The next few paragraphs are all about adding lots and lots of angular momentum vectors together. We are going to start with the ground state and then work our way through the table.

(tbl-8-1)=
**Table 8.1** The first 6 states of atomic oxygen. The last column is the frequency of a laser needed if we were to try to excite the atom from the ground state to that state

| Electron configuration | Term symbol | Energy $(\text{cm}^{-1})$ | *f* (Hz) |
| --- | --- | --- | --- |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{3}\text{P}_{2}$ | 0 |  |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{3}\text{P}_{1}$ | 158.265 | $4.74\times 10^{12}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{3}\text{P}_{0}$ | 226.977 | $6.80\times 10^{12}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{1}\text{D}_{2}$ | 15,867.862 | $4.76\times 10^{14}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^4$ | ${ }^{1}\text{S}_{0}$ | 33,792.583 | $1.01\times 10^{15}$ |
| $1\text{s}^2 2\text{s}^2 2\text{p}^3 3s$ | ${ }^{5}\text{S}_{2}$ | 73,768.200 | $2.21\times 10^{15}$ |

**Reminder of Eq.** [](#eq-7-5)

Suppose we have two quantum mechanical angular momenta vectors whose magnitudes are represented by quantum numbers *L* and *S*. Depending on the orientation of the two vectors, adding them together produces a new quantum mechanical angular momentum vector that can have different magnitudes, represented by the quantum numbers

```{math}
\begin{array}{c}
J=(L+S), \dots , |L-S| \\
\text{in integer steps}
\end{array}
```

For example, if $L=3$ and $S=1$, then *J* can be 4, 3, or 2. If $J=4$, then there are 9 possible orientations of this new angular momentum vector represented by the quantum number $m_J=$ 4, 3, 2, 1, 0, $-1, -2, -3$, or $-$4. Similarly, if $J=2$, then there are 5 possible orientations of this new angular momentum vector represented by the quantum number $m_J=$ 2, 1, 0, $-$1, or $-$2.

The ground state of oxygen has the designation $1\text{s}^2 2\text{s}^2 2\text{p}^4$ ${ }^{3}\text{P}_{2}$. This designation tells us that both the 1s and 2s subshells are completely filled, and we can essentially ignore them. The 2p subshell is partially filled with 4 electrons (the 2p subshell can hold up to 6 electrons). From the electronic configuration, we know the orbital angular momentum of each electron. The 4 electrons in the 2p subshell each have $\ell =1$, or each electron in this subshell has orbital angular momentum with size $\sqrt {\ell (\ell +1)}\hbar =\sqrt {2}\hbar$.

Each of the electrons in the 2p subshell has the same magnitude of orbital angular momentum ($\ell =1$), but has a different orientation. If we were to add all four of those vectors together, we would get a new vector that represents the orbital angular momentum of all four electrons as a composite system. For the ground state, the orbital angular momentum of the composite system has a magnitude represented by quantum number $L=1$ (P in the term symbol).

Those same four electrons also have individual spin vectors that add up to $S=1$ $(2S+1=3)$. Again, that spin vector represents the total spin of all four electrons as a composite system. Since the orbital angular momentum vector for all four electrons has a size and orientation and the spin vector for all four electrons has a size and orientation, we can ask the question, “What are the possible magnitudes for the total electronic angular momentum for the composite system?” The answer is $J=2$, 1, or 0. The orientations that produce a vector whose magnitude is represented by $J=2$ have the lowest energy, so that is the ground state.

**Important Foreshadowing Statement**

The total electronic angular momentum for the ground state ($J=2$) has 5 possible orientations that, in the absence of nuclear spin, all have the same energy. In other words, there are 5 states that all have the same energy. When there are states that have the same energy, we call those states **degenerate**.

Now let’s move on to the next energy level. This level has an energy that is $158.265\,\text{cm}^{-1}$ larger than the ground state. The only difference in the designation for the ground state and this state is that *J* in the term symbol ($J=2$ for the ground state and $J=1$ for this state). The orbital angular momentum for all four electrons and the spin for all four electrons still add together, but the result has a different total electronic angular momentum for the composite system. The orientation of all the electrons to produce this new composite vector has a different internal torque, so that orientation has a different energy than the $J=2$ ground state.

The first 5 energy levels of atomic oxygen have the same electron configuration: $1\text{s}^2 2\text{s}^2 2\text{p}^4$. To determine how the angular momenta of the last 4 electrons combine, we look at the term symbols. As you can see from the table, there are multiple ways this can happen, each resulting in a different energy level. In a hypothetical world without the internal torque, all 5 of these levels would be degenerate. However, due to the internal interactions, these levels split into the 5 distinct levels observed experimentally. This phenomenon is known as fine structure splitting.[^7]

While the nucleus of oxygen-16 has no angular momentum, a different nucleus might. That nuclear angular momentum, whose magnitude is represented by the quantum number *I*, exerts an additional internal torque that, once again, shifts the energy of the states. This additional internal torque “breaks” the degeneracy of the fine structure states. For example, oxygen-17 has nuclear spin $I=5/2$ (6 possible orientations). The ground state has a total electronic angular momentum of $J=2$ (5 possible orientations). Adding together vector *J* and vector *I* produces a new angular momentum vector whose magnitude is represented by the quantum number *F* with possible values that range from $J+I$ to $|J-I|$ in integer steps, or in this case $F =$ 9/2, 7/2, 5/2, 3/2, and 1/2. So the ground state of oxygen-17 further splits into five hyperfine levels, each with a different energy. From the “important foreshadowing statement,” the orientation of a particular *F* vector will not change the energy. If $F=3/2$, there are four orientations represented by $m_F=$ 3/2, 1/2, $-1/2$ and $-1$. All four of these states are degenerate. We will explore hyperfine structure and how the nucleus affects our energy levels further in Chap. [](#ch-9).

**Common Question**

If $J=2$, there are 5 states with different orientations that have the same energy. Can we do anything to “split” those final orientations so they have different energies? Yes! The internal torque doesn’t do it, but we can apply a torque from the outside to “break the degeneracy”. Applying an external torque using an external magnetic field is called the Zeeman Effect, named after the Dutch physicist Pieter Zeeman. Applying an external torque by applying an electric field is called the Stark Effect, named after the German physicist Johannes Stark. Both of these effects “break” the degeneracy of those states.

**Summary**

The orientation and size of angular momentum impact the energy of a state. For an atom with no nuclear spin, a state can be described by the individual electron configurations, which tell us the angular momentum of each individual electron, and the term symbol, which tells us about the orientation of the angular momentum vectors of the electrons as a whole.

**Super Short Summary**

The orientation and size of the angular momentum vectors matter.

(sec-8-4)=
## 8.4 Connecting Angular Momentum to Orbitals

You may have learned about orbitals in high school chemistry. Orbitals are visual representations of different energy states for an electron in a hydrogen atom. Figures [](#fig-8-6) and [](#fig-8-7) show some orbital pictures for different energy states in hydrogen. These are analogous to the shaking energy modes we studied in Chap. [](#ch-1) (Fig. [](#fig-1-7)) and Chap. [](#ch-6) (Fig. [](#fig-6-2)). There are 3 numbers on each plot given in bra-ket notation. The first number is the principal quantum number (also called the shell number). The second is the orbital angular momentum quantum number, and the last is the projection of the orbital angular momentum quantum number along the *z*-axis (orientation). For example, $|4~3\ \text{-}1\rangle$ means $n=4$, $\ell =3$, and $m_\ell =-1$. You can think of all of these orbitals as different standing waves of the electron. The “loops” are a bit harder to see in 3-dimensional space, so in Fig. [](#fig-8-6) we plot a few different orbitals in 3D and in Fig. [](#fig-8-7) we plot a few cross sectional views. The reason they are so hard to visualize is that we only have 3 dimensions to view 4 dimensions of information.
```{figure} ../images/ch-08/541577_1_En_8_Fig6_HTML.png
:label: fig-8-6
:alt: 3D illustrations of different electron orbitals in a hydrogen atom. The darker the shade the larger the amplitude of the standing wave

3D illustrations of different electron orbitals in a hydrogen atom. The darker the shade the larger the amplitude of the standing wave

```
```{figure} ../images/ch-08/541577_1_En_8_Fig7_HTML.png
:label: fig-8-7
:alt: A cross sectional view of different electron orbitals in the Hydrogen atom. The closer the color is to white, the larger the amplitude of the standing wave

A cross sectional view of different electron orbitals in the Hydrogen atom. The closer the color is to white, the larger the amplitude of the standing wave

```

For example, if you look at Fig. [](#fig-6-2) you’ll see that we need two dimensions to see the energy state for 1 dimension of shaking energy. The vertical axis shows the amplitude of the energy state while the horizontal shows position in 1 dimension. An example of a 2 dimensional standing wave would be a drum head vibrating. To visualize a 2 dimensional standing wave, we need a 3 dimensional plot: 1 dimension for the amplitude and 2 for the position dimensions. We run into a problem for 3 dimensional energy states. We now need to plot 3 dimensions of position, but we also need to visualize the amplitude. Figures [](#fig-8-6) and [](#fig-8-7) attempt to show the amplitude by shading.

It is important to point out that these orbitals are not discrete regions of space (for example an orbital is not like a hollow ping pong ball or a uniformly filled sphere). It is more like a foam ball where the density of the foam ball is not uniform but varying in space. If we were to measure the position of the electron, it would be most probable to find the electron at a place where the energy state is most dense. As an analogy, if we were to measure the position of the quantum particle for a system in an energy state seen in Fig. [](#fig-6-2), the most probable place to find the quantum particle would be where the amplitude is largest.

(sec-8-5)=
## 8.5 Fermions and Bosons

In atomic and nuclear physics, particles are categorized into two major groups: **fermions** and **bosons**. Fermions are particles with half-integer spin quantum numbers (e.g., 1/2, 3/2, etc.). Examples of fermions are electrons, protons, and neutrons, all of which have a spin quantum number of 1/2. Bosons are particles with integer spin quantum numbers (e.g., 0, 1, etc.). So far, we have encountered only one boson, the photon, which has a spin quantum number of 1.

This is important because two *identical* fermions cannot “hang out” in the same space while two identical bosons can. This is the essence of the **Pauli Exclusion Principle**: two fermions cannot simultaneously occupy the same quantum state; that is, no two fermions can have the same set of quantum numbers within a quantum system. As an example, consider the two electrons, both of which are fermions, in the atomic ground state of a helium atom, which has the electronic configuration $1\text{s}^2$. Let’s write out the quantum numbers for the two electrons using bra-ket notation with the quantum numbers $|{n~\ell ~m_\ell ~s~m_s}\rangle$. The two electrons have quantum numbers:

```{math}
\begin{array}{rl}
\text{First Electron:} & ~|{1~0~0~\frac{1}{2}~\frac{1}{2}}\rangle \\
\text{Second Electron:} & ~|{1~0~0~\frac{1}{2}\,\text{-} \frac{1}{2}}\rangle
\end{array}
```

Notice that the two electrons have a different set of quantum numbers. If they did have the same quantum numbers, the math from quantum mechanics shows that the two electron wavefunctions would cancel each other out.[^8] This is a very bad thing. If the individual electron wavefunctions added together to produce no wavefunction, neither electron would exist. Therefore, the two electrons must have different quantum numbers. This is what is meant by the phrase, “two *identical* fermions cannot hang out in the same space”. They must have a different set of quantum numbers.

The Pauli Exclusion Principle is part of why electron shells and subshells exist. Every electron in the atom *must* have a different set of quantum numbers. Interestingly, bosons don’t have this problem. Two bosons can have the same set of quantum numbers and not destructively interfere with each other. So, two identical bosons can hang out in the same space. In fact, the two bosons can constructively interfere with each other.

There can also be composite fermions and bosons. For example, helium-4 is a system that acts as a composite boson. Helium-4 contains 2 protons, 2 neutrons, and 2 electrons. All of these particles are fermions, but they can pair up to behave like bosons. Other examples of composite bosons include Cooper pairs[^9] (important for superconductors) and Bose–Einstein condensates[^10]. Helium-3, which has 2 protons, 2 electrons, and 1 neutron, is a composite fermion.

(sec-8-6)=
## 8.6 Problems

```{exercise}
:label: prob-8-1
:enumerator: 8.1

As discussed in the chapter, hydrogen has 1 Coulomb interaction and helium has 3. Assuming the nucleus is one big particle with a positive charge, how many Coulomb interactions do lithium, beryllium, and boron have?

Challenge: What is the general formula to calculate the number of Coulomb interactions for an atom with *N* electrons, assuming the nucleus is one big particle with positive charge?
```

````{exercise}
:label: prob-8-2
:enumerator: 8.2

The electron configuration for hydrogen is 1s. There is 1 electron in the first s subshell. The electron configuration for helium is $1\text{s}^2$. That means there are 2 electrons in the first s subshell, which completely fills the shell. Lithium has 3 electrons, so the electron configuration is $1\text{s}^2 2\text{s}$. Notice since the first shell is filled, we begin to fill the second shell. Write out the electron configurations for

- (a) beryllium (4 electrons)
- (b) boron (5 electrons)
- (c) carbon (6 electrons)
- (d) nitrogen (7 electrons)
- (e) oxygen (8 electrons)
- (f) fluorine (9 electrons)
- (g) neon (10 electrons)
- (h) sodium (11 electrons).

Note: The electron configurations are something that you can easily find on the internet. You can also find the answers in Appendix B. Don’t search for the answer before you try yourself first.
````

````{exercise}
:label: prob-8-3
:enumerator: 8.3

For each of the following term symbols, what is the magnitude of the total electronic spin, the total electronic orbital angular momentum, and the total electronic angular momentum?

- (a) ${ }^{3}\text{P}_{2}$
- (b) ${ }^{3}\text{P}_{0}$
- (c) ${ }^{1}\text{S}_{0}$
- (d) ${ }^{1}\text{F}_{2}$
````

```{exercise}
:label: prob-8-4
:enumerator: 8.4

Appendix B has a list of all of the elements with their ground state electronic configurations. Look through the list and find all the atoms that will have an energy level structure similar to hydrogen (i.e. all the shells are filled except for a single electron in the last s subshell). All of these elements will have energy level diagrams that look similar to hydrogen.
```

````{exercise}
:label: prob-8-5
:enumerator: 8.5

If we ionized (removed 1 electron) from beryllium, its electronic structure would look just like lithium, see Fig. [](#fig-8-8). While the energy level spacings are proportionally similar, lithium is more compact. Why?
```{figure} ../images/ch-08/541577_1_En_8_Fig8_HTML.png
:label: fig-8-8
:alt: Energy levels for a neutral lithium atom and a singly ionized beryllium atom

Energy levels for a neutral lithium atom and a singly ionized beryllium atom

```
````

````{exercise}
:label: prob-8-6
:enumerator: 8.6

In Sect. [](#sec-8-3) when exploring oxygen, we had the sentence, “This designation tells us that both the 1s and 2s subshells are completely filled, and we can essentially ignore them.” Let’s explore this sentence a bit more.

- (a) Write the term symbol for the two electrons that fill the 1s subshell. Explain the reasoning you used to determine the term symbol. The answer (without explanation) is in the footnotes.[^11]
- (b) Write the term symbol for the two electrons that fill the 2s subshell. Explain your reasoning.
- (c) Write the term symbol for the four electrons with the electronic configuration $1\text{s}^2 2\text{s}^2$. This is the same as the ground state of a beryllium atom, which has 4 electrons. Explain your reasoning.
- (d) Write the term symbol for the ground state of neon. Neon has 10 electrons, so the 2p subshell is completely filled. Explain your reasoning.
- (e) Write the term symbol for the ground state of lithium, which has 3 electrons. Explain your reasoning.
- (f) Write the term symbol for the ground state of cesium, which has all subshells filled except for the last electron that is in the 6s subshell. Explain your reasoning.
- (g) Boron has all subshells filled except for the last electron that is in the 2p subshell. For that last electron, there are two possible values for *J*. What are they?
- (h) For part (g), the term symbol with the lower value of *J* corresponds to the lower energy and thus the ground state. Write the term symbol for the ground state of boron.
````

````{exercise}
:label: prob-8-7
:enumerator: 8.7

- (a) Make a sketch of a saturated absorption spectroscopy spectrum where the lower state has $J=0$ and the upper state has $J=1$. The transition frequency is $f_r=652,000,000\,\text{MHz}$ and the natural linewidth is 1 MHz.

  Next, we put the atoms in an external magnetic field. The magnetic field shifts the energy levels according to the formula $\Delta E = \bigl (1\frac {\text{GHz}}{\text{T}}\bigr )h~m_J~B_{\text{ext}}$, where $B_{\text{ext}}$ is the external magnetic field and the unit T stands for Tesla (the unit for magnetic field).

- (b) We place the atoms in a uniform magnetic field with $B_{\text{ext}}=0.1\,\text{T}$. Make a sketch of a saturated absorption spectroscopy spectrum where the lower state has $J=0$ and the upper state has $J=1$. Don’t worry about the relative amplitudes.

- (c) Optional Challenge: Next, we place the atoms in a magnetic field described by the function $B_{\text{ext}}=\bigl (0.001 \frac {\text{T}}{\text{cm}}\bigr ) z$. Make a sketch of the three $J=1$ states as a function of *z*. Use frequency units instead of Joules for the vertical axis (this is equivalent to using a laser to excite the atoms).
````

[^1]: Remember that the ground states of hydrogen, helium, lithium, and europium do not have 0 energy. Each element’s ground state has an energy like the lowest mode of a standing wave has energy. The actual ground state energy of hydrogen is very different than that of helium or lithium. But, we always do spectroscopy with respect to the element’s ground state energy. Figure [](#fig-8-1) is a nice learning tool, but it can be misleading by giving the impression that, for example, the first excited state of lithium has a similar energy to the first excited state of europium. They do not!! The energy difference compared to their ground state is similar. A subtle, but important difference. ☺

[^2]: That was a really complicated way of saying “a star.”

[^3]: The neutrons in the nucleus also matter, but not as much as the proton charge. The effect the neutrons have on the energy states is a topic in Chap. [](#ch-10).

[^4]: 10

[^5]: This is sometimes called fine splitting.

[^6]: This is sometimes called hyperfine splitting.

[^7]: For completeness, Einstein’s theory of special relativity, which deals with the physics of fast-moving objects, also shifts the energy of a state and is included as part of fine structure splitting, but we will not explore that here. If this book has inspired you to pursue further studies in quantum mechanics ☺, you will learn about perturbation theory and the effects of electron velocity.

[^8]: More specifically, the wavefunction for the two-electron system is “antisymmetric” and would be zero everywhere if the electrons had identical quantum numbers.

[^9]: Also known as Bardeen–Cooper–Schrieffer pairs named after American physicists John Bardeen, Leon Cooper, and John Schrieffer.

[^10]: Named after Indian physicist Satyendra Nath Bose and German born physicist Albert Einstein.

[^11]: ${ }^{1}\text{S}_{0}$.
