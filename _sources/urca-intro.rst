*********
Lab Goals
*********

Our goal is to model nuclear processes in an accreting O/Ne white dwarf to understand
temporal evolution (and ultimately whether the white dwarf can explode).

We need to understand some concepts from astronomy:

* Electron degeneracy and the equation of state
* The structure of white dwarfs
* Nuclear reactions, including strong-mediated and weak-interactions (like electron-capture and $\beta$-decay).

We'll start with a framing of the problem and then discuss the concepts.

Urca intro
==========

We will consider the competition of different nuclear processes.  For weak interactions, we have:

* Electron-capture: a nucleus captures an electron, converting a proton to a neutron.
* $\beta$-decay: a neutron in a nucleus decays into a proton + electron

Each of these processes emits a neutrino, which carries energy out of the star---this can
lead to cooling.

The Urca process is when the electron-capture and $\beta$-decay competes, converting a nucleus back and forth,
and robbing the star of energy.

The high densities inside a white dwarf can inhibit these processes, so we need to understand
how electrons behave at white dwarf densities.

.. tip::

   Why is it called Urca?

   Gamow and Schenberg named it after the `Cassino da Urca <https://en.wikipedia.org/wiki/Urca_Casino>`_ in Urca, Rio
   de Janeiro.

      the Urca Process results in a rapid disappearance of thermal
      energy from the interior of a star, similar to the rapid
      disappearance of money from the pockets of the gamblers on the
      Casino de Urca.


Environments where Urca is at play
==================================

We will focus on cooling in massive O/Ne WDs.  Some background (and inspiration
for these labs) can be found in:

* `The importance of Urca-process cooling in accreting ONe white
  dwarfs <https://academic.oup.com/mnras/article/472/3/3390/4093085>`_
  (Schwab et al. 2017)

  This is the main inspiration for these labs

* `The Formation of Electron-capture Supernovae: A Review <https://arxiv.org/abs/2509.25915v2>`_ (Wang et al. 2025)

  This discusses electron-capture supernova, where Urca in the O/Ne core can also be important.



Beyond the setup in this lab, we can encounter Urca in other contexts:

* Convective Urca in massive C/O WDs (possible SN Ia progenitors?)
  See:

  * `The nuclear diversity of Type Ia supernova explosions
    <https://ui.adsabs.harvard.edu/abs/2008NewAR..52..381P/abstract>`_
    (Podsiadlowski et al. 2008)

  * `Exploring the Carbon Simmering Phase: Reaction Rates, Mixing, and the Convective Urca Process <https://iopscience.iop.org/article/10.3847/1538-4357/aa9a3c>`_ (Schwab et al. 2017)


  * `Some Thoughts on the Convective Urca Process <https://arxiv.org/abs/2111.00132>`_ (Schwab 2021)

  * `3D Convective Urca Process in a Simmering White Dwarf <https://iopscience.iop.org/article/10.3847/1538-4357/ad9bb0>`_ (Boyd et al. 2025)

* Neutron star cooling

  * `Direct URCA process in neutron stars <https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.66.2701>`_ (Lattimer et al. 1991)

  * `Urca Cooling in Neutron Star Crusts and Oceans: Effects of Nuclear Excitations <https://arxiv.org/abs/2102.06010>`_ (Wang et al. 2021)


