# Protocols

### 1. **Processing of RNA-Seq Data**
**Materials**:
- Computer with installed R studio and relevant bioinformatics packages.
- Human tissue RNA-seq data from specified databases.

**Procedure**:
1. **Preparation**: Install necessary packages and libraries on R studio. Ensure stable internet connectivity for data download.
2. **Data Download**:
   - Navigate to the respective database web pages.
   - Select the desired datasets and initiate download.
   - Store data in a specified folder for easy access.
3. **Processing**:
   - Load the data into R studio.
   - Use the `DESeq2` package (or similar) for differential expression analysis.
   - Filter out genes with low counts.
   - Normalize the data.
4. **Analysis**:
   - Generate heatmaps, PCA plots, and other relevant plots to visualize gene expression patterns.
   - Save and catalog results.

**Specific Conditions**:
- Ensure the computer has sufficient memory and processing power for large datasets.

---

### 2. **Protein Tertiary Structure Prediction and Mutation Analysis**
**Materials**:
- Computer with internet access.
- AlphaFold2 platform access.
- UCSF Chimera software.
- DNA sequences for the target proteins.

**Procedure**:
1. **Protein Prediction**:
   - Navigate to the Bkunyun Platform and upload the DNA/protein sequence.
   - Initiate AlphaFold2 prediction and wait for results.
2. **Structural Analysis**:
   - Download the resulting PDB files.
   - Open the PDB files in UCSF Chimera.
   - Visualize, compare, and analyze structures.
3. **Mutation Analysis**:
   - Highlight and label mutation sites on the structures using UCSF Chimera tools.
   - Predict potential functional changes due to mutations.

**Specific Conditions**:
- Ensure a stable internet connection for online platforms.
- Ensure sufficient storage space for saving PDB and other files.

---

### 3. **Collagen and Elastin Purification**
#### **a. Chromatography-free purification method**
**Materials**:
- BL21 (DE3) strain with appropriate plasmid.
- PBS (pH 9.0, 0.5 M NaCl).
- 10 KDa & 1 KDa ultrafiltration tubes.
- HPLC system.

**Procedure**:
1. **Cultivation**:
   - Inoculate a fresh culture of BL21 in LB medium (pH 8.5) supplemented with 50 mg/L kanamycin.
   - Incubate at 37°C, 200 rpm until OD600 ~0.6.
   - Add 0.3 mM IPTG to induce protein expression and incubate overnight.
2. **Protein Extraction**:
   - Harvest cells by centrifugation at 4,000 rpm, 15 minutes, 4°C.
   - Resuspend the cell pellet in 50 mL PBS.
   - Lyse cells using high-pressure homogenization.
   - Centrifuge lysed cells at 10,000 rpm, 30 minutes, 4°C to remove cell debris.
3. **Ultrafiltration**:
   - Pass supernatant through a 10 KDa ultrafiltration tube to remove proteins >10 KDa.
   - Adjust pH of filtrate to 6.5 using 1 M HCl.
   - Incubate at 30°C overnight for potential peptide cleavage.
   - Pass the solution through a 1 KDa ultrafiltration tube.
4. **Quality Control**:
   - Analyze filtrate using HPLC to assess peptide purity and concentration.

**Specific Conditions**:
- All steps involving cells and proteins should be done on ice or at 4°C, unless otherwise stated.
- Use sterile techniques to prevent contamination.

---

### 4. **ARTP-PANCE for Screening Intein and T7 RNAP Mutants In Vivo**

**Materials**:
- Primary M13 phage for GyrA or T7 RNAP.
- S1030 strain with pJC175e plasmid.
- DNA-LAMP method kit.
- LB medium, appropriate antibiotics.

**Procedure**:
1. **Phage Addition**:
   - Inoculate a fresh culture of S1030 strain containing the pJC175e plasmid.
   - At early log phase, add the primary M13 phage.
   - Incubate to allow for bacterial-phage interactions.
2. **ARTP Mutation**:
   - Centrifuge and re-suspend bacterial cells in fresh LB medium.
   - Expose to ARTP treatment in controlled settings for specified durations (e.g., 30s, 120W).
   - Dilute treated cells in fresh LB medium.
3. **Phage Titer Estimation**:
   - Use the DNA-LAMP method to periodically measure phage titers.
   - When phage titer reaches 10^6 CFU/mL, proceed to the next step.
4. **Phage Collection**:
   - Centrifuge culture and collect the supernatant containing the M13 phage.

**Specific Conditions**:
- Use sterile conditions throughout to prevent contamination.
- The ARTP mutagenesis equipment should be calibrated to provide the right exposure intensity.
- Monitor cultures for any signs of contamination or cell death.

---

### 5. **CRISPR-Associated Transposon Protocol**

**Materials**:
- BL21 strain containing specified plasmids.
- LB medium with appropriate antibiotics.
- PCR equipment, reagents, and primers.
- Sanger sequencing setup.

**Procedure**:
1. **Strain Induction**:
   - Inoculate BL21 strain with the necessary plasmids in LB medium with required antibiotics.
   - Grow until OD600 reaches 0.6.
   - Induce with 0.2 mM IPTG and continue incubation overnight.
2. **Isolation**:
   - Plate culture on LB plates with antibiotics to isolate monoclonal strains.
   - Grow plates until colonies are visible.
3. **Identification**:
   - Use bacterial PCR to identify strains with the desired insert fragments.
   - Confirm insertions through Sanger sequencing.

**Specific Conditions**:
- Use a controlled incubator set at 37°C for bacterial growth.
- Maintain sterility throughout to avoid contamination.
- Optimize PCR conditions for specific primers and target regions.

---

### 6. **TADR-FADS for Screening Proline Hydroxylase Mutants**

**Materials**:
- BL21 strain with specific genomic modifications and plasmids.
- Fluorescent microplate reader.
- LB medium and appropriate antibiotics.

**Procedure**:
1. **Strain Transformation**:
   - Transform BL21 with the desired plasmid.
   - Grow transformed cells in LB medium with appropriate antibiotics until OD600 ~0.6.
2. **Induction**:
   - Add 0.5 mM IPTG to the culture.
   - Continue overnight incubation.
3. **Fluorescence Measurement**:
   - Measure GFP fluorescence intensity of the cultures using a fluorescent microplate reader.

**Specific Conditions**:
- Maintain cultures at 37°C, 200 rpm throughout.
- Calibration of the microplate reader is essential for accurate fluorescence readings.

---

### 7. **Microfluid Chip and Device Preparation**

**Materials**:
- PDMS
- HFE7500 fluorinated oil.
- Microscopy and imaging setup with lasers and cameras.

**Procedure**:
1. **Chip Fabrication**:
   - Create microfluidic patterns using PDMS.
   - Allow PDMS to cross-link and cure.
   - Punch the necessary ports and channels.
2. **Assembly**:
   - Attach the PDMS structure to a glass slide.
   - Apply a hydrophobic surface coating.
   - Fill electrode holes as necessary.
3. **Droplet Generation**:
   - Use a dropmaker chip with fluorinated oil to generate droplets.
   - Employ imaging equipment to monitor and manipulate droplets.

**Specific Conditions**:
- PDMS curing should be done under controlled temperature conditions for consistency.
- Maintain a clean environment to ensure dust or contaminants do not interfere with microfluidic operations.

---

### 8. **Activity Assay for Proline Hydroxylase**

**Materials**:
- Bacterial Protein Extraction Kit.
- Hydroxyproline (HYP) content detection kit.

**Procedure**:
1. **Protein Extraction**:
   - Extract total proteins from E. coli using the extraction kit.
2. **Quantification**:
   - Measure protein concentration using a BCA protein quantification kit.
3. **Activity Assessment**:
   - Determine proline hydroxylation levels using the HYP content detection kit.

**Specific Conditions**:
- All extraction steps should be carried out at 4°C or on ice to maintain protein stability.
- Ensure that all reagents, especially those in the HYP detection kit, are at the appropriate temperature and freshly prepared.
- Control samples (non-hydroxylated proline samples) should be run alongside experimental samples for accurate comparison.

---

### 9. **Collagen and Elastin Synthesis via CFPS Reaction**

**Materials**:
- 20 standard amino acids, glycine, proline, 2-oxoglutarate, etc.
- Cell extract from a high yield source.
- Target plasmid or DNA encoding collagen/elastin sequences.
- Necessary buffers and cofactors for in vitro transcription and translation.

**Procedure**:
1. **Preparation**:
   - Thaw all reagents on ice.
   - Prepare a master mix containing all the components except the cell extract and DNA.
2. **Reaction Setup**:
   - In a sterile reaction tube, mix the master mix, cell extract, and target DNA/plasmid.
   - Ensure thorough mixing without introducing bubbles.
3. **Incubation**:
   - Place the reaction tube in a controlled incubator set at 37°C.
   - Allow the reaction to proceed for 8 hours.
4. **Analysis**:
   - After incubation, analyze the reaction mixture for synthesized collagen/elastin using SDS-PAGE or Western Blot.

**Specific Conditions**:
- Ensure all components are fresh and uncontaminated. This is crucial for the efficiency of the CFPS system.
- Maintain a sterile environment during the setup to prevent external protein or RNA contamination.
- Optimal temperatures for the CFPS system might vary depending on the specific cell extract source. Adjust accordingly.

---

### 10. **Proline Hydroxylase Mutant Screening via Microfluidic Chips**

**Materials**:
- Microfluidic chips prepared from PDMS.
- HFE7500 fluorinated oil.
- Culture of strains containing the P4Hc mutant library.
- Necessary buffers and reagents for droplet generation.

**Procedure**:
1. **Strain Preparation**:
   - Grow the strains containing the P4Hc mutant library in LB medium until OD600 reaches ~0.6.
   - Dilute the culture for use in droplet generation.
2. **Droplet Generation**:
   - Set up the microfluidic chip on the appropriate device.
   - Introduce the bacterial culture and HFE7500 fluorinated oil into the chip to generate droplets.
3. **Droplet Analysis**:
   - Using the attached imaging system, monitor the droplets for desired phenotypes or activities.
   - Sort and collect droplets of interest for further analysis.

**Specific Conditions**:
- Ensure consistent flow rates for both the bacterial culture and the fluorinated oil to generate uniform droplets.
- Calibrate the imaging system for accurate detection and analysis of droplets.
- Maintain a clean setup to prevent clogging or contamination within the microfluidic channels.


