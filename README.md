CNS 2021 Allen Institute Tutorials
==================================

The Allen Institute recently released multiple free resources focusing on the structure and function of brain circuits. These resources include data, associated analysis software, and models integrating the data to enable bio-realistic simulations. They provide a powerful ecosystem for a new generation of analyses, theory, and modeling in computational neuroscience.

We will introduce several of these resources in a series of 1-hour sessions. Each session will include a scientific introduction for the resource and an online demonstration of accessing and analyzing the data.


Schedule
--------

**Wednesday, June 30, 2021**

    11:30 am – 11:45 am EST - Introduction
    11:45 am – 12:45 pm EST - Synaptic Physiology (Luke Campagnola)
    12:45 pm – 1:00 pm EST  - Break
    1:00 pm – 2:00 pm EST   - Visual Coding 2-photon (Saskia de Vries)
    2:00 pm – 3:00 pm EST   - Visual Coding Neuropixels (Josh Siegle)

**Thursday, July 1, 2021**

    11:30 am – 11:45 am EST - Introduction
    11:45 am – 12:45 pm EST - PatchSeq (Nathan Gouwens)
    12:45 pm – 1:00 pm EST  - Break
    1:00 pm – 2:00 pm EST   - Visual Behavior (Alex Piet)
    2:00 pm – 3:00 pm EST   - Bio-realistic model of the mouse primary visual cortex (Anton Arkhipov and Kael Dai)


Resources Covered
-----------------

- [**PatchSeq Characterization of Cell Types**](https://portal.brain-map.org/explore/classes/multimodal-characterization) [1]. This dataset describes >4,000 cells from the mouse and human cortex. Intrinsic electrophysiological properties, morphologies, and transcriptomic profiles are measured from the same neurons, and types are assigned to those cells based on different properties.
- [**Synaptic Physiology**](http://portal.brain-map.org/explore/connectivity/synaptic-physiology) [2]. This dataset describes >1,500 synapses from mouse and human cortex. Measured properties include connectivity, synaptic strength, variance, and short-term plasticity. Cells are classified by their layer, transgenic markers, morphology, and intrinsic physiological features, allowing comparisons between many cell subclasses.
- [**Visual Coding 2-photon**](https://portal.brain-map.org/explore/circuits/visual-coding-2p) [3]. This dataset contains 2-photon calcium imaging data that surveys visual responses across 6 cortical areas, 4 cortical layers, and 14 transgenically defined cell populations. Activity was imaged in awake mice in response to a variety of stimuli, while tracking the mouse’s running speed and pupil size in each session.
- [**Visual Coding Neuropixels**](https://portal.brain-map.org/explore/circuits/visual-coding-neuropixels) [4]. This dataset includes spiking activity from neurons recorded across more than dozen brain regions while mice viewed diverse visual stimuli. Each experiment includes spikes from hundreds of simultaneously recorded neurons, as well as local field potentials.
- [**Visual Behavior**](https://portal.brain-map.org/explore/circuits/visual-behavior-2p) [5]. This dataset contains 2-photon calcium imaging recordings from transgenically defined cell populations across two cortical regions while mice perform a visual change detection task. Each experiment includes the activity of individual neurons and behavioral data.
- [**Bio-realistic model of the mouse primary visual cortex**](https://portal.brain-map.org/explore/models/mv1-all-layers) [6]. The model integrates data from the Allen Institute and the literature on composition, connectivity, and in vivo activity of cortical circuits.


Software Tools
--------------

- Allen SDK: https://allensdk.readthedocs.io/en/latest/
- Brain Modeling ToolKit (BMTK): https://alleninstitute.github.io/bmtk/
- SONATA: https://github.com/AllenInstitute/sonata


Background Reading
------------------

1. Gouwens NW, Sorensen SA, Baftizadeh F, Budzillo A, Lee BR, Jarsky T, et al. Integrated Morphoelectric and Transcriptomic Classification of Cortical GABAergic Cells. Cell. 2020;183: 935-953.e19. doi:https://doi.org/10.1016/j.cell.2020.09.057
2. Campagnola L, Seeman SC, Chartrand T, Kim L, Hoggarth A, Gamlin C, et al. Connectivity and Synaptic Physiology in the Mouse and Human Neocortex. bioRxiv. 2021; 2021.03.31.437553. doi:10.1101/2021.03.31.437553
3. de Vries SEJ, Lecoq JA, Buice MA, Groblewski PA, Ocker GK, Oliver M, et al. A large-scale standardized physiological survey reveals functional organization of the mouse visual cortex. Nat Neurosci. 2020;23: 138–151. doi:10.1038/s41593-019-0550-9
4. Siegle JH, Jia X, Durand S, Gale S, Bennett C, Graddis N, et al. Survey of spiking in the mouse visual system reveals functional hierarchy. Nature. 2021. doi:10.1038/s41586-020-03171-x
5. Garrett M, Manavi S, Roll K, Ollerenshaw DR, Groblewski PA, Ponvert ND, et al. Experience shapes activity dynamics and stimulus coding of VIP inhibitory cells. Elife. 2020;9. doi:10.7554/eLife.50340
6. Billeh YN, Cai B, Gratiy SL, Dai K, Iyer R, Gouwens NW, et al. Systematic Integration of Structural and Functional Data into Multi-scale Models of Mouse Primary Visual Cortex. Neuron. 2020;106: 388-403.e18. doi:10.1016/j.neuron.2020.01.040


Support for this Repository
---------------------------

This repository is provided to the community as-is. Users are welcome to submit issues, but please do not expect an active response. For support in using these resources, we recommend posting to the [Allen Institute Community Forum](https://community.brain-map.org/).
