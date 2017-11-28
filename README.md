# PNPy-PaperFigures

The Python scripts in this repository can be used to generate figures illustrating the capabilities of the Peripheral Nerve simulator for Python: [PNPy](https://github.com/caaarl/PNPy).

This scientific software is released under the GNU Public License GPLv3.

## fig3: Extrapolate myelinated axon parameters

Extrapolation of parameters of the myelinated axon model of McIntyre et al. 2002 [1].

## fig6: Membrane currents

Example current time course of a myelinated and an unmyelinated axon.

## fig7: Potential profiles

Potential profile caused by a current point source in a homogeneous medium, a nerve in saline and a nerve in a cuff electrode.

## fig8A: Action potentials

Single fibre action potential (SFAP) of a myelinated and an unmyelinated fibre in the three different media.

## fig8B: Action potential amplitudes

Amplitude of SFAPs over diameter for both axon types in all three media. `...calculation`: simulate and save the SFAPs in a file to disk. `...loading`: load the simulated SFAPs and plot the curves.

## fig9: Cuff length influence

Influence of cuff length on SFAP amplitude for both axon types. `...calculation`: simulate and save the SFAPs in a file to disk. `...loading`: load the simulated SFAPs and plot the curves.

## fig10: Compound action potential

Compute the compound action potential (CAP) of a stimulated rat vagus nerve. Takes long to calculate. The bundle length `electrodeDistance` and the number of axons `nAxons` can be reduced to speed things up.

## fig11: Spectrum of the compound action potential

Spectrum of the CAP computed in figure 10 for both axon types compared to an experimental recording.

## fig12AB: Direction change distribution of axons

Matlab scripts to generate direction change distributions observed in mouse vagus and sciatic nerves and distributions from Gaussian and uniform distributions as an input to the axon placing algorithm implemented in PNPy.

## fig12C: Example axons in PNPy

Example axons as generated by PNPy.

## fig14: Recording from tortuous axons

SFAPs from tortuous axons are generated and compared in terms of similarity.

## fig15: Stimulation of tortuous axons

Activation of axons in an extracellularly stimulated nerve at different degrees of tortuosity is computed and displayed. `...calculation`: a dictionary of activation ratios is generated and saved. `...loading`:  a previously generated dictionary can be selected and the activation is displayed over stimulation current amplitudes and degrees of tortuosity.

# References

[1] McIntyre, C C, A G Richardson, and W M Grill (2002). “Modeling the excitability of mammalian nerve fibers: Influence of afterpotentials on the recovery cycle.” Journal of Neurophysiology 87.2, pp. 995–1006.




