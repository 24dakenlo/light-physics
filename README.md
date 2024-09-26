# light-physics

## Two aspects of light

We see and experience light every day; it’s always around us and helps us see things. But understanding what light really is can be quite complex and needs a lot of advanced science. In this chapter, we will explain the most important ideas about light that we need for studying radiation ecology, without getting too technical.

## Light is electromagnetic wave

Light can be thought of in two main ways. One way is as a "wave in the electromagnetic field." In science, this kind of wave is called an "electromagnetic wave" or "radiation." In everyday life, we might call it "light" if its wavelength is small, or "radio wave" if the wavelength is long. Actually, light is basically the same as the radio waves used in TVs, radios, and cell phones except for the difference in the wavelength.

So, what is the "electromagnetic field"? It is a basic feature of space that includes both an "electric field" and a "magnetic field." No one knows exactly why space has these features, but they exist. The electric field and the magnetic field exert forces on electrically charged particles such as electrons. The force from electric field is independent of the particle's velocity, whereas the force from magnetic field depends on the particle's velocity. More precisely, this relationship is described by the equation:

${\bf F} = q {\bf E} + q {\bf v} \times {\bf B}$    (1.1)

where, ${\bf F}$ is the force on the particle, ${\bf E}$ is the electric field, ${\bf B}$ is the magnetic flux density (an expression of magnetic field), $q$ is the electric charge of the particle, and ${\bf v}$ is the velocity of the particle. The symbol $\times$ means "vector product" which you can find its definition and meaning in a mathematics textbook. This equation is the fundamental fact which defines the two fields, so that we do not need to worry about why they work this way. 

## Light is photons

Another way to think about light is as a "particle produced by the electromagnetic field." The particle is called "photon". Unlike particles we usually think of, like tiny bits of dust, a photon is a much more abstract concept. It is not a normal particle but a special kind of object known as a "quantum." It is an idea of "quantum physics", which mainly treats objects too small to be treated by the physics of our daily life (so called Newtonian dynamics). 

The main idea in quantum physics is that properties such as energy, momentum, and angular momentum are impossible to determine in many cases. Instead, they are described by something called a "linear operator." The value of these properties is not definite unless the system is in a special state called an "eigenstate," where the value is equal to something called the "eigenvalue."

In case of the electromagnetic field's energy, the eigenvalue of its "liner operator" (called "Hamiltonian operator") is related to a non-negative integer $n$. We understand this integer $n$ as the number of photons. In other words, we recognize the eigen state of electromagnetic field's energy as "there are $n$ photons in the space". 

You may feel it is too abstract to understand, but it's ok. It's too much for human's intelligence to imagine a perfect picture of a photon. In many cases you may imagine them as tiny balls, but you should remember that sometimes this imagination is invalid. It's enough.

## Principle of superposition

Regardless of the aspect, ligh has a very important and useful property called "principle of superposition". It is a general idea which can be applied to many phenomena other than light, but we only mention about light here. The "principle of superposition" says "light can be considered as a superposition of many other lights". "Superposition" is a technical word in physics. It is like "combination" or "mixture". Let's look at an example. 

We imagine several different light waves existing in a same space. We will call electric field of the light waves as ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$. ${\bf E}_i$ describes electric field produced by the $i$-th wave. ${\bf E}_i$ is a function of time and place. Then a new light wave can be created by combining (superpositioning) these waves like this:

${\bf E} = a_1 {\bf E}_1 + a_2 {\bf E}_2 + ... + a_n {\bf E}_n$

Here, ${\bf E}$ is (the electric field of) the new light wave, and it is made up of the original waves ${\bf E}_1$, ${\bf E}_2$, …, ${\bf E}_n$, with each wave multiplied by a certain number (called a scalar) $a_1, a_2,…, a_n$. This form (multiplying things by scalars and summing up them) is exactly called "superposition" in physics, or "linear combination" in mathematics. If you learn the fundamental theories of light, you would find that the any linear combination of lights also satisfies the theory. It is the reason why this principle is valid for light.


## Wave is superposition of sinusoidal waves.

For the moment, let's consider light as a wave. The most physics textbooks mention "sinusoidal wave", which is described by the trigonometric functions: cos⁡(x) and sin(x). These functions repeat the same "up and down" pattern over and over again, meaning they are "periodic."

(figure of sinusoidal wave)

However, sinusoidal waves are just one type of waves. A wave is not have to be sinusoidal. Any patterns that moves through space can be a wave. The "pattern" can be mostly any shapes you can imagine, like a pulse, a bell shape, or sinusoidal. For instance, a flash light is like a pulse pattern moving through space. 

But still, sinusoidal wave concepts are useful enough to describe and understand light waves. Why? Because sinusoidal light wave can be so simple that its treatment is easy and straightforward. Moreover, by using the afforementioned "principle of superposition", we can describe any pattern of light waves by superposition of sinusoidal waves. And surprisingly, mathematicians have proved that virtually any shapes of waves can be described in this way.


## Fourier analysis and Spectrum

This idea is called "Fourier analysis". Fourier analysis is creating a wave (or decomposing a wave) by superposition of sinusoidal waves with various wavelength. 
Therefore, the main target of physics of light can be sinusoidal lights or their superposition. By taking advantages of this idea, you may imagine sinusoidal pattern in many stories about light. If you need to consider more complicated cases, you can imagine the equation of superposition using sinusoidal lights as ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$ with various wavelength. Then what matters is the coefficients $a_1, a_2, ... a_n$ which tell us the contribution of each wavelength of sibnusoidal light wave. They describe the amplitude of each sinusoidal wave. In many cases we are interested in their squared values because the energy of light is proportional to the square of its amplitude. The graph of the wavelength (x-axis) and square of the amplitudes of the sinusoidal waves with that wavelength is called a "spectrum." 

The spectrum is a very common way of describing phenomena of light. For instance, the spectrum of the sunlight is as follows (Figure):

We can see the sunlight consists of various wavelength of sinuspidal lights. Particularly, the graph has a peak in between 400 nm to 700 nm. It means that a big portion of energy of the sunlight comes from the sinusoidal waves with wavelength in between 400 nm and 700 nm. This category of light is called "visible light" because our human eyes can sense them. Coincidentally, they are "photosynthetically active radiation" which activates photosynthesys in many of the terrestrial plants. 

## Color of light

The color sense of human's vision is essentially related to the spectrum. In short, if a spectrum of light is given, we can predict its color. How? The human's eyes contain three 

The human's eyes have three different types of color-sensing cells called "cones". The brain recognizes the signals from these three types of cones, namely, "S-cones", "M-cones", and "L-cones", as blue color, green color, and red color, respectively. The intensity of the response of each type of cone depends on the light's spectrum: If the dominant wavelength are 400 nm in the spectrum, the S-cones' response is big and other cones' response is small, resulting in the recognition of blue by the brain. If the light's spectrum consists of multiple peaks or broad range of wavelength, all the S-, M-, and L-cones responds differently and the color is a mixture of blue, green, and red, resulting in a huge variation of possible colors. 

The human's vision takes place in response to the light called "visible light", whose wavelength is in between about 400 nm and about 700 nm. Our eyes cannot detect light whose wavelength is outside this range. It is because the cones in human's eyes do not respond to such light. Therefore, if some animals have different types of cones from human, they may be able to see light which is invisible for human. In fact, birds and some insects have cones which respond to light shorter that our visible light. 

I explained that a spectrum decides color of the light. Interestingly, the reverse story is invalid. Namely, a color does not decide lights' spectrum. In other words, lights with different spectrum can have a same color. Let's understand it by an example: suppose a light with a spectrum of double peaks at 550 nm (stimulating M-cones) and 680 nm (stimulating L-cones). Then the color is a mixture of green (response by M-cones) and red (response by L-cones), which is yellow. On the other hand, suppose a light with a single peak around 610 nm. To some extent, both M-cones and L-cones repond to this wavelength, resulting in the the color of a mixture of green and red, which is yellow which is the same as the previous example. 

Now you understand the necessity and utility of considering sinusoidal light. In other word, light with a certain single wavelength. Such light is called "monochromatic light". The word "monochromatic" consists of "mono" meaning "single" and "chrome" meaning "color". 

Quantum features of a photon

Suppose we consider a monochromatic light 
The most important fact of photons is relation between the energy $E$, frequency $\nu$, wavelength $\lambda$,  of a single photon $E$ is 


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

If an object's temperature is high, the constituent particles of the objects are in high-energy states. They may sometimes transit to lower states, yielding photons. It is the source of the thermal radiation. In case of 

Because energy of the photon is inversely proportional to the wavelength, 


## Polarization

## Refraction





