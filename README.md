# Molecular Docking Analysis of Curcumin Against SARS-CoV-2 Main Protease (Mpro)

## Project Overview

This project focuses on the computational investigation of the binding interaction between the phytochemical **Curcumin** and the **SARS-CoV-2 Main Protease (Mpro)** using molecular docking analysis. The study was performed to evaluate the potential inhibitory activity of curcumin against the viral protease, which plays an important role in SARS-CoV-2 replication and viral polyprotein processing.

Molecular docking provides an understanding of ligand–protein interactions by analyzing binding energy, intermolecular interactions, and possible binding conformations of the ligand within the active site of the target protein.

---

# Ligand Information

**Ligand Name:** Curcumin
**Synonym:** Diferuloylmethane
**PubChem CID:** 969516

**Chemical Classification:**

* Polyphenol
* Diarylheptanoid
* Beta-diketone
* Aromatic ether
* Enone compound

**Natural Source:**
Curcumin is a naturally occurring bioactive compound obtained from the rhizome of *Curcuma longa* (turmeric). It is responsible for the yellow color of turmeric and is widely studied for its pharmacological properties.

Curcumin consists of two feruloyl groups connected through a methane bridge and belongs to the class of natural phenolic compounds. It exhibits multiple biological activities including antioxidant, anti-inflammatory, antimicrobial, antiviral, anticancer, immunomodulatory, and neuroprotective effects.

Curcumin has been investigated for several therapeutic applications due to its ability to regulate different molecular pathways. It has been reported to act as a radical scavenger, enzyme inhibitor, iron chelator, biological pigment, and nutraceutical compound.

Despite its biological potential, the therapeutic application of curcumin is limited due to poor bioavailability caused by low absorption, rapid metabolism, and fast systemic elimination. Computational approaches such as molecular docking help in predicting its interaction potential with important biological targets.

---

# Protein Target Information

**Target Protein:** SARS-CoV-2 Main Protease (Mpro / 3CLpro)
**PDB ID:** 6LU7

**Protein Title:**
Crystal structure of COVID-19 main protease in complex with an inhibitor N3

**Classification:** Viral Protein

**Organism:**
Severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2)

**Expression System:**
*Escherichia coli* BL21(DE3)

**Mutation Status:**
No mutation

The SARS-CoV-2 main protease (Mpro) is an essential viral enzyme involved in the cleavage of viral polyproteins into functional proteins required for viral replication. Since Mpro has no closely related human homolog, it is considered an important target for antiviral drug discovery.

---

# Molecular Docking Methodology

Molecular docking was performed between curcumin and SARS-CoV-2 main protease (PDB ID: 6LU7).

The docking analysis was carried out to evaluate:

* Binding energy of ligand–protein complex
* Intermolecular interaction energy
* Internal energy changes
* Torsional energy contribution
* Binding conformations of curcumin

The generated docking poses were ranked according to their docking scores and energy parameters.

---

# Docking Results

## Selected Docking Conformation

Among the generated docking conformations, **Conformation 1 (Rank 1)** was selected for analysis.

### Docking Energy Parameters

| Energy Component                                   |            Value |
| -------------------------------------------------- | ---------------: |
| Estimated Free Energy of Binding                   | +247.68 kcal/mol |
| Final Intermolecular Energy                        | +244.70 kcal/mol |
| van der Waals + Hydrogen Bond + Desolvation Energy | +244.55 kcal/mol |
| Electrostatic Energy                               |   +0.14 kcal/mol |
| Final Total Internal Energy                        |  +15.74 kcal/mol |
| Torsional Free Energy                              |   +2.98 kcal/mol |
| Unbound System Energy                              |  +15.74 kcal/mol |

The estimated free energy of binding was calculated as:

**Binding Energy = (Final Intermolecular Energy) + (Final Total Internal Energy) + (Torsional Free Energy) − (Unbound System Energy)**

---

# Docking Pose Ranking

A total of 10 ligand conformations were generated during docking analysis. The ranking of different poses is shown below:

| Rank | Ligand Conformation | Docking Energy (kcal/mol) |
| ---- | ------------------- | ------------------------: |
| 1    | Ligand 1_1          |                    102.44 |
| 2    | Ligand 1_2          |                    130.73 |
| 3    | Ligand 1_3          |                    170.19 |
| 4    | Ligand 2_1          |                    221.24 |
| 5    | Ligand 3_1          |                    247.68 |
| 6    | Ligand 4_1          |                    263.66 |
| 7    | Ligand 5_1          |                    291.98 |
| 8    | Ligand 6_1          |                    235.23 |

The docking output showed different possible binding orientations of curcumin inside the SARS-CoV-2 main protease binding region. Each conformation varies based on ligand flexibility, intermolecular interaction energy, and internal strain.

---

# Docking Interpretation

The docking study provides computational insight into the interaction behavior of curcumin with SARS-CoV-2 main protease. The intermolecular energy represents the contribution of ligand–protein interactions, including van der Waals forces, hydrogen bonding, desolvation effects, and electrostatic interactions.

The torsional energy represents the energetic cost associated with ligand flexibility during the docking process.

The obtained docking poses indicate that curcumin is capable of interacting with the viral main protease target. These results support the potential role of curcumin as a candidate phytochemical molecule for further antiviral investigation.


# Software and Databases Used

* Protein Data Bank (PDB) – Protein structure retrieval
* PubChem Database – Ligand information retrieval
* AutoDock / AutoDock Vina – Molecular docking analysis
* PyMOL – Protein–ligand visualization
* Discovery Studio Visualizer – Interaction analysis

---

# Conclusion

The molecular docking study of **Curcumin (PubChem CID: 969516)** against the **SARS-CoV-2 Main Protease (PDB ID: 6LU7)** was performed to investigate its binding behavior and interaction potential.

#Author 
Anusree pattamsetty || Bioinformatics 

The docking analysis generated multiple ligand conformations and provided information about binding energy, intermolecular interactions, and ligand flexibility. Curcumin showed interaction capability with SARS-CoV-2 Mpro, suggesting that it may serve as a potential lead molecule for antiviral research.

Further investigations such as molecular dynamics simulation, ADMET prediction, and experimental validation are required to confirm the antiviral activity and therapeutic potential of curcumin.
