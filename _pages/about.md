---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a postdoctoral research fellow at the Computational and Biological Learning Lab (CBL) at the Department of Engineering of the University of Cambridge.

My research focuses on how neural circuits give rise to complex cognitive functions, and what causes their impairment in neurological diseases like Alzheimer's and Amblyopia (Lazy Eye). I use theoretical and computational methods to investigate the computational principles of biological neural networks.
I am especially interested in networks that contain inhibitory neurons — a neuron class that suppresses network activity and constitutes >30% of all neurons in the human brain. Although the importance of inhibitory neurons to stabilise excitatory neural activity has long been acknowledged, their fundamental contribution to network *computations* only recently shifted into focus.
Previous work mostly considered static networks and did not consider the dynamic nature of synaptic connections that adapt to the statistics of the sensory input.
During my Ph.D., I showed how networks of excitatory and inhibitory neurons with rich computational functions can emerge from realistic plasticity mechanisms while the statistical structure of their inputs became reflected in their recurrent connectivity.

Importantly, these models only considered computations in the neocortex, a brain region involved in the encoding of sensory stimuli. In my current research, I work on generalising these network models to brain regions of the hippocampus that are involved in the processing of episodic memories.
In the future, a better understanding of these networks will help to understand why we remember some experiences but not others and how memory acquisition can be facilitated or disturbed.

## Projects

“Synapse-type-specific competitive learning forms functional recurrent networks”
— Eckmann & Gjorgjieva, 2022, bioRxiv.
------
Computation in neural circuits is based on the interactions between recurrently connected excitatory and inhibitory neurons. Previous work has identified the balance between excitatory and inhibitory currents as a critical requirement for many neural computations, but did not consider how the required synaptic connectivity emerges from biologically plausible plasticity rules. In my research, I developed a learning framework where synapses evolve according to a minimalistic plasticity rule that is stabilized by the competition for a limited supply of synaptic resources. Motivated by the unique protein composition of excitatory and inhibitory synapses, my key assumption is that different synapse types compete for separate resource pools. Using theory and modeling, I analyzed synaptic weight dynamics in fully plastic networks and derived stability conditions that enable their development into functional recurrent circuits. In a single framework, my work explains a wide range of experimental findings, such as the simultaneous development of excitation-inhibition balance and stimulus selectivity, the decorrelation of neural tuning curves and activities, the formation of assembly structures, the emergence of response normalization, and the development of orientation-specific surround suppression. My results demonstrate how neurons can self-organize into functional circuits and provide a foundational understanding of plasticity in recurrent networks.

“Active efficient coding explains the development of binocular vision and its failure in amblyopia”
— Eckmann et al., 2020, PNAS.
======
Brains must operate in an energy-efficient manner. The classic efficient coding hypothesis states that sensory systems achieve this by adapting neural representations to the statistics of sensory input signals. Importantly, however, these
statistics are shaped by the organism’s behavior and how it samples information from
the environment. Therefore, optimal performance requires jointly optimizing neural
representations and behavior, a theory we call active efficient coding (Fig. 1). I tested the plausibility of this theory by proposing a computational model of the development of binocular vision. My model, for the first time, explains the self-calibration of accurate binocular vision under healthy conditions. In the case of refractive errors, however, the model develops into a state reminiscent of amblyopia, a leading cause of vision impairment, and suggests conditions for successful treatment.