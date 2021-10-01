## To helium

### Proton-proton chain reaction

i.e. **making helium.**

1. **Formation of deuterium** (hydrogen-2).
   $$
   \begin{rcases}
   p+p\to{^2_1D}+e^++\nu_e\\
     e^++e^-\to 2\gamma&
   \end{rcases}~{+1.442MeV}
   $$

   - The slow step, because:

     - The protons have to fuse first. This requires a **high temperature** to overcome **Coulomb repulsion**.

       > Interestingly, the temperature required is **lower** than classically predicted: the reason for this is because the protons are so small that **tunnelling** gets involved!

     - A **proton** also has to get converted to a **neutron,** because otherwise they'll just unfuse. This involves the **weak interaction,** and requires quite a bit of **energy.** 

2. **Deuterium fusion:** 
   $$
     {^2_1D}+{^1_1H}\to{^3_2}He+\gamma&+5.493MeV\\
   $$

   - Fast step — the deuterium nucleus barely sticks around. So deuterium is pretty rare.

3. **Formation of helium-4…** somehow. There are several branches, all involving the ${^3_2He}$ you just made. These are the most common reactions, and are pretty much what you'd expect.

   1. Reacting it with more ${^3_2He}$. ($10-14MK$)
      $$
      {^3_2He}+{^3_2He}\to{^4_2He}+2{^1_1H}&+12.859 MeV\\
      $$

   2. Reacting it with **existing** $^4_2He$, and making **lithium.** ($14-23MK$)
      $$
      {^3_2He}+{^4_2He}\to {^7_4Be}+\gamma&+1.59MeV\\
         {^7_4Be}+e^-\to {^7_3Li}^-+\nu_e&+0.861 MeV\\
         {^7_3Li}+{^1_1H}\to 2{^4_2He}&+17.35MeV
      $$

   3. Reacting it with existing $^4_2He$ and making **boron.** ($>23MK$)
      $$
      {^3_2He}+{^4_2He}\to {^7_4Be}+\gamma&+1.59MeV\\
      \begin{rcases}
      {^7_4}Be+{^1_1H}\to {^8_5B}+\gamma\\
      {^8_5B}\to {^8_4Be}+e^++\nu\\
      {^8_4Be}\to 2{^4_2He}
      \end{rcases}&+18.209 MeV
      $$

   4. Reacting it with $^1_1H$. (This one has the highest possible energy, but is also really rare.)
      $$
      {^3_2He}+{^1_1H}\to {^4_2He}+e^++\nu_e&+19.795 MeV\\
      $$

And now you have helium!

What crimes will you commit?

### Carbon-nitrogen-oxygen cycle

i.e. making helium but :sparkles:fancier:sparkles:. This relies on having larger atoms to serve as **catalysts,** continually undergoing **fusion** and **beta decay,** and emitting 4-helium through **alpha decay**.

Overall:
$$
4{^1_1H}+2e^-\to {^4_2He}+7\gamma+2\nu_e&+26.7 MeV\\
{^{12}_6C}\to{^{13}_7N}\to{^{13}_6C}\to {^{14}_7}N\to{^{15}_8O}\to {^{15}_7N}\to{^{12}_6C}\\
$$
Where you can probably see where each proton/electron was inserted.
$$
\begin{align*}
+{^1_1H}&:{^{12}_6C}\boxed\to{^{13}_7N}\to{^{13}_6C}\boxed\to {^{14}_7}N\boxed\to{^{15}_8O}\to {^{15}_7N}\boxed\to{^{12}_6C}\\
+e^-&:{^{12}_6C}\to{^{13}_7N}\boxed\to{^{13}_6C}\to {^{14}_7}N\to{^{15}_8O}\boxed\to {^{15}_7N}\to{^{12}_6C}
\end{align*}
$$
There are several variations of this process:
$$
{^{12}_6C}\to{^{13}_7N}\to{^{13}_6C}\to {^{14}_7}N\to{^{15}_8O}\to \boxed{^{15}_7N}\to{^{12}_6C}\\
$$

- **CNO-II:** a minor branch, continuing from ${^{15}_7}N$: 
  $$
  {^{15}_7}N\to{^{16}_8O}\to{^{17}_9}F\to\boxed{^{17}_8O}\to{^{14}_7N}\to{^{15}_8O}\to{^{15}_7}N
  $$

  - **CNO-III:** a subdominant branch, only in **massive stars,** continuing from $^{17}_8O$:
    $$
    {^{17}_8}O\to{^{18}_9F}\to\boxed{^{18}_8O}\to{^{15}_7}N\to{^{16}_8O}\to{^{17}_9F}\to{^{17}_8}O
    $$

    - **CNO-IV:** continuing further from $^{18}_8O$, of course only in massive stars:
      $$
      {^{18}_8}O\to{^{19}_9F}\to{^{16}_8}O\to{^{17}_9}F\to{^{17}_8}O\to\boxed{^{18}_9F}\to{^{18}_8}O
      $$
      and $^{18}_9F$ can sometimes fuse with $^4_2He$ to start a **sodium-neon** cycle!

## Beyond helium

Anyway, now you've got all this helium. What do you do with it?

### Triple-alpha process

i.e. making **carbon** from **three alpha particles.**

$$
{^4_2He}+{^4_2He}\to {^8_4}Be&-0.0918 MeV\\
$$

Beryllium-8 does *not* like existing, and will decay, unless…
$$
{^8_4Be}+{^4_2He}\to {^{12}_6}C+2\gamma&+7.367 MeV\\
$$
The carbon-12 is created in an **excited resonance state,** and will typically happily decay into three alpha particles. Occasionally ($p=4.13\times 10^{-4}$), though, it simply *returns to its stable form!*

### Alpha ladder

Now you have carbon.

This lets you make a whole host of elements by simply **adding alpha particles**. All of these reactions **release energy!**
$$
{^{12}_6C}\to{^{16}_8O}\to{^{20}_{10}Ne}\to\dots\to{^{52}_{26}Fe}\to{^{56}_{28}Ni}
$$
Remember how you stop at $^{56}_{26}Fe$ because its binding energy per nucleon is highest? *yeah that was a lie.* 

$^{62}_{28}Ni$ is actually **more tightly bound,** but is scarcer as it undergoes **photodisintegration** (emitting a **subatomic particle** upon **excitation**) more readily.

---

There are many more cycles that we won't get into (for example, odd atomic numbers), but note that all these fusion reactions **release energy.** This naturally makes your stars bright. 

Through all these processes, note that **hydrogen nuclei** remain key components — unfortunately, the 'initial material' the star has is finite, and eventually we run out of hydrogen! :(

Now it starts fusing helium, but its days are clearly numbered.