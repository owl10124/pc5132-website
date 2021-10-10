Stars are essentially little element-factories, right? Tiny (okay, maybe $1.99\times 10^{-31}kg$ is *not* tiny…) messes of mostly-hydrogen **plasma,** doing their best to make things that are *not* hydrogen. But, much like the average NUS High student, they're tiny messes with *a lot of issues.*

So — as we would any good student — we dissect them.

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b9/Heat_Transfer_in_Stars-en.svg/2880px-Heat_Transfer_in_Stars-en.svg.png" />

<p style="text-align:center"><small>source: Wikipedia, yet again! By Д.Ильин: vectorization - File:Heat Transfer in Stars.png of www.sun.org, CC0, <a href="https://commons.wikimedia.org/w/index.php?curid=103174661">https://commons.wikimedia.org/w/index.php?curid=103174661</a></small></p>

## Core

The star is *heavy,* and that means **gravity.** Specifically, it's getting crushed inwards by its own weight, much like how students collapse under the weight of expectations. 

As a result, the centre of the star gets **very hot** (haha GPE becomes KE) and **very dense**. Until (in a zone called the **core**) it gets hot and dense enough that **fusion** starts happening! This **releases energy** (mostly thermal???) which creates thermal pressure, **counterbalancing** the gravity. 

> And if fusion *stops,* the centre **loses energy,** and **contracts,** and **heats up,** and **loses more energy,** and bad feedback loops happen and the core collapses and bad things happen.

In the simplest model, we assume the star is steady-state-ish… somehow. The **outward pressure** from within the star must **equal** the inward gravity, much like how students exert pressure on themselves… okay, this analogy's falling apart. (Just like the students–)
$$
\frac{dP}{dr}=-g=-\frac{Gm\rho}{r^2}=-\frac{G\rho\int_0^r4\pi r^2\rho ~dr}{r^2}
$$

This star is in **stable equilibrium** because if the **fusion rate increases,** the core **expands,** so pressure and temperature would **decrease** and the fusion rate decreases again.

## Convection (heat transfer via fluid movement)

So, deep in the star, you have a little parcel of warm gas. It's less dense, so it rises, because that's what warm gas does.

Its new surroundings have **lower pressure and temperature.** (ratio: **temperature gradient**).

- Pressure means the **parcel** expands and cools (dependent on **heat capacity**).
- Temperature means the **surroundings** cool.

Now, **convection** occurs if the parcel is *still* warmer (less dense) than its new surroundings and **rises more.** 

Someone quantified this, actually! The **Schwarzschild criterion** relates the **temperature gradient** to the **pressure gradient.** For convection to **not occur,** we need:
$$
-\frac{dT}{dr}<-\frac1{c_p}\frac{dP}{dr}=\frac g{c_p}
$$
(where $c_p$ is the **heat capacity** of the gas, expanding under **constant pressure**)

> A full derivation may be found [here](https://www.astro.umd.edu/~jph/A320_Convection.pdf) (*not* copying that out) but in essence, we assume that: 
>
> 1. $Q=0$ (the parcel's expansion is **adiabatic**). This means $P_{par}V_{par}^\gamma=P_{par}\rho_{par}^{-\gamma}$ is a **constant**. (Where $\rho=\frac1V=\text{density}$.)
> 2. $P_{par}=P_{surr}$ (**pressure equalises** much faster than the parcel moves). 
>
> ![](/static/blobnt.png)
>
> <p style="text-align:center"><small>source: <a href="https://www.astro.umd.edu/~jph/A320_Convection.pdf">https://www.astro.umd.edu/~jph/A320_Convection.pdf</a> (the derivation mentioned earlier)</small></p>
>
> And we want to show that the **density** of the **parcel** eventually becomes **higher** than that of the **star**. So for the same $-dP$ (pressure decrease), we want to show $-d\rho_{parcel}=-d\rho_{adiabatic}$ (density decrease) is **smaller** than $-d\rho_{star}$.
>
> So we want to take the inequality
> $$
> \left(\frac{dP}{d\rho}\right)_{adiabatic}>\left(\frac{dP}{d\rho}\right)_{star}
> $$
> and express it in terms of $\frac{dP}{dr}$ and $\frac{dT}{dr}$.
>
> Hope you remember your thermodynamics.

Anyway, all that just means that a **steeper temperature gradient** (against **radius**) means **convection** is **more likely.** 

Areas where **convection** is the dominant method of **heat transfer** are called… **convection zones!** 

<small>Properly mathematically modelling stars is hard, though, because turbulence is complicated.</small>

## Radiation (heat transfer via electromagnetic emission)

**Radiation zones** are just zones where **radiation** is **dominant,** instead of convection. (Conduction too, sometimes.)

These zones are typically **very dense** so photons are **absorbed or scattered** quite a lot.

Remember that equation from earlier? In radiation zones, we have a concrete formulation for $\frac{dT}{dr}$:
$$
\frac{dT}{dr}=-\frac{3\kappa\rho L}{(4\pi r^2)(16\sigma_B)T^3}
$$
where ($\kappa,\rho,L$) refer to (**opacity, density** and **luminosity**) respectively.

> How is this derived? To be honest, I haven't the slightest clue, but apparently it involves integrating **Fick's first law** — correlating **diffusive flux** to **concentration gradient** using $J=-D\frac{d\phi}{dx}$. 
>
> Check some [real sources](https://en.wikipedia.org/wiki/Radiation_zone) for actual info please.

## Temperature and luminosity

We can plot stars on a **scatter plot** of **absolute magnitude / luminosity** against **stellar classification / temperature**. 

This graph has been pretty important for the understanding of stellar evolution: the most prominent diagonal (see? there, down there) is known as the **main sequence,** and astute viewers wondered if stars could descend it **over their lifetime.** (Spoiler: yes.)

<img class="noinvert" src="https://upload.wikimedia.org/wikipedia/commons/6/6b/HRDiagram.png" />

<p style="text-align:center"><small>source: how many times must I say Wikipedia? by Richard Powell - The Hertzsprung Russell Diagram, CC BY-SA 2.5, <a href="https://commons.wikimedia.org/w/index.php?curid=1736396">https://commons.wikimedia.org/w/index.php?curid=1736396</a></small></p>


## Stellar nucleosynthesis

is the process happening in stellar **cores** — via which they **release energy,** and in the process create **new atomic nuclei**. **Lighter** elements are made via **nuclear fusion** over stars' main lifetime, while **heavier** ones are generally formed… later.
