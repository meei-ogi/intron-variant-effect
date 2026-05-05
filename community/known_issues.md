
## Known issues:

## Biological methodology

We performed both stable and transient HEK293 cells transfection approaches. The difficulties to set gates during FACS sorting using pure and ultrapure sorting resulted in too many mixed bin cells. This was the reason why we switched to transient transfection in this particular project.

## Next task:

Systematically identify and experimentally validate deep intronic variants in RetNet genes (~300) based on AlphaGenome pathogenicity predictions.

**Approach:**

**Variant extraction:**
1. Compile all possible deep intronic variants across RetNet genes (excluding canonical splice regions).
2. Prediction-based stratification:
3. Select variants with **high** predicted pathogenicity (quantile score >0.8).
4. Select variants with **low** predicted pathogenicity (predicted benign; e.g., quantile score <0.2).

**Experimental validation:**
1. Functionally test both sets using a high-throughput splicing assay
2. Quantify splicing disruption in vitro.

**Benchmarking:**
1. Compare experimental outcomes with AlphaGenome predictions.
2. Assess false positives (predicted pathogenic but benign) and false negatives (predicted benign but disruptive).

**Goal:**
Define the accuracy of AlphaGenome for deep intronic variants and generate a validated dataset to improve non-coding variant interpretation in inherited retinal diseases.
