---
title: "Combining experiments and MD simulations"
category: research_theme
type: analysis
illustration: "md-nmr-combination.png"
simple_id: "combining"
---

Because they describe a system at an (more or less) atomic level, <abbr title="Molecular Dynamics">MD</abbr> simulations are perfectly suited to
provide another perspective compared to NMR or other experimental method which provides a much more averaged (both timely and spacially) description.
Obviously, in the context of molecule/membrane interaction (see <a href="#interactions">above</a>), this can be really helpful for a better understanding and/or confirmations.

All <abbr title="Molecular Dynamics">MD</abbr> simulations rely on forcefields to generate the forces that will be integrated to create the molecular motions.
These forcefields are generally validated by comparing the results from the <abbr title="Molecular Dynamics">MD</abbr> simulations with an experimental parameter.
In the case of forcefields dedicated to lipids, the experimental parameters taken into account are typically derived from thermodynamics (enthalpies, free energies...) or from structural properties (order parameters, thickness) of pure lipid bilayers.

The goal of the combination/comparison of experiments with simulations is then double:
<ol>
    <li>
        to provide further information to experimental data.
    </li>
    <li>
        to provide experimental data to ease the validation of the forcefields.
    </li>
</ol>
