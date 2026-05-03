# MangoCats

Undergraduate research group at the **Center for Language Technologies**, College of Computer Studies, De La Salle University, Manila.

Stephen Borja    [@OutForMilks](https://github.com/OutForMilks)     <br>
Erin Chua        [@chua-e](https://github.com/chua-e)               <br>
Gideon Chua      [@hootawsneaks](https://github.com/hootawsneaks)   <br>
Zhean Ganituen*  [@zrygan](https://github.com/zrygan)               <br>

\* **Correspondence**. Talk to Zhean via [`zhean_robby_ganituen@dlsu.edu.ph`](mailto:zhean_robby_ganituen@dlsu.edu.ph). <br>
**Faculty Adviser**: Nathaniel Oco

## Thesis Project

Medication errors arising from Look-Alike Sound-Alike (LASA) drug name confusion represent a critical patient safety concern. These errors account for approximately 25% of medication errors reported to the US Food and Drug Administration. Existing LASA detection frameworks rely on American English phonological models to assess the auditory confusability of drug names. Drug names in Philippine clinical settings follow Filipino phonological patterns that systematically diverge from American English by featuring reduced vowel inventories, consonant substitutions, and syllable-timed prosody without vowel reduction.
This linguistic distance renders English-centric phonetic similarity measures unreliable for local pharmaceutical safety screening. This study addresses this gap through three objectives: (1) establishing a cross-lingual transferability baseline by evaluating existing phonetic similarity measures on Philippine drug names, (2) developing a Filipino-aware Grapheme-to-Phoneme (G2P) algorithm that maps pharmaceutical name strings to IPA transcriptions reflecting Philippine English pronunciation patterns across the lectal continuum, and (3) adapting the ALINE phonetic similarity algorithm using Filipino phonological constraints to improve sound-alike drug name detection.

## Repositories

### **ginger**
- **repository**: https://github.com/Mango-Cats/ginger
- **keywords**: `grapheme-to-phoneme`, `transformers`, `HuBERT`
- **tl; dr**: A grapheme-to-phoneme model for Filipino using transformers and HuBERT.

### **pho (🍜)**
- **repository**: https://github.com/Mango-Cats/pho
- **keywords**: `phonetic algorithms`, `genetic algorithm`, `Filipino phonology`
- **tl; dr**: Phonetic algorithms and phonetic similarity measures are centered on Western languages. The goal of this project is to (1) localize popular phonetic similarity measures; and (2) learn a weighted sum of orthographic and phonetic measures for LASA detection.

### **TagaBaybay (ᜆᜄᜊᜌ᜔ᜊᜌ᜔)**
- **repository**: https://github.com/Mango-Cats/tagabaybay
- **keywords**: `orthographic nativization`, `loanword adaptation`, `Filipino`, `rule-based systems`, `low-resource NLP`
- **tl; dr**: How do we orthographically adapt frequently used loanwords in Filipino?

### **walter**
- **repository**: https://github.com/Mango-Cats/walter
- **keywords**: `large language models`, `dataset construction`, `drug names`
- **tl; dr**: We need a dataset to evaluate the algorithm for automated detection of LASA drugs names in the Philippines. So, we will construct one by using an LLM-assisted approach with few-shot prompting and expert validation.

### Other Projects

- [`Mango-Cats/SemanticDrugSim`](https://github.com/Mango-Cats/SemanticDrugSim). Semantic similarity of generic drug names by unsupervised learning.

---

<img width="282" height="374" alt="image" src="https://github.com/user-attachments/assets/918000b3-71ba-4c24-b8c7-2866ca429865" />
