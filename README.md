# light-physics

In this chapter, we will explain the fundamental physics that we need for studying radiation ecology, without getting too technical.

## Radiation is light

"Radiation" means a beam of tiny particles. For example, $\alpha$ ray is a beam of $\alpha$ particles (nucleus of helium), while $\beta$ ray is a beam of electrons. However, "radiation" in "radiation ecology" means, specifically, a beam of particles called "photons". It is also a wave called "electromagnetic wave". These two words mean a same phenomenon which we call "light". You may wonder "how are particles and a wave same?". We will see it later. 

The theory of light is called "optics". Therefore, radiation ecology is an ecology which is strongly related to optics. 

## Visible light and invisible light

In daily life, by the word "light" we usually mean the light which we can see, such as the light of sun or desktop display. They are categorized as "visible light". Invisible light also exists in nature. Ultraviolet (UV) light and infrared light are examples of the invisible light. What is different is wavelength. The wavelength of the visible light is, roughly speaking, in between 400 nm and 700 nm (nm is "nano meter", which is equal to $10^{-9}\text{ m}$ and $0.001 \micro\text{ m}$). This range of light can activate human eyes' photo receptors, hence we can "see" them. The light which is outside this range is the invisible light. For example, a light with wavelength a little shorter than the visible light is the ultraviolet (UV) light, whereas a little longer one is the near infrared (NIR) light. Likewise, light is categorized into groups by wavelength: from shorter to longer, $\gamma$ ray, X ray, ultraviolet (UV) light, visible light, near infrared (NIR) light, shortwave infrared (SWIR) light, thermal infrared (TIR) light, microwave, etc. The "radio wave" used in the broadcast of TVs or radios are also light, whose wavelength is even longer. 

## Wavelength of light

Wavelength is an important feature of light, because the nature and the behavior of light strongly depends on its wavelength. Wavelength is defined for a wave whose pattern is sinusoidal. "Sinusoidal" means, it is described by a trigonometry function such as sine and cosine. The wavelength is the distance between a peak and the nearest peak (or bottom to the nearest bottom). A Greek letter $\lambda$ is conventionally and popularly used to describe wavelength.

A very important fact: a photon's energy $E$ is directly connected to the wavelenght $\lambda$ by a formula:

$E=\frac{hc}{\lambda}$, (eq. 1-1)

$where$, $h\fallingdotseq 6.63\times10^{-34}$ J s is the "Planck constant" and $c\fallingdotseq 3.00\times10^{8} \text{m s}^{-1}$ is the "speed of light", both of which are fundamental constants in physics. Let's try some exercises:

#### Exercise 1-1: Derive enery of a photon in case (1) $\lambda = 450\text{ nm}$, (2) $\lambda = 680\text{ nm}$. 
Answer: (1) $E=6.63\times10^{-34}\text{J s}\times 3.00\times 10^{8} \text{m s}^{-1}/(450\times 10^{-9} \text{m})=4.4\times 10^{-19}\text{ J}$. (2) $E=2.9\times 10^{-19}\text{ J}$.

This exercise calculated energy of photon of two lights: blue light (1) and red light (2) both of which are at the peak of absorption by the chlorophyll $a$ which is a main pigment of photosynthesis by terrestrial plants. The result shows the photon's enegy of blue light is larger than that of red light. It is understandable because the formula indicates inversely proportional relation between the energy and the wavelength: the longer the wavelength, the smaller the energy. An example which is related to this fact is, when we watch an old poster photo which has been displayed on a wall for long time: Red color disappears faster than blue paint, resulting in pale, blueish photo on the poster. It is because the red pigment preferably absorbs light in shorter wavelength (such as blue or UV) who has enough high energy to destroy the structure of the pigment. In other words, by absorbing the destructive photons of the short wave light, the red or brown pigments block them. It is the reason why some plants' leaves are red: their red pigments blocks harmful photons contained in the sunlight or skylight from going inside the leaf and destroy the tissue.

## particle and wave?

But wait. Don't you deel strange? While we were talking about photon's energy, "wavelength" sudenly came up. Wavelength is a feature of a sinusoidal wave. It is hard to connect an idea of wavelength to a particle, because a sinusoidal wave repeats the same pattern from far away to far away. It does not look like a single particle which we imagine like a small basket ball. It is a mysterious story. As mentioned, light has two aspects: wave and particle. Many people try imagining light in such a way that satisfies these two aspects at a same time in vein. Not only you but also everybody may feel uneasy to catch up this mystery. My suggestion: give up imagination and accept the two aspects without asking how and why. We call a mysterious particle which has both particle and wave aspects "quantum". The theory of nature and behavior of a quantum is called "quantum dynamics". 


## Quantum dynamics of light and electron

Quantum dynamics is a big subject in physics. It's theoretical basis depends on advanced mathematics which is too much for most of ecologists. Therefore, we give up getting a systematic understanding of the quantum physics, and instead, we will just summarize the most imporatnt and useful concepts and facts in quantum dynamics for builind radiation ecology. 

A photon is a quantum. An electron is also a quantum. Indeed, an electron, which we may imagine as a particle, behaves as a wave in an electron microscope: in that device, we use an electron wave instead of a light wave to capture an image of a tiny target. Interestingly, a photon and an electron interacts with each other in a way electron absorbs or emits a photon. It is a mechanism of absorption and scattering of light by substances such as:

- Absorption of photons by an electron in chlorophyll molecules. It is the start of photosynthesis.
- Scattering of photons by an electron in atmospheric molecules in the sky. It makes blue sky.
- Absorption and emission of photons by electrons in the Sun. It causes sunlight.
- Emission of photons by an electron in chlorophyll molecules. It causes chlorophyll fluorescence.

Therefore, we must learn about electron in order to understand photon's behavior. We summarize the most important rules in quantum dynamics for this purpose:

1. The behavior of an electron or a group of electrons is described by a concept called "quantum state". "State" here is not something like solid, liquid, and gas, which are "thermodynamic state". You may imagine a quantum state like a mathematical function. The phyical properties such as position, energy, momentum (something rekated to velocity), and angular momentum (something related to rotation) are ambiguous unless the quantum state is a special state called "eigenstate" for each property.

2. If the quantum state depends on time in an oscillating manner with a frequency $\nu$ or an angular frequency $\omega$ ($=2\pi\nu$), it is the eigenstate of the energy and the energy $E$ is decided by the following formula (these two are the same):

$E=h\nu$, (eq. 1-2)

$E=\hbar \omega$, (eq. 1-3)

This is a general rule in quantum dynamics. In fact, the energy of photon $E=hc/\lambda$ is also derived from this formula: for light wave, $\nu$ is how many cycles a wave repeats in unit time, hence it is a distance in unit time divided by wavelength, i.e., $\nu=c/\lambda$. By putting this to $E=h\nu$, we get $E=hc/\lambda$. 

3. Depending on situation, an electron (or other quantum) can take various different energy eigen states in a systematic manner. We call them "energy levels." The electron (or quantum) can change its state from one energy eigen state to another. When it happens, the electron (or quantum) can absorb oremit a photon and the photon's energy $E_\text{photon}$ satisfies the following formula:

$E_\text{photon} = E_\text{high}-E_\text{low}$ (eq. 1-4)

where, $E_\text{high}$ and $E_\text{low}$ are the energies of the states between which the electron (or quantum) make a transition. If the transition is from lower energy state to the higher energy state, the photon is aborbed and disappears. If the transition is from the higher energy state to the lower energy state, the photon is emitted. 


## Thermal radiation

Now we learn about light source. In ecology, the the most important light source is "thermal radiation". Every object spontaneously emit light with certain wavelength and intensity determined by its temperature: a hot object emit photons with shorter wavelength and higher intensity. Accordingly, the the Sun (ca 6000 K) emits photons (sunlight) with wavelength mostly in between 0.1 um and 4 um. On the other hand, the Earth (ca 300 K) emits photons with wavelength mostly in between 4 um and 100 um. These two groups of photons are important in the energy balance in the Earth's environment. The former group (0.1 um to 4 um) is called "shortwave radiation", whereas the latter group (4 um to 100 um) is called "longwave radiation".

The mechanism of thermal radiation is as follows: many particles (molecules, atoms, electrons, etc.) which make up an object are in thermal motion: They 

## 
It is a wave which transfers in the "electromagnetif field". So, what is the "electromagnetic field"? It is a basic feature of space that includes both an "electric field" and a "magnetic field." No one knows exactly why space has these features, but they exist.


Light can be thought of in two main ways. One way is as a "wave which travels in the electromagnetic field." In science, this kind of wave is called an "electromagnetic wave" or "radiation." 

The electric field and the magnetic field exert forces on electrically charged particles such as electrons. The force from electric field is independent of the particle's velocity, whereas the force from magnetic field depends on the particle's velocity. More precisely, this relationship is described by the equation:

${\bf F} = q {\bf E} + q {\bf v} \times {\bf B}$    (1.1)

where, ${\bf F}$ is the force on the particle, ${\bf E}$ is the electric field, ${\bf B}$ is the magnetic flux density (an expression of magnetic field), $q$ is the electric charge of the particle, and ${\bf v}$ is the velocity of the particle. The symbol $\times$ means "vector product" which you can find its definition and meaning in a mathematics textbook. This equation is the fundamental fact which defines the two fields, so that we do not need to worry about why they work this way. 


is For convenience, people prefer using a word "light" to describe electromagnetic wave. 


## Light is photons

Another way to think about light is as a "particle produced by the electromagnetic field." The particle is called "photon". Unlike particles we usually think of, like tiny bits of dust, a photon is a much more abstract concept. It is not a normal particle but a special kind of object known as a "quantum." It is an idea of "quantum physics", which mainly treats objects too small to be treated by the physics of our daily life (so called Newtonian dynamics). 

In the radiation ecology, the quantum physics may appear in some topics involving not only photons but also electrons, such as photosunthesis or chlorophyll fluorescence. Therefore, it is a good idea to know about some of the main ideas in quantum physics: 
- Properties such as energy, momentum, and angular momentum of a quantum particle (such as photon and electron) are impossible to determine in general cases.
- Instead, these properties are described by something called a "linear operator."
- The value of these properties is determined if the system is in a special state called an "eigenstate," where the value is equal to something called the "eigenvalue."

In case of the electromagnetic field's energy, the eigenvalue of its "liner operator" (called "Hamiltonian operator") is related to a non-negative integer $n$. We understand this integer $n$ as the number of photons. In other words, we recognize the eigen state of electromagnetic field's energy as "there are $n$ photons in the space". 

You may feel it is too abstract to understand, but it's ok. It's too much for human's intelligence to imagine a perfect picture of a photon. In many cases you may imagine them as tiny balls, but you should remember that sometimes this imagination is invalid.

## Principle of superposition

Regardless of the aspect, ligh has a very important and useful property called "principle of superposition". It is a general idea which can be applied to many phenomena other than light, but we only mention about light here. The "principle of superposition" says "light can be considered as a superposition of many other lights". "Superposition" is a technical word in physics. It is like "combination" or "mixture". Let's look at an example. 

We imagine several different light waves existing in a same space. We will call electric field of the light waves as ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$. ${\bf E}_i$ describes electric field produced by the $i$-th wave. ${\bf E}_i$ is a function of time and place. Then a new light wave can be created by combining (superpositioning) these waves like this:

${\bf E} = a_1 {\bf E}_1 + a_2 {\bf E}_2 + ... + a_n {\bf E}_n$

Here, ${\bf E}$ is (the electric field of) the new light wave, and it is made up of the original waves ${\bf E}_1$, ${\bf E}_2$, …, ${\bf E}_n$, with each wave multiplied by a certain number (called a scalar) $a_1, a_2,…, a_n$. This form (multiplying things by scalars and summing up them) is exactly called "superposition" in physics, or "linear combination" in mathematics. If you learn the fundamental theories of light, you would find that the any linear combination of lights also satisfies the theory. It is the reason why this principle is valid for light.


## Fourier analysis

For the moment, let's consider light as a wave. The most physics textbooks mention "sinusoidal wave", which is described by the trigonometric functions: cos⁡(x) and sin(x). These functions repeat the same "up and down" pattern over and over again, meaning they are "periodic."

(figure of sinusoidal wave)

However, sinusoidal waves are just one type of waves. A wave is not have to be sinusoidal. Any patterns that moves through space can be a wave. The "pattern" can be mostly any shapes you can imagine, like a pulse, a bell shape, or sinusoidal. For instance, a flash light is like a pulse pattern moving through space. 

But still, sinusoidal wave concepts are useful enough to describe and understand light waves. Why? Because sinusoidal light wave is so simple that its treatment is easy and straightforward. Moreover, by using the afforementioned "principle of superposition", we can describe any pattern of light waves by superposition of sinusoidal lights. And surprisingly, mathematicians have proved that virtually any shapes of waves can be described in this way. This idea and theory is called "Fourier analysis". It is creating an arbitrary wave (or decomposing a wave) by superposition of sinusoidal waves with various wavelength. 

Hereafter, we may call a sinusoidal light as a "monochromatic light". It means "light with a single wavelength". The word "monochromatic" consists of "mono" meaning "single" and "chrome" meaning "color". Why color? You would understand later soon. 


## Spectrum

By using Fourier analysis, we may consider light as superposition of monochromatic lights with various wavelength. Therefore, we may simply focus on understanding the monochromatic light. If we need to consider more complicated cases, we can imagine the superposition of monochromatic lights ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$ with various wavelength $\lambda_1, \lambda_2, ..., \lambda_n$. Then what matters next is the coefficients $a_1, a_2, ... a_n$ which tell us the contribution of the monochromatic lights. In other words, each of $a_1, a_2, ... a_n$ describes the amplitude of each monochromatic light. In many cases we are interested in their squared values because the energy of light is proportional to the square of its amplitude. The graph of the wavelength (x-axis) and square of the amplitudes of the monochromatic lights is called a "spectrum." 

The spectrum is a very common way of describing phenomena of light so that we should be familiar with it. For instance, the spectrum of the sunlight is as follows (Figure):

We can see the sunlight consists of various wavelength of sinuspidal lights. Particularly, the graph has a peak in between 400 nm to 700 nm. It means that a big portion of energy of the sunlight comes from the sinusoidal waves with wavelength in between 400 nm and 700 nm. This category of light is called "visible light" because our human eyes can sense them. Coincidentally, they are "photosynthetically active radiation" which activates photosynthesys in many of the terrestrial plants. 


## Categories of light

As I wrote, the wange of wavelength of visible light, or the light human's eyes can detect, is between 400 nm to 700 nm. Although it occupies a big portion of solar light, it is a very narrow and limitted category of light in nature. In fact, lights' wavelength can be much shorter or longer than them. From short to long, we can call lights as: gamma-ray, X-ray, ultraviolet (UV), visible light, infrared light, microwave, .... These cateories do not have reasonably clear boundaries with each other. Actually, the wavelength of light can take positive values arbitrarily and continuously. Nonetheless, it is convenient to categorize light into these groups because the features and behaviours of light depends on the scale of wavelength so strongly that we may need to consider a different model for each of them. For example, interaction of light and a plant leaf is very different between visible light and microwave: visible light can be largely absorbed or reflected by the leaf, while microwave may have little interaction with the leaf.


## Colors of visible light

The color sense of human's vision is essentially related to the spectrum. In short, if a spectrum of light is given, we can predict its color. How? The human's eyes have three different types of color-sensing cells called "cones". The brain recognizes colors by the signals from these three types of cones, namely, "S-cones", "M-cones", and "L-cones", as blue color, green color, and red color, respectively. The intensity of the response of each type of cone depends on the light's spectrum: If the dominant wavelength are 400 nm in the spectrum, the S-cones' response is big and other cones' response is small, resulting in the recognition of blue by the brain. If the light's spectrum consists of multiple peaks or broad range of wavelength, all the S-, M-, and L-cones responds differently and the color is a mixture of blue, green, and red, resulting in a huge variation of possible colors. 

As I wrote, the human's vision takes place when our eyes are illuminated by the light called "visible light", whose wavelength is in between about 400 nm and about 700 nm. Our eyes cannot detect light whose wavelength is outside this range. It is because the cones in human's eyes do not respond to such light. Therefore, if some animals have different types of cones from human, they may be able to see light which is invisible for human. In fact, birds and some insects have cones which respond to UV light, whose wavelength is shorter that our visible light. Therefore, we should consider invisible light (for us) when we study about those animal's vision.

I explained that a spectrum decides color of the light. Interestingly, the reverse story is invalid. Namely, a color does not decide lights' spectrum. In other words, lights with different spectrum can have a same color. Let's understand it by an example: suppose a light with a spectrum of double peaks at 550 nm (stimulating M-cones) and 680 nm (stimulating L-cones). Then the color is a mixture of green (response by M-cones) and red (response by L-cones), which is yellow. On the other hand, suppose a light with a single peak around 610 nm. To some extent, both M-cones and L-cones repond to this wavelength, resulting in the the color of a mixture of green and red, which is yellow which is the same as the previous example.

Nonetheless, we may discuss spectrum in a context of colors for convenience. In particular, we describe monochromatic visible ligh not only by wavelength but also its color in an order of shorter wavelength to longer wavelength as follows: violet, purple, blue, green, yellow, orange, red. It is not a coincident that this order is the same as the order of colors in a rainbow. In fact, rainbow is a collection of concentric arcs of monochromatic lights: the inside arc is shorter light (violet or blue) and the outside arc is longer light (red). It is a good idea to memorize this order of colors because it helps us understand and imagine the phenomena of light in terms of wavelengths.

## Features of monochromatic light

Now let's learn about some important feature of monochromatic light. Suppose we consider a monochromatic light 

The most important fact of photons is relation between the energy $E$, frequency $\nu$, wavelength $\lambda$,  of a single photon $E$ is 



## Colors of objects

In the previous section, we discussed about colors of lights. Now we discuss about colors of things (objects). They are similar but different ideas which we need to distinguish carefully. For example, let's imagine a plant's green leaf. The plant's leaf is illuminated by some light coming from a certain light source. Then the plant's leaf scatters the light to our eyes. Therefore, the color of the plant's leaf depends on the color of the illuminating light and how the light is scattered by the plant's leaf. reflectance to our eyes is a scattered light. Because color is a feature of light, we cannot discuss color of the leaf unless considering light source which illuminates the leaf. The color or leaf is, in fact, discussed in relation to the color of light which is scattered by the leaf. Then something strange may happen: if the light is originally red, containing little light which stimulates M-cones (which gives response of green), the reflected light can be also red. 

plants' leaf "scatters" green light stronger than other lights (red and blue). 

simple: the response of our eyes' cones give signals of green in response to the lights' spectrum. 



some more about colors. Colors 
absorption
reflection
color of shadow

 The important lesson for us is:
- Light is not necessarily visible to human's eyes. There is a broan range of invisible light and they are also important for ecology.
- Color is a feature of visible light only. There is no color for invisible light.
- Nevertheless, the idea of monochromatic light can be applied to the invisible light, too. It simply means "ligh with a single wavelength".




## Three optics

When we talk about how light behaves, we usually use one of three different approaches: geometrical optics, wave optics, or quantum optics. In geometrical optics, we think of light as traveling in straight lines. In wave optics, we treat light as a wave that spreads out in space. In quantum optics, we treat light as a group of photons.

You might wonder why we need three different ways to describe the same thing. The reason is that it is related to the idea of "modeling," which is a key concept in physics. Natural phenomena are often too complex for us to describe perfectly, so we simplify them by focusing on the most important features and ignoring the rest.

For example, when we talk about a rainbow in the sky, we usually use geometrical optics. This approach assumes that light travels in straight lines and bends when it passes a boundary between air and water. We can calculate its angle using the well known value of "refractive index" of each wavelength of the light in the water. 

However, if we want to understand how the refractive index is determined, we need to use wave optics. Wave optics is based on something called the "Maxwell equations," which are the fundamental rules of electromagnetism. This theory uses two key properties: "permittivity" and "permeability," which describe electromagnetic feature of materials (like water in a rainbow). If you have enough math skills, you can work with the Maxwell equations and create "wave equations" that explain how light behaves as a wave. These wave equations show how the refractive index is related to permittivity and permeability.

You might then ask, "How are permittivity and permeability determined?" They are actually derived using quantum optics. Quantum optics explains how light interacts with tiny particles like a molecule, an atom, and an electron, each of which is known as a "quantum."

The three types of optics—geometrical, wave, and quantum—overlap, but they use different ways to describe light. In other words, they are different models of light. Geometrical optics is useful for tracing how light travels through space involving reflection, absorption, and transmission at the boundary or inside of big objects. However, it is not accurate if the light's wavelength is as large as the the objects (or the objects are as small as the wavelength of light). In those cases, we need wave optics, which is more complex because it involves tracking the light wave’s "phase" (we'll learn about that later).

The geometrical optics is essentially a kind of simplification and apptoximation of wave optics. Therefore, essentially, there are (not three but) two perspectives of light: electromagnetic wave and photon. 

The quantum optics is necessary if we deeply analyze the interaction of the light with materials involving the transition of energy and/or angular momentum, such as "thermal radiation", "Rayleigh scattering", "Mie scattering", "Raman scattering", "fluorescence", and so on.


## Generation of light
How does light happen? According to the wave optics, light happens when an electric charge moves with non-zero
acceleration. For example, if an electron is moving around a circle, it emits light. It is the principle of "synchrotron radiation". According to the quantum optics, a photon (the element of light in the quantum mechanics' perspective) happens when a system change its energy from a level to some lower level.


## Thermal radiation
In ecology, The most important process of light generation is perhaps "thermal radiation" (or "thermal emission"). It says, depending on its temperature, every object emits light. For example, because the sun is an object, it emits light depending on its temperaturre. It is the sunlight. 

You may know temperature of an object is an index of mean energy of particles which make up the object. Therefore, if an object is hot, the particles are in high-energy states. They may sometimes transit to lower states, yielding photons. It is a rough summary of the thermal radiation. You should know three formula about it. The first one is Planck's low. It is the most fundamental law of thermal radiation:

$B(\lambda, T) = \frac{2 h c^2}{\lambda^5} \frac{1}{\text{exp}\Bigl(\frac{h c}{\lambda k_B T}\Bigr) - 1}$

where:
$B(\lambda, T)$ is the spectral radiance (power per unit area per unit wavelength per unit solid angle) at wavelength $\lambda$ and temperature $T$; $h$ is Planck's constant ($6.626 \times 10^{-34}$ J$\cdot$s); $c$ is the speed of light in a vacuum ($3.00 \times 10^8$ m/s); $\lambda$ is the wavelength of the photon; $k_B$ is the Boltzmann constant ($1.381 \times 10^{-23}$ J/K); $T$ is the absolute temperature; $e$ is the base of the natural logarithm.
    
Because energy of the photon is inversely proportional to the wavelength, 


## Polarization

## Refraction

量子的なphotonとレイトレーシングのphotonは違う

## Flux

## PAR


