# AI Use Log
- Tool/model & version: Gemini 3.5 Flash integrated within Google Colab.
  
- What I asked for: Prompts where the Bioinformatics_Module03 asked for AI usage. Additional assistance regarding some errors in code or clarification regarding new code topics. Assistance for coding in Rosalind.
  
- Snippet of prompt(s):
- "Why does printing my_list[1] in TASK P7.1 output "World" instead of "Hello"?"
- "How do I insert a new item at index 1 in the list?"
- "Could you help me find a single-cell prostate cancer dataset, at least one for training and some that can be withheld as a test dataset? Provide a link to these."

- Snippet out output(s):
1. How to find the CELLxGENE Prostate Datasets
Go to your web browser and search for "CZ CELLxGENE Discover".
Once on the homepage, click on the "Datasets" or "Collections" tab.
In the search bar on their site, type "Prostate Cancer".
You will find the major study titled "Single-cell map of diverse immune phenotypes in the metastatic prostate cancer microenvironment" (by the Tucci et al. group or similar) and the "Healthy and hyperplastic human prostate" atlas. You can download these directly as .h5ad files, which Scanpy reads perfectly!
2. How to find the GEO Datasets (NCBI)
Search on Google for "NCBI GEO".
In the GEO database search bar, type the accession number "GSE141445" or "GSE176031".
This will take you directly to the study pages:
GSE141445 is the Single-cell RNA sequencing of human prostate cancer study.
GSE176031 is the Single-cell RNA-seq of primary prostate cancer and matched normal tissues study.
Scroll to the bottom of the page to the "Supplementary file" section to download the count matrices (often named GSE141445_family.tar.gz or similar matrix files).
3. How to find the Broad Single Cell Portal Dataset
Search for "Broad Single Cell Portal" in your browser.
In their main portal search bar, type "Prostate Cancer".
Look for the study named "Single-cell RNA-seq of human prostate cancer microenvironment". You can download the metadata and expression files directly from their portal after a free sign-in.
  
- What I changed before committing: Phrasing, some variable names, spaces in code. Added certain comments to improve understanding of how AI-generated code works and what certain lines do.
  
- How I verified correctness (tests, sample data): Code was tested using Rosalind datasets and trial and error until the correct sample output was received from the sample dataset's inputs.
