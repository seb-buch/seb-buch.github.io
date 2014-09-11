---
title: "Development of analytical tools"
category: research_theme
type: development
illustration: "analytical-tools.png"
simple_id: "development"
---

When dealing with <abbr title="Molecular Dynamics">MD</abbr> simulations, data analysis can represent a quite important part of the work.
Time required to perform the analysis of a <abbr title="Molecular Dynamics">MD</abbr> trajectory can even be longer than the time taken to create the trajectory.
Because a <abbr title="Molecular Dynamics">MD</abbr> trajectory is, after all, just raw atom coordinates with bonuses (energies, pressure, temperatures...), it is unlikely that it natively contains what is usually wanted (distance, orientation...).
This is why the main difficulty in <abbr title="Molecular Dynamics">MD</abbr> data analysis is often to build, from the trajectory, the observable that is actually needed.

Unfortunately, there is no real standard software available to perform this task, this is why people usually rely on scripts/tools developed with a specific goal in mind.
Because I am no different from other, I also develop tools to treat data from <abbr title="Molecular Dynamics">MD</abbr> trajectories (as well as from <abbr title="Nuclear Magnetic Resonance">NMR</abbr>).
And because I am also a good advocate of Open Source Software in science, I also make these tools available (see the <a href="{{ site.url }}/tools">tools</a> section).

