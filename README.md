# light-physics

## Two aspects of light

We see and experience light every day; it’s always around us and helps us see things. But understanding what light really is can be quite complex and needs a lot of advanced science. In this chapter, we will explain the most important ideas about light that we need for studying radiation ecology, without getting too technical.

## Light is electromagnetic wave

Light can be thought of in two main ways. One way is as a "wave in the electromagnetic field." In science, this kind of wave is called an "electromagnetic wave" or "radiation." In everyday life, we might call it "light" if its wavelength is small, or "radio wave" if the wavelength is long. Actually, light is basically the same as the radio waves used in TVs, radios, and cell phones except for the difference in the wavelength.

So, what is the "electromagnetic field"? It is a basic feature of space that includes both an "electric field" and a "magnetic field." No one knows exactly why space has these features, but they exist. The electric field and the magnetic field exert forces on electrically charged particles such as electrons. The force from electric field is independent of the particle's velocity, whereas the force from magnetic field depends on the particle's velocity. More precisely, this relationship is described by the equation:

${\bf F} = q {\bf E} + q {\bf v} \times {\bf B}$

where, ${\bf F}$ is the force on the particle, ${\bf E}$ is the electric field, ${\bf B}$ is the magnetic flux density (an expression of magnetic field), $q$ is the electric charge of the particle, and ${\bf v}$ is the velocity of the particle. The symbol "$\times$x" means "vector product" which you can find its definition and meaning in a mathematics textbook. This equation is the fundamental fact which defines the two fields, so that we do not need to worry about why they work this way. 

## Light is photons

Another way to think about light is as a "particle produced by the electromagnetic field." The particle is called "photon". Unlike particles we usually think of, like tiny bits of dust, a photon is a much more abstract concept. It is not a normal particle but a special kind of object known as a "quantum." It is an idea of "quantum physics", which mainly treats objects too small to be treated by the physics of our daily life (so called Newtonian dynamics). 

The main idea in quantum physics is that properties such as energy, momentum, and angular momentum are impossible to determine in many cases. Instead, they are described by something called a "linear operator." The value of these properties is not definite unless the system is in a special state called an "eigenstate," where the value is equal to something called the "eigenvalue."

In case of the electromagnetic field's energy, the eigenvalue of its "liner operator" (called "Hamiltonian operator") is related to a non-negative integer n. We understand this integer n as the number of photons. In other words, we recognize the eigen state of electromagnetic field's energy as "there are n photons in the space". 

You may feel it's too abstract to understand, but it's ok. It's too much for human's intelligence to imagine a perfect picture of a photon. In many cases you may imagine them as tiny balls, but you should remember that sometimes this imagination is invalid. It's enough.


## Principle of superposition

Regardless of the aspect, ligh has a very important property called "principle of superposition". It is a general idea which can be applied to many phenomena other than light, but we only mention about light here. The "principle of superposition" says "every light is considered as a superposition of many other lights". The reason of validity of this principle stands from "linearity" of the fundamental theory of light (so called Maxwell equation or the quantum physics). "Superposition" is a technical word in physics. It is like "combination" or "mixture". Let's look at an example. 

We imagine several different light waves existing in a same space. We will call electric field of the light waves as ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$. ${\bf E}_i$ describes electric field produced by the $i$-th wave. ${\bf E}_i$ is a function of time and place. Then a new light wave can be created by combining (superpositioning) these waves like this:

${\bf E} = a_1 {\bf E}_1 + a_2 {\bf E}_2 + ... + a_n {\bf E}_n$

Here, ${\bf E}$ is (the electric field of) the new light wave, and it is made up of the original waves ${\bf E}_1$, ${\bf E}_2$, …, ${\bf E}_n$, with each wave multiplied by a certain number (called a scalar) a1, a2,…, an. This form (multiplying things by scalars and summing up them) is exactly called "superposition" in physics, or "linear combination" in mathematics. 


## Wave is superposition of sinusoidal waves.

For the moment, let's consider light as a type of wave. When it comes to wave, most physics textbooks mention "sinusoidal wave", which is described by the trigonometric functions: cos⁡(x) and sin(x). These functions repeat the same "up and down" pattern over and over again, meaning they are "periodic."

(figure of sinusoidal wave)

However, sinusoidal waves are just one type of waves. There are various wave patterns which are not sinusoidal. A wave is a pattern that moves through space. The "pattern" can be mostly any shapes you can imagine, like a pulse, a bell shape, or sinusoidal. For light, a flash of light is like a pulse pattern of the electromagnetic field moving through space. 

But still, sinusoidal wave concepts are useful enough to describe and understand light waves. Why? Because of two important concepts: "principle of superposition" and "Fourier analysis" which we learn from now on.



Because we can choose any wave patterns for ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$ for this equation, we can pick sinusoidal wave patterns with different wavelength for ${\bf E}_1, {\bf E}_2, {\bf E}_3,…, {\bf E}_n$. This is the idea of "Fourier analysis". In other words, Fourier analysis is creating a wave (or decomposing a wave) by superposition of sinusoidal waves with various wavelength. The magic of this idea is, virtually any shapes of waves can be described in this way. It is too much to prove its reason here (Please refer to a mathematics textbook if you are interested).

Therefore, once we are successful to get understanding and descrption and prediction of sinusoidal light waves, we can use them for arbitrary patterns of light. Then the scalars $a_1, a_2, ... a_n$ tell us the contribution of each wavelength of sibnusoidal light wave. This is called a "spectrum." 


## Three optics

When we talk about how light behaves, we usually use one of three approaches: geometrical optics, wave optics, or quantum optics. In geometrical optics, we think of light as traveling in straight lines. In wave optics, we treat light as a wave that spreads out in space. In quantum optics, we look at light as a group of photons.

They are different way of describing light. You might wonder why we need three different ways to describe the same thing. The reason is that it’s related to the idea of "modeling," which is a key concept in physics. Natural phenomena are often too complex for us to understand perfectly, so we simplify them by focusing on the most important features and ignoring the rest.

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





