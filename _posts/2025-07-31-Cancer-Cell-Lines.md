A cancer cell line is a population of cancer cells that originated from a patient's tumor and has been grown in the lab under controlled conditions, so that it can divide indefinitely. 
Normal cells cannot divide indefinitely and stop after a few rounds (known as senescence, which is related to agining).
However, cancer cells have mutations, allowing them to bypass the normal limits on growth.
Cancer cells cells can grow on petri dishes or flasks, in a process known as cell culture.

The first cancer cell line was successfully grown in 1951; the HeLa cells were derived from a cervical cancer tumor in Henrietta Lacks, a young African American woman.
The HeLa cells were grown in Johns Hopkins Hospital, Baltimore, MD by scientist Dr. George Gey.
These cells were the first human cells grown to divide indefinitely, which revolutionized biomedical research. HeLa cells contributed to testing vaccines and drugs.
Microscopy also plays an important role; from a microscopy image, the number of cells can be counted. So, after testing a drug, if there's no growth, it means the drug is working.

Cell lines are useful because they're easy to grow and manipulate in the lab.
Different cell lines are used to represent various human cancers.
They serve as models to study tumor genetics, discover cancer vulnerabilities, and test therapeutic compounds, and they can be used to study molecular mechanism of cancer cells and the signaling pathways in cancer.
Performing knockdown or overexpression of genes with cancer cell lines can help to observe functional changes.
Scientists can also investigate the role of oncogenes or tumor suppressors.

Cancers are heterogeneous diseases; for example, breast cancers have different subtypes.
Subtypes are defined based on the presece or absence of certain receptors and gene expression profiles.
The main breast cancer subtypes are based on the presence of receptors: Luminal A (Estrogen Receptor (ER+), Progesteron Receptor (PR+), HER2-; gives a good prognosis), Luminal B (ER+, PR+-, HER+-; gives moderate prognosis), HER2+ (ER-, PR-, HER2+), and triple negative (ER-, PR-, HER2-; gives a poor prognosis).
(A prognosis is the expected course and outcome of a condition; it can also be defined as the likelihood of recovery.)

The discovery of breast cancer subtypes occured in 2000. A group of people working at Stanford (Perou et al) published an article regarding this discovery in Nature.
They used microarrays to profile ~65 tumors and identified the molecular subtypes: Luminal A, Luminal B, HER2-enriched, Basal-like, and Normal-like.
This discovery introduced the concept of intrinsic subtypes based on gene expression.
In the test, 2000 genes were used.

In 2009, Parker et al. published a paper in Journal of Clinical Oncology
refined Perou's gene set to 50 genes (PAM50) for clinical use, hospitals adopted this technique use
classified tumors into the same 5 subtypes using qRT-PCR/NanoString
the subtype can guide the choice of therapy
introduced Risk of Recurrence (ROR) score, based on expression, chance of tumor coming back after surgical removal
led to the clinical test Prosigna, used in ER+/HER2- breast cancer
Prosigna diagnostic assay was developed and commercialized by NanoString Technologies, Inc.
Dr. Charles Perou, now a professor at UNC-Chapel, is the co-inventor of Prosigna

Nanostrings Technologies Inc. is a biotech company founded in 2003, under the leadership of Dr. Leroy Hood.
Technology platforms: nCounter (digital gene expression platform, uses color-code colecular barcodes to directly count RNA, DNA), Prosigna Assay (FDA-cleared diagnostic test for early-stage, hormone recptor-positive breast cancer), DeoMx Digital Spatial Profiler (DSP)
Bruker Corporation (global leader in life-science instrumentation) acquired its assets at $392.6 million (nCounter, GeoMx, CosMx, AtoMx, Prosigna)
Bruker aims to integrate NanoString's gene expression and spatial biology platforms into its broader CellScape proteomics systems

CCLE is a public resource of cancer cell lines developed by the Broad Institute
contains multi-omics data (genomic, transcriptomic, proteomic, pharmacologic (how cancer cell lines respond to certain compounds))
used to study cancer biology and predict drug sensitivity
https://sites.broadinstitute.org/ccle

In Jupyter Notebook, using the data from Model.csv, I categorized the cancer cell lines by Oncotree Lineage, selecting for Myeloid, which has the primary disease Acute Myeloid Leukemia. There were 87 cancer cell lines with the Oncotree Lineage of Myeloid. When looking at the subtype features, there were 11 BCR-ABL1 positive, two CBFA2T3::GLIS2 and TP53, and various other types, one of each.  (http://localhost:8888/lab/tree/classAI/classAI-25-07-31.ipynb)

evaluate the efficacy, potency, and selectivity of drugs against different cancer types
first, select cell lines
seed cell line into multi-well plates (96-well, 384-well). This action allows cells to adhere and grow to a certain density under standard conditions. 
A library of candidate drugs (or concentrations of a drug) is applied to cells.
Cells are incubated with drugs for 24 to 72 hours, or more.
Assay readouts and data analysis generate a drug dose response curve

Point a on the curve (position of curve along the x-axis) defines potency, point b (greatest response attainable) gives maximal efficacy, and point c is IC50 (inhibiting concentration) or EC50 (effective concentration).
Comparison of dose-response curves
Concentration (nM) plotted against % Cell Viability

CCLE, through the DepMap portal, provides drug sensitivity data from several large-scale screening projects.
PRISM Repurposing Dataset (Broad Institute) is a pooled barcoded screening of ~500 cell lines, with over 4500 compounds, giving the relative viability (log fold change) at multiple concentrations.

breast cancer drugs on the market: chemotherapy (doxorubicin, paclitaxel), homrmone therapy (tamoxifen, anastrozole, exemestane), and targeted therapy (trastuzumab, pertuzumab, and palbociclib

