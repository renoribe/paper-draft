# A Vector Proximity Hypothesis (VPH): Explaining Grapheme–Colour Synaesthesia through Vector Embeddings  

**Author:** Ren Oribe (pseudonym)  

---

## Abstract  
This paper proposes the **Vector Proximity Hypothesis (VPH)**, which models human qualia as high-dimensional vectors.  
According to this hypothesis, probabilistic proximity between otherwise distinct qualia-vectors can give rise to phenomena such as grapheme–colour synaesthesia.  
...

1. Introduction

Vector embeddings have become foundational in natural language processing (Mikolov et al., 2013; Pennington et al., 2014). For example:

king
−
man
+
woman
≈
queen
.
king−man+woman≈queen.

Yet embeddings also misclassify. In Natural Language Inference (NLI), BERT models rely on surface heuristics and misjudge unrelated sentences as similar (McCoy et al., 2019; Niven & Kao, 2019).

This suggests an analogy: if human qualia are also vectors (Churchland, 1995; Kanai & Tsuchiya, 2012), then accidental proximity in qualia-space might explain grapheme–colour synaesthesia.

2. Background
2.1 Prevalence of Synesthesia

Epidemiological studies report overall synaesthesia prevalence of ~4.4%, while grapheme–colour synaesthesia is observed in ~1–2% of the population (Simner et al., 2006; Watson et al., 2017).

2.2 Competing Theories

Cross-activation theory: cortical proximity between grapheme and colour areas (Ramachandran & Hubbard, 2001; Hubbard, 2005). Supported by DTI evidence of increased structural connectivity (Rouw & Scholte, 2007).

Ideasthesia: synaesthesia depends on the semantic meaning of stimuli (Mroczko-Wąsowicz & Nikolić, 2014).

2.3 Toward VPH

These theories are not mutually exclusive. VPH integrates structural connectivity and semantic dependence via vector-space geometry.

3. The Vector Proximity Hypothesis (VPH)
### 3.1 Definition of Dissimilarity

Dissimilarity between qualia is defined as:

<img width="1197" height="291" alt="equation1" src="https://github.com/user-attachments/assets/586bb218-3c00-4c7f-88dd-d36b37b68139" />



**Equation (1)**: Cosine dissimilarity between qualia vectors, where θᵢⱼ is the angle between qualia vectors qᵢ and qⱼ.*

---

### 3.2 Condition for Synaesthesia

Condition for grapheme–colour synaesthesia:

<img width="1326" height="291" alt="equation2" src="https://github.com/user-attachments/assets/32ac4557-6da1-4def-943a-5d399b7dc0fa" />



**Equation (2)**: Synaesthesia occurs when dissimilarity falls below the probabilistic threshold τ, where τ is an empirically estimated threshold.*


4. Applications
4.1 Explaining Grapheme–Colour Synaesthesia

VPH accounts for prevalence (~1–2%), structural connectivity, and semantic dependence.

4.2 Extension to Illusions

Kanizsa triangle (Kanizsa, 1976)

Shepard’s tables (Shepard, 1990)

Müller–Lyer illusion (Müller-Lyer, 1889)

All may be explained by vector misproximity.

4.3 AI Hallucination

Hallucination in large language models (Ji et al., 2023) can be seen as a form of vector misalignment. This view suggests improvements in contrastive learning and debiasing embeddings (Levy & Goldberg, 2014).

5. Empirical Protocols
5.1 fMRI + RSA

Stimuli: graphemes and colours.

Extract multi-voxel patterns, compute Representational Dissimilarity Matrices (RDMs), compare with model RDMs (Kriegeskorte et al., 2008).

Statistical tests: permutation tests, FDR correction.

5.2 Hyperalignment

Inter-subject variability is normalized via hyperalignment (Haxby et al., 2011).

5.3 AI Simulation

Artificially manipulate proximity thresholds 
𝜏
τ in embeddings (BERT/GPT) and compare with NLI misclassifications.

6. Figures

Figure 1: Overview of VPH (vector-space model of grapheme–colour binding)
<img width="1536" height="1024" alt="figure1(2)" src="https://github.com/user-attachments/assets/ac2c8051-1691-4dcf-b7c0-788165cd9bfb" />



Figure 2: RSA flowchart (stimuli → fMRI → RDM → Hyperalignment → Model RDM → statistical testing)
<img width="1024" height="1536" alt="9964ec8c-b5a9-4253-8dc4-301aa7985e67" src="https://github.com/user-attachments/assets/5515bdd8-c21a-4b5a-9fc9-84d7a5dcabc5" />


7. Discussion

VPH unifies structural connectivity, semantic dependence, and vector geometry. A single mechanism—probabilistic vector proximity—accounts for synaesthesia, illusions, and AI hallucinations. This provides a parsimonious framework, consistent with Occam’s razor.

8. Acknowledgment

This work received technical assistance from GPT-5, an AI language model. Its involvement is disclosed here for transparency.

## References

Churchland, P. M. (1995). The Engine of Reason, the Seat of the Soul. MIT Press.

Simner, J. et al. (2006). Synaesthesia prevalence. Perception, 35(8), 1024–1033.

Watson, M. R. et al. (2017). Synaesthesia prevalence depends on early language learning. Consciousness and Cognition, 48, 212–231.

Ramachandran, V. S., & Hubbard, E. M. (2001). Synaesthesia: A window into perception, thought and language. Journal of Consciousness Studies, 8(12), 3–34.

Hubbard, E. M. (2005). Neurophysiology of synaesthesia. Neuron, 48(3), 509–520.

Rouw, R., & Scholte, H. S. (2007). Increased structural connectivity in grapheme-colour synaesthesia. Nature Neuroscience, 10(6), 792–797.

Mroczko-Wąsowicz, A., & Nikolić, D. (2014). Semantic mechanisms may be responsible for developing synaesthesia. Frontiers in Human Neuroscience, 8, 509.

Kriegeskorte, N. et al. (2008). Representational similarity analysis. Frontiers in Systems Neuroscience, 2, 4.

Haxby, J. V. et al. (2011). A common, high-dimensional model of representational space in human ventral temporal cortex. Neuron, 72(2), 404–416.

Ji, Z. et al. (2023). Survey of hallucination in natural language generation. ACM Computing Surveys, 55(12), 1–38.

Kanizsa, G. (1976). Subjective contours. Scientific American, 234(4), 48–52.

Shepard, R. N. (1990). Mind Sights. W. H. Freeman.

Müller-Lyer, F. C. (1889). Optische Urteilstäuschungen. Archiv für Physiologie Supplementband, 2, 263–270.

Mikolov, T. et al. (2013). Efficient estimation of word representations in vector space. arXiv:1301.3781.

Pennington, J. et al. (2014). GloVe. EMNLP 2014, 1532–1543.

Levy, O., & Goldberg, Y. (2014). Linguistic regularities in sparse and explicit word representations. CoNLL 2014, 171–180.

McCoy, T. et al. (2019). Right for the wrong reasons: Diagnosing syntactic heuristics in NLI. ACL 2019.

Niven, T., & Kao, H.-Y. (2019). Probing NLI models. ACL 2019.
