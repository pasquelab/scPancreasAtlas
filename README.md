# Revealing the Key Regulators of Cell Identity in the Human Adult Pancreas

This repository contains the .loom file supplemental to the article "Revealing the Key Regulators of Cell Identity in the Human Adult Pancreas".

As a resource to the community, this .loom file contains gene expression and regulon based UMAP plots, cluster annotations, integrated gene expression and gene regulatory data from datasets analyzed in this manuscript.

The .loom file can be downloaded here: [scPancreasAtlas.loom](https://filesender.belnet.be/?s=download&token=8d087b4d-3909-4fc4-8c11-a92fb9989bec) and browsed interactively using the [SCope platform](http://scope.aertslab.org/#/). Alternatively, the standalone SCope app for macOS and Linux can be downloaded from [here](https://github.com/aertslab/SCope/releases).

SCope was developed and is maintained by [Aerts lab](https://www.aertslab.org/).

We recommend to open SCope in a Google Chrome webbrowser to ensure optimal interaction with the loom file. 

## SCope Tutorial

Upload the loom file by clicking on ‘upload new dataset ‘ on the left. This can take a few minutes depending on your internet connection. 

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_1.png?raw=true)

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_2.png?raw=true)

The uploaded .loom file should now be visible under the ‘User uploaded’ tab. Successfully uploading the .loom file will activate a private, temporary session for the user. Each session expires after 5 days, but can be renewed by re-uploading the loom file. Click on the file to start interacting with the data.

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_3.png?raw=true)

You can change the UMAP coordinates from the left sidebar **(1)** to visualise gene expression (as seen in Figure 1)  or regulon based UMAP (as seen in Figure 2).
Next, you can use the three (Red, Green and Blue) search bars above **2** to search for genes, regulons or annotations of interest. 
Please note that the integrated gene expression is already log normalized so toggle the ‘Log transform’ and ‘CPM normalise’ options on the left side off.

The color scaling can be adjusted using the sliders on the left **3**. 
Colors will blend to indicate overlap. Gene expression, regulon activity and cell type annotation can be freely combined like this. 

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_4.png?raw=true)
*The NEUROD1 regulon (red) is active in gamma cells (blue) indicated by purple*

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_4_2.png?raw=true)
*[A recent study](https://www.sciencedirect.com/science/article/pii/S1934590920302824?via%3Dihub) has identified human islets as a model to study SARS-CoV-2 infection. Two proteins associated with SARS-CoV-2 infection are ACE2, the putative SARS-CoV-2 receptor, and TMPRSS2, the effector protease [(Hoffmann et al., 2020)](https://www.sciencedirect.com/science/article/pii/S0092867420302294). ACE2 (green) is mostly expressed in stellate, ductal cells and a subset of beta cells. TMPRSS2 (red) is expressed in acinar, ductal and a subset of alpha cells.* 

Regulons can be explored in more detail in the 'Regulon' tab.
Here, you can assess the distribution of regulon activity across all cells and binarise regulon activity by moving the slider. 
An overview of all target genes of the selected regulon can be found on the right. Clicking on a target gene will show its expression on the UMAP.
A list of target genes of specific regulons can be downloaded as an .tsv file by pressing the blue button below to further explore in [iRegulon](http://iregulon.aertslab.org/) or perform [gene ontology analyses](http://geneontology.org/).   

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_5.png?raw=true)
*[Tcf 21](https://pubmed.ncbi.nlm.nih.gov/31549421/) has been identified as a transcription factor that deactivates fibrogenic hepatic stellate cells when liver fibrosis occurs in mice. Binarisation of TCF21 regulon activity reveals high regulon activity in stellate cells, suggesting the importance of TCF21 in human pancreatic stellate cells.*

Gene expression and regulon activity can be compared between different annotated groups in the 'Compare' tab.
Annotations can be dragged into the boxes for visualisation.

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_6.png?raw=true)
*Comparing the activity of the regulon ARX between alpha, beta, delta and gamma cells reveals high IRX2 activity in alpha and gamma cells.*

Different annotations can be combined together for comparison by selecting 'AND' as superposition **(1)** (eg. non-diabetic beta cells vs type 2 diabetic alpha or beta cells).

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_7.png?raw=true)
*EGR1 regulon activity seems slightly elevated in type 2 diabetic alpha cells compared to non-diabetic alpha cells. EGR1 was shown to be essential for basal and gastrin-dependent glucagon gene transactivation in alpha cells, consistent with observed chronic hyper-glucagonemia in type 2 diabetes [(Leung-Theung-Long et al., 2005)](https://pubmed.ncbi.nlm.nih.gov/15611055/).*
