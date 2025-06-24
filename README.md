# CD8-Tcells_GeneSig
From "Pan-Cancer T cell atalas links a cellular stress response state to immunotherapy resistance" [article](https://www.nature.com/articles/s41591-023-02371-y#MOESM3)

Excel File[]()
### Naive

- Markers: `IL7R`, `CCR7`, `SELL`

### Activation: Effector function

### Exhaustion

### TCR Signaling

### Cytotoxicity

### Cytokine/Cytokine receptor

### Chemokine/Chemokine receptor

### Senescence

### Anergy

### Stress Response

### MAPK Signaling

### Adhesion

### IFN Response

### Oxidative Phoshorylation

### Glycolysis

### Fatty Acid Metabolism

### Pro-Apoptosis

### Anti-Apoptosis

## R code

```gene_signatures <- list()

# Naive
gene_signatures$Naive <- c("IL7R", "CCR7", "SELL", "FOXO1", "KLF2", "KLF3", "LEF1", "TCF7", "ACTN1", "FOXP1")

# Activation_Effector_function
gene_signatures$Activation_Effector_function <- c("FAS", "FASLG", "CD44", "CD69", "CD38", "KLRF1", "FOXP1", "KLRG1", "FCGR3A", "CX3CR1")

# Exhaustion
gene_signatures$Exhaustion <- c("PDCD1", "LAYN", "HAVCR2", "LAG3", "CTLA4", "TOX", "VSIR", "BTLA", "ENTPD1", "CD160")

# TCR_Signaling
gene_signatures$TCR_Signaling <- c("CALM1", "CALM2", "CALM3", "CAST", "GNLY", "PRF1", "CD3D", "CD3E", "CD3G", "CSK")

# Cytotoxicity
gene_signatures$Cytotoxicity <- c("GZMA", "GZMB", "GZMH", "GZMK", "GZMH", "NKG7", "PRF1", "KLRF1", "KLRK1", "FCGR3A")

# Cytokine_Cytokine_receptor
gene_signatures$Cytokine_Cytokine_receptor <- c("CSF1", "IL10RA", "IL16", "IL17RA", "IL18RAP", "IL21R", "IL2RB", "IL2RG", "IL32", "IL9R")

# Chemokine_Chemokine_receptor
gene_signatures$Chemokine_Chemokine_receptor <- c("CCR4", "CCR5", "CCR7", "CXCR3", "CXCR4", "CXCR5", "CXCR6", "CXCL13", "CXCL8", "CCL3")

# Senescence
gene_signatures$Senescence <- c("NT5E", "IZUMO1R", "LAG3", "CBLB", "DOK1", "DOK2", "SERPINB1", "SERPINB6", "SERPINB9", "ADAM10")

# Anergy
gene_signatures$Anergy <- c("NFKB1", "NFKB2", "NFKBIA", "NFKBIB", "NFKBIZ", "CHUK", "IKBKB", "IKBKG", "RELA", "RELB")

# NFKB_Signaling
gene_signatures$NFKB_Signaling <- c("HIKESHI", "UBA52", "RPA2", "RPA3", "MAP2K1", "MAP2K2", "MAP2K3", "MAP3K4", "MAP3K5", "MAP3K8")

# Stress_response
gene_signatures$Stress_response <- c("MAP2K1", "MAP2K2", "MAP2K3", "MAP3K4", "MAP3K5", "MAP3K8", "MAPK1", "MAPK1", "MAPK11", "MAPK13")

# MAPK_Signaling
gene_signatures$MAPK_Signaling <- c("ITGA1", "ITGA4", "ITGAE", "ITGAL", "ITGAM", "ITGB1", "ITGB2", "ITGB7", "SELL", "SELPLG")

# Adhesion
gene_signatures$Adhesion <- c("IFIT1", "IFIT2", "IFIT3", "IFIT5", "STAT1", "STAT2", "IRF1", "IRF4", "IRF7", "IRF8")

# IFN_Response
gene_signatures$IFN_Response <- c("ATP1B3", "ATP2A3", "ATP2B1", "ATP2B4", "ATP5A1", "ATP5B", "ATP5C1", "ATP5D", "ATP5E", "ATP5EP2")

# Oxidative_phosphorylation
gene_signatures$Oxidative_phosphorylation <- c("SLC2A3", "SLC2A8", "SLC2A8", "PFKFB3", "ALDOA", "PGAM1", "PGK1", "PKM", "LDHA", "LDHB")

# Glycolysis
gene_signatures$Glycolysis <- c("ACAA1", "ACADM", "ACADVL", "ACSL5", "ALDH16A1", "ALDH9A1", "ALDH9A1", "BAK1", "BAX", "BID")

# Fatty_acid_metabolism
gene_signatures$Fatty_acid_metabolism <- c("BCL2L11", "BCL11B", "BCL2L1", "BIN1", "BIN2", "BIN1", "BAG3", "BAG4", "BAK1", "BAX")

# Pro-apoptosis
gene_signatures$Pro_apoptosis <- c("BCL2L11", "BCL11B", "BCL2L1", "BIN1", "BIN2", "BIN1", "BAG3", "BAG4", "BAK1", "BAX")

# Anti-apoptosis
gene_signatures$Anti_apoptosis <- c("BCL2L1", "BCL11B", "BCL2L1", "BIN1", "BIN2", "BIN1", "BAG3", "BAG4", "BAK1", "BAX")
```
