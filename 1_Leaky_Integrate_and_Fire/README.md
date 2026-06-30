### 🧠 The Leaky Integrate-and-Fire (LIF) Model

To read about this model in full detail, go check out this link: [Neuronal Dynamics Textbook (EPFL)](https://neuronaldynamics.epfl.ch/online/Ch1.S3.html).

In short, this is one of many neuron models out there where we try to understand the brain through computational techniques. The LIF model is a simplified spiking neuron model that describes neural activity at the level of membrane potential dynamics and spike timing. 

By far, this is the easiest neuron model available. It treats the cell membrane as a capacitor and the passive leak channels (where ions naturally flow out at rest) as a resistor to mathematically describe how neurons generate electrical signals. It literally strips away all the complexities of biological neurons, things like multi-dendrite networks, complex refractory periods, and active, opening-and-closing ion channels. 

What this model essentially asks is:  
**If we ignore all the messy mechanics of active ion channels, can we predict the amount of current that will flow inside the cell membrane versus the equivalent that leaks out?** This calculation lets us predict the exact value of input current that will cause the voltage to reach its threshold, resulting in the neuron firing!

The resource listed above also walks through the beautiful derivation of the model's equation, so definitely check it out if you're interested.

Historically, this whole integrate‑and‑fire concept was first introduced by Louis Lapicque way back in 1907, making it one of the earliest models of neuronal firing.
