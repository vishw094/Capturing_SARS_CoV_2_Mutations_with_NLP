# Capturing_SARS_CoV_2_Mutations_with_NLP
My Research Project


This repository contains the code and methodology for the research project: "Capturing SARS-CoV-2 Mutations with Natural Language Processing." The project explores how techniques from Natural Language Processing (NLP) can be applied to genomic sequences to analyze and track mutations in the SARS-CoV-2 virus, with potential applications for monitoring variant evolution and aiding in early detection of emerging threats.

# 🧬 Project Overview

SARS-CoV-2, the virus responsible for COVID-19, has undergone numerous mutations since its emergence. Traditional methods for tracking mutations can be labor-intensive and slow. This project proposes an innovative approach: treating genomic sequences as a "language" and using NLP models—particularly word2vec—to learn representations of codons (3-nucleotide words). These embeddings help identify patterns and shifts that correspond to emerging variants.

# 📊 Key Contributions
- Developed a word2vec-based model to create distributed representations of codons.

- Introduced the concept of "blips" in latent dimensions—sudden shifts in codon embeddings that signal mutations.

- Demonstrated that blips can be predictive of upcoming surges in COVID-19 cases.

- Applied temporal and spatial analyses to link embedding changes to specific variants like Alpha, Beta, and Delta.

- Offered an interpretable, language-based representation of mutations, aiding in early warning systems.

# 🧠 Methodology
- Data Collection: SARS-CoV-2 genome sequences obtained from GISAID.

- Preprocessing: Sequences tokenized into non-overlapping codons.

- Modeling: Trained a skip-gram word2vec model to learn codon embeddings.

- Blip Detection: Monitored fluctuations in latent dimensions to identify significant changes ("blips").

- Analysis: Correlated blip patterns with epidemiological data to assess predictive power.

# 📈 Results
- Certain embedding dimensions captured functionally important mutation sites, including L452R, D614G, and P681R.

- Detected consistent blip patterns across countries prior to variant outbreaks.

- Found high correlation (r > 0.9) between blip counts and future COVID-19 case numbers.
