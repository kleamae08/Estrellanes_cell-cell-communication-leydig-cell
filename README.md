# Cell-to-Cell Communication: Leydig Cell–INSL3–RXFP2 Signaling

**Name:** Klea Mae G. Estrellanes  
**Course:** Cell & Molecular Biology  
**Organism:** *Homo sapiens*  

**Sender Cell:** Leydig cell  
**Signaling Molecule:** INSL3 (Insulin-like peptide 3)  
**Receptor:** RXFP2 (Relaxin Family Peptide Receptor 2)  
**Receiver Cell:** Post-meiotic testicular germ cell / early round spermatid  

---

## 1. Biological Question

How can a Leydig cell communicate with a testicular germ cell through the peptide signaling molecule INSL3 and its receptor RXFP2, and what intracellular signaling processes may connect receptor activation to a cellular response?

---

## 2. Chosen Sender Cell and Biological Context

The selected sender cell is the **Leydig cell**, an interstitial cell of the testis.

Leydig cells are located in the interstitial tissue of the testis and produce signaling molecules, including **INSL3 (insulin-like peptide 3)**. INSL3 is a peptide of the insulin-like family and is a recognized product of testicular Leydig cells.

In this model, the Leydig cell functions as the **sender cell**, producing INSL3 as the signaling molecule. The proposed receiver is a testicular germ cell.

---

## 3. Candidate Ligand and Evidence for Sender-Cell Production

### Signaling Molecule: INSL3

**INSL3** stands for **insulin-like peptide 3**.

INSL3 was selected as the signaling molecule because it is a peptide signal produced by Leydig cells and has a known receptor, **RXFP2**.

Published research identifies INSL3 as a Leydig-cell product. The INSL3–RXFP2 ligand–receptor pair is also well established in the literature.

This choice follows the laboratory instruction to preferably use a protein or peptide signaling molecule rather than a system based mainly on steroid hormones.

**Sender → ligand:**

**Leydig cell → INSL3**

---

## 4. Receptor and Receiver Cell

### Receptor

**RXFP2 — Relaxin Family Peptide Receptor 2**

**Human UniProt accession:** Q8WXD0

RXFP2 is a G-protein-coupled receptor and is the known receptor/target for INSL3.

### Receiver

The proposed receiver is a:

**Post-meiotic testicular germ cell / early round spermatid**

The selected receiver is based on reported RXFP2 expression in testicular germ-cell populations.

Therefore, the proposed ligand–receptor relationship is:

**Leydig cell → INSL3 → RXFP2 → testicular germ cell**

The receiver-cell assignment should be interpreted as a biologically supported model rather than proof that every Leydig cell communicates with every RXFP2-positive germ cell under all conditions.

![Sender Cell Evidence](./%20%20%20%2001_sender_cell_evidence.JPG)

---

## 5. Type of Cell-to-Cell Signaling

The proposed Leydig-cell-to-germ-cell interaction is classified as **paracrine signaling**.

The model focuses on communication between different cell types within the testicular environment. The Leydig cell produces INSL3, while the proposed receiver is a nearby testicular germ cell.

INSL3 also has endocrine functions, but the specific sender–receiver relationship represented in this model is treated as local/paracrine communication.

---

## 6. OmniPath Findings

The OmniPath search was performed using:

**Ligand:** INSL3  
**Organism:** *Homo sapiens*

The selected OmniPath interaction was:

**INSL3 (P51460) → RXFP2 (Q8WXD0)**

The displayed OmniPath result showed:

- **Ligand:** INSL3
- **Receptor:** RXFP2
- **Direction:** INSL3 → RXFP2
- **Interaction:** stimulatory
- **References:** 19
- **Sources shown:** CellChatDB, CellPhoneDB, CellTalkDB, and additional integrated sources

This supports the proposed INSL3–RXFP2 ligand–receptor relationship.

However, OmniPath is an integrated signaling resource. The presence of an interaction in OmniPath does not by itself prove that signaling occurs specifically between the selected Leydig and germ cells under every physiological condition.

**Evidence file:**

![OmniPath Evidence](./%20%20%20%2002_omnipath_evidence.PNG)

---

## 7. STRING Network Interpretation

A STRING network was generated using:

**Input protein:** RXFP2  
**Organism:** *Homo sapiens*

The resulting network contained several functionally associated proteins.

The proteins considered most relevant to the proposed receptor-associated response were:

- **GNAS**
- **GNAO1**

These proteins are associated with G-protein-mediated signaling.

Functional enrichment identified:

**G protein-coupled receptor signaling pathway (GO:0007186)**

Other relevant enriched terms included:

- Adenylyl cyclase-modulating G protein-coupled receptor signaling pathway
- Post-receptor signaling
- Signal transduction

These results are consistent with RXFP2 being a G-protein-coupled receptor and with the involvement of G-protein-mediated intracellular signaling.

However, STRING reports **functional associations**. A STRING edge does not automatically prove direct physical binding or establish the direction of a causal signaling pathway.

Therefore, GNAS and GNAO1 are used in the final model as **STRING-supported signaling associations**, not as experimentally proven consecutive steps.

**Evidence file:**



![OmniPath Evidence](./%20%20%20%2002_omnipath_evidence.PNG)

---

## 8. IntAct Validation

The IntAct database was searched using human RXFP2.

**RXFP2 UniProt:** Q8WXD0

The selected experimentally supported interaction was:

**RXFP2 – LIMK1**

### Interaction Information

| Item | Result |
|---|---|
| Molecule A | RXFP2 |
| Molecule B | LIMK1 |
| RXFP2 UniProt | Q8WXD0 |
| LIMK1 UniProt | P53667 |
| Species | *Homo sapiens* |
| Host organism | HEK293T embryonic kidney cells |
| Positive interaction | Yes |
| Detection method | Anti-tag co-immunoprecipitation |
| Publication | 10.1016/j.cell.2021.04.011 |
| PMID | 33961781 |

The IntAct record provides experimental evidence for an association between RXFP2 and LIMK1.

Because co-immunoprecipitation detects molecular association, this result is **not automatically interpreted as proof of direct physical binding**.

The RXFP2–LIMK1 result is therefore treated as experimental interaction evidence and is kept separate from the proposed GNAS/GNAO1 signaling sequence.

**Evidence file:**

![IntAct Evidence](./%20%20%20%2004_intact_evidence.JPG)

---

## 9. Final Cell-to-Cell Communication Model

The proposed model is:

**Leydig cell**  
↓  
**INSL3 (peptide ligand)**  
↓  
**Extracellular space**  
↓  
**RXFP2 receptor**  
↓  
**G-protein signaling**  
↓  
**GNAS / GNAO1**  
↓  
**cAMP-related signaling**  
↓  
**Regulation of testicular/germ-cell function**

The final diagram distinguishes database-supported observations from biological inference.

**Final model:**

![Final signaling model](./05_final_model.PNG)

### Final Model Interpretation

In this model, the Leydig cell acts as the sender and produces the peptide signaling molecule insulin-like peptide 3 (INSL3). INSL3 is proposed to act on the relaxin family peptide receptor 2 (RXFP2) on a receiving testicular germ cell. OmniPath supports the INSL3–RXFP2 ligand–receptor relationship, while STRING analysis of RXFP2 identified functional associations with G-protein signaling proteins, including GNAS and GNAO1. Functional enrichment identified the G protein-coupled receptor signaling pathway as an enriched biological process. These findings support a model in which RXFP2 activation is connected with intracellular G-protein and cAMP-related signaling. IntAct also provided experimental evidence for an RXFP2–LIMK1 association through anti-tag co-immunoprecipitation in HEK293T cells. However, this result represents an experimentally detected association and does not by itself establish a direct causal pathway in the selected receiver cell. Therefore, the final model separates experimentally supported observations from proposed downstream signaling. Overall, the model illustrates how a peptide produced by a specific sender cell may initiate receptor-associated signaling and potentially contribute to regulation of testicular and germ-cell functions.

---

# 10. Questions

## 1. What sender cell did you choose, and in what tissue or biological context does it act?

I chose the **Leydig cell**, an interstitial cell of the testis. Leydig cells function within the testicular reproductive environment and produce signaling molecules including INSL3.

## 2. What signaling molecule did you identify, and what evidence supports its production or presentation by the sender cell?

The signaling molecule identified was **INSL3 (insulin-like peptide 3)**. Published evidence identifies INSL3 as a product of testicular Leydig cells. INSL3 is a peptide signaling molecule of the insulin-like family and has a known receptor, RXFP2.

## 3. What receptor receives the signal, and which receiver cell did you select?

The receptor is **RXFP2 (Relaxin Family Peptide Receptor 2)**, UniProt **Q8WXD0**.

The selected receiver is a **post-meiotic testicular germ cell / early round spermatid**. The receiver selection is based on reported RXFP2 expression in testicular germ-cell populations.

## 4. What type of cell-to-cell signaling is represented: paracrine, endocrine, autocrine, or contact-dependent?

The proposed interaction is classified as **paracrine signaling** because the model represents communication between different cell types within the testicular tissue. The Leydig cell produces INSL3 and the proposed receiver is a different testicular cell.

## 5. Which proteins in your STRING network appear most relevant to the receptor-associated response? Explain briefly.

**GNAS and GNAO1** were considered the most relevant proteins in the STRING network. They are associated with G-protein signaling and provide a reasonable connection between the GPCR RXFP2 and downstream intracellular signaling.

However, STRING associations do not automatically demonstrate direct physical interaction or prove the exact causal order of the pathway.

## 6. What enriched pathway or biological process is consistent with your proposed mechanism?

The most relevant enriched biological process was:

**G protein-coupled receptor signaling pathway (GO:0007186).**

Other relevant enriched terms included adenylyl cyclase-modulating GPCR signaling, post-receptor signaling, and signal transduction.

These processes are consistent with RXFP2 functioning as a G-protein-coupled receptor.

## 7. What did IntAct show for the molecular interaction you examined? What type of evidence was reported?

IntAct showed a positive **RXFP2–LIMK1 association**.

The interaction was detected using **anti-tag co-immunoprecipitation** in **HEK293T embryonic kidney cells**.

The associated publication was:

**DOI:** 10.1016/j.cell.2021.04.011  
**PMID:** 33961781

Because co-immunoprecipitation detects an association, the result is not automatically interpreted as proof of direct physical binding.

## 8. Which parts of your final model are strongly supported, and which parts remain an inference?

The strongest-supported components are:

- Leydig cells produce INSL3.
- INSL3 is associated with RXFP2 as its receptor/target.
- RXFP2 is a GPCR.
- OmniPath identifies the INSL3 → RXFP2 relationship.
- STRING associates RXFP2 with G-protein signaling proteins.
- The STRING network is enriched for GPCR signaling.

The exact sequence from:

**RXFP2 → GNAS/GNAO1 → cAMP-related signaling → specific germ-cell response**

remains a **proposed model and biological inference**, rather than a completely established causal pathway in the selected human receiver cell.

The RXFP2–LIMK1 IntAct result is also experimental evidence from HEK293T cells and should not automatically be transferred into the specific Leydig-cell-to-germ-cell pathway.

## 9. What cellular response is expected in the receiver cell, and why?

The expected response is described cautiously as:

**Regulation of testicular/germ-cell function.**

The INSL3–RXFP2 system is biologically relevant to testicular development and reproductive processes. However, the exact downstream cellular response of the selected human post-meiotic germ cell is not completely established by the databases used in this laboratory activity.

Therefore, the final model does not claim a specific response such as increased spermatogenesis as a proven outcome.

---

# 11. Evidence Summary

| Component | Selected result | Evidence Source |
|---|---|---|
| Sender cell | Leydig cell | Literature / HPA |
| Ligand | INSL3 | Literature / HPA |
| Receptor | RXFP2 (Q8WXD0) | UniProt / OmniPath |
| Receiver | Post-meiotic germ cell / early round spermatid | Literature |
| Signaling type | Paracrine | Biological interpretation |
| OmniPath | INSL3 → RXFP2 | OmniPath |
| STRING proteins | GNAS, GNAO1 | STRING |
| Enriched process | GPCR signaling, GO:0007186 | STRING |
| IntAct pair | RXFP2–LIMK1 | IntAct |
| IntAct method | Anti-tag co-immunoprecipitation | IntAct |
| Expected response | Regulation of testicular/germ-cell function | Proposed biological model |

---

# 12. Evidence Files

The repository contains the following evidence files:

figures/
├── 01_sender_cell_evidence.png
├── 02_omnipath_evidence.png
├── 03_string_network.png
├── 04_intact_evidence.png
└── 05_final_model.png

---

# 13. Interaction Summary

The main modeled signaling relationship is:

Leydig cell  
↓  
INSL3  
↓  
RXFP2  
↓  
G-protein-associated signaling  
↓  
GNAS / GNAO1  
↓  
cAMP-related signaling  
↓  
Regulation of testicular/germ-cell function

The molecular interaction examined separately using IntAct was:

RXFP2 — LIMK1

### Interaction Summary Table

| Component | Molecule/Result | Evidence Source |
|---|---|---|
| Sender cell | Leydig cell | HPA / Literature |
| Ligand | INSL3 (P51460) | HPA / Literature |
| Receptor | RXFP2 (Q8WXD0) | UniProt / OmniPath |
| Receiver | Post-meiotic germ cell / early round spermatid | Literature |
| STRING-associated proteins | GNAS, GNAO1 | STRING |
| Enriched process | G protein-coupled receptor signaling pathway (GO:0007186) | STRING |
| IntAct interaction | RXFP2–LIMK1 | IntAct |
| IntAct detection method | Anti-tag co-immunoprecipitation | IntAct |
| IntAct host organism | HEK293T embryonic kidney cells | IntAct |
| Expected response | Regulation of testicular/germ-cell function | Proposed model |

---

# 14. Database Interpretation and Limitations

Several limitations should be considered when interpreting this model.

1. Database presence is evidence, but it does not prove that signaling occurs in every cell type or physiological condition.

2. Expression of a ligand or receptor does not by itself prove that signaling occurs between the selected cells.

3. STRING associations do not automatically represent direct binding or establish pathway direction.

4. IntAct results should be interpreted together with their experimental method, organism, and publication context.

5. The RXFP2–LIMK1 IntAct association was detected in HEK293T cells. Therefore, it should not automatically be interpreted as proof that the same interaction occurs in the selected testicular germ-cell context.

6. GNAS and GNAO1 were selected from the STRING network as relevant proteins associated with RXFP2 signaling. Their appearance in the STRING network does not prove that they form a single linear pathway in the selected receiver cell.

7. The cAMP-related portion of the final model is therefore presented as a proposed downstream mechanism rather than a completely established causal sequence in the selected human germ-cell context.

8. The final cellular response is stated conservatively as **regulation of testicular/germ-cell function** rather than as a definitively proven specific response.

---

# 15. References and Database Resources

## Database Resources

- **OmniPath:** https://omnipathdb.org/
- **STRING:** https://string-db.org/
- **IntAct:** https://www.ebi.ac.uk/intact/
- **Human Protein Atlas:** https://www.proteinatlas.org/
- **UniProt:** https://www.uniprot.org/

## Literature and Supporting Sources

1. **Discovery of small molecule agonists of the Relaxin Family Peptide Receptor 2.**

   PubMed: https://pubmed.ncbi.nlm.nih.gov/36333465/

   This source describes RXFP2 as a class A G-protein-coupled receptor and identifies it as the known target of INSL3.

2. **Structure-Activity Relationship Studies toward the Optimization of First-In-Class Selective Small Molecule Agonists of the GPCR Relaxin/Insulin-like Family Peptide Receptor 2.**

   PubMed: https://pubmed.ncbi.nlm.nih.gov/41710979/

   This study used human RXFP2-transfected HEK293T cells and examined RXFP2 activation by INSL3.

3. **RXFP2–LIMK1 IntAct interaction**

   Publication DOI: 10.1016/j.cell.2021.04.011  
   PMID: 33961781

   The IntAct result reports an RXFP2–LIMK1 association detected using anti-tag co-immunoprecipitation.

---

# 16. Repository Structure

The repository is organized according to the recommended laboratory structure:

cell-cell-communication-leydig-cell/
│
├── README.md
│
├── figures/
│   ├── 01_sender_cell_evidence.png
│   ├── 02_omnipath_evidence.png
│   ├── 03_string_network.png
│   ├── 04_intact_evidence.png
│   └── 05_final_model.png
│
└── data/
    └── interaction_summary.csv

### Figure Files

**01_sender_cell_evidence.png**  
Evidence supporting the production of INSL3 by the Leydig sender cell.

**02_omnipath_evidence.png**  
OmniPath evidence showing the INSL3 → RXFP2 ligand–receptor relationship.

**03_string_network.png**  
STRING network for human RXFP2, including the relevant G-protein-associated proteins and enrichment results.

**04_intact_evidence.png**  
IntAct evidence for the RXFP2–LIMK1 molecular association.

**05_final_model.png**  
Original final cell-to-cell communication model.

---

# 17. Conclusion

This laboratory activity developed a proposed cell-to-cell communication model involving a **Leydig cell**, the peptide signaling molecule **INSL3**, the receptor **RXFP2**, and a testicular germ-cell receiver.

The evidence collected from multiple databases supports different parts of the model. OmniPath identified the **INSL3 → RXFP2** ligand–receptor relationship. STRING identified functional associations between RXFP2 and G-protein signaling proteins, including **GNAS** and **GNAO1**, and identified the **G protein-coupled receptor signaling pathway (GO:0007186)** as an enriched biological process. IntAct provided experimental evidence for an **RXFP2–LIMK1 association** detected by anti-tag co-immunoprecipitation in HEK293T cells.

The final model therefore combines database-supported observations with clearly identified biological inference. The proposed downstream signaling sequence and cellular response should not be interpreted as completely proven causal events in the selected human germ-cell context. Instead, the model represents a biologically reasonable communication pathway supported by available signaling, expression, network, and molecular-interaction evidence.
