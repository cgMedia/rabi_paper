## Reviewer comments

> There are few references in the main text connected to derivation of the equations. For instance, where does eq3 come from? I think that I get it but a brief explanation or a reference would be nice.

1. Add reference to Dyadic Green's Function (Rothwell's book)
2. Explain (or detail, possibly in appendix) Fourier transform procedure

> There are only a few references to collective effects in QD or related systems [4-6], but none to quantum dot super and subradiance which I feel is closely related. This is only mentioned in the conclusions, while I feel it should be discussed as prior art in the introduction. In particular regarding studies with a focus on quantum dots ([7, 27, 28] are historic papers). One example: scheibner2007, Superradiance of quantum dots, http://dx.doi.org/10.1038/nphys494 This is heavily cited and many multi-particle simulations have been done motivated by this, such as this for 2-4k QDs ("first hit"): https://journals.aps.org/pra/pdf/10.1103/PhysRevA.78.051801 I would also find it important if the authors could compare their results to some published before, if it is possible!

1. Investigate papers, attempt to uncover phenomena to compare with

> T1 time 10ps. This is very short, I am only aware of similarly short lifetimes under very strong Purcell enhancement. Have the authors chosen this because of computational restrictions?

1. I thought 10ps was typical of these systems
2. Interesting that they think it's due to computational limitations. 10ps is about the maximum time we can simulate and I would imagine you would want a decay time shorter than that. I don't think we chose 10ps for computational reasons, but that might be important going forward.

> The real-world issue of inhomogeneously broadened quantum dot transition energies, dipole orientations, linewidths, decoherence rates, dipole orientations, and consequently also pi pulse areas, is not discussed. Would observation of the proposed effects ever be possible? Note that there might be ways around this, such as cavity enhanced Raman interaction between quantum dots which probably does not require strict resonance condition.

1. Carlo's ballpark; confer with him

> The authors study a ~1ps long optical pulse, but as far as I see in the RWA everything is monochromatic, while a 1ps pulse is not monochromatic. I feel that this should be discussed, probably it is not a problem but I don't know (even more so for the fs time scale in the last figure).

1. No pulse is strictly monochromatic, but the electromagnetics community's conventions are to call it as such if it meets certain width criteria. We can definitely elaborate on why everything works in this regime.

> The effect of nonlocal effects on the population in Fig.2a is very strong. Can the authors compare/comfirm this result by comparing to other studies or experiments?

* See #2.

> Dimensionality: The authors study a 3D geometry with (e.g.) 1024 dots in 6.4e-2 um-3, which means that the dot separation is around
40nm. This might be doable but I wonder if anything could be seen in 2D, where currently much progress is done regarding narrowing of the inhomogeneous broadening.

1. "The dot separation" -- does this mean average or nearest? Need to check that; if nearest, something is definitely off (they should be far closer than 40nm).
2. 2D is a significant problem with this technique due to the form of the Green's function (no longer a delta function in time). We can certainly arrange dots in planar geometries, however.

> Eqs. 3+5: is the dagger of r^\dagger correct? If so, what does it mean?

1. It's intentional if perhaps unorthodox; it denotes a standard conjugate-transpose though, as the vectors are real, it's only a transpose to signify an outer product.

> About the intriguing isolated outliers in Fig 3+5: can the authors extend their explanation?

1. This depends a lot on what results we can compare with after another lit search. Will re-evaluate this response later.

> Probably it would be good to mention what is means by "polarization" somewhere clearly (==coherences, |rho01|^2).

1. Definitely. Can (and will!) do.


## Additional notes

1. The expression for the corrector in the P/C stuff isn't the best (requires better indexing) and should be fixed.
