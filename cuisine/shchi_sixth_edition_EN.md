# On the Formation of the Acid–Flavor Profile of Traditional Shchi

**A. N. Koriakin**
2026
*Research manuscript*

*Interdisciplinary study: food chemistry, fermentation microbiology, sensory analysis, food history*

*Sixth edition. The third edition was revised following peer review: a three-level model architecture, a prototypicality model, a section of falsifiable predictions, and a revised experimental program were introduced; the fourth edition was harmonized with the companion study on borscht [47]; the fifth edition was revised following the fourth review of the joint project: vector A and buffer capacity were operationalized, effect sizes were specified for predictions P1–P5, a cross-class asymmetry test with the borscht model and statistical additions were introduced; the sixth edition was revised following the fifth review: a comparison metric was assigned to vector A, the Shchi Index axes received scale anchors, the experimental program was supplemented with training/test splits, a confounder matrix, a causal scheme, and a four-level design for Experiment 2, and the statistical model now treats batch and day as random effects (see the editorial notes at the end of the main text).*

> *"...this place was also remarkable for our first tasting the native soup, ЩІ, (pronounced shtshee), which was quite drinkable, though it contained some sour element, which perhaps is necessary for Russian palates."*
> **Lewis Carroll, *The Russian Journal*, 1867** [42]

---

## Abstract

Two heterogeneous questions that are commonly conflated in culinary literature are considered: (1) what forms the acid–flavor profile of shchi — a chemical–sensory question; and (2) what features make a dish shchi — a categorical question. These questions are shown to require different methods: the first is addressed experimentally, while the second is addressed through a prototype model. A three-level analytical architecture (chemical → sensory → categorical) is proposed, together with a decomposition of the acid profile into five components (intensity, acid composition, duration, temporal position, and character), a classification of acidity sources along two axes (origin of the acid × time of addition), and two independent scales for acidity measurement — chemical (pH, titratable acidity, buffer capacity) and sensory. Cabbage is described as a functional carrier of several functions that proved historically optimal but is not necessary. A “Shchi Index” (ИЩ) is formulated — a model of shchi prototypicality as a conceptual construct whose weights and functional form require experimental calibration. Eight falsifiable predictions (P1–P8) are advanced, and a five-experiment program (Experiments 0–4) is developed with control samples, a statistical plan, and temperature control. The work is a research program: its result is not a “proven theory of shchi,” but a model that generates testable consequences.

**Keywords:** shchi; sauerkraut; lactic acid fermentation; organic acids; pH; titratable acidity; buffer capacity; sensory analysis; prototype; umami; green tomatoes; sorrel; culinary classification.

---

## 1. Introduction

### 1.1. Statement of the problem

In popular understanding, shchi are “cabbage soup,” while sour shchi are “shchi made with sauerkraut.” Culinary reality is broader than either definition: there are shchi without cabbage (sorrel, nettle, ground elder), shchi with fundamentally different levels of acidity (from neutral to sharply sour), fasting and “rich” shchi, day-old and freshly cooked shchi — and bearers of the tradition classify all of these within the same category. This gives rise to two questions that must be distinguished from the outset:

> **Q1 (chemical–sensory): what forms the acid–flavor profile of shchi?**
>
> **Q2 (categorical): what features make a dish shchi?**

Conflating these questions is the main methodological risk: a person may call a soup shchi not because it has a certain pH or technology, but because they recognize it as a cultural type. A dish may be chemically almost indistinguishable from shchi and yet not be perceived as shchi — and vice versa. Q1 and Q2 therefore require different tools, and the present study pursues them in parallel without reducing one to the other.

### 1.2. Historical context and its evidentiary weight

The Old Russian form of the word is *shti*, attested in the *Domostroi* (sixteenth century); according to one hypothesis, it derives from Old Russian *sъto* — “sustenance,” while another relates it to sorrel [33]. Dialectal meanings are broad: “boiled dish, broth, soup dressed with cabbage, sorrel, and other greens” [33]. The *Domostroi* mentions shchi as an everyday dish of all social estates [34, 35]. Cabbage, which spread in Rus’ approximately from the ninth century, became the principal component because of its yield and storability [35], but the seasonal cycle retained substitutes: in spring, ground elder and nettle, followed by sorrel and cabbage seedlings [35, 36]. A technological constant was prolonged slow cooking in the Russian stove [35, 36]; historical souring/dressing agents included cabbage brine, stewed sour apples, and smetana [35].

**The earliest documentary layer: birch-bark letters.** The ingredient complex from which the shchi tradition developed is documented several centuries before the *Domostroi* in the birch-bark letters of Novgorod and Staraya Russa (eleventh–fifteenth centuries): cabbage as a mass garden crop (household notes concerning harvesting, preservation, and sale), turnip as the principal vegetable component of dense soups before the spread of potatoes, salt and salting processes including cabbage fermentation, and a broth base of pork, salted meat, and fish [41]. This documentary layer has particular value: birch-bark letters are neither normative nor literary texts, but everyday business and household correspondence, and therefore testify to actual practice rather than prescription (the source used here is a secondary compilation; see bibliographic entry [41]). In the mid-sixteenth century, the *Domostroi* already records household fermentation as an economic norm: “in autumn, salt the cabbage” [34].

**Literary record.** By the beginning of the nineteenth century, shchi were already functioning as a cultural symbol. In Pushkin’s *Fragments from Onegin’s Journey*: “My ideal now is a housewife, / My wishes are peace, / And a pot of shchi, and I myself the master” [44] — the verse is based on a Russian saying whose sense is “I eat simple food, but I am my own master”; the pot of shchi here signifies simple food and personal independence. In the first chapter of Gogol’s *Dead Souls*, Chichikov ends his day with “a portion of cold veal, a bottle of sour shchi, and sound sleep…” [43]; for the meaning of the expression “a bottle of sour shchi,” see §5.4.

**Caveat on evidentiary weight.** Etymology is *consistent with* the hypothesis that the name was historically not rigidly tied to cabbage, but it does not prove the structure of the modern class of dishes. Moreover, lexical history itself contains a counterexample (see §5.4): “sour shchi” historically also denoted a sour malt-and-honey beverage [35]. Linguistic membership of the word therefore cannot serve as direct evidence of culinary structure. Historical data are used in the present study as contextual evidence consistent with the model, not as the basis for its conclusions. The same principle is adopted in the companion study on borscht [47]: its historical-cultural review (etymology, imperial canonization, diasporas) functions likewise — as context consistent with the model rather than proof of it.

**An external view.** Lewis Carroll, who visited Russia in 1867, recorded that shchi (“shtshee”) “turned out to be quite edible, although they contained some sour ingredient, perhaps necessary to the Russian taste” [42]. The evidentiary function of this quotation is limited but real: it is testimony to the **sensory salience** of a sour component to a nineteenth-century foreign observer — an indirect sign that acidity was already perceived as a characteristic feature of Russian cuisine. No conclusion about the constitutive role of acidity follows from it: Carroll noticed sourness; he did not prove its necessity.

**Summary table of historical evidence.** To make the evidentiary discipline of this section explicit, each historical fact is paired with what it permits one to infer and what it does not prove:

| Fact | What it permits one to infer | What it does NOT prove |
|---|---|---|
| Birch-bark letters: cabbage, turnip, salt/fermentation, meat and fish in the diet of the 11th–15th centuries [41] | the antiquity of the ingredient complex from which the shchi tradition developed (an unbiased, non-normative source) | the existence of shchi as a dish in that period; the presence of acidity in it |
| Etymology of *shti* and broad dialect meanings [33] | the name was historically not rigidly tied to cabbage | the structure of the modern class of dishes; the antiquity of any specific recipe |
| Shchi as an everyday dish of all estates in the *Domostroi* [34] | early normative status of the dish in the tradition | the composition and acidity of those shchi |
| *Domostroi*: “in autumn, salt the cabbage” [34] | household cabbage fermentation as a sixteenth-century economic norm | that sauerkraut was used specifically in shchi; the acid profile of such cabbage |
| Seasonal cycle of substitutes (ground elder, nettle, sorrel, seedlings) [35, 36] | functional substitutability of the carrier of vegetable mass | that the substitutes are sensorially equivalent to cabbage |
| Slow cooking in the Russian stove as a technological constant [35, 36] | primacy of technology for the identity of the dish | that slow cooking is necessary (tested by axis T) |
| Historical sour dressings (brine, stewed apples, smetana) [35] | long-standing variability of acidity sources | that acidity was a constitutive feature |
| “Sour shchi” as a beverage (polysemy) [34, 35, 43] | the lexical category is graded and polysemous | any conclusions about soups from word usage (§5.4) |
| Carroll’s observation (1867) [42] | sensory salience of the sour component to an external observer | necessity of acidity; its intensity and source |
| Pushkin, Gogol — shchi as a cultural symbol [43, 44] | early categorical stability | chemical–sensory properties of the dish |

### 1.3. Aim, objectives, and status of the study

**Aim** — to construct a model of the formation of the acid–flavor profile of shchi and a model of the categorical membership of a dish in the shchi class, formulating testable consequences for both.

**Objectives:** (1) systematize data on fermentation, organic acids, and sourness perception; (2) decompose the “acid profile” into measurable components; (3) describe cabbage as a functional carrier and research variable; (4) formulate a model of shchi prototypicality; (5) advance falsifiable predictions; (6) develop an experimental program.

**Status of the study.** This is a theoretical-modeling study; experimental data on shchi themselves are absent from the literature, and no original experiment has yet been conducted. Three levels of claims are distinguished and marked throughout the text: **[Д]** — established by sources; **[П]** — transfer of data from adjacent domains to shchi (plausible, untested); **[Г]** — the author’s own hypothesis.

---

## 2. What Is Known

### 2.1. Cabbage fermentation

**[Д]** In a simplified scheme, spontaneous cabbage fermentation proceeds in two phases: initiation is driven by heterofermentative bacteria (*Leuconostoc mesenteroides*), while completion is driven by homofermentative bacteria (*Lactiplantibacillus plantarum* and others) [4, 5]. Organic acids in sauerkraut include lactic acid (the structural, “indispensable” acid [7]), as well as citric and acetic acids [2]. The bacterial community plays a leading role in the formation of acids and volatile compounds [1]; salt concentration during fermentation affects the microbiome and metabolite profile [2, 5]; fermentation regimes can be optimized, up to and including salt-free fermentation [37].

**[Д] Important recent caveat:** the linear two-phase scheme is a simplification. A 2026 study shows that temperature and fermentation scale can substantially alter microbial dynamics [10]. For the present purpose, this strengthens the thesis that “fermentation phase” is not an abstract stage but a bundle of process variables.

**[Д]** The taste and aroma of fermented cabbage are formed not only by acids, but also by glucosinolate degradation products and sulfur-containing volatile compounds [9]; sauerkraut retains significant amounts of vitamin C [9].

**[П]** Transfer to the Russian tradition: the data were obtained predominantly on Chinese northeast sauerkraut; Russian cultivars, salting practices, and temperature regimes may produce a different profile. All conclusions about “Russian sauerkraut” in the present study are transfers requiring verification.

### 2.2. pH, titratable acidity, and perceived sourness are three different quantities

**[Д]** pH reflects hydrogen-ion activity; titratable acidity (TA) reflects the total acid reserve (the amount of alkali required for neutralization). These quantities can diverge: products with low pH but non-corresponding TA have been documented [14]. Perceived sourness correlates primarily with the ratio of sugars to TA rather than with pH [16, 17]; different acids at equal pH may differ in sensory intensity. The physiology of sour taste involves pH-dependent ionic mechanisms in taste cells [15]; a trigeminal component (the burn of vinegar) adds a second perceptual channel [18].

**[Д → П]** For the shchi matrix, a third parameter is also relevant — **buffer capacity**: the system’s ability to resist changes in pH. Shchi contain proteins, amino acids, phosphates, organic acids, salts, starch, and fat and therefore constitute a buffered system. Adding the same dose of acid to shchi with different buffer capacities will produce different pH shifts, making buffer capacity a necessary experimental measurement (transfer of general solution chemistry to shchi — level [П]).

**Protocol for measuring buffer capacity.** Because buffer capacity is included in the measurements of both companion studies [47], its method is fixed here. A soup sample is homogenized and filtered according to one rule used for all samples (removal of suspended solids and fat emulsion); titration is performed with a standardized alkali solution (NaOH of known concentration) at controlled temperature to a specified pH endpoint (for example, pH 6.0), with the titration curve recorded; the measure of buffer capacity is the volume of titrant per unit of sample required to reach the endpoint. The heterogeneity of soup (proteins, starch, fat, organic acids) makes standardization of sample preparation essential: this, rather than titration itself, is the main source of dispersion.

**Buffer-sensitivity coefficient.** For comparison of matrices, a working index is introduced: **βₚ = Δ(added acid) / ΔpH** — the amount of acid required for a unit pH shift in a given soup matrix. The higher βₚ, the more strongly the buffer system “damps” acidification: two portions of shchi with the same initial pH may require markedly different amounts of brine to achieve the same shift. The index is obtained from the titration curve using the common protocol; its practical meaning is to translate recipe doses of acidifier from “liters of brine” into the “expected pH shift of this matrix.” The buffer profile of soup matrices as a subject in its own right (βₚ across soup classes and the contributions of matrix components) is taken outside the scope of the present study, into a separate project article.

### 2.3. Taste interactions

**[Д]** Salt and sugar suppress perceived sourness [13]; in fatty media there are effects of mutual suppression (sweetness ↔ “creaminess”) that depend on the taster’s phenotype [19]; sweetness–acidity–fat interactions have been demonstrated in consumers [20, 23]; the broader framework is given in [21]. Acid and umami also interact, and the effect may be asymmetric (increasing acidity can reduce perceived umami). *(The term “umami” — from Japanese* umai, *“delicious” — denotes the fifth basic taste, “savory” or “brothy”; its chemical carriers are glutamic acid (glutamate) and certain nucleotides characteristic of meat, mushrooms, ripe tomatoes, and fermented foods.)*

**[Г]** Applied to shchi: umami components (tomato, mushrooms, meat) may alter the overall flavor balance and the relative salience of sourness. The direction and magnitude of this effect in the shchi matrix are unknown and require testing. (Earlier formulations such as “umami shifts attention” were psychological interpretations and have been removed from the present edition.)

### 2.4. Tomatoes

**[Д]** The principal organic acids in tomato are citric and malic acids; their ratio and total content depend substantially on cultivar and ripening stage (unripe fruit has higher acidity and lower sugar and glutamate) [25, 26, 27]. The chemical profile is broader than the pair of “major acids”: it also includes, among other compounds, ascorbic acid and free amino acids, including glutamate — the principal carrier of umami in ripe fruit [26, 27]. Tomato sensory qualities are predictable from the metabolite profile [28]. Of particular importance here is a study showing that fermentation of **unripe tomatoes** by yeasts and lactic acid bacteria produces a profile of organic acids (citric, acetic, malic, lactic) and umami amino acids [24].

### 2.5. Sorrel and oxalates

**[Д]** Sorrel leaves contain 273–954 mg of total oxalates per 100 g of fresh mass [38]; oxalates contribute to both sour **and astringent** sensory perception [22, 38]. Sorrel soup retains a sour taste after processing and dilution; smetana reduces the fraction of soluble oxalates through calcium binding [38]; cooking and blanching reduce oxalic-acid levels [30].

**[П]** Sorrel is an experimentally valuable case because it shows that “sour taste” is not equivalent to the presence of ordinary food acids. Sour sensation, astringency, mineral interactions, and green aroma act simultaneously here; two systems with the same pH may be sensorially completely different. This directly supports the central hypothesis of the study (§7, P1–P2).

### 2.6. History and cultural context

**[Д]** There are no studies of shchi as an object of food science. The historical-cultural layer comprises etymology [33], the *Domostroi* [34], works by food historians [35, 36], Pokhlebkin [39], cultural studies of the role of soups in the Russian tradition [32], and the status of sour-dairy tastes [31]. Related soups (*kapuśniak*, kapusnyak, *kapustnica*, *Sauerkrautsuppe*) are documented mainly in culinary literature [40]; kapusnyak is associated with the Cossack cuisine of Zaporizhzhia [40].

**Caveat on historical causality.** Claims such as “sour dressings replaced expensive salt” [35] require weakening: high salt prices in certain historical and social contexts *may* have increased the importance of alternative ways of shaping flavor; the history of salt prices is a separate subject, and no causal inference is made here. What is unambiguous [Д] is only that sour products simultaneously performed flavoring and preservation functions [11].

**Nutritional context.** Sauerkraut combines the probiotic potential of lactic acid fermentation [11] with retention of significant amounts of vitamin C [9]; sorrel shchi require attention to oxalate load, which is reduced by cooking and blanching [30] (see also the health caveat in §9). These data are reference information in the present study and are not included in the model.

**Diaspora contrast.** Shchi have no analogue of either Shanghai *luosong tang* or the “Borscht Belt” [47]: unlike borscht, they lack a pronounced diasporic history. Working hypotheses for the contrast are that borscht has a strong visual marker (red color), an adaptable sweet–sour balance, and a historical connection to Ashkenazi identity; shchi have neither. A comparative analysis of the diasporic trajectories of the two dishes is deliberately bracketed: it belongs to the joint methodological paper of the project, not to the structure of the acid–flavor profile.

---

## 3. Theoretical Framework: Three Levels of the System

Three related but non-identical systems are distinguished:

```
CHEMICAL LEVEL               SENSORY LEVEL                 CATEGORICAL LEVEL
molecules, pH, TA,      →     perceived sourness,      →   “shchi / not shchi / how much like shchi”
buffer capacity,              sourness character, balance   (cultural recognition)
acid profile
```

Each arrow is not an identity but a lossy mapping. Consequences:

- identical chemistry does not guarantee identical sensory perception (matrix effects, §§2.2–2.3);
- identical sensory perception does not guarantee identical categorization (cultural prototype, §5);
- therefore “acidity of shchi” and “shchi-ness” are separate objects, related empirically rather than by definition.

### 3.1. Decomposition of the acid profile

The term “acid profile” is formally defined as the vector:

**A = (I, C, D, P, R)**, where

- **I** — intensity of perceived sourness (scale 0–10);
- **C** — acid composition: lactic / acetic / citric / malic / oxalic acids and their combinations;
- **D** — duration of sour sensation, including aftertaste;
- **P** — temporal position of acidity: attack (first sensation), middle, finish;
- **R** — character: soft, sharp, astringent, fruity, lactic.

Each component is tied to a concrete measurement method — without this, the vector remains a concept rather than a measurement instrument:

| Component | Measurement method |
|---|---|
| I — intensity | gLMS sensory scale (general Labeled Magnitude Scale with verbal anchors); a calibrated 0–10 scale with fixed reference samples is acceptable |
| C — acid composition | HPLC (organic acids) / GC–MS (volatile components) + descriptive sensory analysis |
| D — duration | temporal sensory analysis: time–intensity (sensation curve) or TDS |
| P — temporal position | TDS (sequence of dominant sensations: attack / middle / aftertaste) |
| R — character | descriptive analysis using an agreed descriptor lexicon (§4.1); free-choice profiling with subsequent projection into a common semantic space is acceptable |

**Vector comparison metric.** To make the claim “the profiles differ” testable, vector A is assigned a metric. Its components are of different types, so the distance between two profiles is defined component-wise, with a typed metric for each component:

| Component | Scale type | Comparison metric |
|---|---|---|
| I — intensity | interval (gLMS / 0–10) | normalized absolute difference \|I₁ − I₂\| / 10 |
| C — acid composition | compositional (acid fractions) | compositional distance after clr transformation (centered log ratios) of profiles; for the sensory version (descriptor set), Jaccard distance |
| D — duration | interval + curve | difference between areas under time–intensity curves (AUC TI) and difference between aftertaste half-lives, normalized to the panel reference range |
| P — temporal position | ordinal (attack < middle < finish) | ordinal distance between dominance positions (0 — same; 1 — adjacent phases; 2 — attack ↔ finish), normalized by 2 |
| R — character | nominal, multidimensional | Mahalanobis distance in principal-component (PCA) space of panel descriptor ratings; for small samples, Euclidean distance between mean descriptor profiles |

The overall distance between profiles is the weighted sum of component-wise distances: **d_A(x, y) = Σⱼ wⱼ·dⱼ(xⱼ, yⱼ)**, where before calibration the weights wⱼ are equal (0.2 each) and have the same status as the weights of the Shchi Index (§5.2): an a priori model to be estimated from panel data. Temporal sensation is thus formalized not by a single number but by an intensity curve I(t): component D corresponds to the area and decay of that curve, while component P corresponds to the position of its maximum and the phase of dominance; recording the temporal course of sensation is included in the panel questionnaire (Appendix D).

The central thesis following from this decomposition is:

> **[Г]** Two portions of shchi may have the same sourness intensity (I) while having completely different acid profiles (C, D, P, R). For example: vinegar-acidified shchi — rapid attack and a short, sharp sensation; cabbage-and-brine shchi — integrated, “long” sourness; sorrel shchi — a sour-astringent profile; tomato shchi — fruity-sour. “Depth of sourness” is not a metaphor but a point in the (D, P, R) space that can be measured; in the questionnaire (Appendix D) it is not collected directly, but computed as an integral characteristic from the separately recorded components D, P, and R.

### 3.2. Two independent scales instead of one

Instead of a single table “score ↔ pH” (which presented the desired relationship as if it had been measured), two independent measurement systems are introduced; the relationship between them is a subject of experiment, not an assumption:

| Chemical axis | Sensory axis |
|---|---|
| pH | sourness intensity I (0–10) |
| titratable acidity | sourness character (R) |
| buffer capacity | temporal profile (D, P) |
| organic-acid profile (C) | balance, acceptability |
| sugars / salt | identification (“similar to shchi”) |

Gastronomic categories (neutral / slight sourness / classic sour / vividly sour) are retained, but exclusively as **sensory** categories, without tying them to pH ranges before calibration.

### 3.3. Causal scheme and confounding variables

To allow the experimental contrasts (§8) to be interpreted causally rather than correlationally, an explicit causal scheme is fixed:

```
COMPOSITION (acids,           TECHNOLOGY            DISH MATRIX (fat,
metabolites, sugars)      →   (slow cooking,    →   salt, starch, proteins,
                               time of addition)     buffer capacity)
                                  ↓                      ↓
                      CHEMICAL STATE (pH, TA, profile C)
                                  ↓
                      SENSORY PROFILE A = (I, C, D, P, R)
                                  ↓
                      CATEGORIZATION (“shchi / not shchi / how much like shchi”)
                                  ↑
           TASTER'S CULTURAL EXPERIENCE (prototype, expectations) —→
```

Confounding variables capable of producing a spurious association at each arrow include serving temperature (affects perceived sourness and aroma); the visual channel (sample color sets an expectation of acidity); fat content and salinity of the matrix (suppress sourness without changing chemistry, §2.3); taster phenotype (individual strength of taste suppression [19]); serving order and panel fatigue; and taster cultural experience (shifts categorization with unchanged sensory profile). Each variable is paired in §8 with a control procedure (confounder table); an uncontrolled confounder renders the corresponding arrow of the scheme non-identifiable, which is explicitly acknowledged in the interpretation of results (§7.1).

---

## 4. Acid Profile of Shchi

### 4.1. Classification of acidity sources: origin × time of addition

An earlier version of the study classified sources as “fermentative / non-fermentative”; review showed this scheme to be inadequate (smetana is a fermented product, but its acid does not arise “in the pot”). A cleaner scheme is proposed along two axes: **origin of the acid** (biogenic — produced by fermentation; raw-material — inherent in the plant; chemical — added as a substance) and **time of addition** to the dish system.

| Source | Origin of acid | Time of addition | Acid profile (C) | Character (R) |
|---|---|---|---|---|
| Sauerkraut | biogenic | before cooking (ingredient) | lactic + citric + acetic [2, 7] | soft, integrated |
| Cabbage brine | biogenic | before / after cooking | lactic (+ acetic) | concentrated, “long” |
| Fermented green tomatoes | biogenic | before cooking | lactic + citric + malic + acetic [24] | complex, with umami background |
| Fermented mushrooms | biogenic | before cooking | lactic | mushroom, umami background |
| Kvass | biogenic | before cooking | lactic + acetic | bready |
| Smetana | biogenic | after cooking (serving) | lactic | lactic, “rounded” [31] |
| Fresh tomatoes | raw-material | during cooking | citric + malic [25–27] | fresh, fruity |
| Fresh green tomatoes | raw-material | during cooking | citric + malic, low sugars [25] | hard, herbaceous |
| Sorrel | raw-material | during cooking | oxalic (+ malic) [38] | sharp, astringent [22] |
| Sour apples (stewed) | raw-material | during cooking | malic | soft fruity [35] |
| Commercial marinade brine | chemical* | before / after | acetic | sharp, short |
| Vinegar | chemical* | after cooking | acetic | sharp, volatile |

\* Vinegar (and commercial marinade brine based on it) is itself a product of fermentation, but in the dish system it functions as a ready-made substance: the acid was produced outside the shchi-cooking process and is introduced from outside. The “origin” axis records precisely this — where the acid arose relative to the preparation of shchi, not how it was manufactured industrially.

The classification implies a practically important distinction **[П]**: biogenic sources carry an *acid profile* plus fermentation metabolites (amino acids, aromas [1, 8, 9]), whereas chemical sources carry a single acid. Hence the working assumption that vinegar can reproduce the intensity (I) of cabbage sourness but not its profile (C, D, P, R). This assumption is tested directly in Experiment 2 (§8).

### 4.2. Cabbage as a functional carrier and independent variable

Cabbage performs several functions in shchi simultaneously: vegetable mass/body, acidity (after fermentation), texture, and an aromatic layer. This makes it an optimal carrier, but not the essence of the dish. The state of the cabbage is a full experimental variable **[П]**:

| State | Fermentation | Sensory reference | Note |
|---|---|---|---|
| Fresh | none | neutral base | dense texture; “glassy” when undercooked |
| Young fermented | phase 1 (*Leuconostoc*) [4] | slight sourness, bright aroma | crisp |
| Mature fermented | phase 2 (*Lactiplantibacillus*) [4, 5] | pronounced acidity, characteristic shchi aroma [9] | standard for sour shchi |
| Over-fermented | prolonged | high acidity, possible harshness | risk of excessive souring |
| Seedlings (historical) | none | green profile | seasonal variant [35] |

Additional parameters of the variable are salt dose during fermentation [2, 5, 37], degree of shredding, cultivar, and washing before addition (a technique that directly reduces incoming acidity; in kapusnyak the cabbage is deliberately not washed [40]).

**Caveat.** Specific acidity ranges for these states (on the order of 1–2% lactic acid and pH about 3.3–3.7 for mature sauerkraut) are transferred from the sauerkraut literature [2, 5, 37]; they require independent measurement for the Russian salting tradition.

### 4.3. Tomatoes: a multifunctional module and hybrid case

**[Д → П]** Tomato is **one of the most pronounced** multifunctional components of shchi (not the only one: sauerkraut is also multifunctional). Tomato works along three axes: acidity (citric and malic acids [25–27]), umami (glutamate [26, 27]), and body (pectins, sugars).

**Green tomatoes are the central experimental case of the study.** The same plant material exists in two states: fresh green tomato (raw-material acidity, little sugar and glutamate [25]) and fermented green tomato (biogenic acidity + native tomato acids + umami [24]). The ladder *fresh green tomato → fermented green tomato → sauerkraut*, with final acidity equalized, allows the variable “pathway by which acidity arose” to be isolated — a direct test of the principal thesis of the paper (see P2–P3, §§7–8). Traditional Russian fermentation of green tomatoes removes the exoticism from the proposal: this is a reinterpretation of an existing practice.

### 4.4. Technological regulators

**[П]** Factors that alter the profile while composition remains unchanged:

- **Slow simmering vs vigorous boiling** — the historical technology of the Russian stove [35, 36]; gentle cooking integrates flavors differently from vigorous boiling.
- **Sorrel cooking time** reduces oxalic acidity [30, 38] — heating as a regulator.
- **Broth fat content** — a matrix modulator of perceived sourness (§2.3).
- **Time of adding the sour component** (classification axis §4.1): early addition produces an integrated taste; late addition produces “foreground” sourness.
- **Rye-flour slurry** (historical rye dressing [36]) — a starchy regulator of body; displaced by potato, while the function remained.
- **Smetana at serving** — a final regulator that reduces perceived sourness without a proportional change in pot pH [31]; in sorrel shchi it additionally binds soluble oxalates [38]. A direct model prediction is given in P4.
- **Serving temperature** — a critical sensory variable: hot and warm shchi may be perceived differently; experiments fix it at 65 ± 2 °C.
- **Resting (day-old shchi).** **[Г]** It is hypothesized that holding changes the profile through diffusion and equalization of the acid–salt background; the claim that “sourness rounds out” is a hypothesis tested in Experiment 4 (0 / 6 / 24 / 48 h, with pH, TA, and sensory measurements).

**Accompaniments (serving layer).** Traditional accompaniments to shchi include black rye bread (including bread rubbed with garlic or served with salo), smetana, and fresh herbs; a stable historical pairing is shchi with porridge (the formula “shchi and porridge” is already attested in the *Domostroi* [34]). As in the companion borscht study [47, §4.4], this layer is treated as an **external cultural modifier**: it affects perception and the cultural status of the dish, but does not enter the structural axes of the Shchi Index. The functional logic of accompaniment is the same as for borscht: starchy bread and porridge provide a neutral counterpoint to the acid axis; salo and garlic provide a fatty and aromatic accent. Smetana is the exception with a dual role: it is both an element of serving and a final regulator of perceived sourness (see above and P4).

### 4.5. Control of perceived sourness: four mechanisms

Four ways of changing the final sourness of shchi are distinguished; conflating them is the principal source of culinary error **[П/Г]**:

| Mechanism | What happens | Techniques | Chemical change |
|---|---|---|---|
| Dilution + matrix change | increased volume, reduced acid concentration, increased viscosity and starchiness | broth, potato, fresh cabbage; washing fermented cabbage | yes, moderate |
| Masking | suppression of perception with unchanged chemistry | smetana, fatty broth, sweetness of carrot and onion | no |
| Chemical neutralization | shift of acid–base equilibrium; CO₂ release; salt formation; change in buffer system and aromatic background | a pinch of baking soda (folk technique) | yes, substantial |
| Compensation | restructuring the relative salience of tastes | strengthening umami (tomato, mushrooms), salt, aromatics | no |

Protocol: when acidity is excessive, use masking first (reversible), then dilution; baking soda only as a last resort because of side effects on aroma and the buffer system; compensation is paradoxical but possible (strengthening the umami background can make sourness seem coherent). When acidity is insufficient, brine is preferable to vinegar (profile C differs, §4.1); sorrel and kvass change the type of dish. Potato is not an “acid absorber” (no neutralization occurs) but a means of dilution and matrix change.

**Caveat on the status of the categories.** The four mechanisms are analytical categories, not mutually exclusive strategies: in actual practice they are combined (masking + compensation when adding smetana to tomato shchi; dilution + neutralization when broth and baking soda are added together). If necessary, they can be decomposed along two axes — chemical/sensory action × reversibility of the technique; for the purposes of the present study, the one-dimensional typology is sufficient provided its non-exclusive nature is explicitly acknowledged.

---

## 5. The Shchi Prototype and Categorical Membership

### 5.1. Why not “necessary features”

An earlier version of the study contained an internal contradiction: acidity was declared simultaneously a “constitutive feature” and an “optional axis.” The contradiction is removed by moving from a logic of necessary conditions to a **prototype logic**:

> Acidity is a strong prototypical feature of shchi, but not a necessary condition for their classification. Sour shchi are closer to the center of the prototype; fresh-cabbage shchi are on its periphery; both points belong to the category.

The same applies to cabbage: it is the most effective carrier of several functions at once (body + acidity + storability), which explains its historical dominance, but it is not a logically necessary element (green and spring shchi [35, 36]).

### 5.2. Shchi Index (ИЩ) — a conceptual model of prototypicality

The **Shchi Index (ИЩ)** is introduced (the Russian name is a mirrored rearrangement of the word *щи*; it is a mnemonic, not an element of the model): the index reads the dish not by composition but by structure. Scientifically, ИЩ is defined as a **conceptual** (uncalibrated) measure of structural similarity to the shchi prototype along five axes, each ranging from 0 to 1:

**ИЩ = w₁·O + w₂·V + w₃·K + w₄·T + w₅·N**

- **O** — liquid base (broth of any kind);
- **V** — vegetable mass/body (cabbage or a functional substitute);
- **K** — acidic component of any origin (variable axis; expected to have the smallest weight — a hypothesis, not a fact);
- **T** — technology (slow simmering / dressed-soup structure). Serving with smetana or an analogue is excluded from this axis: the cooking process and the external serving layer are different entities; smetana is treated as an external cultural serving modifier and a final regulator of perceived sourness (masking, §4.5), following the model of modifiers Г and Тр in the okroshka study [48];
- **N** — richness/body of broth (protein-fat richness or lean equivalents: mushroom umami, flour slurry, oil).

**Operationalization of the scales.** Before calibration, each axis is rated on a three-point ordinal scale with explicit anchors (harmonized with the anchors of the companion ИБ model [47], where they have already been introduced):

- O: 0 — water; 0.5 — weak stock; 1 — rich broth;
- V: 0 — no vegetable mass; 0.5 — a single vegetable component; 1 — pronounced vegetable body (cabbage or a functional substitute in a full proportion);
- K: 0 — no acidic component; 0.5 — background acidity; 1 — pronounced acidity;
- T: 0 — different technology (assembled soup without integrative heat treatment); 0.5 — partial correspondence; 1 — slow simmering / dressed-soup structure (smetana is not part of the scale — it is a serving modifier; see above);
- N: 0 — liquid base without richness; 0.5 — lean equivalent (mushroom umami, flour slurry, oil); 1 — pronounced protein-fat richness.

Intermediate values are allowed; the anchors define calibration points of the scale, not discrete grades.

**Status of the model.** The weights wᵢ, independence of the axes, and even the set of axes itself **have not been established**. In the present study, ИЩ is a scheme that generates predictions; numerical calibration (including the form of the function itself — linear or nonlinear) is the task of Experiment 3, where weights will be derived from panel data rather than assigned by expert judgment. A binary threshold (“ИЩ > x → shchi”) is deliberately not introduced: the category is treated as a continuous degree of prototypicality. The term “Shchi Index” is the primary scientific name; its substantive interpretation is “index of structural similarity to the shchi prototype.”

**Relation to the categorical framework of the companion study.** The categorical structure of shchi can also be described in terms of Ludwig Wittgenstein’s “family resemblance” [45] — a class without a single necessary feature, whose members are connected by a network of overlapping similarities; the two frameworks are not synonymous. The prototype model (E. Rosch [46]) assumes a central exemplar and graded membership around it; family resemblance assumes a network of overlapping features without a single center. ИЩ is primarily prototypical: a continuous degree of similarity to a prototype is its main content; the Wittgensteinian formulation is used as a framework for harmonization with the companion borscht study [47], where it accounts for the scope of the family (the periphery included by genealogy) rather than the structure of the core. Two structural differences between the models are nevertheless fundamental. First, unlike the borscht model [47], ИЩ has no pigment axis: the color of shchi varies (from transparent to greenish) but carries no categorical load, whereas in the borscht-ness index pigment is an independent, albeit optional, axis Ц. Second, acidity occupies mirror-image positions in the two models: in ИЩ, axis K is a strong but optional feature expected to receive the smallest weight, whereas in the borscht model the sour–sweet axis is a necessary filter (K ≥ 0.5 and S₁ ≥ 0.5), and acidity is proposed as the hypothetical strongest predictor of identification (hypothesis H1 in [47]). The pair of models therefore generates a contrastive empirical prediction that can be tested by the same type of experiment.

**A culinary prototype among prototypes.** Prototype structure has been established across very different domains — colors, animals, artifacts [46]; a culinary category differs from them in two respects: the multimodality of the stimulus (taste, smell, color, texture, and temperature are integrated into one similarity judgment) and the cultural conditioning of the center — the prototype is set by tradition and may therefore shift between bearers of different traditions, which is itself a testable prediction (Experiment 3, §8).

### 5.3. Boundary and related cases

Related soups are used not as evidence for the model (that would be circular: define shchi structurally → find similar dishes → declare them confirmation), but as comparative material that delineates the class boundary:

| Dish | Why it resembles shchi | Why it may not be shchi |
|---|---|---|
| *Kapuśniak* / kapusnyak [40] | sauerkraut + brine + soup structure | different cultural category and filling (smoked meats, millet, beans) |
| *Kapustnica*, *Sauerkrautsuppe* [40] | the same sour-cabbage base | different technology and flavor framework |
| Borscht | vegetable mass + broth + sour dressing | required sweet-earthy axis of root vegetables (axis S of the borscht model [47], absent from shchi); different pigment function (betalains, axis Ц [47]); acidity is a necessary filter in borscht (K ≥ 0.5), but an optional axis in shchi |
| Rassolnik | acidity + vegetables + broth | cucumber-and-grain framework, different V |
| Solyanka | acidity + rich base | compositionally different class |
| Vegetable soup | vegetables + liquid | lacks shchi-like structure (T, V) |

The question “does there exist a soup that belongs equally to the prototypes of shchi and borscht?” (a beet–cabbage midpoint) is an open empirical task for comparison of the two models [47].

### 5.4. Lexical boundary: “sour shchi” as a beverage

Historical polysemy of the term is a counterexample to the study’s own etymological argument: “sour shchi” also denoted a specific sour malt-and-honey beverage [35]. This usage is textually attested in Gogol: Chichikov’s day ends with “a bottle of sour shchi” [43] — a beverage is poured from a bottle; soup is not served that way. Consequently, historically the word “shchi” did not even guarantee membership in the class of soups. This limits the evidentiary force of §1.2 and at the same time strengthens the study as a whole: categorical membership of a dish is determined not by the word but by recognition of its structure by bearers of the tradition — precisely what Experiment 3 measures. The theoretical conclusion from the counterexample should be stated explicitly: the historical polysemy of the word “shchi” does not undermine the prototype model but supports it — the lexical category proves to be as graded and polysemous as the culinary one. At the same time, polysemy shows that the word is an unreliable witness to structure; hence the methodological principle of the present study: the category is measured through recognition by bearers (Experiment 3), not through lexical analysis.

### 5.5. Formal type code

For compact notation of variants, a **type code Щ = (O, V, K, T, N)** is introduced — mirroring the code Б = (Ц, К, Б, Т, С) of the companion borscht study [47] and the code Ок = (О, Х, Н, П, К) of the okroshka study [48]. The coordinates of the code correspond semantically to the axes of ИЩ (§5.2), but their status differs: the code is a **taxonomic** instrument (what kind of shchi these are), whereas the index is a **metric** instrument (how fully a dish realizes the features of the class). The code records discrete grades; the ИЩ scales are ordinal ratings on the same axes.

Coordinate grades (a preliminary template; the final typology is to be refined using data from Experiments 0 and 3):

- **O (liquid base):** O1 — water; O2 — weak stock; O3 — rich broth.
- **V (vegetable body):** V1 — sauerkraut; V2 — fresh cabbage; V3 — green mass (sorrel, nettle, ground elder); V4 — mixed.
- **K (acid source):** K1 — sauerkraut; K2 — brine; K3 — sorrel (oxalic acid); K4 — vinegar; K5 — kvass; K6 — mixed or other source.
- **T (technology):** T1 — slow simmering (day-old shchi); T2 — simple boiling; T3 — dressed-soup structure (sequential addition with integrative heat treatment); T4 — assembled.
- **N (richness):** N1 — meat richness; N2 — mushroom or other lean equivalent (umami); N3 — flour slurry; N4 — no richness (“thin” shchi).

Examples: classic day-old shchi — (O3, V1, K1, T1, N1); green shchi on broth — (O3, V3, K3, T2, N1); fasting shchi on water with a flour slurry — (O1, V1, K1, T2, N3). Unlike the borscht code, the Щ code has no pigment coordinate: shchi color varies but carries no categorical load (§5.2).

The code transforms the set of shchi into a finite-dimensional discrete space in which **distance between types** is defined as the number of non-matching coordinates (Hamming distance). As in the companion study [47], unweighted Hamming distance is declared an **explicit baseline** metric: the substantively preferable generalization is a typed weighted sum d_f(Щᵢ, Щⱼ) = Σⱼ wⱼ·dⱼ(Щᵢⱼ, Щⱼⱼ), where for nominal coordinates (V, K), dⱼ is binary mismatch, while for ordered scales (O, T, N) it is a normalized ordinal distance between positions; weights wⱼ are taken from calibration of ИЩ (Experiment 3). The criterion for accepting the more complex metric is the same as in [47]: complexity is accepted only if it predicts sensory and identification similarity of samples better than the Hamming baseline. **[Г]**

### 5.6. Place of the model in the trilogy: three category configurations

**[Г]** The Shchi Index forms a methodological trilogy with models ИБ [47] and ИО [48]; the models are not reducible to one another:

| Parameter | ИЩ (shchi) | ИБ (borscht) [47] | ИО (okroshka) [48] |
|---|---|---|---|
| Constitutive feature | technology (slow simmering), vegetable mass | taste balance (K, S₁) | physical parameters (Х, Н) |
| Necessary filter | none | taste: K ≥ 0.5 and S₁ ≥ 0.5 | physical: Х ≥ 0.5 and Н ≥ 0.5 |
| Core threshold | none (threshold-free model) | ИБ ≥ 0.6 | ИО ≥ 0.6 |
| Acidity | optional axis, expected to be weakest | necessary filter, hypothetical strongest predictor | variable axis with substitutable carrier (axis K + code О) |
| Multifunctional carrier | sauerkraut (V, K, T) | beet (Ц¹, S₁, S₂, T) | kvass (O, K, Г) |
| Type code | Щ = (O, V, K, T, N) | Б = (Ц, К, Б, Т, С) | Ок = (О, Х, Н, П, К) |
| Convergent analogue/control | kapusnyak | gazpacho / luosong tang | tarator / šaltibarščiai / gazpacho |

*Note to the table.* In the “multifunctional carrier” row for ИО, carbonation (Г) is listed: it is a modifier, not an index axis — kvass covers axes O and K and modifier Г, but not axes Х, Н, П, З; in the ИЩ and ИБ rows only axes are listed. Identically named letters in different models do not necessarily denote the same measured variable: for example, axis O in ИЩ spans “water → rich broth,” while in ИО it spans “neutral water → fermented sour base”; in joint reading they should be distinguished as O_щ, O_б, O_ок. A unified metalanguage of the trilogy’s features is a task for a separate methodological paper of the project.

The trilogy’s hypotheses are mirror-like and mutually testable: acidity is a weak axis of shchi, a strong predictor in borscht, and a substitutable carrier in okroshka; compensatory architecture is common to all three (P6/P8 of the present study, H8 in [47], [48]); cross-class tests (removing acid from all three dishes; serving okroshka hot) can be performed within one restaurant cycle (§8). A full comparison of the three architectures is the subject of a joint methodological article; the present table records a working template. The striking symmetry of the three configurations (no filter / taste filter / physical filter) is declared a **hypothesis of the trilogy, not an established fact**: the models may in part have been selected to fit the symmetry, and the experimental program is entitled to destroy that symmetry — in which case the elegance of the construction will have been a falsified prediction, not an ornament.

---

## 6. Conclusions from the Analysis: What the Model Assumes

The assumptions of the study (levels [П] and [Г]) can be collected into an explicit list — these are statements that the model *asserts* but the sources *do not prove*:

1. Sensory sourness in shchi is not a monotonic function of pH; at controlled pH it depends on the dish matrix (fat, sugars, salt, umami) and on the acid profile.
2. Biogenic (fermented) carriers of acidity produce a different sensory profile from pure acids of the same intensity because of fermentation metabolites.
3. Cabbage is a functional carrier; identification of a dish as shchi is determined by a combination of structural features, not by the presence of cabbage alone.
4. Historical data (etymology [33], seasonal cycle [35, 36], Carroll’s observation [42]) are **consistent** with this model but do not confirm it: only experiment can provide confirmation.

---

## 7. Falsifiable Predictions

The model generates eight testable predictions. Each is accompanied by a falsification condition.

- **P1.** At the same pH, different acid systems (vinegar / brine / tomato / kvass) will produce different perceived sourness and a different sourness character. *Falsification:* at equal pH, samples are sensorially indistinguishable.
- **P2.** At the same titratable acidity, different acids will likewise differ in sensory profile. *Falsification:* the differences disappear when TA is equalized.
- **P3.** Fermented carriers (brine, sauerkraut, fermented green tomato) will receive higher ratings for depth/integration of sourness than pure acids adjusted to the same pH and TA. *Falsification:* pure lactic acid is indistinguishable from brine at equal pH and TA.
- **P4.** Smetana will alter perceived sourness of shchi without a proportional change in the pH of the portion. *Falsification:* the sensory shift is fully explained by the measured pH/TA shift.
- **P5.** The set of structural features (O, V, K, T, N) will predict identification as “shchi” better than the single feature “cabbage present.” *Falsification:* cabbage presence predicts identification no worse than the full model.
- **P6.** Compensatory architecture (general principle): weakening any one ИЩ axis is partly compensated by strengthening others while preserving identification. *Falsification:* identification depends on each axis independently and additively, with no compensatory interactions (a model without axis-interaction terms describes the data no worse than a model containing them).
- **P7.** Strengthening P3: at equalized pH and TA, fermented carriers (brine, sauerkraut) and pure acids differ in sensory profile also in a **blinded subseries** (visual channel excluded — brine color, turbidity; opaque vessels, §8). *Falsification:* the differences disappear in the blinded subseries — in that case they are mediated by the visual channel rather than the flavor profile itself.
- **P8.** A specific compensatory pair (symmetrical to H8 in [47]): weakening axis K is compensated by strengthening axes T and N — fresh-cabbage shchi with pronounced broth richness and a dressed-soup structure (“rich” fresh shchi) retain identification no worse than sour shchi at a comparable total ИЩ. *Falsification:* fresh shchi with strengthened T and N lose identification to the same extent as fresh shchi without such strengthening — the K→(T, N) compensation channel is absent.

**Effect sizes.** To make the predictions falsifiable, quantitative specifications are added; thresholds are fixed before the series: P1 — a difference in perceived sourness between acid systems at equal pH of at least d = 0.5 on scale I; P2 — the same at equal TA; P3 — an advantage of fermented carriers over pure acids in ratings of depth/integration of sourness of at least d = 0.5; P4 — the sensory shift produced by smetana significantly exceeds the shift predicted by the measured change in pH/TA (residual of the model “sensory response ~ pH + TA”); P5 — the full model exceeds the single feature “cabbage present/absent” in classification quality (AUC) by at least a prespecified amount; P6 — axis-interaction terms provide a significant improvement in identification-model quality (ΔAUC or ΔR² beyond the additive model) on the test subset; P7 — the difference between fermented carriers and pure acids on sourness-profile scales (at least d = 0.5) persists in the blinded subseries; P8 — the difference in the proportion of “shchi” identifications between “fresh shchi with strengthened T and N” and “fresh shchi without strengthening,” at equal ИЩ, is at least a prespecified amount. The formulation “there will be a difference” without a threshold is considered insufficient and is not accepted into the experimental series.

### 7.1. How to interpret negative results

A null or negative experimental result does not necessarily refute the entire model: it localizes failure to a specific arrow of the causal scheme (§3.3). The following interpretation table is fixed in advance:

| Negative result | What it refutes | What it does NOT refute |
|---|---|---|
| At equal pH and TA, pure acids are indistinguishable from fermented carriers (P3), including in the blinded subseries (P7) | contribution of fermentation metabolites to the sensory character of sourness | differences in chemical profiles C; practical value of fermentation (preservation, aroma) |
| Smetana does not change perceived sourness at unchanged pH (P4) | masking mechanism for smetana | other mechanisms (dilution, compensation); role of smetana in texture and balance |
| The full model does not outperform “cabbage present/absent” (P5) | predictive value of the multi-axis ИЩ model in this sample | prototype structure of the category as such (the axes or their weights may be wrong rather than the framework) |
| Compensatory interactions are not detected (P6), or the specific K→(T, N) channel is absent (P8) | nonlinear ИЩ architecture — the model is simplified to an additive one | the set of axes itself and their weights |
| There is no cross-class asymmetry with borscht (acid removal) | the mirror hypothesis of the pair of models (H6 in [47]) | internal predictions of each model considered separately |

---

## 8. Experimental Program

General protocol for all experiments: the baseline requirement common to the trilogy is 5 independent batches of each variant; the minimum acceptable size of a pilot subseries is 3 batches; a sensory panel of 8–12 tasters; samples coded with random three-digit codes; serving order randomized with counterbalancing; serving temperature fixed at 65 ± 2 °C; sample volume fixed; water and neutral bread between samples; a subset of samples evaluated repeatedly (panel-reproducibility check). The statistical plan is specified in advance: pH and TA — one-way ANOVA or the Kruskal–Wallis test; sensory ratings — a mixed-effects model of the form “rating ~ variant + serving order + temperature + (1 | taster) + (1 | batch)”; for batches prepared on different days, a random effect (1 | day) is added because batches from the same day are not fully independent (shared raw-material lot, common kitchen regime); identification — logistic regression on axis features. The protocol is harmonized with the experimental program of the companion borscht study [47]: divergences (number of independent batches, serving temperature — borscht has cold variants for which 65 ± 2 °C is inapplicable) reflect the specificity of the object and are noted there; panel questions in Experiment 3 of both studies have been made compatible (binary identification + graded similarity). The protocol is supplemented by three blocks. **Blinding and carryover:** between samples — water and neutral bread with a fixed interval of at least 2 minutes; with many variants, the panel is divided into balanced incomplete blocks to reduce taster fatigue; the contribution of the visual channel is assessed in a control subseries using opaque vessels. **Power and multiple comparisons:** the number of batches and panel size are justified by power analysis for the minimum substantively meaningful effect size (§7); if power analysis requires a larger n, the baseline requirement (5 batches, as in [47]) is increased but not reduced below the trilogy-wide minimum; multiple comparisons use Holm correction or FDR control. **Collinearity and open data:** axes O, V, K, T, N are correlated through multifunctional carriers (sauerkraut simultaneously covers V, K, and part of T), so the regression in Experiment 3 includes multicollinearity diagnostics (VIF) and, if needed, regularization (ridge) or a shift to latent variables; after completion of the series, open data are published — raw sensory ratings, chemical measurements, and recipe specifications. The statistical plan is harmonized with [47] and is identical to it in the shared parts.

**Matrix of confounding variables.** Each confounder in the causal scheme (§3.3) is paired with an explicit control measure:

| Confounding variable | Bias mechanism | Control measure |
|---|---|---|
| Serving temperature | changes perception of sourness and volatiles | fixed at 65 ± 2 °C; thermometry of each portion |
| Visual channel | color sets an expectation of acidity | control subseries in opaque vessels |
| Serving order, fatigue | contrast and adaptation effects | randomized counterbalancing; balanced incomplete blocks; pauses ≥ 2 min |
| Matrix (fat, salt, sugars, starch) | suppression of sourness without chemistry changing | recipe standardization; measurement of actual fat content/salinity of each batch; covariates in the model if needed |
| Batch / day | between-batch variation, common raw-material lot | random effects (1 | batch), (1 | day); at least 3 independent batches |
| Taster phenotype | individual strength of taste suppression [19] | random effect (1 | taster); repeated evaluation of a subset of samples |
| Taster cultural experience | shifts categorization with unchanged sensory profile | experience questionnaire; Experiment 0 of the present program (survey of tradition bearers) as an external calibration slice |

**Pilot and main series.** The series is conducted in two stages: a pilot (panel of 8–12 tasters — a typical size for descriptive sensory analysis — and the minimum number of batches) serves to debug the protocol, test panel reproducibility, and estimate actual effect sizes; the main series is planned from the pilot results, with batch count and panel size determined by power analysis, and expanded through tasting by restaurant patrons with informed consent (without replacing the panel).

### Experiment 0. Pilot survey on necessary features

**[Г]** Mirroring Experiment 0 in the companion borscht study [47]: before the laboratory series, bearers of the tradition (at least 30 participants) are surveyed on which features they consider necessary for shchi (cabbage, sourness, broth/richness, slow simmering or dressed-soup structure, smetana at serving, green mass). The questionnaire is harmonized with those of the companion studies [47], [48] and includes symmetrical blocks for all three dishes of the trilogy — providing a comparable empirical baseline of human classification and an external calibration slice for the latent variable in Experiment 3 (previously this role in the present study was played by Experiment 0 of the paired program; a dedicated survey makes calibration direct). Expected result: cabbage and sourness receive a higher proportion of “necessary” responses than richness and slow simmering — a direct test of the hierarchy of ИЩ axes before the laboratory series. Survey results are not entered into ИЩ: they calibrate interpretation of the axes, not the model.

### Experiment 1. Stage of cabbage fermentation

One recipe; variable — state of the cabbage: fresh / young fermented / mature fermented / over-fermented + brine.  
**Measurements:** pH, TA, buffer capacity; sensory profile using vector A = (I, C, D, P, R) + balance + acceptability.  
**Tests:** dependence of profile on fermentation phase; hypothesis that “depth” is maximal for mature (not over-fermented) cabbage.

### Experiment 2. Type of acid and pathway of its formation (four-level design, with controls)

The design decomposes the transition “molecule → product” into four levels so that effects conflated in a two-level scheme can be separated:

- **Level A — real products:** fresh-cabbage shchi + acidifier: brine / vinegar / tomato / kvass / stewed apples.
- **Level B — pure acids individually:** the same shchi + lactic / acetic / citric / malic acids.
- **Level C — mixtures of pure acids matching the profile:** for each Level A acidifier, a mixture of pure acids is prepared to reproduce its profile C according to HPLC data (for example, lactic + citric + acetic in the proportions found in brine) — without other metabolites or accompanying substances.
- **Level D — real product in a standardized matrix:** the same Level A acidifier is introduced into a matrix with normalized NaCl and dry-matter content, in order to separate the product’s contribution from accompanying changes in the matrix.

**Logic of contrasts:** B→C isolates the effect of the *acid profile* (one molecule versus its natural mixture); C→D isolates the effect of *fermentation metabolites and accompanying substances* (amino acids, aromas); D→A isolates the effect of the *matrix* (fat, salt, starch, buffer capacity). Thus prediction P3 (“fermented carriers outperform pure acids”) is decomposed into three testable links, and a negative result at any link localizes the source of the effect.

**Control:** fresh cabbage + lactic acid (separates the effect of lactic acid from the effect of a complete fermented product).  
**Equalization subseries:** 2A — pH equalization; 2B — TA equalization; 2C — equalization of both.  
**Separate line (experimental center of the study):** the ladder *fresh green tomato → fermented green tomato → sauerkraut* at equal final acidity [24] — isolation of the variable “pathway by which acidity arose.”  
**Tests:** P1, P2, P3. The key question in subseries 2C is whether differences between acids remain when pH and TA are both equal — if they do, “acid character” is determined by the molecule and/or matrix rather than concentration alone.

### Experiment 3. Prototypicality (calibration of ИЩ)

The panel is **not told** about the ИЩ model. Samples: classic sour shchi; fresh-cabbage shchi; green shchi; nettle shchi; chard shchi; kapusnyak; rassolnik; shchi with green tomatoes; vegetable soup; borscht.  
**Panel question:** “How similar is this sample to shchi?” (0–10) — not the binary “shchi/not shchi.” In parallel, binary identification (“do you classify the sample as shchi?” yes/no) is recorded for direct comparability with the protocol of Experiment 3 in the companion borscht study [47], where the binary question is primary and is supplemented by a graded one — as well as **confidence** in the answer (0–3). The measures are separated into two quantities: **membership** (“how much is this shchi?”), with two indicators of the latent variable — binary identification and graded similarity — and **boundary certainty** (“how confident am I in the classification?”, 0–3). Confidence is deliberately removed from the latent membership variable: an answer “definitely not shchi” with confidence 3 demonstrates that confidence measures boundary certainty rather than direction of membership. An additional uncertainty metric is the entropy of the binary decision based on response proportion p: H = −p·log₂p − (1−p)·log₂(1−p) — canonical shchi and obvious non-shchi have H ≈ 0, while at the class boundary (p ≈ 0.5) H is maximal. Testable consequence: peripheral samples should show not merely intermediate membership values, but increased entropy together with reduced boundary certainty. Including borscht in the sample set mirrors the inclusion of shchi in Experiment 3 of [47] as an inter-class negative control; together, the two experiments provide a cross-check of predictions P5 and H4 [47] at the class boundary. The set additionally includes a series in which the acidic component is removed — shchi without an acidifier while O, V, T, N are preserved: the drop in identification proportion is compared with the analogous acid-removal series for borscht in the second week of the cycle [47]. The models predict an asymmetry: for shchi (K is an optional axis expected to have the smallest weight), the drop is moderate; for borscht (K is a necessary filter), it is sharp; this is a direct cross-class test of hypothesis H6 of the companion study [47] and the strongest joint test of the pair of models.  
Sensory features of the samples are collected in parallel (axes O, V, K, T, N are evaluated independently).  
**Analysis:** regression of “similarity to shchi” on axis features; ИЩ weights are derived from the data rather than assigned by experts. To avoid circular calibration (estimating and testing the model on the same data), the sample is split in advance into **training and test subsets by batches and days** (not by individual ratings: ratings from the same batch are dependent): weights and functional form are estimated only on the training part, while model quality is evaluated on held-out batches and days not used in fitting. Panel responses serve as an **operational criterion** of categorical membership (the term “gold standard” is deliberately avoided: 8–12 tasters are a working reference for laboratory calibration, not a reference for the cultural category as such): a cultural category is by definition measured through recognition by its bearers; an additional panel-independent external criterion is documented historical-cultural membership of the dish (by analogy with the two-level scheme in [47]). **Separation of panels.** The sensory panel is responsible for acidity, aroma, and texture; categorical responses are additionally collected from an expanded panel of tradition bearers (at least 30 people, questionnaire from Experiment 0) — cultural experience thereby ceases to be a confounder and becomes one of the main independent variables. **Adversarial subseries:** deliberately constructed counterexamples are included — a sample with formally high ИЩ that bearers are expected not to call shchi, and canonically named shchi with deliberately reduced ИЩ: disagreement between the index and the panel on such samples diagnoses holes in the model more strongly than agreement on prototypes. **Generalization check:** in addition to splitting by batches and days, leave-one-recipe-out validation is used — the weights are trained with one entire type of shchi excluded, after which the model must correctly classify a recipe it has never seen (for example, a regional variant). Comparison of the predictive power of the full model with the single feature “cabbage present/absent” is performed on the test part.  
**Tests:** P5; the architecture of the model itself (nonlinearity and axis interactions are possible).

### Experiment 4. Dynamics of resting (day-old shchi)

One batch of shchi; sampling points: 0 / 6 / 24 / 48 h under standardized cold storage and reheating to 65 ± 2 °C.  
**Measurements:** pH, TA, buffer capacity; sensory profile using vector A + acceptability.  
**Tests:** the hypothesis that acidity “rounds out” during resting (§4.4); expected result — dynamic curves of chemical and sensory indicators, whose divergence is itself informative.

### Venue and schedule: restaurant format (shchi week)

The experimental program is designed for implementation in a working restaurant and forms, together with the program of the companion study [47], a single two-week cycle: **week one — shchi** (the present program), **week two — borscht** [47]. The restaurant format is chosen for three reasons: (1) ecological validity — dressed soups are prepared and evaluated under the natural conditions of a professional kitchen rather than a laboratory; (2) distributing batches across different days reduces their dependence but does not eliminate it completely (shared raw-material lot, common kitchen regime), so replicates are not automatically treated as independent — batch and day enter the statistical model as random effects (see the statistical plan), and at least 3 batches per variant fit within a working week; (3) a restaurant kitchen provides the control of temperature, mass, and time required by the common protocol (65 ± 2 °C at serving).

Schedule for the shchi week: days 1–2 — Experiment 1 (stages of cabbage fermentation); days 3–4 — Experiment 2 (real acidifiers, pure acids, green-tomato ladder); day 5 — Experiment 3 (prototypicality panel, including borscht as a sample); in parallel throughout the week — Experiment 4 (resting points 0 / 6 / 24 / 48 h). Preparatory work — fermenting cabbage and green tomatoes to the required stages — begins 2–4 weeks before the cycle. The sensory panel consists of invited tasters (8–12 people) under the common protocol; with restaurant approval, tasting by patrons under informed consent may be used to expand the sample (without replacing the panel). During the second week of the cycle, the present program supplies shchi (fresh and sour) as an inter-class negative control for Experiment 3 of [47]; the statistical plan and panel requirements do not change.

---

## 9. Discussion and Limitations

**Strengths of the construction.** The three-level framework eliminates the conflation of chemistry and categorization; the decomposition A = (I, C, D, P, R) converts metaphors (“deep sourness”) into measurable components; the model generates eight falsifiable predictions; the experimental program includes controls and pure acids, allowing the effect of the molecule to be separated from the effect of the matrix.

**Limitations.**

1. The study is theoretical; all numerical reference points (acidity of sauerkraut, pH ranges) are transferred from data on sauerkraut [2, 5, 37] and adjacent systems [14, 16, 17], level [П].
2. The main body of fermentation data was obtained on Chinese northeast sauerkraut [1–8, 10]; the Russian tradition may differ; the two-phase fermentation scheme is a simplification [10].
3. Perception is individual: the strength of taste suppression depends on taster phenotype [19]; sensory scales are averages.
4. The soup matrix (a hot buffered medium with a fat emulsion) differs from the model systems studied; the buffer capacity of shchi has never been measured.
5. Historical data [33–36, 39, 42] are used as contextual evidence consistent with the model, not as proof; causal historical conclusions (for example, about a relationship between sour dressings and the price of salt) are deliberately not drawn.
6. Health caveat: regular consumption of sorrel shchi by people with oxalate-related risks requires cooking/blanching the sorrel [30, 38].
7. Before calibration, ИЩ is a conceptual scheme; the set of axes, their independence, and the form of the function may be revised using data from Experiment 3.
8. The ИЩ axes are correlated through multifunctional carriers; regression weights obtained from such predictors are unstable without collinearity diagnostics and, if needed, regularization — this is built into the statistical plan (§8), but remains a limitation before calibration.

**Open questions.** The optimum acidity of classic shchi (analogous to a sugar/acid ratio [16, 17]); quantitative dynamics of resting; the “middle ground” between the shchi and borscht prototypes [47]; transfer of the model to rassolnik and solyanka; temperature dependence of sourness perception in shchi; the status of umami — a modulating module (§2.3) or an independent axis in models of shchi and borscht, given its asymmetric interaction with acidity. Shared tasks of the paired studies — a general theoretical framework “chemistry → sensory perception → category,” a joint historical chronology, and mapping regional variation in both dishes — are assigned to a separate methodological paper of the project and are outside the present study.

---

## 10. Conclusions

**The sources show:** cabbage fermentation is a controllable multifactor process producing a profile of several organic acids [1–10, 37]; pH, titratable acidity, and perceived sourness are three diverging quantities [13–17]; tomato and green tomato (including fermented green tomato) are chemically substantive components of the acid–umami profile [24–28]; sorrel contributes a sour-astringent component through oxalates [30, 38].

**The model assumes:** shchi acidity is a system property decomposable into vector A = (I, C, D, P, R); biogenic and chemical acidity sources are not sensorially equivalent even at equal intensity; cabbage is an optimal but not necessary functional carrier; shchi form a prototypical category in which acidity is a strong but optional feature; categorical membership of a dish is measured by degree of prototypicality rather than by a binary threshold.

**The experimental program must test:** predictions P1–P6 (§7) through four experiments with control samples, pure acids, a statistical plan, and temperature control (§8).

**Practical significance** (if the model is confirmed): deliberate construction of shchi with a specified acid profile; standardization of sour soups in food service; a framework for recipe development; methodologically, together with the borscht model [47], ИЩ forms the beginning of a general theory of prototypicality for dressed soups: a dish is defined by a recognizable structure of functions rather than by a fixed composition. The models are not reducible to each other: ИБ includes pigment (Ц¹) and sweetness (S₁, S₂) axes absent from ИЩ, and a two-stage classification procedure (necessary filter K ≥ 0.5 and S₁ ≥ 0.5, followed by a core threshold), whereas ИЩ deliberately has no binary threshold and includes decomposition of the acid profile into temporal components (D, P of vector A), which has no analogue in ИБ. The asymmetry reflects different functional architectures of the dishes: shchi identity is carried primarily by slow-cooking technology and vegetable mass, whereas borscht identity is carried by taste balance and the pigment function of the acid; the pair’s hypotheses are mirror-like (acidity is expected to be the weakest ИЩ axis and the strongest H1 predictor in ИБ) and are therefore mutually testable.

---

## 11. References

The full list appears below (48 entries). Blocks: I — cabbage fermentation [1–12]; II — sourness perception [13–18]; III — taste interactions [19–23]; IV — tomatoes [24–29]; V — sorrel and oxalates [30, 38]; VI — history, cultural context, and category theory [31–46]; VII — related works by the author [47, 48]; additionally — fermentation optimization [37].

---

## 12. Appendices

### Appendix A. Classification of acidity sources

See the table in §4.1 (origin × time of addition × acid profile × character).

### Appendix B. Two acidity scales

See the table in §3.2 (chemical and sensory axes; the relationship between them is a subject of experiment, not an assumption).

### Appendix C. Mechanisms for controlling acidity

See the table in §4.5 (dilution + matrix / masking / neutralization / compensation).

### Appendix D. Sensory-evaluation questionnaire (template)

| Parameter | Scale | Comment |
|---|---|---|
| I — sourness intensity | 0–10 | perceived |
| R — sourness character | soft / sharp / astringent / fruity / lactic | according to §4.1 |
| P — temporal position | attack / middle / aftertaste | the first dominant sensation is recorded separately |
| D — duration | short / medium / long | including aftertaste |
| Temporal profile I(t) | intensity marks at: swallowing / +10 s / +30 s / +60 s | simplified time–intensity recording for components D and P (§3.1) |
| Depth of flavor (umami) | 0–5 | brothiness |
| Body | 0–5 | axis V |
| Richness | 0–5 | axis N |
| Balance / acceptability | 0–10 | |
| Similarity to shchi | 0–10 | Experiment 3 question; panel is unaware of the model |
| Identification (“is this shchi?”) | yes/no | collected in parallel with graded similarity for comparability with protocol [47] |
| Confidence in identification | 0–3 | third indicator of the latent variable “category membership” (§8, Experiment 3) |
| Desire to have it again | yes/no | |

*Samples are coded with three-digit codes; serving order is randomized with counterbalancing; temperature is 65 ± 2 °C; some samples are repeated.*

### Appendix E. Illustrative matrix of ИЩ axes (expert ratings, NOT calibrated)

| Variant | O | V | K | T | N |
|---|---|---|---|---|---|
| Classic sour shchi | 1 | 1 | 1 | 1 | 1 |
| Fresh-cabbage shchi | 1 | 1 | 0 | 1 | 1 |
| Green (sorrel) shchi | 1 | 1 | 1 | 1 | 0.5–1 |
| Spring nettle shchi (reconstruction) | 1 | 1 | 0.5–1 | 1 | 0–0.5 |
| Fasting mushroom shchi | 1 | 1 | 1 | 1 | 0.5 |
| “Empty” shchi | 1 | 1 | 0–1 | 1 | 0 |
| *Kapuśniak* | 1 | 1 | 1 | 1 | 1 |
| Rassolnik | 1 | 0.3 | 1 | 0.7 | 1 |
| Vegetable soup | 1 | 0.5 | 0 | 0.5 | 0 |

*The values are given solely to illustrate the logic of the model and have no empirical status. Calibration is the task of Experiment 3.*

### Appendix F. Traceability matrix: claim → variable → experiment → falsifier

Every substantive claim of the study is traced to a way of testing it and a condition for falsification:

| Claim | Variable(s) | Experiment | Falsifier |
|---|---|---|---|
| Shchi acidity is a system property not reducible to pH | pH, TA, buffer capacity × vector A | Experiments 1–2 | P1, P2 (differences disappear at equal pH and TA) |
| Biogenic carriers are not sensorially equivalent to pure acids | profile C, metabolites; depth/integration rating | Experiment 2 (levels B→C→D) | P3 (pure lactic acid is indistinguishable from brine at equal pH and TA) |
| Pathway by which acidity arises is an independent variable | tomato ladder; vector A | Experiment 2 (separate line) | P2–P3 on the ladder (profiles coincide at equal final acidity) |
| Smetana is a final regulator of perceived sourness | I with portion pH/TA controlled | Experiment 2 (serving subseries) | P4 (sensory shift is exhausted by pH/TA shift) |
| Resting “rounds out” sourness | pH, TA, A at 0/6/24/48 h | Experiment 4 | dynamic curves of chemistry and sensory response do not diverge |
| The category “shchi” is prototypical and multi-axis | axes O, V, K, T, N; similarity 0–10; identification; confidence | Experiment 3 | P5 (full model no better than “cabbage”); P6 (no compensatory interactions) |
| Acidity is an optional shchi axis (unlike borscht) | identification proportion after removal of acidic component | Experiment 3 (removal series) + Experiment 3 of [47] | no cross-class asymmetry (jointly with H6 in [47]) |
| Historical data are consistent with the model | — (context) | — | see the table in §1.2: history does not prove structure |

---

**Revision history (third through sixth editions; the first and second editions were internal drafts and are not included in the protocol).**

*Third edition. Principal changes relative to the second: the three-level framework (chemistry → sensory perception → category) was introduced; the acid profile was decomposed into components (I, C, D, P, R); the Shchi Index (ИЩ) was redefined as a conceptual prototypicality model without calibrated weights (the name retained: ИЩ is a mirrored mnemonic based on the Russian word «щи»); buffer capacity, falsifiable predictions P1–P5, control samples, and a statistical plan were added; historical and etymological arguments were weakened to “consistent with”; the counterexample of “sour shchi” as a beverage was added. The study forms a methodological pair with *Borscht as a Multifactor Culinary System* [47].*

*Fourth edition (harmonization with companion study [47]): a reference to Ludwig Wittgenstein’s concept of “family resemblance” [45] was added in §5.2, the boundary description of borscht was refined in terms of the ИБ model (table in §5.3), and notes were added on the absence of a pigment axis in ИЩ and the mirror-image position of acidity in the two models; a paragraph directly comparing the architectures of ИЩ and ИБ was added to the conclusions (optional K axis versus mandatory K/S filter; threshold-free versus threshold logic of classification); a binary identification question was added to the Experiment 3 protocol and the questionnaire (Appendix D) for comparability with [47]. In addition, the style of historical notes was harmonized with [47] (explicit principle of “consistent context,” §1.2); the experimental program was framed as a two-week restaurant cycle “shchi week / borscht week” together with [47] (§8).*

*Fifth edition (revision following the fourth review of the joint project): vector A = (I, C, D, P, R) was operationalized by a “component → measurement method” table (§3.1); a buffer-capacity measurement protocol was added (§2.2); predictions P1–P5 were supplemented with effect sizes (§7); Experiment 3 was supplemented with a series removing the acidic component — a cross-class asymmetry test with hypothesis H6 of the companion study [47]; the general protocol in §8 was supplemented with visual-channel blinding, balanced incomplete blocks, power analysis, multiple-comparison corrections, axis-collinearity diagnostics, and an open-data plan; the distinction between prototype and family resemblance was clarified and a paragraph on the cognitive literature on prototypes was added (§5.2, source [46]); the theoretical conclusion from the polysemy of “sour shchi” was completed (§5.4); reference paragraphs on nutrition and the diaspora contrast were added (§2.6), along with a caveat on the non-exclusivity of acidity-control mechanisms (§4.5) and the open question of umami as a possible axis (§9).*

*Sixth edition (revision following the fifth review of the joint project): vector A was given a typed comparison metric with weighted distance d_A (§3.1), temporal sensation was formalized as curve I(t) and added to the questionnaire (Appendix D); ИЩ axes received scale anchors 0 / 0.5 / 1 harmonized with the companion model [47] (§5.2); a causal scheme with confounding variables (§3.3) and a confounder-control matrix (§8) were added; Experiment 2 was rebuilt as a four-level design (real products → pure acids → profile-matched mixtures → standardized matrix), separating profile, metabolite, and matrix effects (§8); Experiment 3 was supplemented with a training/test split by batches and days and a third indicator of the latent membership variable — confidence (0–3); the statistical model includes random effects for batch and day, and the claim of “automatic independence” of replicates was corrected; the program was separated into pilot and main series; prediction P6 (compensatory architecture), a table for interpreting negative results (§7.1), buffer-sensitivity coefficient βₚ (§2.2), a summary table of the evidentiary value of historical evidence (§1.2), and a claim-traceability matrix (Appendix F) were added.*

# References

for the study *On the Formation of the Acid–Flavor Profile of Traditional Shchi*

---

## I. Cabbage Fermentation and the Microbiology of Acid Formation

1. Wang J., Sui Y., Lu J., Dong Z., Liu H., Kong B., Chen Q. Correlations between bacterial communities, organic acids, and volatile metabolites of traditional fermented sauerkraut collected from different regions // Food Chemistry: X. 2023. URL: https://www.sciencedirect.com/science/article/pii/S2590157523002833

2. Yang X., Hu W., Ziu X., Jiang A., Yang X., Ji Y. et al. Effect of salt concentration on microbial communities, physicochemical properties and metabolite profile during spontaneous fermentation of Chinese northeast sauerkraut // Journal of Applied Microbiology. 2020. Vol. 129, No. 6. P. 1458–1472. URL: https://academic.oup.com/jambio/article-abstract/129/6/1458/6715232

3. Yang X., Hu W., Ziu X., Jiang A., Yang X., Ji Y. et al. Comparison of northeast sauerkraut fermentation between single lactic acid bacteria strains and traditional fermentation // Food Research International. 2020. URL: https://www.sciencedirect.com/science/article/pii/S0963996920305780

4. Yang X., Hu W., Ziu X., Jiang A., Yang X., Ji Y. et al. Microbial dynamics and volatilome profiles during the fermentation of Chinese northeast sauerkraut by Leuconostoc mesenteroides ORC 2 and Lactobacillus plantarum // Food Research International. 2020. URL: https://www.sciencedirect.com/science/article/pii/S0963996919308129

5. Yang X., Hu W., Jiang A., Ziu X., Ji Y., Guan Y., Yang X. Effect of salt concentration on quality of Chinese northeast sauerkraut fermented by Leuconostoc mesenteroides and Lactobacillus plantarum // Food Bioscience. 2019. URL: https://www.sciencedirect.com/science/article/pii/S221242921930015X

6. Hu W., Yang X., Ji Y., Guan Y. Effect of starter cultures mixed with different autochthonous lactic acid bacteria on microbial, metabolome and sensory properties of Chinese northeast sauerkraut // Food Research International. 2021. URL: https://www.sciencedirect.com/science/article/pii/S0963996921005044

7. Wang J., Liu X., Liu J., Sui Y., Yu W., Kong B., Chen Q. Improving the bacterial community, flavor, and safety properties of northeastern sauerkraut by inoculating autochthonous Levilactobacillus brevis // Food Chemistry: X. 2024. URL: https://www.sciencedirect.com/science/article/pii/S2590157524002955

8. Wu C., Zheng J., Huang J., Zhou R. Reduced nitrite and biogenic amine concentrations and improved flavor components of Chinese sauerkraut via co-culture of Lactobacillus plantarum // Annals of Microbiology. 2014. URL: https://link.springer.com/article/10.1007/s13213-013-0724-8

9. Wieczorek M.N., Drabińska N. Flavour generation during lactic acid fermentation of brassica vegetables — literature review // Applied Sciences. 2022. Vol. 12, No. 11. Art. 5598. URL: https://www.mdpi.com/2076-3417/12/11/5598

10. Cheng K., Tang X., Zhong H., Chen X., Li F., Xie L. et al. Dynamic changes of microorganisms and flavor components during the production of sauerkraut with Lacticaseibacillus paracasei // Food Processing and Nutrition. 2026. URL: https://link.springer.com/article/10.1186/s43014-026-00374-z

11. Peres C.M., Peres C., Hernández-Mendoza A. et al. Review on fermented plant materials as carriers and sources of potentially probiotic lactic acid bacteria — with an emphasis on table olives // Trends in Food Science & Technology. 2012. URL: https://www.sciencedirect.com/science/article/pii/S0924224412000234

12. Huang N., Yu S., Li S., Fang L., Wu Z. et al. Microorganisms, Quality Changes, and Process Optimization in Fermented Vegetable Processing // Food Reviews International. 2026. URL: https://www.tandfonline.com/doi/abs/10.1080/87559129.2026.2707556

## II. Sourness Perception: pH, Titratable Acidity, Sensory Analysis

13. Breslin P.A.S. Interactions among salty, sour and bitter compounds // Trends in Food Science & Technology. 1996. URL: https://www.sciencedirect.com/science/article/pii/S092422449610039X

14. Agorastos G., Klosse B., Hoekstra A., Meuffels M. et al. Instrumental classification of beer based on mouthfeel // International Journal of Gastronomy and Food Science. 2023. URL: https://www.sciencedirect.com/science/article/pii/S1878450X23000392

15. Sugita M. Taste perception and coding in the periphery // Cellular and Molecular Life Sciences. 2006. URL: https://link.springer.com/article/10.1007/s00018-006-6100-0

16. Xiao Z., Lester G.E., Park E., Saftner R.A., Luo Y. et al. Evaluation and correlation of sensory attributes and chemical compositions of emerging fresh produce: Microgreens // Postharvest Biology and Technology. 2015. URL: https://www.sciencedirect.com/science/article/pii/S0925521415300697

17. Threlfall R.T., Hines O.S., Clark J.R., Howard L.R. et al. Physiochemical and sensory attributes of fresh blackberries grown in the southeastern United States // HortScience. 2016. Vol. 51, No. 11. P. 1351–... URL: https://journals.ashs.org/view/journals/hortsci/51/11/article-p1351.xml

18. Briand L., Salles C. Taste and trigeminal perception: from detection to integration // Flavor. 2023. URL: https://www.sciencedirect.com/science/chapter/edited-volume/pii/B9780323899031000104

## III. Taste Interactions: Fat, Sweetness, Salt, Astringency

19. Hayes J.E., Duffy V.B. Revisiting sugar–fat mixtures: sweetness and creaminess vary with phenotypic markers of oral sensation // Chemical Senses. 2007. Vol. 32, No. 3. P. 225–... URL: https://academic.oup.com/chemse/article-abstract/32/3/225/372120

20. Stevenson R.J., Boakes R.A., Oaten M.J. et al. Chemosensory abilities in consumers of a western-style diet // Chemical Senses. 2016. Vol. 41, No. 6. P. 505–... URL: https://academic.oup.com/chemse/article-abstract/41/6/505/1744924

21. Prescott J. Taste Matters: Why we like the foods we do. L.: Reaktion Books, 2013. URL: https://books.google.com/books?id=iw8dhyZV5-oC

22. Laaksonen O. Astringent food compounds and their interactions with taste properties. Turku: University of Turku, 2011. URL: https://www.utupub.fi/items/19ef056c-a196-4acb-841b-a855e7a4f3eb

23. Pedersen L., Bertelsen A.S., Byrne D.V., Kidmose U. Sensory interactions between sweetness and fat in a chocolate milk beverage // Foods. 2023. Vol. 12, No. 14. Art. 2711. URL: https://www.mdpi.com/2304-8158/12/14/2711

## IV. Tomatoes: Organic Acids, Umami, Fermentation of Green Fruit

24. Simões S., Santos R., Bento-Silva A. et al. Improving nutritional quality of unripe tomato through fermentation by a consortium of yeast and lactic acid bacteria // Journal of the Science of Food and Agriculture. 2022. URL: https://scijournals.onlinelibrary.wiley.com/doi/abs/10.1002/jsfa.11476

25. Wang S., Qiang Q., Xiang L., Fernie A.R. et al. Targeted approaches to improve tomato fruit taste // Horticulture Research. 2023. Vol. 10. Art. uhac229. URL: https://academic.oup.com/hr/article-abstract/10/1/uhac229/6758278

26. Guo X., Zhou S., Li Y., Li L., Han Z. The dissection of tomato flavor and key nutrients: Chemical composition, biological function and molecular regulation // Journal of the Science of Food and Agriculture. 2026. URL: https://scijournals.onlinelibrary.wiley.com/doi/abs/10.1002/jsfa.70750

27. Saito T. Effect of Salt Stress on the Growth and Fruit Quality of Tomato Plants // Abiotic Stress Biology in Horticultural Plants. Tokyo: Springer, 2015. URL: https://books.google.com/books?id=zGkzBgAAQBAJ

28. Li X., Tsuta M., Hayakawa F., Nakano Y., Kazami Y. et al. Estimating the sensory qualities of tomatoes using visible and near-infrared spectroscopy and interpretation based on gas chromatography–mass spectrometry // Food Chemistry. 2021. URL: https://www.sciencedirect.com/science/article/pii/S0308814620323323

29. Fisher C., Scott T.R. Food flavours: biology and chemistry. Cambridge: RSC Publishing, 2007. URL: https://books.google.com/books?id=UXUoDwAAQBAJ

## V. Sorrel and Oxalates

30. Das S., Mondal P., Mohanta R., Mondal T. et al. Leafy Vegetables and Their Nutraceutical Health Impacts // Exploration of the Pharmacognostic Potential of Functional Foods. CRC Press, 2026. URL: https://api.taylorfrancis.com/content/chapters/edit/download?identifierName=doi&identifierValue=10.1201/9781003559894-6&type=chapterpdf

## VI. History and Cultural Context of Russian Cuisine

31. Myachikova N., Shamtsyan M. Culinary traditions, food, and eating habits in Russia // Nutritional and Health Aspects of Traditional and Ethnic Foods of Eastern Europe. Elsevier, 2022. URL: https://www.sciencedirect.com/science/chapter/edited-volume/pii/B9780128117347000062

32. Ekström K.M., Ekström M.P., Potapova M. et al. Changes in food provision in Russian households experiencing perestroika // International Journal of Consumer Studies. 2003. URL: https://onlinelibrary.wiley.com/doi/abs/10.1046/j.1470-6431.2003.00322.x

33. Фасмер М. Щи // Этимологический словарь русского языка: в 4 т. М.: Прогресс, 1986–1987. Article “щи”: Old Russian *шти* (gen. *штей*) in the *Domostroi*; proposed origins — Old Russian *съто*, “sustenance,” or a relationship with “sorrel”; dialect meanings “boiled dish, broth, soup dressed with cabbage, sorrel, and other greens.” URL: https://www.slovorod.ru/etym-vasmer/vas-sc.htm

34. Домострой. XVI в. (1550-е): references to *шти* (“щи да каша”), “кислаштяной”; sour shchi as a beverage. See also the discussion in [35].

35. Сытное кушанье с зеленью: история и рецепт щей — визитной карточки русской кухни // Вокруг света. 2024. URL: https://www.vokrugsveta.ru/article/266829/ (etymology; cabbage in Rus’ from the 9th century; seasonal cycle of shchi; sour dressings — brine, stewed sour apples, smetana — as a substitute for expensive salt; Russian-stove technology; reference to Syrnikov M., *Настоящая русская еда* — shchi made with bracken fern).

36. Щи от рассвета до заката / рубрика «Еда с историей» (material with comments by food historian P. Syutkin). URL: https://p-syutkin.livejournal.com/801113.html (shchi in the *Domostroi* of the 1550s; rye-flour slurry and its displacement by potato; seasonal succession of carriers: sauerkraut → nettle, sorrel → young cabbage; role of the Russian stove; proverbs about shchi).

37. Optimisation of Lactobacillus fermentation conditions and its application in the fermentation of salt-free sauerkraut // Frontiers in Microbiology. 2024. DOI: 10.3389/fmicb.2024.1482163. URL: https://www.frontiersin.org/journals/microbiology/articles/10.3389/fmicb.2024.1482163/full

38. Tuazon-Nartea J., Savage G. Investigation of Oxalate Levels in Sorrel Plant Parts and Sorrel-Based Products // Food and Nutrition Sciences. 2013. URL: https://pdfs.semanticscholar.org/b20d/474a774dae4f7736c9ea2eda06ab470de698.pdf (273–954 mg total oxalates per 100 g fresh mass of sorrel leaves; soup retains sour taste after processing; smetana reduces the fraction of soluble oxalates).

39. Похлёбкин В. В. Национальные кухни наших народов. М.: Пищевая промышленность, 1978.

40. *Kapuśniak* / kapusnyak and related soups: Kapusnyak — Ukrainian Sauerkraut soup // Kitchen Epiphanies. URL: https://www.kitchenepiphanies.com/kapusnyak-ukrainian-sauerkraut-soup/ (kapusnyak as the second most important soup in the Ukrainian tradition; association with the Cossack cuisine of Zaporizhzhia in the 15th–18th centuries; Polish *kapuśniak*, Slovak *kapustnica*; control of acidity by brine dose and washing of cabbage); Kapusniak (Ukrainian Sauerkraut Soup) // Budget Bytes. 2022. URL: https://www.budgetbytes.com/kapusniak/

41. Что ели древние новгородцы: продукты питания по берестяным грамотам // Arzamas (based on materials from the Institute of Archaeology of the Russian Academy of Sciences). URL: https://arzamas.academy/mag/1311-beresta (secondary popular-science compilation of evidence from birch-bark letters of the 11th–15th centuries: cabbage, turnip, salt and salting processes, meat and fish in the diet of Novgorod and Staraya Russa; used only as a pointer to the primary corpus of letters, §1.2).

42. Carroll L. (Dodgson C. L.) The Russian Journal: A Record of a Tour in Russia in 1867 / Russian translation: Кэрролл Л. Дневник путешествия в Россию в 1867 году. Entry on shchi (“shtshee”): “…turned out to be quite edible, although they contained some sour ingredient, perhaps necessary to the Russian taste.” Fragments of the Russian translation: https://biography.wikireading.ru/193795 ; trip context: https://afisha.london/en/2023/06/30/lewis-carroll-in-19th-century-russia-monasteries-theatres-and-russian-shchi/

43. Гоголь Н. В. Мёртвые души. 1842. Chapter 1: “День, кажется, был заключен порцией холодной телятины, бутылкой кислых щей и крепким сном во всю насосную завертку…” (evidence for the usage “sour shchi” = beverage; see discussion: https://chgbiblio.ru/archives/65532).

44. Пушкин А. С. Отрывки из «Путешествия Онегина» // Евгений Онегин. “Мой идеал теперь — хозяйка, / Мои желания — покой, / Да щей горшок, да сам большой” (the verse is based on the saying “I eat simple food, but I am my own master”; text with commentary: https://nabokov-lit.ru/nabokov/kritika-nabokova/evgenij-onegin/otryvki-iz-puteshestviya.htm).

45. Витгенштейн Л. Философские исследования // Витгенштейн Л. Философские работы. Ч. 1. М.: Гнозис, 1994 (§§ 65–71: concept of family resemblance; used to harmonize the categorical framework with the companion study [47]).

46. Rosch E., Mervis C.B. Family Resemblances: Studies in the Internal Structure of Categories // Cognitive Psychology. 1975. Vol. 7, No. 4. P. 573–605 (classic study of prototype structure in categories; §5.2).

## VII. Related Works by the Author

47. Корякин А. Н. Борщ как многофакторная кулинарная система: классификация видов, источники цвета и вкусового профиля. Manuscript, 2026. (Methodological companion to the present study: model of the “borscht-ness index,” method of functional substitutes, raw material as an independent variable.)

48. Корякин А. Н. Окрошка как кулинарная система: классификация видов, источники кислотности и категориальная принадлежность. Manuscript, 2026. (Third study of the trilogy: model of the “okroshka-ness index” (ИО), type code Ок = (О, Х, Н, П, К), physical filter Х ≥ 0.5 and Н ≥ 0.5; §5.5.)

---
<details>
*Note. The list is grouped thematically; the main text uses continuous reference numbering (48 entries; corresponding to the sixth edition with supplements). Sources are additionally marked in the main text by evidentiary strength: [Д] — source data; [П] — transfer of data from adjacent fields to shchi. Scientific works were selected using Google Scholar (August 2026); the historical-cultural block [33–36, 39–41] includes primary sources, dictionaries, and works by food historians — identified as such and separated in the text from experimental data. Some links lead to publisher pages where abstracts and full texts are available by subscription; open access is available for preprints and articles in MDPI, Springer Open, and Frontiers.*

*Supplement to the sixth edition (following review of the trilogy of studies): the baseline number of batches was unified (5 for the main series, 3 for the pilot — as in the companion studies); the reference to a separate bibliography file was removed (the list is included in full); the notes block was titled “Revision history”; the name ИЩ was characterized as a mnemonic; “depth of sourness” was explicitly operationalized as an integral characteristic of components D, P, R; the typo in “Kruskal–Wallis” was corrected; formal type code Щ = (O, V, K, T, N) was introduced with coordinate grades and the Hamming metric as an explicit baseline (§5.5); reference [48] (the third study of the trilogy, on okroshka) was added to the bibliography; Experiment 0 (pilot survey of tradition bearers with a questionnaire unified across the trilogy, mirroring companion study [47]) and predictions P7 (difference between fermented carriers and pure acids in a blinded subseries — strengthening P3) and P8 (specific compensatory channel K→(T, N), separated from the general principle P6) were added, with effect sizes and rows in the interpretation table (§7); a summary table of the ИЩ/ИБ/ИО trilogy was added (§5.6).*

*Supplement to the sixth edition (following the second review of the trilogy): outdated counters were corrected (eight predictions P1–P8, five experiments 0–4 — abstract and §9); serving with smetana was excluded from axis T — smetana was moved to external serving modifiers (§5.2); confidence was removed from the latent membership variable and separated as boundary certainty, and entropy metric H(p) was introduced (Experiment 3); “gold standard” was replaced by an operational criterion, and the sensory panel was separated from the expanded panel for cultural categorization; an adversarial subseries and leave-one-recipe-out validation were added (Experiment 3); the trilogy summary table was supplemented with caveats about the differences between identically named axes (O_щ, O_б, O_ок) and about the symmetry of the three configurations being a hypothesis that the experiment is allowed to destroy (§5.6).*
</details>