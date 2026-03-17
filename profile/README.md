# Mango Cats

Undergraduate research group at _College of Computer Studies_, De La Salle University, Manila.

Stephen Borja    [@OutForMilks](https://github.com/OutForMilks)     <br>
Erin Chua        [@chua-e](https://github.com/chua-e)               <br>
Gideon Chua      [@hootawsneaks](https://github.com/hootawsneaks)   <br>
Zhean Ganituen*  [@zrygan](https://github.com/zrygan)               <br>
Nathaniel Oco†                                                      <br>

\* **Correspondence**. Talk to Zhean via [`zhean_robby_ganituen@dlsu.edu.ph`](mailto:zhean_robby_ganituen@dlsu.edu.ph). <br>
† **Faculty Adviser**.

## Main Projects

### **Orthographic Nativization as Rule-Based Rewrite Cascades**
**TagaBaybay**
- Repository: https://github.com/Mango-Cats/tagabaybay
- Keywords: `orthographic nativization`, `loanword adaptation`, `Filipino`, `rule-based systems`, `low-resource NLP`
- <details><summary>Abstract.</summary>
  Orthographic nativization, generating standardized written forms of loanwords in a recipient language, remains understudied computationally despite its importance for text normalization and multilingual NLP. We present a rule-based rewrite cascade for orthographic nativization of English loanwords into Filipino. The system operates through four stages: graphemic tokenization, priority-ordered rewrite rules, phonetic resolution via grapheme-to-phoneme lookup, and output normalization. Rules are hand-authored from prescriptive orthographic guidelines and descriptive phonological sources, enabling deployment without parallel training corpora. We evaluate on a newly constructed gold standard of 2,319 English-Filipino loanword pairs. The proposed method achieves 5.14% character error rate under a 5-vowel evaluation and 4.05% under a 3-vowel evaluation that accounts for Filipino's vowel variation. The system outperforms a regular expressions, an orthographic-only ablation without phonetic resolution, and zero-shot prompting of a large language model given the same mapping rules. Error analysis reveals that most remaining errors stem from schwa ambiguity in unstressed syllables, glide insertion, and the quality of the phonetic transcription, suggesting directions for refinement. The linguistically grounded approach demonstrates that prescriptive rules can be operationalized into effective orthographic nativization systems for low-resource languages.
</details>

### **Sound-Alike Drug Name Detection for Filipino**
**PhOCA**
- Repository: none
- Keywords: `drug names`, `string similarity`, `Filipino phonology`
- <details><summary>Abstract.</summary>
  Medication errors arising from Look-Alike Sound-Alike (LASA) drug name confusion represent a critical patient safety concern, accounting for approximately 25\% of medication errors reported to the US Food and Drug Administration. Existing LASA detection frameworks rely on American English phonological models to assess the auditory confusability of drug names. However, in Philippine clinical settings, drug names are pronounced according to Filipino phonological patterns that systematically diverge from American English---featuring reduced vowel inventories, consonant substitutions, and  syllable-timed prosody without vowel reduction. This linguistic distance renders English-centric phonetic similarity measures unreliable for local pharmaceutical safety screening. This study addresses this gap through three objectives: (1) establishing a cross-lingual transferability baseline by evaluating existing phonetic similarity measures on Philippine drug names, (2) developing a Filipino-aware Grapheme-to-Phoneme (G2P) algorithm that maps pharmaceutical name strings to IPA transcriptions reflecting Philippine English pronunciation patterns across the lectal continuum, and (3) adapting the ALINE phonetic similarity algorithm using Filipino phonological constraints to improve sound-alike drug name detection.
</details>

## Other Projects

- [`Mango-Cats/SemanticDrugSim`](https://github.com/Mango-Cats/SemanticDrugSim). Semantic similarity of generic drug names by unsupervised learning.
