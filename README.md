# VIDEOS
## <ins>Vi</ins>sualization of <ins>De</ins>viati<ins>o</ins>n <ins>S</ins>cores
### Personalized MRI in Neuropsychiatry

Background: Schizophrenia is a devastating, complex, and heterogeneous neuropsychiatric disorder. While there is an extensive literature on neuroimaging in schizophrenia and emerging evidence that it may be an important tool for planning and monitoring response to interventions like TMS, it is not routinely used in clinical care in schizophrenia. Several commercial products are available that potentially address subtle MRI findings, however, they are focused on atrophy and neurodegeneration, have coarse volumetric segmentations, and only generate a report rather than annotated images.

Methods: Cortical thickness and surface area were measured in >1,000 healthy controls and >100 participants with schizophrenia using Freesurfer and divided into 180 bilateral cortical regions using the Glasser/HCPMMP1 atlas. The volumes of 18 bilateral subcortical structures including 10 thalamic nuclei, basal ganglia, and the claustrum were measured using sTHOMAS. Individual deviation scores (i.e. z-scores) relative to the reference population of healthy controls were calculated for all measures, mapped to T1w images, and summarized across lobes, canonical networks, and cortical functional groups.

Results: T1w images annotated with deviations scores created interactive, personalized MRIs that identified subtle alterations in the cortex and subcortical regions, which are not otherwise detectable on standard T1w images. Summary statistics provide additional context for the interpretation of subtle alterations. 

Conclusions: Deviation scores allow disparate neuroimaging measures like regional cortical thickness and subcortical volumes to be visualized and compared on an individual basis. The methodology is extendable to structural and functional connectivity, which may facilitate the identification of personalized cortical and subcortical targets for both invasive and non-invasive neuromodulation.

https://github.com/user-attachments/assets/fadbb74e-08f6-4010-960b-6d6c94790076

**Figure 1 -** Scrollable MRI annotated with deviation scores (|z| > 1.96)

**Table 1 -** Most severe deviations in the thalamus and subcortical regions
| label | name | z | deviation |
| --- | --- | --- | --- |
| R12 | Mediodorsal-Parafascicular (MD-Pf) - Right | -3.519983466 | 1 |
| R8 | Pulvinar (Pul) - Right | -2.811988485 | 1 |
| L28 | Claustrum (Cla) - Left | -2.537453808 | 1 |
| R28 | Claustrum (Cla) - Right | -2.479697374 | 1 |
| L14 | Mammilo-Thalamic Tract (MTT) - Left | -2.1832951 | 1 |
| R26 | Accumbens Area (Acc) - Right | 2.902897511 | 1 |

**Table 2 -** Individual cortical regions with the most severe deviation scores in cortical thickness
| label | z | deviation | name | lobe | cortex | network | laterality |
| --- |--- |--- |--- |--- |--- |--- |--- |
| R_PSL | -4.78083086613012 | 1 | PeriSylvian - Leftanguage Area - Right | Parietal | Temporo-Parieto-Occipital Junction | Ventral Attention | Right |
| R_PFm | -4.5149346187815 | 1 | Area PFm Complex - Right | Parietal | Inferior Parietal | Frontoparietal | Right |
| R_DVT | -3.94018047917037 | 1 | Dorsal Transitional Visual Area - Right | Parietal | Posterior Cingulate | Visual | Right |
| R_TPOJ2 | -3.88618863342557 | 1 | Area TemporoParietoOccipital Junction 2 - Right | Parietal | Temporo-Parieto-Occipital Junction | Ventral Attention | Right |
| R_FST | -3.69793810393835 | 1 | Area FST - Right | Occipital | MT+ Complex and Neighboring Visual Areas | Dorsal Attention | Right |
| L_PeEc | -3.64690223550697 | 1 | Perirhinal Ectorhinal Cortex - Left | Temporal | Medial Temporal | Limbic | Left |
| L_Ig | -3.59187505439839 | 1 | Insular Granular Complex - Left | Insula | Insular and Frontal Opercular | Somatomotor | Left |
| R_V6A | -3.58289844724316 | 1 | Area V6A - Right | Parietal | Dorsal Stream Visual | Visual | Right |
| R_OP1 | -3.56181920973329 | 1 | Area OP1-SII - Right | Parietal | Posterior Opercular | Somatomotor | Right |
| L_LO1 | -3.55593228759335 | 1 | Area - Lateral Occipital 1 - Left | Occipital | MT+ Complex and Neighboring Visual Areas | Visual | Left |

**Table 3 -** Cortical functional groups with the most severe deviations in cortical thickness
| laterality | cortex | n.roi | n.deviations | pct.deviation | min.z | max.z | mean.z | mean.abs.z |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Right | Temporo-Parieto-Occipital Junction | 5 | 5 | 1 | -4.78 | -2.63 | -3.42 | 3.42 |
| Left | Early Visual | 3 | 3 | 1 | -3.35 | -1.99 | -2.55 | 2.55 |
| Right | Inferior Parietal | 10 | 8 | 0.8 | -4.51 | -1.44 | -2.64 | 2.64 |
| Left | Inferior Parietal | 10 | 8 | 0.8 | -3.38 | -1.31 | -2.53 | 2.53 |
| Right | Lateral Temporal | 8 | 6 | 0.75 | -2.88 | -0.31 | -1.97 | 1.97 |
| Right | Posterior Cingulate | 13 | 9 | 0.69 | -3.94 | -0.58 | -2.48 | 2.48 |
| Left | Inferior Frontal | 9 | 6 | 0.67 | -3.16 | 0.02 | -2.04 | 2.04 |
| Left | Orbital and Polar Frontal | 9 | 6 | 0.67 | -2.85 | 0.12 | -1.91 | 1.94 |
| Left | Lateral Temporal | 8 | 5 | 0.62 | -3.55 | -0.96 | -2.26 | 2.26 |
| Left | Posterior Opercular | 5 | 3 | 0.6 | -3.55 | -1.73 | -2.55 | 2.55 |
| Left | Temporo-Parieto-Occipital Junction | 5 | 3 | 0.6 | -3.39 | -1.08 | -2.34 | 2.34 |
| Left | Somatosensory and Motor | 5 | 3 | 0.6 | -3.08 | -1.01 | -2.11 | 2.11 |
| Left | Ventral Stream Visual | 7 | 4 | 0.57 | -3.01 | -0.8 | -2.02 | 2.02 |
| Left | MT+ Complex and Neighboring Visual Areas | 9 | 5 | 0.56 | -3.56 | -1.14 | -2.19 | 2.19 |
| Right | Dorsal Stream Visual | 6 | 3 | 0.5 | -3.58 | -1.12 | -1.98 | 1.98 |
| Right | Auditory Association | 8 | 4 | 0.5 | -3.5 | -0.64 | -2 | 2 |
| Left | Auditory Association | 8 | 4 | 0.5 | -2.98 | -0.48 | -1.91 | 1.91 |
| Left | Dorsolateral Prefrontal | 13 | 6 | 0.46 | -2.83 | -1.11 | -1.83 | 1.83 |

**Table 4 -** Canonical networks with most severe deviations in surface area
| laterality | network | n.roi | n.deviations | pct.deviation | min.z | max.z | mean.z | mean.abs.z |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| Left | Somatomotor | 27 | 12 | 0.44 | -0.75 | 4.66 | 2.06 | 2.12 |
| Right | Default | 34 | 15 | 0.44 | -1.37 | 4.58 | 1.65 | 1.82 |
| Left | Default | 34 | 14 | 0.41 | -0.42 | 4.27 | 1.8 | 1.86 |
| Left | Ventral Attention | 26 | 10 | 0.38 | -1.86 | 4.46 | 1.41 | 1.69 |
| Right | Somatomotor | 27 | 9 | 0.33 | -1.24 | 4.08 | 1.46 | 1.65 |
| Right | Ventral Attention | 26 | 7 | 0.27 | -1.41 | 4.51 | 0.9 | 1.51 |
| Right | Frontoparietal | 27 | 7 | 0.26 | -1.43 | 3.73 | 1 | 1.3 |
| Left | Frontoparietal | 27 | 7 | 0.26 | -1.74 | 3.19 | 1.12 | 1.42 |

