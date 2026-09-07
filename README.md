# Fundamental Neuroscience for Neuroimaging

My study notes for the Johns Hopkins *Fundamental Neuroscience for Neuroimaging*
course, written in LaTeX.

📄 **[neuroimaging_notes.pdf](neuroimaging_notes.pdf)**

One notes document covers the whole course, growing as each week is added.
Lecture material for each week lives in its own numbered folder.

## 01 — Structural Neuroanatomy of the Brain

*Module 1 — introduction.* The growth of MRI from a handful of papers in the early 1990s to over 16,000 in 2014, and from 106 data points in 1977 to over 10 billion in a single study · multi-site consortia such as ADNI, and why modern neuroimaging is a genuine big-data problem · neuroscience as the multidisciplinary study of the biological basis of behaviour, its disciplines and its branches · and neuroimaging as a *method* used across those branches rather than a branch of its own.

*Module 2 — structural anatomy.* Neurons and glia · the four parts of a neuron — axon, cell body, dendrites, axon terminals — and the direction of flow between them · dendritic spines as the physical basis of learning · glia, which outnumber neurons, and the myelin they produce, which is what makes white matter white on a scan · and four complementary ways of dividing the brain: cytoarchitecture and Brodmann's 1909 map, anatomical atlases, connectivity-defined networks, and the six lobes.

*Module 3 — developmental organisation.* Great variability in brain size and shape across species against great overlap in organisation · the structures conserved from mouse to human — brainstem, thalamus, cerebellum, hippocampus, corpus callosum · the cortex as the one that differs most · development from the embryonic neural tube through spinal cord, hindbrain, midbrain and finally cortex · and why the developmental order explains which animal-model findings transfer to humans.

*Module 4 — vascular anatomy.* Why an imaging course cares about blood at all, given that fMRI measures a blood-derived signal rather than neural activity · the route from aorta through common carotid to the internal carotid artery · the Circle of Willis, and why a ring provides collateral supply · the major cerebral arteries, and the distinction between vessels that feed the circle and vessels that leave it · and cortical vascular territories, which explain why blockages produce characteristic deficits.

*Terminology of brain organisation.* The rostral–caudal and dorso–ventral axes as defined for four-legged animals, and why standing upright breaks that scheme · the human replacements — anterior, posterior, superior, inferior, medial, lateral · three planes under two sets of names, frontal/coronal, transverse/axial and sagittal · stating positions on several axes at once · why an MRI image cannot show which side is left, since the same picture results from viewing the person from the front or from behind · radiological and neurological convention, and how mixing them reports a finding in the wrong hemisphere with nothing looking amiss · fiducial markers as the physical fix · and proximal, distal, ipsilateral, contralateral and oblique.

## 02 — Functional Neuroanatomy of the Brain

*Methods of communication I — the synapse.* Golgi's reticular theory against Cajal's neuron doctrine, settled by the electron microscope in the 1950s · sensory, inter- and motor neurons · ion channels and the resting potential · the nine steps of synaptic transmission, converting electrical to chemical and back · excitation and inhibition as depolarisation and hyperpolarisation · why a single EPSP rarely reaches threshold, and how summation makes a neuron a decision element · and intracellular versus extracellular recording, where the local field potential already cannot resolve single cells — the first loss on the way to a voxel.

*Methods of communication II — neurotransmitters and hormones.* Over 50 transmitters, and why the diversity of brain signalling lives in the chemistry rather than the electrics · why the effect belongs to the receptor and not the molecule, so dopamine can excite or inhibit · acetylcholine and Alzheimer's, dopamine and both Parkinson's and schizophrenia, glutamate and excitotoxicity · AMPA and NMDA receptors, and the magnesium plug that makes NMDA a coincidence detector underlying LTP · agonists and competitive versus non-competitive antagonists · direct innervation through cranial nerves and corticospinal tracts against hormonal broadcast · the blood–brain barrier as both protection and delivery problem · and adrenaline reaching memory circuits via the vagus nerve without ever crossing it.

*Functional anatomy.* Cortical columns and layers · CSF, grey matter and white matter as protection, processing and transmission · the primary motor and somatosensory cortices, and why the homunculus is scaled by receptor density rather than body size · the thalamus as relay station, and the crossing at the medulla that makes everything contralateral · visual cortex organised by orientation column and visual field, and the split into dorsal "where" and ventral "what" streams · and the cerebellum, whose motor role is settled and whose cognitive role is not.

*Cognitive domains.* Broca's patients Leborgne and Lelong, and Wernicke's contrasting cases — a double dissociation between producing and comprehending language · Phineas Gage, where what was preserved matters as much as what was lost · H.M. and E.P., two different routes to the same medial temporal lesion and the same inability to form new memories · the mirror-drawing result, where performance improved while any memory of practising was absent, forcing memory to be recognised as several systems · and specialised regions such as the fusiform face area, where perceiving a face and identifying one come apart.

*Neuropsychological assessment.* The cognition–performance distinction, and everything — sensory, attentional, motivational, motor — that sits between an ability and a score · IQ as valid but insufficient, and the four cognitive domains that replaced it · why comparison to population norms demands identical testing conditions, and why a person's own baseline is better · screening, hypothesis testing and battery approaches · the Wechsler Memory Scale and word-list learning, and why delayed recall is the sensitive measure · and the Stroop and Tower of London tests, targeting inhibitory control and planning respectively.

## 03 — Principles and Methods of Neuroimaging

*Approaches to neuroimaging.* Structural against functional imaging · EEG, which records electrical activity directly but localises poorly · CT and its radiation dose · SPECT, and PET as its refinement — detecting a *pair* of annihilation photons is exactly why it localises better · PET tracers as the experiment itself, with FDG for glucose, AV-45 for amyloid and PBB3 for tau · MRI hardware, the always-on superconducting magnet at −270 °C, and a field some 60,000 times the Earth's · and fMRI, DTI and spectroscopy as three refinements running on that same hardware.

*Basics of MRI.* Protons precessing parallel or anti-parallel to B₀, and why a static system carries no information · excitation by a radio-frequency pulse · T1 and T2 as the same motion resolved along two axes · tissue-specific relaxation times, and Damadian's 1979 observation that tumours relax differently · T1- and T2-weighted contrast · the Larmor frequency and the swing-set analogy · how a linear gradient makes the resonant frequency vary with position, so one frequency excites one slice · frequency and phase encoding · and why every voxel is an inference from a timing measurement rather than a photograph.

*Basics of fMRI.* Oxygenated and deoxygenated haemoglobin, and BOLD as a measure of field inhomogeneity · T2 against T2* · deoxygenated haemoglobin as paramagnetic and oxygenated as weakly diamagnetic · the haemodynamic response function, including the undershoot the lecture admits is unexplained · the astrocyte chain that turns signalling into oxygen demand · and Logothetis's result that BOLD tracks local field potentials rather than spiking — so it reflects a population's *input* and local processing rather than its output.

*Structural MRI studies.* Qualitative evaluation of infarction, hyperintensities, shearing and periventricular lesions · volumetric analysis by manual and automated segmentation · cortical thickness between pial and white-matter surfaces · voxel-based morphometry, which asks *where* rather than quantifying a region chosen in advance · structural morphology, which exists because shape can change while volume does not · longitudinal designs · relating structure to behaviour · and the limitations — exercise, substance use, inflammation and especially gliosis, which can mimic neurodegeneration with the neurons intact.

*fMRI studies and experimental design.* What fMRI buys against single-cell recording · matrix size as the resolution-against-time decision · TR and the per-voxel time series · block designs, where the robustness to HRF variation and the inability to study it are the same property · event-related designs, deconvolution, and post-hoc trial sorting · cognitive subtraction, and why there is no "off" condition — every fMRI result is a difference · Donders' pure-insertion assumption, convenient and not obviously true · and why rest is a poor baseline while faces-against-scrambled-faces is a good one.

## 04 — Experimental Design and Special Applications

*Designing an fMRI experiment.* The constrained environment — stimuli projected from outside the room and viewed through a mirror, three or four response buttons per hand · varied stimulus spacing, without which individual responses cannot be deconvolved · runs capped at 4–6 minutes because scanner drift changes the field as the hardware heats · sessions under an hour · motion measured in the same millimetres as the voxels · whether the psychological state actually fills the trial, illustrated by a three-second trial answered in 500 ms · how a predictable sequence turns response inhibition into anticipation · slow emotional states that resist switching · unintended states such as frustration · and five statistical designs — subtraction, factorial, parametric, individual differences and outcome measures — each a different point on the same power-against-specificity trade, with the parametric design's linearity assumption failing once a task becomes impossible.

*Functional connectivity and the default mode network.* Correlating time series rather than contrasting conditions, which frees the method from the control-condition problem and costs it any direct claim about function · the Hebbian premise applied to voxels · voxel-to-voxel against seed-based analysis, validated by left motor cortex correlating with right motor cortex but not with visual cortex · independent component analysis, which asks the data what networks it contains · the default mode network, its hub in posterior cingulate cortex, its emergence between ages 9 and 12, and its overlap with rodent and monkey resting networks · deactivation scaling with task difficulty and predicting successful encoding · why the same mind-wandering that disqualifies rest as a baseline is the object of study here · and why connectivity changes reported in nearly every disorder studied make a sensitive marker rather than a specific one.

## Notes on sources

Parts are named by content rather than by module number: the source decks label
themselves inconsistently, with two decks both called "Module 3" and the vascular
material appearing under two different numbers.

LaTeX sources and figures are kept local, so the `.tex` file and `figs/` are not
in the repo — the built PDF above is the readable output. Lecture slides and
transcripts are third-party course material and are not redistributed here.
