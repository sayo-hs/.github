# Sayo Project

The Sayo Project aims to promote the use of the effect system in Haskell by attempting to address the current challenges faced in Haskell's effect system landscape.

This project is founded on the notion of bifurcating the effect system into two realms: the *Effect Space* and the *Handler Space*. The Effect Space is envisioned as a domain that houses standardized interfaces upon which consensus is reached among the community. In contrast, the Handler Space is seen as a domain housing entities akin to handlers and interpreters, and ultimately, concrete software implementations that adhere to the interfaces of the Effect Space.

* **Objective 1 - Exploring ways to improve interoperability among the myriad Haskell effect system libraries**

    To curb the proliferation of various definitions within the Effect Space, we advocate for the adoption of the classy-effects protocols (CEPs). We are also developing software to simplify adherence to these protocols. For more details, please refer to the [classy-effects repository](https://github.com/sayo-hs/classy-effects).

* **Objective 2 - Research on the 'Heftia' approach for next-gen Extensible Effect aimed at enhancing the treatment of higher-order effects**

    To breathe new life into the challenges of handling higher-order effects in the current Haskell effect system,
    we are conducting research and development on an effect-handler system based on the Heftia approach. This method is inspired by the [Hefty Algebras (Casper et al., 2023)](https://doi.org/10.1145/3571255). For a detailed exploration, visit the [Heftia repository](https://github.com/sayo-hs/heftia).
