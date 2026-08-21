---
title: 1. Introduction to Atoms and Light
short_title: "Ch. 1 — Atoms and Light"
label: ch-1
doi: 10.1007/978-3-031-69507-0_1
---

## Abstract

In this chapter, we explore the nature of light and atoms, focusing on their dual nature as both particles and waves. We examine why atoms have discrete energy levels and how only certain frequencies of light can excite electrons within these atoms. Through this exploration, we will understand the relationship between light’s frequency, wavelength, and photon energy. We also explore key concepts such as wave interference and the historical experiments that shaped our understanding of quantum mechanics. Most importantly, this chapter emphasizes the scientific method, encouraging continual questioning of ideas, understanding, theories, and results to uncover the fundamental nature of the universe.

**Learning Goals**

By the end of this chapter, you should be able to understand:

- the basic structure of an atom.
- the concept of wave-particle duality and how it applies to both light and electrons.
- that atoms have discrete energy levels, and we can think about electrons as waves to understand why these energy levels are discrete.
- the historical experiments that led to the development of quantum mechanics, particularly the double-slit experiment.
- the basic principles of spectroscopy and its importance in studying atomic structure.
- that knowing the frequency of a laser, the wavelength of a laser, or the energy of a photon allows you to determine the other two. All three quantities are related by fundamental constants.

(sec-1-1)=
## 1.1 What Is Atomic Physics?

Before we discuss **atomic physics**,[^1] we should first ask a more fundamental question: What is **physics**? Before you read further, pause and think for a few minutes. If someone was to ask you, “What is physics?”, how would you respond? My answer is below the word search:

```{figure} ../images/ch-01/541577_1_En_1_Figa_HTML.png
```

My answer: Physics is a branch of science that tries to understand the universe. We do this through exploring physical concepts and often explain those concepts using the language of mathematics.

All subfields of physics focus on a particular portion of the universe. For example, plasma physicists try to understand ionized gases, which are called plasmas. Atomic physicists[^2] try to understand the world of atoms, which I like to refer to as the world of the super small.

Below are a few reminders that are important starting points for this book. If you aren’t familiar with one of them, take 5 minutes to read the Wikipedia page on the topics.

- Atoms are composed of three types of particles: **protons**, **neutrons**, and **electrons**.
  - Protons and neutrons form the center of the atom, called the nucleus, and electrons orbit around the nucleus.
  - If an atom has an equal number of electrons and protons, the atom has no net charge. We call this a **neutral atom**. If we take an electron away from the atom or give the atom an extra electron, it is now charged. We call this an ion.
- **Molecules** are made from multiple atoms bound together. They can be the same atoms, like a nitrogen molecule consists of two nitrogen atoms, or different atoms, like a water molecule that has two hydrogen atoms and one oxygen atom.
- Atoms can be in the gas phase, liquid phase, or a solid phase.[^3],[^4] Most atomic physicists study atoms in the gas phase to avoid the complexity of liquids and solids. In liquids and solids, atoms are bonded to one another, which makes the system more complicated. Our ideal system is a single atom all by itself away from all outside interactions.
- The periodic table of elements is a common way to view all the elements we know about. A copy of the periodic table can be found in Appendix A.
- Spectroscopists use light to interact with and learn about the world of the super small.

This book is aims to teach **quantum mechanics**, atomic physics, and **spectroscopy** without any advanced math. The most complicated math we use is algebra and some trigonometry (sines and cosines). Spectroscopy is a subfield of atomic physics that tries to learn about an atom through its interaction with light. Spectroscopy can be thought of as both a subfield and a tool. As a subfield, it is using atom-light interactions to try and understand the world of the super small. Additionally, it serves as a tool. The goal of atomic physics is to understand how atoms work, and spectroscopy is just a tool to accomplish this goal. The important thing is that spectroscopists use light to interact with atoms with the end goal of understanding the world of the super small. Scientists in lots of fields use spectroscopy, including atomic physicists, nuclear physicists, chemists, geologists, atmospheric scientists, and astronomers.

Atomic physicists try to reach this goal by starting with a simple system and building up complexity over time. One of our simplest systems is a single electron orbiting a single proton, also known as a hydrogen atom. More complicated systems include helium (2 electrons and 2 protons), lithium (3 electrons and 3 protons), neodymium (60 electrons and 60 protons), europium (63 electrons and 63 protons), and californium (98 electrons and 98 protons). Other fields of physics start with complicated systems and either “build up” or “build down” in complexity. For example, condensed matter physics, which includes subfields like superconductivity, has incredibly complex systems!

[](#fig-1-1) is a flowchart for how I like to explain how we, as scientists, try to understand something. For atomic physicists, our goal is to try to understand the world of the super small. We start with a simple system, for example the hydrogen atom. Next, we use theory that is based on previous knowledge to make a prediction. If the theory is good, the prediction should be confirmed by experiment. Once experimentalists make their first measurement, they start to improve the experimental setup to measure things better and better. While the experimentalists are improving their setup, the theorists are also improving their models. This process continues over and over and over until we, as a community, conclude that (1) the model is doing a really good job predicting the simple system, and (2) we run out of ways to make the experiment or theory more precise. If, after all that time stuck in that loop, we find that experiment and theory agree, we give out high fives and conclude we understand this simple system. If theory and experiment start to deviate from each other, physicists start to get excited because there is something we don’t understand.

```{figure} ../images/ch-01/541577_1_En_1_Fig1_HTML.jpg
:name: fig-1-1

A flowchart for trying to understand something. This is a version of the scientific method showing the interplay between experiment and theory
```

Once the atomic physics community is happy with the simple system, we make the system slightly more complex. For example, after we conclude that we understand hydrogen (1 electron, 1 proton, 0 neutrons), we move on to trying to understand deuterium (1 electron, 1 proton, 1 neutron) or helium (2 electrons, 2 protons, 2 neutrons). The most important thing to emphasize here is that if the model/theory is good, it should predict the experimental results before the experimentalists go and measure. If the theorists and experimentalists disagree, either the theorists messed up the math, the experimentalists messed up their experiment, or the theory is simply incomplete or all together wrong. The most exciting time in physics is when this last one happens.

The theoretical framework in atomic physics is quantum mechanics. Quantum mechanics has a more modern and complete version called the **Standard Model of Particle Physics**, the topic of [](#ch-11). The Standard Model came about because, while quantum mechanics did a great job describing the world of the super small, it didn’t do a perfect job. In other words, quantum mechanics isn’t complete (it doesn’t describe everything). As we worked through the flowchart, theory and experiment started to disagree as both theorists and experimentalists improved their methods. The Standard Model, which is far more mathematically complicated than Quantum Mechanics, does a much better job, but it is also not complete. For example, the Standard Model doesn’t know how to describe lots of things we observe in real life like gravity, dark matter, dark energy, and baryon asymmetry, all of which will be discussed in [](#ch-11). Despite these problems, experimental measurements that test the validity of the Standard Model always seem to confirm the Model is accurately describing nature![^5] Therefore, we test it over and over again hoping that (1) we find a disagreement between experiment and theory and (2) this discrepancy leads to a more complete model describing the world of the super small.

In this book, we are going to think about atoms in their gaseous form, so we don’t have to worry about how two or more atoms interact in a molecule, a liquid, or a solid. If you are reading this book as part of a class, you may also have an experimental portion where you are focusing on a single atom like sodium, cesium, europium, or neodymium. One of the most important things to note right now is that we want to know general properties of the atom of choice. For example, if we want to know the energy separation between two atomic states (more on this below) of a single, isolated atom, we want to know that energy separation in the absence of external interactions. We don’t care about these properties in a magnetic field, an electric field, or even a laser field. Imagine a single atom in the middle of outer space, completely in the dark, and far from any other object. We want an experiment that helps us figure out these general properties. If a scientist knows the general properties, they can then calculate or estimate what would happen to that property if the atom was, for example, put in a magnetic field. The important thing is that we provide the general information that can later be used by theorists, other experimentalists, and engineers.

(sec-1-2)=
## 1.2 Conceptually Understanding the Atom

We are not going to discuss the Standard Model right now. We are going to keep things a bit simpler and discuss, conceptually, the atom. Later on in the book, we will add to our conceptual model to make things more complete. So, what does quantum mechanics say about the atom?

To answer that question, let’s first think about an electron that is orbiting around a nucleus, as shown in [](#fig-1-2). The electron has negative charge and the nucleus has positive charge. According to electromagnetic theory, the electron should radiate away energy. Imagine if you were flying a hand glider and you slowly lost energy. In this scenario you would slowly drift down until you landed on the ground. According to electromagnetic theory, the electron will also lose energy and should orbit closer and closer to the nucleus until it collides with the nucleus. Experiment shows this is not true. In fact, if it were true, we wouldn’t be here reading this book because atoms wouldn’t exist and thus the universe wouldn’t exist,[^6] which disagrees with experimental observation.

```{figure} ../images/ch-01/541577_1_En_1_Fig2_HTML.png
:name: fig-1-2

A helpful conceptual, but incorrect, way of thinking about atoms. The model where the electrons orbiting around the nucleus is called the Bohr model, named after Danish physicist Niels Bohr
```

There were some amazing experiments conducted in the late 1800s and early 1900s that seemed to imply that the electron is *not* like the moon orbiting around the earth. One of my favorite experiments that showed this behavior is called the double-slit experiment. If we assume electrons are like little sticky balls and send them through two small slits in a barrier, as shown in [](#fig-1-3), we expect to have two strips of balls stuck to the screen. However, that isn’t what is seen experimentally!

```{figure} ../images/ch-01/541577_1_En_1_Fig3_HTML.png
:name: fig-1-3

A double-slit experiment where the electrons behave like little sticky balls. In panel A, the electrons are moving towards a barrier that has two small slits in it. Behind the barrier with two small slits is a screen with no holes. In panel B, the electrons have crashed into or passed through the barrier to crash into the screen. Panel C shows a front view of the electrons that passed through the barrier and crashed into the screen
```

Before we get to the real experimental results, we need to define some important terms and explore the concept of **wave interference**. Below are three important definitions about waves. [](#fig-1-4) is a visual representation of two of those definitions: wavelength and frequency.

```{figure} ../images/ch-01/541577_1_En_1_Fig4_HTML.jpg
:name: fig-1-4

A visual description of wavelength and frequency. Wavelength is the distance between two “like” points on the wave, for example the distance between two adjacent peaks or two adjacent troughs. If the wave is moving towards the right, frequency is how many peaks pass through the dashed line every second. If both waves are moving with the same speed, the upper wave has a higher frequency than the lower wave since more peaks pass the dashed line in 1 second
```

**Definitions**

- **Wavelength:** The distance between any two “like” points on a wave, such as two adjacent wave peaks. The variable we use for wavelength is the lowercase Greek letter lambda, $\lambda$. Since wavelength is a distance, we use length units such as meter, centimeter, or nanometer.
- **Frequency:** The number of oscillations per second. We use the variable *f* for frequency. The unit for frequency is 1/seconds, which is called a hertz, named after the German physicist Heinrich Hertz. A hertz is shortened to Hz. Some other units that we use for frequency include a megahertz (1 MHz $=1\times 10^{6}$ Hz), a gigahertz (1 GHz $=1\times 10^{9}$ Hz), and a terahertz (1 THz $=1\times 10^{12}$ Hz).
- **Period:** The time it takes for the wave to complete one full oscillation. We use the variable *T* for period, and the unit is seconds. Frequency and period are related by the formula $T=1/f$.

**Wave Interference**

Wave interference happens whenever two or more waves overlap. Those waves can be traveling in the same direction, opposite directions, or at an angle with each other. In fact, they don’t even have to look like the waves in [](#fig-1-4). They could instead be single pulses like in [](#fig-1-5). In this example, the two pulses, represented by the blue and red dashed lines, are on the same rope (the thicker gray line) and traveling in opposite directions. When the pulses overlap, they constructively add to make a larger pulse. The is known as constructive interference. However, if we have a positive amplitude pulse and a negative amplitude pulse, we will get destructive interference, see [](#fig-1-6).

```{figure} ../images/ch-01/541577_1_En_1_Fig5_HTML.png
:name: fig-1-5

Two pulses that constructively interfere with each other: The thick gray line is what we would actually see. The blue dashed line shows the pulse traveling to the right while the red dashed line shows the pulse traveling to the left. When they pass through one another, they add to create a larger pulse. At $t = 1.0$ s, this is 100% constructive interference. At all other times, the pulses are only partially constructively interfering
```

```{figure} ../images/ch-01/541577_1_En_1_Fig6_HTML.png
:name: fig-1-6

Two pulses that destructively interfere with each other: The thick gray line is what we would actually see. The blue dashed line shows the pulse traveling to the right while the red dashed line shows the pulse traveling to the left. When they pass through one another, they perfectly cancel each other out creating no disturbance on the actual rope for a brief period of time. At $t = 1.0$ s, this is 100% destructive interference. At all other times, the pulses are only partially destructively interfering
```

**Try This**

Find a piece of thin rope or a slinky and a stopwatch. If you have a friend nearby, have them hold one end of the rope or slinky. If not, tie or connect one end of the rope or slinky to a door knob. Stand a distance apart so that there is a bit of tension on the rope or slinky. Send a pulse down the rope or slinky and watch what happens when the pulse reflects off your friend or the doorknob. Next, start creating a sine wave motion with your hand, see [](#fig-1-4). Try to move your arm up and down so that the rope or slinky creates the shapes seen in [](#fig-1-7).

```{figure} ../images/ch-01/541577_1_En_1_Fig7_HTML.png
:name: fig-1-7

The first three standing waves of a one dimensional rope or slinky. Each standing wave is drawn with the same amplitude *A*. Interestingly, the frequency of a standing wave is independent of the amplitude of the standing wave
```

You will find that your hand has to move up and down with a very specific frequency to create these shapes, which are called standing waves. When you produce standing waves, the wave that you are creating with your hand is constructively interfering with the reflected wave. No other frequencies produce perfect constructive interference. Using your stopwatch, find the time for ten full oscillations (the time it takes for your hand to move up and down ten times) for each of the first three standing waves. The period of the standing wave is that time divided by 10. If you count twenty full oscillations, you would divide the time by 20 to find the period. Next use the formula $f=1/T$ to find the frequency needed to produce that standing wave. The frequency of the standing wave with one “loop” (the left picture) is called the fundamental frequency. You should find that the second picture with two loops has twice the fundamental frequency. The third picture with three loops should have a frequency that is three times the fundamental frequency. In general, $f_n = n f_1$, where *n* is how many loops the standing wave has. Notice that the higher mode standing waves (the waves with more loops) require more shaking energy! This will be important later.

**Back to the Double-Slit Experiment**

Ok, let’s run a different experiment. Instead of little, sticky balls, let’s send a wave towards the screens, as shown in [](#fig-1-8). Panel A shows the wave traveling towards the slits. The vertical lines are supposed to indicate the peaks of the wave. The troughs are halfway between each peak, so you are visualizing the wavelength of the wave. Panel B shows the wave as it passes through the slits. The straight wave turns into two arc waves, one coming from each slit. The arc waves are basically half circles with the center of the circle at the slit. I changed the color of one of the circular waves to better visualize the evolution of each wave. The two circular waves interfere with each other on the screen. Places where peaks of the waves overlap, indicated by the black lines between the slits and the screen, are where the two circular waves constructively interfere. Half way between the points of constructive interference are points of perfect destructive interference. Panel C shows what we see on the screen. The bright parts are where the two waves constructively interfere. The dark parts are where the two waves destructively interfere. At the very center of the dark parts, the waves are 100% destructively interfering.

```{figure} ../images/ch-01/541577_1_En_1_Fig8_HTML.jpg
:name: fig-1-8

A double-slit experiment using waves
```

Now, let’s do the experiment with electrons! Real experimental results can be seen in [](#fig-1-9). The electron behaves like a wave! There is actually a lot more to the double-slit experiment, but we aren’t going to go into any more detail in this book. You will learn much more about it if you take a Modern Physics class. The really important thing we need to conceptually understand is that the electron has wavelike behavior. This is incredibly important information for us because an electron that is orbiting a nucleus is *not* like the moon orbiting the earth, which is depicted in [](#fig-1-2). Experiments show that electrons behave like waves.

```{figure} ../images/ch-01/541577_1_En_1_Fig9_HTML.jpg
:name: fig-1-9

Experimental results of a double-slit experiment with electrons. Image Credit: Dr. Tonomura and Belsazar from Wikimedia Commons CC BY-SA 3.0
```

$\blacktriangleright$ **Important Concept**

Electrons in atoms behave like waves, so we need to think about interference effects.

This is a really hard concept to wrap our brains around, but experiments seem to indicate this idea is correct. How does a wave “orbit” around a nucleus? As an analogy, imagine a wave that wraps around upon itself in a circle, see [](#fig-1-10). This figure is just a conceptual example since there is no start or end to the wave. But to explore this concept we are going to wrap the electron wave counter-clockwise around the nucleus, and the wave is going to interfere with itself. If the electron wave does not perfectly wrap back around so that two peaks don’t overlap perfectly, the electron will destructively interfere with itself. If an electron destructively interferes with itself, there is no wave! If there is no wave, then there is no electron. Since electrons exist, the electron wave must constructively interfere with itself.

```{figure} ../images/ch-01/541577_1_En_1_Fig10_HTML.png
:name: fig-1-10

A conceptual exploration of an electron wave orbiting a nucleus that would result in destructive interference. In (**a**), we imagine the electron wave starting at the top of the circle and traveling counter-clockwise. In (**b**), the electron wave has made one full orbit, but notice that the wave does not line up with its starting point. For (**c**), the wave continues and should be interfering with itself, but we aren’t going to add the waves together quite yet. In (**d**), the wave continues for 12 orbits. To explore destructive interference, (**e**) shows adding together this wave after 4 full rotations. (**f**) shows destructive interference of this wave after 10 full rotations
```

A lot has happened, so let’s do a quick recap. We have learned that:

- Electrons have wavelike properties ([](#fig-1-9))
- Waves interfere with one another ([](#fig-1-5), [](#fig-1-6), and [](#fig-1-7))
- A wave can also interfere with itself ([](#fig-1-8) and [](#fig-1-10))
- An electron exists, so it better not destructively interfere itself out of existence.

Pause here and see if you can come up with a conclusion. When you have reached a conclusion, read on. My conclusion is below this fun fact:

**Fun Fact**

Many musical instruments make noise (hopefully pleasant noise!) because of standing waves. For example, when a guitarist plucks a guitar string, which is fixed at both ends, they are creating many standing waves (see [](#fig-1-7)) with different amplitudes all at the same time. Each of those standing waves has a frequency that is a multiple of the fundamental frequency. The amplitude of each of those standing waves is what gives the guitar it’s distinctive sound. To play a different note, the guitarist changes the length of the string by pressing on the string in a different spot, which in turn changes the fundamental frequency.[^7] The same is true for a piano. A piano key strikes a wire that produces standing waves that result in a (hopefully!) pleasant noise. The amplitudes of all the standing waves on a struck piano wire are different than the amplitudes of a guitar string, which is why they sound different.

A note played on a trumpet or saxophone also produces standing waves, but the standing waves are created in the air and are physically manifested as places of high and low air density.

**Conclusion**

The electron must constructively interfere with itself. This idea is conceptually shown in [](#fig-1-11).

```{figure} ../images/ch-01/541577_1_En_1_Fig11_HTML.png
:name: fig-1-11

Four conceptual examples of an electron wave orbiting a nucleus that would result in constructive interference. Going from left to right is going from a lower energy state to higher energy states
```

An electron can only “orbit” around the nucleus if it satisfies a standing wave condition. Each standing wave has an energy associated with it. Just like how the standing wave on a string with 2 loops has a shorter wavelength and requires more shaking energy than the standing wave with 1 loop, the higher energy “states” of an electron have shorter wavelengths. Thus the allowed energies of the electron are “discrete”: they can only have the specific values corresponding to these standing waves.

We call the discrete energies an electron orbiting a nucleus can have “energy levels” or “energy states” and describe them in diagrams like [](#fig-1-12). The lowest energy state is called the ground state of the atom, or the ground state for short. States with higher energy are called excited states. These energy level pictures are sometimes called Grotrian diagrams, named after German astronomer and astrophysicist Walter Grotrian. The SI unit for energy is a joule, which is named after the English physicist James Joule. A joule is shortened to $\text{J}$.[^8] A joule is shorthand for $\text{kg}\,\text{m}^2/\text{s}^2$. For reference, the energy of a baseball moving at 50 mph is about 36 joules. The energy of an apple moving at 1 meter/second is about 0.05 joules.

```{figure} ../images/ch-01/541577_1_En_1_Fig12_HTML.png
:name: fig-1-12

A conceptual picture that shows an atom with a single ground state and three excited states. A real atom has many excited states
```

**Important Comment**

Atomic physicists and spectroscopists often say that the ground state energy is 0. This is not true! Think about the standing wave on a string with a single loop. This is the standing wave with the smallest amount of shaking energy, but it still has energy! The ground state of an atom also has energy. In experiments, we measure the energy difference between the ground state and excited states. For this purpose, we assign the lowest energy state to be 0 so that everything is measured with respect to that state.

The energy difference between the ground state and the lowest energy excited state in the hydrogen atom is $0.000000000000000001634\,\text{J}=1.634\times 10^{-18}\,\text{J}$. That is a small number! A more common unit for energy in atomic physics is the electronvolt (eV). The conversion is $1\,\text{eV} = 1.602\times 10^{-19}\,\text{J}$, so the energy of the lowest excited state is $10.2\,\text{eV}$ above the energy of the ground state.

**One Final Thing**

The above description of an electron in an atom is a good starting point to understanding how and why atoms behave the way they do. Think about this chapter as making a first pass-through [](#fig-1-1). The conceptual idea you just learned is correct. However, the electron wave turns out to be more complicated than the simple picture given above. For one thing, the electron wave is going to be in 3 dimensions. But, more importantly, the actual wave that describes the electron in an atom, which is called a wavefunction, is a bit messier to deal with. All of the concepts like wave interference and energy levels in the atom are still correct, but the presentation of the electron wave has been simplified. You will refine these ideas in future classes such as Modern Physics and Quantum Mechanics.

**A Little Bit Extra**

A careful reader might have noticed something odd about [](#fig-1-9). While there was clearly a wave interference pattern, this wave interference is composed of tiny bright dots. The electrons are moving through the slits as waves. However, we have experimentally found that when the electron hits the screen, which is often called a measurement, the electron wave “collapses” to a single point. You may have heard the phrases “wavefunction collapse” or “**wave-particle duality**”. This is a fancy way of saying that the electron behaves like a wave until something interacts with it before it starts behaving like a particle (i.e. a single point on the screen). The amplitude of the wave interference tells us the *probability* of where the wave collapses back to a point. Thus where the electron wave destructively interferes on the screen produces 0 probability that the particle will be detected at that point. The process of going from a wave to a point is a fascinating and yet unexplained phenomenon! There are many physicists and philosophers who think very hard about how this “collapse” occurs. We will explore more about the probabilistic interpretation of quantum mechanics, which is often called the orthodox or Copenhagen interpretation, in [](#ch-6).

(sec-1-3)=
## 1.3 Photons and Spectroscopy

Suppose we want to measure the energy difference between the ground state and any one of the excited states. How do we do it? Answer: Spectroscopy! We shine light onto the atoms and look at what happens to the light. In modern spectroscopy, we use laser light. Light, including laser light, is composed of tiny particles known as **photons**.[^9] As an analogy, think about a stream of water. The water looks continuous, but it is actually made up of tiny water molecules. The same thing is true with light. Light is composed of tiny particles we call photons. There is, however, a really important difference between water molecules and photons. The energy of a photon is determined only by the frequency of the light wave. The more the light wave oscillates up and down in one second, the larger the energy of an individual photon that makes up that light wave. The energy of a water molecule, on the other hand, is related to how fast the molecule is moving, rotating, and vibrating. We will explore the connection between the frequency of the light wave and the energy of a photon more in the next section.

**Important Statement**

If a photon has the same energy as the energy difference between the ground state and an excited state, the atom will absorb that photon and move an electron to the excited state. If the photon does not have the same energy as that energy difference, the atom will completely ignore the photon.[^10]

**Thought Experiment Time**

Imagine you have an electron behaving like a wave orbiting around a nucleus. That electron wave has to constructively interfere with itself, and we can think about that standing wave as having some amount of energy. Let’s call this energy $E_1$. If we wanted to add another loop to the standing wave, we need to add energy to the system. Suppose an electron with 1 more standing wave loop has energy $E_2$. Remember that the electron needs to be a standing wave, which has a specific energy. If it wasn’t, the electron would experience destructive interference. We want to move an electron from the lower energy standing wave to the higher energy standing wave. How much energy do we need to put into the system? The answer is in the footnotes.[^11]

This is the basic idea behind spectroscopy. If we want to excite an electron from one energy level, which has some energy, to another energy level, which has a different energy, we need to provide the system with the correct difference in energy.

Restating that in terms of an actual experiment: We send a laser through an optically clear container, called a cell or vapor cell, filled with atoms. We will smoothly scan the energy of the photons over time and monitor the transmission of the laser through the cell. If the energy of the photons does not match the energy difference between the ground state and an excited state, the laser light will pass right through the atoms with no losses. If the energy of the photons matches that energy difference, light will be lost from the laser and the transmission will decrease. Experiments that match the above description are known as absorption spectroscopy experiments. We, as experimentalists, simply monitor the transmission of the laser through an atomic sample as we change the photon energy. When the amount of transmitted light drops, we learn what energy is required to excite the atoms from the ground state to an excited state. Believe it or not, that is, conceptually, all there is to it. In the lab things are a bit more complicated, but this is the basic idea. We will finish up this section with a new definition.

**Definitions**

- **Resonance:** When an atom gets excited by a photon from one state to another, we say the atom “goes through resonance.” This is similar to playing the trumpet. When you blow correctly into a trumpet, a standing wave is excited in the pipe to create a note. The same thing happens with an atom. When you excite an atom with the right energy photon, the electron goes from one standing wave mode to another. Atomic physicists use the word “excitation” and “resonance” interchangeably.

(sec-1-4)=
## 1.4 Math

The speed of light, the wavelength of the laser light, and the frequency of the laser light are all related using the formula:

```{math}
:label: eq-1-1

c=f\lambda,
```

where $c=299,792,458\,\text{m/s}\approx 3\times 10^{8}\,\text{m/s}$ is a constant of nature known as the speed of light.[^12] The energy of a photon is given by the formula:

```{math}
:label: eq-1-2

E_{\text{ph}}=hf,
```

where *h* is a constant of nature known as Planck’s constant, named after German physicist Max Planck. Planck’s constant is a very small number, $h = 6.626\times 10^{-34}\,\text{Js}$. The units are joules times seconds, where joules is the unit of energy. The most important thing to emphasize here is that we have multiple ways to state the same property of a photon. If I tell you the wavelength of the light, you can immediately calculate the frequency of the light and the energy of the photons that make up that light. Since all three quantities are related by constants, an atomic physicist will claim that wavelength, frequency, and the energy of a photon are all the same thing. An atomic physicist might very well say, “the energy of the photon is 632 THz” and think nothing of it. It takes some practice to use “wrong” units to describe something! Imagine if you asked me my height, and I responded with $150\,\text{MHz}$. For physicists, there is nothing wrong with doing this since we would only be off by a constant of nature.

A common energy unit is inverse centimeters. For example, the statement, “The energy difference between the two states is $12{,}460\,\text{cm}^{-1}$” is very common. For spectroscopists, this number means the same thing as $2.475\times 10^{-19}\,\text{J}$. Converting between the two numbers requires multiplying by the correct combination of the fundamental constants *h* and *c*. This energy unit is explored more in [](#prob-1-6).

We can now make a new definition:

**Definitions**

- **Resonance frequency:** When the frequency of the laser is just right to excite the atom from the ground state to an excited state, we call that the resonance frequency. We use the variable $f_r$ to represent resonance frequency. Since resonance frequency is a frequency, it uses units of Hz, MHz, GHz, or THz.

**Common Misconception**

Power is not the same thing as energy. Power is the *rate* at which energy is exiting the laser. Imagine two laser beams with two different frequencies. The light from laser #1 has a higher frequency than the light from laser #2. We now know that the photons that make up laser #1 have more energy than the photons that make up laser #2. Power is how much energy is exiting the laser per second. If the same number of photons per second are leaving both lasers, laser #1 has a larger power. In math form, the power of a laser is:

```{math}
:label: eq-1-3

P=N E_{\text{ph}},
```

where *N* is how many photons per second that leave the laser and $E_{\text{ph}}=hf$ is the energy of a single photon. The unit for power is a watt, named in honor of Scottish chemist James Watt. A watt is shortened to $\text{W}$ and is equivalent to joules per second. Imagine you have a 1 watt laser and a 10 watt laser that have photons with the same energy. The 10 watt laser emits 10 times as many photons per second as a 1 watt laser.

(sec-1-5)=
## 1.5 Extra: Polarization

The frequency of light tells us how many times that light wave oscillates up and down in 1 second. Polarization tells us the direction the light is oscillating. There are three major groupings of light polarization: linear, circular, and elliptical. Linearly polarized light is the most common light we use in spectroscopy, so we aren’t going to talk about circularly or elliptically polarized light here. However, there are types of spectroscopy experiments that do use circularly polarized light. If you are curious about them, image search the phrases to find some neat animated gifs showing light with different polarizations moving through space. For now, we will focus on linearly polarized light.

Linear polarization is light that is oscillating up and down in a single plane. There are two specific types of linearly polarized light: horizontal and vertical. Horizontal light oscillates …horizontally with respect to some surface, and vertical light oscillates …vertically to that surface, see [](#fig-1-13) Remarkably, we can use these two polarizations to describe any linearly polarized light. For example, suppose the light was oscillating at a 45${ }^\circ$ angle. We would describe the light as half horizontal and half vertical.

```{figure} ../images/ch-01/541577_1_En_1_Fig13_HTML.png
:name: fig-1-13

Examples of oscillating electric fields propagating along the z-direction. The left picture shows horizontal linear light while the right picture shows vertical linear light
```

In the lab, there are optical devices called half-waveplates, sometimes written as $\lambda /2$ plate or just $\lambda /2$. A half-waveplate can rotate the linear polarization of light. If you have horizontally polarized light, you can use a half-waveplate to change the polarization so that it is 10% vertical and 90% horizontal, 50% vertical and 50% horizontal, 75% vertical and 25% horizontal, etc. You can even make the light exiting the half-waveplate be completely vertical. That might seem like a neat trick, but the real usefulness comes when we put a second optical device after the halfwave plate called a polarizing beam splitter (PBS), see [](#fig-1-14).

```{figure} ../images/ch-01/541577_1_En_1_Fig14_HTML.png
:name: fig-1-14

Using a half-waveplate and a polarizing beam splitter, we can create two beams of light. You can rotate the half-waveplate to control the ratio of light in each path. In normal spectroscopy setups, you are looking down on the light and optics from above. In this orientation, p-polarized light is horizontal, indicated by the blue arrows and s-polarized light is vertical, indicated by the dotted circles
```

By tradition, the light that bounces off the PBS is called s-polarized light while the light that passes through is called p-polarized light.[^13] This is because the PBS can technically be in any spatial orientation. For safety reasons, we almost always keep the light in a horizontal plane. In this typical setup, s-polarized light is vertically polarized light while p-polarized light is horizontally polarized light. If you were to rotate the PBS so that the s-polarized light was going straight up (don’t do this, it is an eye hazard!!), that s-polarized light is now horizontally polarized while the p-polarized light is now vertically polarized. This is why we use “s” and “p”.

In the lab, we use half-waveplates and polarizing beam splitters to split a single laser beam into two beams and also control the power in each of them. If the waveplate is oriented such that the light polarization leaving the waveplate is completely vertical, all of the light would bounce off the PBS. If the polarization of the light leaving the waveplate was at 45${ }^\circ$, there would be equal power in both lasers leaving the PBS.

(sec-1-6)=
## 1.6 The Most Important Equation in All of Science

```{math}
\text{questions + repetition + critical thinking = mastery}
```

Don’t be afraid to ask questions. Don’t be worried about asking for clarification. Don’t expect to remember or understand every single concept the first time you read or hear about it. Mastery is not a short journey. Developing critical thinking skills is not a 5 minute activity that you figure out after watching a 3 minute YouTube video. Practice deep learning, keep a growth mindset, and, most importantly, have fun!

## Problems

```{exercise}
:label: prob-1-1
:enumerator: 1.1

Go through the chapter and write down all of the fundamental constants (there are two of them). Don’t forget units.
```

```{exercise}
:label: prob-1-2
:enumerator: 1.2

Go through the chapter and write down each equation. For each equation, write a brief description about what the equation means.
```

```{exercise}
:label: prob-1-3
:enumerator: 1.3

*(A Different Way to Find the Energy of a Photon)*

- (a) Using two formulas from [](#prob-1-2), derive a formula for the energy of a photon in terms of only fundamental constants and wavelength.
- (b) Check to make sure the units are correct. Physicists always check units. Always.

  Hint: 1 J = $1\,\text{kg}\,\text{m}^2/\text{s}^2$
```

```{exercise}
:label: prob-1-4
:enumerator: 1.4

- (a) What is the energy of a photon that is in a laser that has a frequency of 647.8 THz $(647.8\times 10^{12}\,\text{Hz})$? Express your answer in both joules (J) and electronvolts (eV). Your final answer should have 4 significant figures.
- (b) What is the wavelength of the light in nanometers?
```

```{exercise}
:label: prob-1-5
:enumerator: 1.5

*(Assessments)*

Physicists are trained to assess everything. It is what makes us special ☺.

Assess the formula you found in [](#prob-1-3) (a) by re-finding the energy of a photon using the numbers from [](#prob-1-4) (b). If you get the same answer as [](#prob-1-4) (a), we have built confidence that the formula you derived is correct.
```

````{exercise}
:label: prob-1-6
:enumerator: 1.6

In atomic physics, energy is often measured in the units of $\text{cm}^{-1}$. The method of calculating energy in these units is to first find the wavelength of the laser in centimeters, and then take the inverse. In equation form, this is

```{math}
:label: eq-1-4

E\bigl(\text{cm}^{-1}\bigr)=\frac{1}{\lambda(\text{cm})}.
```

Note that in the above formula, the units to use for each symbol are included in parentheses; the formula does not say “$\lambda$ multiplied by cm”, but rather “make sure wavelength has units of cm before plugging into the formula.”

Using $\lambda =852.347\,\text{nm}$, find the energy in units of inverse centimeters. Your answer should have 6 significant figures.
````

```{exercise}
:label: prob-1-7
:enumerator: 1.7

The equation in [](#prob-1-6) can be confusing. Energy has units of joules and not inverse length! Why are atomic physicists comfortable with using energy in this weird unit? There are multiple correct answers here.
```

```{exercise}
:label: prob-1-8
:enumerator: 1.8

It isn’t only atomic physicists who use energy in weird units. Astronomers, nuclear physicists, and a good number of chemists also use energy in inverse centimeters. Some chemists and condensed matter physicists prefer to use electronvolts (eV). Virtually no one uses the SI unit (joules)! Any thoughts why?
```

[^1]: Words in the glossary are in bold type the first time we use them.

[^2]: In the last half of the twentieth century, atomic physics combined with molecular physics and optical physics to make what is now known as atomic, molecular, and optical physics. We use the acronym AMO physics.

[^3]: There are other phases of matter as well, including plasmas and Bose-Einstein condensates (BEC), which were named after the Indian mathematician and physicist Satyendra Nath Bose and the German born physicist Albert Einstein. A BEC is a really amazing state of matter that was first postulated in 1924. It wasn’t until 1995 when American physicists Carl Wieman and Eric Cornell used atomic physics techniques to create the world’s first BEC from rubidium atoms. Shortly after, German physicist Wolfgang Ketterle made a BEC from sodium atoms. The three atomic physicists won the 2001 Nobel Prize in Physics for this effort.

[^4]: One of my readers suggested that adding nationalities would add a bit of fun and extra history (I agreed!). Lots of sources list Einstein as ‘German born’ because he moved to Switzerland in 1895, giving up his German citizenship. In 1901, he became a Swiss citizen.

[^5]: To be fair, experiment does not always agree with the Standard Model. For example, the Standard Model says that the universe should be nearly equal amounts of matter and antimatter (this is the baryon asymmetry listed above), which would be bad since then all the matter and antimatter would combine to destroy the universe. In other words, the Standard Model says that the universe shouldn’t exist, which disagrees with experiment.

[^6]: Well, maybe the universe would exist. It would just exist without any matter, which wouldn’t be much fun.

[^7]: They could also pluck a different string that has a different mass density or change the tension on the string. All of these changes will result in a different fundamental frequency.

[^8]: Notice the unit ‘joule’ is not capitalized. In general, a unit named after a person is not capitalized.

[^9]: German physicist Max Planck won the 1918 Nobel Prize in physics for discovery of the photon. Albert Einstein won the 1921 Nobel Prize in physics for explaining the photoelectric effect, which determined that a beam of light is made up of a bunch of photons. I may be biased, but Einstein’s explanation of the photoelectric effect was the most important discovery of the twentieth century.

[^10]: This important statement is super important, but it also isn’t 100% correct. We are going to start with this statement to get at some important concepts. In the next few chapters, we are going to discuss some more physics and then restate this important statement to something more correct. It’s kind of like the flowchart from the beginning of the chapter. We start simple and build up complexity.

[^11]: We would need to add precisely $E_{2}-E_{1}$ of energy.

[^12]: This is the speed of light in a vacuum. It is exactly $299,792,458\,\text{m/s}$.

[^13]: Fun fact: the “s” stands for the German word “senkrecht”, which translates to perpendicular; the “p” stands for the German word “parallel”, which translates to parallel (that isn’t a misprint, the German word for parallel is parallel). I like to use “s” for skip and “p” for pass-through.
