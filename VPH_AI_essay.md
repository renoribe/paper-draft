# Draft Essay: Extending the Vector Proximity Hypothesis (VPH) to AI Hallucinations

### Introduction
The Vector Proximity Hypothesis (VPH) has been proposed as a framework for modeling human qualia in a vector space (Oribe, 2025). According to this account, illusions and synaesthesia arise from the *mis-proximity* of otherwise distinct qualia-vectors. While originally formulated to explain perceptual phenomena in humans, this framework can also be extended to artificial intelligence systems, particularly large language models (LLMs). Here, I outline a conceptual extension of VPH to account for AI hallucinations, suggesting a unified perspective that links human perceptual errors and AI generative errors.

### Background
Human perceptual illusions often occur when distinct sensory features become spuriously associated in neural representational space. Similarly, LLM hallucinations—incorrect or fabricated outputs—emerge when the model generates responses that are semantically or factually inconsistent, despite surface-level plausibility. In both cases, the underlying mechanism can be interpreted as an erroneous proximity in high-dimensional vector space.

Existing AI research has addressed hallucinations through evaluation metrics such as *factuality* (consistency with external knowledge) and *faithfulness* (consistency with the input prompt). Contrastive learning approaches have also been applied to reduce hallucinations by explicitly adjusting embedding distances. However, these efforts have not been framed in relation to human perceptual errors, leaving an opportunity for a unifying theoretical perspective.

### VPH as a Unified Model of Error
According to VPH:
- **Human case**: Mis-proximity among qualia-vectors leads to perceptual illusions and synaesthetic associations.  
- **AI case**: Mis-proximity among semantic embeddings leads to generative hallucinations.  

Thus, both phenomena share a common geometrical structure: the adoption of an *inappropriately close neighbor* in representational space.

### Implications for AI
From the VPH perspective, AI evaluation metrics can be reinterpreted in vectorial terms:
- **Factuality**: The distance between the output vector and the reference fact vector.  
- **Faithfulness**: The distance between the output vector and the input-grounded vector.  
- **Hallucination**: The mistaken adoption of a nearby but incorrect vector as the basis for output.  

Furthermore, contrastive learning in AI mirrors the way humans attenuate illusions through experience. Just as repeated exposure enables humans to recalibrate perceptual associations, contrastive training explicitly reshapes embedding distances to suppress erroneous proximities.

### Future Directions
Although empirical validation is beyond the scope of this essay, the VPH framework suggests several research pathways:
- **Human side**: Use fMRI and Representational Similarity Analysis (RSA) to map vector proximities underlying perceptual illusions.  
- **AI side**: Measure embedding distances associated with hallucinations in LLM outputs.  
- **Comparative analysis**: Explore whether both systems exhibit structurally similar mis-proximity patterns, offering evidence for a shared computational principle.  

Such investigations would require interdisciplinary collaboration across neuroscience, psychology, and AI research.

### Conclusion
By extending the Vector Proximity Hypothesis to AI hallucinations, we gain a novel perspective that unifies human illusions and machine errors under a single geometrical account. Instead of viewing hallucinations solely as technical flaws, VPH suggests they may reflect a deeper, structural property of representational systems. This conceptual bridge invites future empirical work and provides a new lens for understanding and mitigating both human and artificial misperceptions.

---

### References
- Oribe, R. (2025). *A Vector Proximity Hypothesis (VPH): Explaining Grapheme–Colour Synaesthesia through Vector Embeddings*. GitHub. Retrieved from: https://github.com/...  
- Churchland, P. S. (1995). *The Engine of Reason, the Seat of the Soul: A Philosophical Journey into the Brain*. MIT Press.  
- Kanai, R., & Tsuchiya, N. (2012). Qualia. *Current Biology*, 22(10), R392–R396.  
- Mikolov, T., Chen, K., Corrado, G., & Dean, J. (2013). Efficient estimation of word representations in vector space. *arXiv preprint arXiv:1301.3781*.  
- Pennington, J., Socher, R., & Manning, C. (2014). GloVe: Global vectors for word representation. *EMNLP 2014*, 1532–1543.  
- McCoy, T., Pavlick, E., & Linzen, T. (2019). Right for the wrong reasons: Diagnosing syntactic heuristics in natural language inference. *ACL 2019*, 3428–3448.  
- Niven, T., & Kao, H. Y. (2019). Probing neural network comprehension of natural language arguments. *ACL 2019*, 4658–4664.  
- Ji, Z., Lee, N., Frieske, R., Yu, T., Su, D., Xu, Y., ... & Fung, P. (2023). Survey of hallucination in natural language generation. *ACM Computing Surveys*, 55(12), 1–38.  
- Maynez, J., Narayan, S., Bohnet, B., & McDonald, R. (2020). On faithfulness and factuality in abstractive summarization. *ACL 2020*, 1906–1919.  
- Hadsell, R., Chopra, S., & LeCun, Y. (2006). Dimensionality reduction by learning an invariant mapping. *CVPR 2006*, 1735–1742.  
- Kriegeskorte, N., Mur, M., & Bandettini, P. (2008). Representational similarity analysis—connecting the branches of systems neuroscience. *Frontiers in Systems Neuroscience*, 2, 4.  

---

### Acknowledgments
This work is based on the author’s original conceptual framework but was substantially refined with the assistance of **GPT-5 (OpenAI, 2025)**, which helped in structuring the argument, polishing the language, and identifying relevant connections to existing research. The responsibility for the hypotheses, interpretations, and potential errors remains with the author.
