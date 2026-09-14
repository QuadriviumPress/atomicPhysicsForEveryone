---
title: 7. Angular Momentum
short_title: "Ch. 7 — Angular Momentum"
label: ch-7
doi: 10.1007/978-3-031-69507-0_7
---

## Abstract

In this chapter, we explore angular momentum, a key concept in quantum mechanics and atomic physics. We cover the quantization of angular momentum, the role of quantum numbers, and their impact on atomic states. We will learn about the different types of angular momentum, the states representing these types of angular momentum, and how angular momenta are added together in quantum mechanics. The chapter also examines the compatibility of different observables, such as the magnitude and components of angular momentum, and the impact of measurements on quantum states.

**Keywords:** Quantum numbers, Angular momentum, Orbital angular momentum, Magnitude projection, Spin, Intrinsic angular momentum, Electronic angular momentum, Adding quantum mechanical angular momentum, Fine structure, Fine structure splitting

## Learning Goals

By the end of this chapter, you should be able to understand:

- that angular momentum is a vector that has both magnitude and direction.
- that quantum mechanics restricts angular momentum to certain discrete magnitudes and directions.
- that there are multiple angular momentum vectors in an atom, and understanding how these vectors add together impacts the energy of a particular state.
- that quantum numbers are key tools for understanding angular momentum in quantum mechanics.
- the concept of compatible and incompatible observables in the context of angular momentum measurements.

(sec-7-1)=
## 7.1 Definitions

**Note**

There are ***a lot*** of new definitions in this section. We will talk about and try to understand all of them, but don’t worry too much about memorizing everything right now. We will use some of the definitions continually throughout the rest of the book. In future discussions, you should come back to these definitions as needed. We are all learners, and learning takes repetition.☺

**Momentum**

This is the same definition from Chap. [](#ch-6): a property of an object that is moving. For a classical object like a baseball, the formula for momentum is $p=m v$, where *p* is the object’s momentum, *m* is the object’s mass, and *v* is the object’s velocity. An object’s momentum will change if something acts on the object from the outside. The larger an object’s momentum, the harder it is to stop. The unit of momentum is $\text{kg}\,\text{m}/\text{s}$.

**Force**

Below are two definitions of force. The first is the most common definition. However, it is only true if the object’s mass is not changing, which is a very common scenario. The second is the real definition of force. The unit of force is $\text{kg}\,\text{m}/\text{s}^2$, which we also call a newton (*N*).

**Definition #1**

An external interaction that causes an object to accelerate (i.e., change velocity). Imagine pushing a block up a ramp. You are pushing on the block and causing its velocity to change. That push is an external interaction (force) on the block. Any single force acting on an object will cause the object to accelerate (change velocity). There can be multiple forces acting on an object. Sometimes those forces cancel each other out. If there are multiple forces that perfectly balance one another so the net force is 0, then the object will not accelerate. However, if the net force is not 0, it will accelerate. This is summarized by Newton’s 2nd Law: “The sum of all forces acting on an object causes an object with mass to accelerate.”

**Definition #2**

An external interaction that causes an object’s momentum to change. Newton’s 2nd Law for momentum: “The sum of all forces acting on an object causes an object’s momentum to change.”

**Torque**

A measure of how effective a force is in causing an object to rotate. The two things that matter for torque are the size of the force that causes the rotation and how far from the axis of rotation that force is being applied. Imagine you have a bicycle wheel. If you exert a force horizontally at the edge of the wheel, the wheel starts to spin. Since that force caused a rotation, there is a torque. Applying that same force on the axle or pushing on the tire directly towards the axle does not cause any rotation, so in those two scenarios there is no torque. The unit for torque is $\text{Nm}=\text{kg}\,\text{m}^2/\text{s}^2$. Interestingly, torque and energy share the same unit: $\text{kg}\,\text{m}^2/\text{s}^2$. However, torque is not energy; they are incredibly different!! To avoid confusion, we tend to not write the unit $\text{kg}\,\text{m}^2/\text{s}^2$ for either energy or torque. We use joules (*J*) for energy and newton meters (*Nm*) for torque. Torque will be important in this chapter.

**Angular Momentum**

A property of an object that is rotating. It is the thing that changes when a torque is applied to the object. There is a parallel between the ideas of force and momentum, and torque and angular momentum. Momentum is a property of an object that is moving along a straight line, and it changes when a force is applied to the object. The larger an object’s momentum, the harder it is to stop the object from moving (a bigger force is needed). In the same way, angular momentum is a property of an object that is rotating, and the object will start to rotate faster or slower when a torque is applied (a bigger torque makes the change happen faster). The unit of angular momentum is $\text{kg}\,\text{m}^2/\text{s}$. Angular momentum is ***extremely*** important in quantum mechanics and atomic physics.

**Reduced Planck’s Constant (h-Bar)**

$\hbar =\frac {h}{2\pi }=1.054\times 10^{-34}\,\text{kg}\,\text{m}^2/\text{s}$.

**Important Comment**

Both Planck’s constant and the reduced Planck’s constant have units of angular momentum, $\text{kg}\,\text{m}^2/\text{s}$, which can also be written as joules times seconds, $\text{Js}$. The reduced Planck’s constant will be used a lot in this chapter. You will see why we call it a fundamental constant.

**Quantum Number**

In quantum mechanics, a lot of different properties are quantized, i.e., can only have certain values. We already know that the energy levels of an atom are quantized. Other properties, like angular momentum, are also quantized. When something is quantized, a quantum number is usually associated with that property. A quantum number is an integer or half-integer. Knowing a quantum number will allow someone to calculate some property of an atom. Quantum numbers have no units.

As an example, we will soon talk about the electronic orbital angular momentum quantum number (that is a mouthful!). That quantum number is represented by a script $\ell$. $\ell$ is a quantum number that can be zero or a positive integer: 0, 1, 2, 3, etc. $\ell$ is a discrete number because, according to quantum mechanics, the size or magnitude of the orbital angular momentum of electron is found to have only certain, discrete values. If I tell you that a state in an atom has $\ell =2$, we can calculate the magnitude of the electron’s orbital angular momentum. $\ell =2$ is not the actual size of the orbital angular momentum, but the quantum number can be used to calculate it from the formula $\sqrt {\ell (\ell +1)}\hbar$. Notice that everything in that formula is either the quantum number $\ell$ or the reduced Planck’s constant. In a way, knowing a quantum number is very similar to how spectroscopists use $\text{cm}^{-1}$ as an energy unit. $\text{cm}^{-1}$ is not the correct unit for energy, but we can multiply it by fundamental constants to get the actual energy. The same is true with quantum numbers. Knowing a quantum number is equivalent to knowing a specific property. You might have to do some math, but the only other parameters in the equation should be fundamental constants. So, being told $\ell =2$ is the same thing as being told that the magnitude of the electron’s orbital angular momentum is $\sqrt {6}\hbar =2.582\times 10^{-34}\,\text{Js}$. We will soon find that we need many quantum numbers to describe a particular state in an atom.

(sec-7-2)=
## 7.2 Angular Momentum

Electrons, protons, and neutrons all have angular momentum. A classical analogy is thinking about the moon orbiting the earth.[^1] The moon has orbital angular momentum because it is orbiting the earth. The moon is also spinning on its own axis, so it also has “spin” angular momentum. So, the moon has two types of angular momentum: orbital and spin. Likewise, an electron in an atom can have orbital angular momentum and spin, which is sometimes called intrinsic angular momentum. Interestingly, an electron always has intrinsic angular momentum, but it does not always have orbital angular momentum. One of the craziest things about quantum mechanics is that we don’t have a great analogy to think about the orbital angular momentum or spin of the electron. The electron is not orbiting around the nucleus or spinning on its axis like the moon, but it has the same properties as if it were. The electron, as far as we can tell, has no size! So, how can it be spinning? Imagine how confusing that must have been when physicists were first trying to understand the electron.[^2] It has all the properties one would expect for a ball spinning on its axis, but it is not a ball and it is not spinning! Understanding electron spin is still a wonderful mystery.

Since there are two types of angular momentum, we could ask the question, “What is the total electronic angular momentum of the electron in an atom?” The total electronic angular momentum is not a simple sum of orbital angular momentum and spin. In other words, you cannot just add the two angular momenta together like $2+3=5$. Angular momentum is something called a vector, which is something with magnitude (i.e., size or length) and direction. To get the total electronic angular momentum you have to add the orbital angular momentum and spin together in their vector forms. As a classical analogy, imagine you walk 30 m due north, see Fig. [](#fig-7-1). That is a vector because it has a magnitude (30 m) and a direction (due north). Next, you walk 40 m due west. Once again, that is a vector. If you were to add the two vectors together, you would be asking the question, “If I restarted my journey but took the shortest path, how far and in what direction would I walk?” The answer to this particular scenario is 50 m at $\tan ^{-1}\bigg (\frac {40\,\text{m}}{30\,\text{m}}\bigg )=53.1^{\circ }$ West of North.
```{figure} ../images/ch-07/541577_1_En_7_Fig1_HTML.png
:label: fig-7-1
:alt: An example of adding two vectors together

An example of adding two vectors together

```

**The Super Important Take Home Message**

Adding two vectors together produces a third vector. The size and direction of the third vector depends upon the sizes and directions of the first two vectors.

Let’s get back to talking about angular momentum in a quantum system. An electron in an atom has a total angular momentum. That total angular momentum of the electron comes from the vector addition of its orbital angular momentum and its spin. There are quantum numbers associated with all three of these angular momentum vectors (orbital, spin, and total). The rest of this chapter is going to be focused on understanding angular momentum in a quantum system. We will find that both the size and direction of an angular momentum vector are quantized (i.e., can only have certain values like the size of an orbital angular momentum vector is $\sqrt {\ell (\ell +1)}\hbar$ where $\ell$ is a positive integer or zero). We will start by exploring the orbital angular momentum of a single electron in an atom and then build up the complexity by exploring (and adding) more and more angular momentum vectors to the system.

(sec-7-3)=
## 7.3 Orbital Angular Momentum of a Single Electron

The magnitude of the orbital angular momentum vector for a single electron in an atom is represented by the quantum number $\ell$. The direction (or orientation) is also quantized and is represented by the quantum number $m_{\ell }$. Fig. [](#fig-7-2)a) shows an example of the three possible orientations of an orbital angular momentum vector represented by $\ell =1$. Each of these vectors has the same magnitude (they all have $\ell =1$), but they all point in different directions (they all have a different $m_{\ell }$ quantum number). While $\ell$ tells us the magnitude of the vector, $m_{\ell }$ tells us how much of the vector points along the *z*-axis; this is called the z-component or z-projection. Fig. [](#fig-7-2)a) has three values of $m_{\ell }$: $-$1, 0, and +1. The dashed blue circles are meant to indicate that the angular momentum vector points anywhere on that circle. Because the angular momentum vector can point anywhere on the circle, some people like to think of angular momentum as a cone, see Fig. [](#fig-7-2)b).[^3] These cones are also referred to as angular momentum states, which we will make more sense as we work our way through Chaps. [](#ch-7) and [](#ch-8).
```{figure} ../images/ch-07/541577_1_En_7_Fig2_HTML.png
:label: fig-7-2
:alt: Two popular ways to think about angular momentum states for a quantum mechanical system, like an electron in an atom. (**a**) A vector representation of the three possible vector orientations for an electron with orbital angular momentum quantum number . (**b**) The same information using cones instead of a vector and a dotted circle

Two popular ways to think about angular momentum states for a quantum mechanical system, like an electron in an atom. (**a**) A vector representation of the three possible vector orientations for an electron with orbital angular momentum quantum number $\ell =1$. (**b**) The same information using cones instead of a vector and a dotted circle

```

Orientation of the angular momentum vector, height of the cone, or component/projection along the *z*-axis are all valid ways to think about $m_{\ell }$. After solving the math for quantum mechanics, we find the component of orbital angular momentum along the *z*-axis to be $m_{\ell }\hbar$. For the upside-down cone in Fig. [](#fig-7-2)b), the orbital angular momentum vector is represented by the two quantum numbers $\ell =1$ and $m_{\ell }=-1$, or the size of the orbital angular momentum is $\sqrt {1(1+1)}\hbar =\sqrt {2}\hbar$ and the amount of orbital angular momentum along the *z*-axis (or height of the cone) is $-\hbar$. The flat cone has the same size ($\ell =1$), but it has no component along the *z*-axis ($m_{\ell }=0$). Finally the upright cone has a component along the *z*-axis represented by $m_{\ell }=+1$. Since $m_{\ell }$ is the amount pointing along the *z*-axis, that number is also restricted by the value of $\ell$. For example, if $\ell =1$, $m_{\ell }$ cannot be 2. If it was, the amount pointing along the *z*-axis would be larger than the total magnitude!

Experimentalists can measure these values. If an electron in an atom has orbital angular momentum represented by $\ell =1$, the experimentalist will measure the size to be $\sqrt {2}\hbar$ every single time. However, if they measured the z-component, they could find $+\hbar$, 0, or $-\hbar$. But wait, couldn’t they measure the x-component? What makes the z-component quantized while the x- and y- components just have to be somewhere along the dashed blue circle? On that note, how does an electron even decide which direction is z?

The general answer to all those questions is that we (the physicists) just decided to call one of the directions z. After we randomly pick a direction and call it z, we measure the amount along that axis. When we do that, we will only find those three values: $+\hbar$, 0, or $-\hbar$. We could certainly measure the x-component and get a value. In fact, if we measured the x-component we would get three possible values: $+\hbar$, 0, or $-\hbar$. The pictures in Fig. [](#fig-7-2) would look very similar except the circles/cones would be aligned along the *x*-axis. Let’s call those components $m_{\ell,x}=1$, $m_{\ell,x}=0$, and $m_{\ell,x}=-1$. The three possible values for the z-component form a basis set of size three. The three possible values for the x-component also form a basis set of size three, but those states making up that basis set are different than the state making up the basis set for the z-component. More importantly, those two basis sets are incompatible with each other.

**Reminder of Important Definitions**

- **Incompatible observables:** If two observables cannot be precisely measured at the same time, they are called incompatible. Measuring one observable changes the system, making subsequent measurements of the other observable unpredictable.
- **Compatible observables:** If two observables can be precisely measured at the same time, they are called compatible. Measuring one observable does not change the system in a way that affects the measurement of the other observable. Remeasuring the first observable will return the same value as initially measured.

**Important**

In the following paragraphs, all of the states $(\psi )$ are for angular momentum. I am going to use $\psi _z$ to represent the z-component of the angular momentum state, $\psi _y$ for the y-component, and $\psi _x$ for the x-component.

Suppose our system is in a state $\ell =1, m_{\ell }=1$. This is the upright cone in Fig. [](#fig-7-2)b). Since the x- and z- components are incompatible, we don’t know what we will measure along the x-direction. We know there will be three possible outcomes for the amount of angular momentum along the *x*-axis ($+\hbar$, 0, or $-\hbar$), but we don’t know which value we will find until we measure it. This concept is what is being represented by the blue circles or the cones.

Mathematically, we can also think about this using the principle of superposition. Each set of three cones forms a basis set. One basis set is the three cones representing orbital angular momentum along z and other is the three cones along x. A state from one basis set can be constructed from a superposition of the other basis set. For example,

```{math}
:label: eq-7-1

\psi_{z} (\ell=1,m_{\ell}=1)=c_{x,1} \psi_{x,1}+c_{x,0} \psi_{x,0}+c_{x,-1} \psi_{x,-1},
```

where $\psi _{z} (\ell =1,m_{\ell }=1)$ is the state representing that upright cone (orbital angular momentum along z), $\psi _{x,1}$, $\psi _{x,0}$, $\psi _{x,-1}$ are the three states making up the x-component of the orbital angular momentum basis set, and $c_{x,1}^2$, $c_{x,0}^2$, and $c_{x,-1}^2$ are the probabilities that, upon measurement of the x-component of angular momentum, the system has x-component values $m_{\ell,x}=1$, $m_{\ell,x}=0$, or $m_{\ell,x}=-1$ (remember the actual value of the x-component of orbital angular momentum is $m_{\ell,x}\hbar$). We could repeat the same argument with the y-component. In fact, all three components are incompatible with each other. To summarize this, here are the three basis sets:

```{math}
:label: eq-7-2

\begin{array}{lc} x: & \psi_{x,1}, \psi_{x,0}, \psi_{x,-1} \\ y: & \psi_{y,1}, \psi_{y,0}, \psi_{y,-1} \\ z: & \psi_{z,1}, \psi_{z,0}, \psi_{z,-1} \end{array}
```

Each state represents a cone along a particular axis. We are certainly allowed to measure any component of angular momentum we want. Upon measurement, we will be in one of those states. However, since they are all incompatible observables, measuring one of the components puts the system in a superposition of the states for the other obervables. Interestingly, we have two separate ways to construct the state $\psi _{z} (\ell =1,m_{\ell }=1)$:

```{math}
:label: eq-7-3

\begin{array}{l} \psi_{z} (\ell=1,m_{\ell}=1)=c_{x,1} \psi_{x,1}+c_{x,0} \psi_{x,0}+c_{x,-1} \psi_{x,-1}\\ \psi_{z} (\ell=1,m_{\ell}=1)=c_{y,1} \psi_{y,1}+c_{y,0} \psi_{y,0}+c_{y,-1} \psi_{y,-1} \end{array}
```

In a way, this makes sense. If the quantum mechanical system is in the state $\psi _{z} (\ell =1,m_{\ell }=1)$ and we measure the x-component of angular momentum, we will get $m_{\ell,x}=1$ with probability $c_{x,1}^2$, $m_{\ell,x}=0$ with probability $c_{x,0}^2$, or $m_{\ell,x}=-1$ with probability $c_{x,-1}^2$. On the other hand, we could have decided to measure the y-component at which point we would need to construct the state from the y-basis set to predict what we would measure if we measured the y-component. I should point out that we can calculate those amplitudes using quantum mechanics. For this particular system, $c_{x,1}=1/2$, $c_{x,0}=-1/\sqrt {2}$, and $c_{x,-1}=1/2$.

Ok, so all three components are incompatible with each other, but what about compatibility with the magnitude of the angular momentum vector? Interestingly, the magnitude of the angular momentum vector is a compatible observable with all three components of angular momentum! At first, this might seem a little weird; how can all the components be incompatible with each other yet each component is compatible with the magnitude? But, in a way, this also makes physical sense. The length of the vector is the same whether the cones point along the x-direction, the y-direction, or the z-direction. Measuring a component of angular momentum does not change the length, but it does change the orientation. For this system, measuring the magnitude of angular momentum will always return $\sqrt {2}\hbar$ (or $\ell =1$). It doesn’t matter if we are in a state for the x-component, y-component, or z-component, $\ell =1$.

The rest of the chapter will be spent making the system more complex and complete. To do this, we will need to pick one component of angular momentum to represent the system. Since the x-, y-, and z- components are just rotations of each other, it doesn’t really matter which one we use to represent direction. By tradition, we pick the z-component.

In the end, the above discussion can be summarized as follows: for $\ell =1$, there are three possible projections for an axis and they all look the same ($+\hbar$, 0, and $-\hbar$). So, we need to pick some axis to represent the idea that there are three orientations for the orbital angular momentum vector.

***A lot*** has happened in this section, so let’s summarize:

**Summary**

- Orbital angular momentum is quantized in two ways: the magnitude and the projection on an axis.
- The magnitude is represented by the quantum number $\ell$, which is used to calculate the magnitude using the formula $\sqrt {\ell (\ell +1)}\hbar$.
- The component of the orbital angular momentum along the *z*-axis is represented by the quantum number $m_{\ell }$, which is used to calculate the component along the *z*-axis using the formula $m_{\ell }\hbar$.
- The choice of the *z*-axis is random, but we need an axis to represent the fact that there are only certain directions the vector can point along that axis.
- We can still measure along other directions, but the measurements along those directions are incompatible with measurements along the z-direction. We use cones to remind us that, while we know the z-component of angular moment, the x- and y-components are incompatible with the z-component.

(sec-7-4)=
## 7.4 The Magnitude and Projection of Angular Momentum

The magnitude of an orbital angular momentum vector is given by the formula $\sqrt {\ell (\ell +1}\hbar$. The amount of the vector pointing along the *z*-axis (or the height of the cone) is $m_{\ell }\hbar$. Notice that the formulas contain only quantum numbers and the reduced Planck’s constant. If you hear someone say, “Angular momentum comes in units of $\hbar$”, this is what they mean. Being told that a quantum mechanical system has quantum numbers $\ell =4$ and $m_{\ell }=-2$ tells us all we need to know about the orbital angular momentum of the system: the magnitude is $\sqrt {4(4+1)}\hbar =\sqrt {20}\hbar$ and the z-component is $-2\hbar$ (the cone is pointed in the negative z-direction with a height of $2\hbar$).

There are also mathematical restrictions on the quantum numbers themselves. $\ell$ can be either zero (no orbital angular momentum) or a positive integer (it has orbital angular momentum). The component along the *z*-axis must be smaller than the magnitude of the orbital angular momentum, so $m_{\ell }$ is restricted to be between -$\ell$ and +$\ell$ in integer steps.

**Example #1**

An electron in an atom has orbital angular momentum represented by the quantum number $\ell =3$. There are 7 possible orientations (cone heights) of that vector represented by $m_{\ell }$= $-$3, $-$2, $-$1, 0, 1, 2, 3, see Fig. [](#fig-7-3). If we measure the magnitude of the orbital angular momentum, we will measure $\sqrt {3(3+1)}\hbar =\sqrt {12}\hbar$. If we measure the z-components, we will measure either $-3\hbar$, $-2\hbar$, $-\hbar$, 0, $\hbar$, $2\hbar$, or, $3\hbar$.
```{figure} ../images/ch-07/541577_1_En_7_Fig3_HTML.png
:label: fig-7-3
:alt: A vector representation of the seven possible vector orientations for an electron with orbital angular momentum quantum number

A vector representation of the seven possible vector orientations for an electron with orbital angular momentum quantum number $\ell =3$

```

**Example #2**

An electron in an atom has orbital angular represented by $\ell =2$. There are 5 possible orientations of that vector represented by $m_{\ell }=$ $-$2, $-$1, 0, 1, and 2.

The form of $\sqrt {\ell (\ell +1)}\hbar$ and $m_{\ell }\hbar$ are the same for other types of angular momentum. All we have to do is replace the quantum numbers representing orbital angular momentum with the quantum numbers that represent the type of angular momentum we are interested in. In the next few sections, we are going to expand our discussion to talk about electron spin, the total electronic angular momentum (orbital + spin), the total orbital angular momentum of multiple electrons in an atom, and more. Each of the above examples of angular momentum will have two quantum numbers associated with it, one for magnitude and one for the z-component (cone height). For example, electron spin will have quantum numbers *s* and $m_{s}$. The formulas for electron spin are $\sqrt {s(s+1}\hbar$ and $m_{s}\hbar$. While the quantum numbers for orbital angular momentum are integers, we will find that the other types of angular momentum quantum numbers can be either integers or half-integers. But they all use the same two formulas and tell us the same information, magnitude and z-component (cone height).

(sec-7-5)=
## 7.5 Adding Angular Momentum Vectors Together

Imagine you had 2 electrons in your atom. Each of those electrons has orbital angular momentum. We want to ask the question, “What is the *total* orbital angular momentum of the system?” To answer that question, we need to add together two quantum mechanical vectors. As an example, suppose we have an electron with the magnitude of the orbital angular momentum vector represented by $\ell _A=1$ (Fig. [](#fig-7-2) with 3 possible orientations) and a second electron with $\ell _B=3$ (Fig. [](#fig-7-3) with 7 possible orientations). We want to add these two vectors together as in Fig. [](#fig-7-1), but we have to be thoughtful for two big reasons: (1) the vectors are really more like “vector cones” and (2) there might be incompatible observables we have to think about.

While the math is surprisingly complicated, the result is quite nice:

```{math}
:label: eq-7-4

L = (\ell_{A}+\ell_{B}), (\ell_{A}+\ell_{B}-1), (\ell_{A}+\ell_{B}-2), \dots, |\ell_{A}-\ell_{B}|
```

where *L* is the quantum number for the composite system. For each value of *L*, there are $2L+1$ possible projections represented by the quantum number $m_{L}$. This might be, understandably, confusing. So, let’s unpack this statement using our example of $\ell _A=1$ and $\ell _B=3$.

If we add together two quantum mechanical vectors whose magnitudes are represented by quantum numbers $\ell _A$ and $\ell _B$, the total angular momentum of the system will be represented by new quantum numbers *L* and $m_{L}$. The math shows there are multiple possible magnitudes one can get when adding two angular momentum vectors together. However, the new cones for *L* and $m_{L}$ follow the same rules that we have been working with: *L* tells us the magnitude of the angular momentum for the system and $m_{L}$ tells us the component (or height of the cone). From the math, the largest possible magnitude of *L* is given by $\ell _{A}+\ell _{B}$, which is $L=4$ in the thought experiment we are working through. The smallest possible magnitude is $L=|\ell _{A}-\ell _{B}|$, or $L=2$ for the example we are working on. To find all possible values of *L*, we make a list that starts with the smallest value and continually add 1 until we reach the largest value. In this case *L* can equal 2, 3, or 4.

To put it another way, there are three different orientations for $\ell _{A}$ and seven different orientations for $\ell _{B}$. Depending on the orientations, adding those two angular momentum vectors results in different possible magnitudes. Working through all possible combinations results in three possible magnitudes. For each possible magnitude, there are different orientations (cone heights). In this example, the individual orbital angular momentum vectors can add together to make $L=2$ (5 possible cones with the same length vector $\sqrt {2(2+1)}\hbar =\sqrt {6}\hbar$), $L=3$ (7 possible cones with the same length vector $\sqrt {3(3+1)}\hbar =\sqrt {12}\hbar$), and $L=4$ (9 possible cones with the same length vector $\sqrt {4(4+1)}\hbar =\sqrt {20}\hbar$).

After all the math, there are $5+7+9=21$ possible cones. This makes sense since the original vectors had 3 and 7 possible orientations, and $3\times 7=21$. However, I want to caution you in that the new cones are not constructed simply by taking one cone chosen from $\ell _A=1$ and one cone from $\ell _B=3$ and adding them together. This is because the z-components of the individual electrons are incompatible with the z-component of the composite system. So, the new cones, which we will call the basis set for the composite system, are a superposition of all the cones from the individual electrons, which we call the individual electron basis set. The complicated math, which we skip in this book, tells us the amplitude or amount that we need from each of the individual electron basis set to construct the new composite system basis set. We will explore this more in Sect. [](#sec-7-5-1).

Another example: Suppose $\ell _{A}=3$ and $\ell _{B}=5$. The largest value for *L* is $3+5=8$, and the smallest value is $|3-5|=2$. Therefore, *L* can have values of 2, 3, 4, 5, 6, 7, or 8. For each value of *L*, there will be different orientations represented by the quantum number $m_{L}$. If $L=3$, there are 7 possible vector cones represented by $m_{L}=3$, 2, 1, 0, $-$1, $-$2, and $-$3.

Quick problem (the answers are in the footnotes[^4]):

Suppose $\ell _{A}=1$ and $\ell _{B}=2$.

- (a) How many projections are there for $\ell _{A}=1$?
- (b) How many projections are there for $\ell _{B}=2$?
- (c) How many possible cones can we add together from part (a) and part (b)? In other words, what is the size of the individual electron basis set?
- (d) What values of *L* are possible?
- (e) For each value of *L*, how many projections are there?
- (f) Add up all the possible projections from part (e).

The answer to (c) should match the answer in (f).

(sec-7-5-1)=
### 7.5.1 Compatible or Incompatible?

For just these two electrons, we have a bunch of quantum numbers floating around. Each quantum number corresponds to something we can measure. For these two electrons, we have six quantum numbers: $\ell _A$, $m_{\ell,A}$, $\ell _B$, $m_{\ell,B}$, *L*, and $m_L$. Which of these represent compatible observables? Is there something we can measure that will disrupt the value of another observable? As learners of quantum mechanics, this is important to keep track of.

All of the magnitudes are compatible with everything. If we know $\ell _A=1$, $\ell _B=3$, and $L=2$, we can measure any of the observables represented by the six quantum numbers without disrupting future outcomes of magnitude measurements. However, the composite z-component $m_L$ is incompatible with the z-components of the individual electrons, $m_{\ell,A}$ and $m_{\ell,B}$. Therefore, we can know either the z-component of the system or the z-components of the individual electrons, but not all three at the same time. The z-components of the two individual electrons are compatible with each other. So, if we know the z-component of the system and want to know what we might measure if we were to measure the z-component of the individual electrons, we have to write the state of the composite system as a superposition of states from the individual electron basis states. The concept remains the same; we would just have to do the math to find the amplitudes.

**Generalization and Summary**

The above discussion is true when adding *any* two quantum mechanical angular momentum vectors together. Suppose we have two angular momentum vectors $\mathbf {A}$ and $\mathbf {B}$. Their magnitudes are represented by quantum numbers *A* and *B*, while their z-components are represented by $m_A$ and $m_B$. We want to add $\mathbf {A}$ and $\mathbf {B}$ together to get $\mathbf {C}$. The possible values for the quantum number representing the magnitude of $\mathbf {C}$ are:

```{math}
:label: eq-7-5

C = (A+B), (A+B-1), \dots , |A-B|
```

For each value of *C*, $m_C = -C,\dots, C$ in integer steps. The compatibility of the observables is as follows:

- The magnitudes are always compatible with everything.
- The z-components of the individual angular momenta are compatible with each other.
- The z-component of the summed angular momentum is incompatible with the z-components of the individual angular momenta.

(sec-7-6)=
## 7.6 Other Types of Angular Momentum

An electron, whether it is in an atom or free, always has spin. The quantum numbers for spin are *s* and $m_s$ for the magnitude and orientation (cone height), respectively. For an electron, $s=1/2$ always, so the possible orientations are always $m_s=-1/2$ or $m_s=+1/2$. From tradition, we call $m_s=+1/2$ “spin up” and $m_s=-1/2$ “spin down”.

If the electron is in an atom, it can also have orbital angular momentum. We can add orbital angular momentum and spin together and ask the question, “What is the total angular momentum of that electron?” This new total angular momentum of the electron is represented by the quantum numbers *j* and $m_j$. Using our new rule (Eq. [](#eq-7-5)), the possible magnitudes of the total are represented by $j=\ell+s,\ldots,|\ell-s|$ in integer steps. Thus, if $\ell =1$ and $s=1/2$, *j* can be $3/2$ or $1/2$. As before, $m_{\ell }$ can be any value between $-\ell$ and $+\ell$ in integer steps, $m_s$ can be any value between $-s$ and $+s$ in integer steps, and $m_j$ can be any value between $-j$ and $+j$ in integer steps. Knowing the quantum numbers *j*, $\ell$, and *s* tells us the magnitude of the angular momentum vectors. Knowing $m_j$, $m_\ell$, and $m_s$ tells us the orientation of each of their respective angular momentum vectors. However, $m_j$ is incompatible with $m_s$ and $m_\ell$.

Here is a table summarizing all of the current types of angular momenta for a single electron in an atom (QN means quantum number):

| Type | QN | Rule | Formula |
| --- | --- | --- | --- |
| Orbital | $\ell$ | Zero or positive integer | Magnitude: $\sqrt {\ell (\ell +1)}\hbar$ |
|  | $m_{\ell }$ | $-\ell$ to $+\ell$ in integer steps | Cone height: $m_{\ell }\hbar$ |
| Spin | *s* | For a single electron, $s=1/2$ | Magnitude: $\sqrt {s(s+1)}\hbar =\sqrt {3/4}\hbar$ |
|  | $m_{s}$ | $-1/2$ and $+1/2$ | Cone height: $m_{s}\hbar$ |
| Total electronic | *j* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {j(j+1)}\hbar$ |
|  | $m_{j}$ | $-j$ to $+j$ in integer steps | Cone height: $m_{j}\hbar$ |

```{prf:example}
:label: example-7-1

An electron in an atom has quantum numbers $\ell =3$ and $s=1/2$.

- (a) What is the magnitude of the electronic orbital angular momentum? Solution: The magnitude is $\sqrt {\ell (\ell +1)}\hbar =\sqrt {12} \hbar \approx 3.46\hbar$
- (b) What is the magnitude of the electron’s spin? Solution: The magnitude is $\sqrt {s(s+1)}\hbar =\sqrt {\frac {3}{4}}\hbar \approx 0.87\hbar$
- (c) What are the possible magnitudes of the total electronic angular momentum? Solution: The possible values for *j* are $j = (\ell +s), \dots, |\ell -s|$ in integer steps. The largest value is $3+\frac {1}{2}=\frac {7}{2}$ and the smallest value is $|3-\frac {1}{2}|=\frac {5}{2}$. So, $j = \frac {7}{2}$ or $j = \frac {5}{2}$. When $j=7/2$, the magnitude is $\sqrt {j(j+1)}\hbar =\sqrt {\frac {7}{2}\frac {9}{2}}\hbar =\sqrt {\frac {63}{4}}\hbar \approx 3.97\hbar$. When $j=5/2$, the magnitude is $\sqrt {j(j+1)}\hbar =\sqrt {\frac {5}{2}\frac {7}{2}}\hbar =\sqrt {\frac {35}{4}}\hbar \approx 2.96\hbar$.
```

We now have all the building blocks we need to add together as many angular momentum vectors as we need. We first add two together to come up with the new possible quantum numbers and projections for this composite system. Next, we treat the composite system as its own individual angular momentum and add a third angular momentum. Then keep going until you have accounted for all electrons in your atom. The magnitudes of each angular momenta will be compatible with everything. The z-component of any summed angular momentum will be incompatible with the two individual angular momenta.

In practice, we don’t go through all this effort. As we will see in Chap. [](#ch-8), there are shortcuts we can take and databases that tell us all we need to know. For atoms with more than 1 electron, we do not keep track of subscripts (i.e., electron 1, electron 2, etc.), we simply ask the question “how much orbital, spin, and total electronic angular momentum do all of the electrons have?” The formulas and ideas are identical, but we use capital letters when we ask how much angular momentum the electrons as a whole have:

| Type | QN | Rule | Formula |
| --- | --- | --- | --- |
| Orbital | *L* | Zero or positive integer | Magnitude: $\sqrt {L(L+1)}\hbar$ |
|  | $m_{L}$ | $-L$ to $+L$ in integer steps | Cone height: $m_{L}\hbar$ |
| Spin | *S* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {S(S+1)}\hbar$ |
|  | $m_{S}$ | $-S$ to $+S$ in integer steps | Cone height: $m_{S}\hbar$ |
| Total electronic | *J* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {J(J+1)}\hbar$ |
|  | $m_{J}$ | $-J$ to $+J$ in integer steps | Cone height: $m_{J}\hbar$ |

All of the magnitudes are compatible with everything. However, $m_J$ is incompatible with $m_L$ and $m_S$.

**Something Super Annoying, But Unfortunately Super Important**

Historically, we assign letters to orbital angular momentum quantum numbers. A system with no orbital angular momentum has the quantum number $L=0$ (or $\ell =0$ for a single electron) is given the letter designation S (or s for a single electron). But, *S* and *s* are also the quantum numbers for spin. They are both angular momenta, but very different types. Technically the quantum numbers are italicized and the letter designations are not, but that is not a rule everyone follows. Below is a table with quantum numbers, the letter designation, and double uses with other types of angular momentum:

| Orbital quantum number | Letter designation | Other uses |
| --- | --- | --- |
| $L=0~(\ell =0)$ | S (s) | *S* and *s* are also used for spin |
| $L=1~(\ell =1)$ | P (p) |  |
| $L=2~(\ell =2)$ | D (d) |  |
| $L=3~(\ell =3)$ | F (f) | *F* is also used for nuclear angular momentum |
| $L=4~(\ell =4)$ | G (g) |  |

I admit it is extremely annoying to have orbital angular momentum represented by letters that also mean different types of angular momentum, but it is unfortunately the way of spectroscopy. It takes some getting used to.

**The Nucleus**

The nucleus can also have angular momentum. Traditionally, this is called nuclear spin, but that is a bit of a misnomer. The angular momentum of the nucleus comes from the spin of the protons and neutrons as well as any orbital angular momentum of those nucleons. So, nuclear spin should really be called total nuclear angular momentum but no one uses that phrase. Nuclear spin has the quantum numbers *I* and $m_I$. Nuclear spin $(I)$ can be added to the total electronic angular momentum $(J)$ find the total angular momentum of the atom. The total angular momentum is represented by the quantum numbers *F* and $m_F$, where *F* is found from *J* and *I* using Eq. [](#eq-7-5):

```{math}
:label: eq-7-6

F = (J+I), (J+I-1), \dots, |J-I|
```

As always, $m_F$ is incompatible with $m_J$ and $m_I$.

So, if an atom has nuclear spin, our table gets a bit longer:

| Type | QN | Rule | Formula |
| --- | --- | --- | --- |
| Orbital | *L* | Zero or positive integer | Magnitude: $\sqrt {L(L+1)}\hbar$ |
|  | $m_{L}$ | $-L$ to $+L$ in integer steps | Cone height: $m_{L}\hbar$ |
| Spin | *S* | Zero, positive integer or half-integer | Magnitude: $\sqrt {S(S+1)}\hbar$ |
|  | $m_{S}$ | $-S$ to $+S$ in integer steps | Cone height: $m_{S}\hbar$ |
| Total electronic | *J* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {J(J+1)}\hbar$ |
|  | $m_{J}$ | $-J$ to $+J$ in integer steps | Cone height: $m_{J}\hbar$ |
| Nuclear spin | *I* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {I(I+1)}\hbar$ |
|  | $m_{I}$ | $-I$ to $+I$ in integer steps | Cone height: $m_{I}\hbar$ |
| Total Atomic | *F* | Zero, positive integer, or half-integer | Magnitude: $\sqrt {F(F+1)}\hbar$ |
|  | $m_{F}$ | $-F$ to $+F$ in integer steps | Cone height: $m_{F}\hbar$ |

We will explore nuclear spin more in Chap. [](#ch-9).

**The Photon**

The photon has intrinsic angular momentum as well. Photon spin is the quantum mechanical description of light polarization, and it has a quantum number of 1. In Chap. [](#ch-1), we talked about how light can be linearly polarized, circularly polarized, or elliptically polarized. That statement is for a laser beam, which is composed of many photons. A single photon is circularly polarized. To help visualize this, imagine a photon traveling straight towards you. The photon would be rotating either clockwise or counterclockwise. To be clear, a photon is not actually rotating just like the electron is not actually spinning like a top. However, both the electron and the photon behave and interact with other particles as if they are spinning or rotating. If it is spinning counterclockwise, the height of the cone is $+\hbar$ (the z-component to photon spin with a quantum number of +1). If the photon is spinning clockwise, the height of the cone is $-\hbar$.[^5]

Circularly polarized light just means that all the photons are rotating in the same direction. A laser beam composed of photons coming towards you that are all rotating clockwise is said to have left (or left-handed) circularly polarized light. A laser beam composed of photons that are all rotating counterclockwise is said to have right (or right-handed) circularly polarized light. To get linearly polarized light, you need to have equal amounts of photons spinning clockwise and counterclockwise. Elliptically polarized light has an imbalance between the number of clockwise and counterclockwise photons.

(sec-7-7)=
## 7.7 A Bit More on Compatible and Incompatible Observables

Every quantum number in every table in Sect. [](#sec-7-6) is something we can measure. Consider the hydrogen atom, which has a single electron. For now, we will ignore the fact that the nucleus of a hydrogen atom has angular momentum (this is the topic of Chap. [](#ch-9) so we will revisit compatible and incompatible observables again in that chapter). Here is a list of things we can measure: $\ell$, $m_\ell$, *s*, $m_s$, *j*, and $m_j$.

Technically, we could also measure *L*, $m_L$, *S*, $m_S$, *J*, and $m_J$, but, since the hydrogen atom has only a single electron, measuring, for example, the total orbital angular momentum of all the electrons is the same as measuring the orbital angular momentum of the single electron in the system.

We want to ask the question, which of these observables is compatible with energy? In other words, if the hydrogen atom was in an energy state, what other properties could we measure and still leave the electron in that same energy state? The answer is:

- Compatible with energy: $\ell$, *s*, *j*, and $m_j$
- Incompatible with energy: $m_\ell$ and $m_s$

That means if the system was in an energy state and we measured the z-component of the electron’s orbital angular momentum, the system is now in a superposition of energy states. But what makes $m_\ell$ and $m_s$ incompatible with $m_j$ and energy? While it isn’t obvious why $m_\ell$ and $m_s$ are incompatible with the energy state, we can visualize why they are incompatible with $m_j$. Fig. [](#fig-7-4) visualizes the incompatibility. This figure shows the addition of two angular momentum cones. Since $m_j$ is compatible with the energy state, we will define the *z*-axis to be along the cone for *j*. I want to point out a few things. First, notice that the cones for both $\ell$ and *s* are tilted with respect to the *z*-axis. This means that the height of those two cones (i.e., the result of a measurement of $m_\ell$ or $m_s$) are no longer perfect projections onto the *z*-axis. In other words, if we measured the z-component of spin with respect to this *z*-axis, we will be in a superposition of the $m_j$ basis set. Compare this to the measurement of the z-component of *j*. The cone for *j* has a rim that is constant along the *z*-axis, so we will always measure the same value of $m_j$. Since $m_j$ is compatible with the energy state, measuring $m_\ell$ or $m_s$ would also put the system into a superposition of energy states.
```{figure} ../images/ch-07/541577_1_En_7_Fig4_HTML.png
:label: fig-7-4
:alt: An example of adding together a spin cone and a orbital angular momentum cone to get the total electronic angular momentum cone. Notice that the z-component of both the spin and orbital angular momentum cones is not the same value at all points of the cone tops. This means the z-component does not have a specific, discrete value, which means that both the z-component of spin and the z-component of orbital angular momentum are incompatible with the z-component of *j*

An example of adding together a spin cone and a orbital angular momentum cone to get the total electronic angular momentum cone. Notice that the z-component of both the spin and orbital angular momentum cones is not the same value at all points of the cone tops. This means the z-component does not have a specific, discrete value, which means that both the z-component of spin and the z-component of orbital angular momentum are incompatible with the z-component of *j*

```

The second thing I would like to point out is that the length of the both *s* and $\ell$ are constants. If we were to measure the slant height of either cone, we will always get the same answer. In other words, both *s* and $\ell$ are compatible with *j* and energy.

To clarify which observables are compatible with the energy states, I’ll reintroduce the quantum number for energy, *n*, from Chap. [](#ch-6). We use the quantum numbers representing those observables that are compatible with energy in a ket: $|{n~\ell ~s~j~m_j}\rangle$. We will discuss these quantum numbers and their relationships to electron shells in more detail in Chap. [](#ch-8). If the electron in the hydrogen atom is in an energy state represented by one of these kets, we can measure any of those observables and still be in that same energy state. If we measured $m_\ell$ or $m_s$, the system would be in a superposition of energy states.

Let’s solidify this idea with a couple of examples. We will do Example #1 together, and then you should do Example #2.

**Example #1**

How many states will there be for the electron in a hydrogen atom that has $n=2$, $\ell =1$, and $s=1/2$?

To start this problem, let’s first calculate what values of *j* are possible. *j* can range from $\ell +s$ to $|\ell -s|$ in integer steps, so *j* can be $1/2$ or $3/2$. If $j=1/2$, then $m_j$ can be $1/2$ or $-1/2$. If $j=3/2$, then $m_j$ can be 3/2, 1/2, -1/2, or -3/2. Therefore, there are 6 energy states with $n=2$, $\ell =1$, and $s=1/2$. Using the notation $|{n~\ell ~s~j~m_j}\rangle$, these states are: $|{2~1~\frac {1}{2}~\frac {1}{2}~\frac {1}{2}}\rangle$, $|{2~1~\frac {1}{2}~\frac {1}{2}\,\text{-}\frac {1}{2}}\rangle$, $|{2~1~\frac {1}{2}~\frac {3}{2}~\frac {3}{2}}\rangle$, $|{2~1~\frac {1}{2}~\frac {3}{2}~\frac {1}{2}}\rangle$, $|{2~1~\frac {1}{2}~\frac {3}{2}\,\text{-}\frac {1}{2}}\rangle$, and $|{2~1~\frac {1}{2}~\frac {3}{2}\,\text{-}\frac {3}{2}}\rangle$.

The above math tells us that there is an energy state in the hydrogen atom that is represented by, for example, the quantum numbers $|{2~1~\frac {1}{2}~\frac {3}{2}\,\text{-}\frac {3}{2}}\rangle$. If the hydrogen atom is in this state, it has a defined magnitude of orbital angular momentum (in this case $\sqrt {\ell (\ell +1}\hbar =\sqrt {1(1+1)}\hbar \approx 1.41\hbar$), a defined magnitude for spin, a defined magnitude for the total electronic angular momentum, and a defined z-component for the total electronic angular momentum. That state does not have a well defined z-component of orbital angular momentum nor a well defined z-component of spin. We can measure any observable compatible with energy and the system will stay in the $|{2~1~\frac {1}{2}~\frac {3}{2}\,\text{-}\frac {3}{2}}\rangle$ state. However, if we measure $m_\ell$ or $m_s$, the system will be in a superposition of energy states.

**Example #2**

The electron in the hydrogen is in the state $|{2~1~\frac {1}{2}~\frac {3}{2}\,\text{-}\frac {1}{2}}\rangle$.

- (a) What ***will*** we measure for the electron’s orbital angular momentum, the electron’s spin, the electron’s total angular momentum, and the electron’s z-component of the electron’s total angular momentum?
- (b) If we measured the z-component of the electron’s orbital angular momentum, what might we get?

The solutions are below the crossword.
```{figure} ../images/ch-07/541577_1_En_7_Figa_HTML.png
:label: fig-7-a
:alt: Crossword puzzle for the angular momentum exercise solutions

```

:::{admonition} Solution
:class: dropdown

- (a)
  - $\ell =1:$ We will measure $\sqrt {1(1+1)}\hbar \approx 1.41\hbar$ with 100% probability
  - $s=1/2:$ We will measure $\sqrt {\frac {1}{2}(\frac {1}{2}+1)}\hbar \approx 0.87\hbar$ with 100% probability
  - $j=3/2:$ We will measure $\sqrt {\frac {3}{2}(\frac {3}{2}+1)}\hbar \approx 1.94\hbar$ with 100% probability
  - $m_j=-1/2:$ We will measure $\text{-}\frac {1}{2}\hbar$ with 100% probability
- (b) We would measure either $-\hbar$, 0, or $\hbar$ with different probabilities. We would need advanced math to calculate those probabilities, so I will just emphasize that we will not measure a definite value for the z-component of the electron’s orbital angular momentum. After the measurement, the system will no longer be in the state $|{2~1~\frac {1}{2}~\frac {3}{2}\,\text{-}\frac {1}{2}}\rangle$, but a superposition of energy states. If we now went back and measured *j*, we might get $j=1/2$ or $j=3/2$ with hard to calculate probabilities.
:::

## 7.8 Problems

```{exercise}
:label: prob-7-1
:enumerator: 7.1

Angular momentum seems to be a pretty important concept in quantum mechanics and atomic physics! In your own words, describe a classical (i.e., not quantum) system that has angular momentum and a classical system that does not. Speculate on a few ways the classical system with angular momentum might behave differently if it were a quantum system.
```

```{exercise}
:label: prob-7-2
:enumerator: 7.2

An electron in an atom has the quantum numbers $\ell =0$ and $s=1/2$.

- (a) What are the magnitudes and projection along the *z*-axis for $\ell$?
- (b) What are the magnitudes and projection along the *z*-axis for *s*?
- (c) What are the possible magnitudes and projections along the *z*-axis for *j*?
```

```{exercise}
:label: prob-7-3
:enumerator: 7.3

An atom has two electrons. One electron has $\ell =1$ and the other has $\ell =0$.

- (a) Find all possible values of *L*.
- (b) Find all possible values of *S*.
- (c) Find all possible values of *J*.

Hint: There will be a different set of *J* values for each combination of *L* and *S*. For example, if your answer to part (a) was $L=2$ or $L=1$ (I hope you didn’t get these numbers, because they aren’t correct) and your answer to part (b) was $S=0$ or $S=1$, then there would be 4 sets of answers to part (c). Word your answer similar to:

“For $L=2$ and $S=0$, *J* can be …”

“For $L=2$ and $S=1$, *J* can be …”

“For $L=1$ and $S=0$, *J* can be …”

“For $L=1$ and $S=1$, *J* can be …”
```

```{exercise}
:label: prob-7-4
:enumerator: 7.4

An atom has two electrons. One electron has $\ell =1$ and the other has $\ell =2$.

- (a) Find all possible values of *L*.
- (b) Find all possible values of *S*.
- (c) Find all possible values of *J*.
```

```{exercise}
:label: prob-7-5
:enumerator: 7.5

The atom in Problem [](#prob-7-3) has a nuclear spin of $I=3$. Find all possible values of *F*.

Hint: There will be a different set of *F* values for each *J* value.
```

[^1]: Remember that in quantum mechanics, an electron is not like the moon orbiting the earth but more like a wave that is surrounding the nucleus. We are just using the moon and earth as an analogy to introduce angular momentum.
[^2]: There are, at least, two things in physics that really boggle my mind. The first is spin. The second is something called the fine structure constant, which you should Google if you want your mind blown!
[^3]: I, personally, like using cones. But, as long as you understand the concepts, it doesn’t matter which version you use.
[^4]: (a) 3; (b) 5; (c) $3\times 5=15$; (d) 1, 2, or 3; (e) 3, 5, or 7; (f) 15.
[^5]: Because the photon has no mass, the math, interestingly, forbids a z-component of 0.