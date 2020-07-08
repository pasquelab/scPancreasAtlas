# The Gene Regulatory Landscape of the Human Adult Pancreas

This repository contains .loom file supplemental to the article "The Gene Regulatory Landscape of the Human Adult Pancreas Reveals Critical Regulators of Cell Identity".

As a resource to the community, this .loom file contains gene expression and regulon based UMAP plots, cluster annotations, integrated gene expression and gene regulatory data from datasets analyzed in this manuscript.

The .loom file can be downloaded here: [scPancreasAtlas.loom](https://filesender.belnet.be/?s=download&token=8d087b4d-3909-4fc4-8c11-a92fb9989bec) and browsed interactively using [SCope platform](https://scope.aertslab.org). Alternatively, standalone SCope apps for macOS and Linux can be downloaded from [here](https://github.com/aertslab/SCope/releases).

SCope was developed and is maintained by [Aerts lab.](https://www.aertslab.org/)



## SCope Tutorial

Upload the loom file by clicking on ‘upload new dataset ‘ on the left. This can take a few minutes depending on your internet connection. 

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_1.png?raw=true)

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_2.png?raw=true)

The uploaded .loom file should now be visible under the ‘User uploaded’ tab. Successfully uploading the .loom file will activate a private, temporary session for the user. Each session expires after 5 days, but can be renewed by re-uploading the loom file. Click on the file to start interacting with the data.

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_3.png?raw=true)

You can change the UMAP coordinates from the left sidebar **(1)** to visualise gene expression (see Figure 1)  or regulon based UMAP (see Figure 2).
Next, you can use the three (Red, Green and Blue) search bars above **2** to search for genes, regulons or cell types of interest to visualise. 
Please note that the integrated gene expression is already log normalized so toggle the ‘Log transform’ and ‘CPM normalise’ options on the left side off.

The color scaling can be adjusted using the sliders on the left **3**. 
Colors will blend to indicate overlap. Gene expression, regulon activity and cell type annotation can be freely combined like this. 


![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_4.png?raw=true)
*The NEUROD1 regulon (red) is active in gamma cells (blue) indicated by purple*

Regulons can be explored in more detail in the 'Regulon' tab.
Here, you can assess the distribution of regulon activity across all cells and binarise regulon activity by moving the slider. 
An overview of all target genes of the selected regulon can be found on the right. Clicking on a target gene will show its expression on the UMAP.
The list of target genes can be downloaded as an .tsv file by pressing the blue button below to further explore in [iRegulon](http://iregulon.aertslab.org/) or gene ontology.   

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_5.png?raw=true)
*[Tcf 21](https://pubmed.ncbi.nlm.nih.gov/31549421/) has been identified as transcription factor that deactivates fibrogenic hepatic stellate cells when liver fibrosis occurs in mice. Binarisation of TCF21 regulon activity reveals high regulon activity in stellate cells, suggesting the importance of TCF21 in human pancreatic stellate cells.*

Gene expression and regulon activity can be compared between different annotated groups in the 'Compare' tab.
Annotations can be dragged into the boxes for visualisation

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_6.png?raw=true)
*Comparing the activity of the regulon ARX between alpha, beta, delta and gamma cells reveals high IRX2 activity in alpha and gamma cells.*

Different annotations can be combined together for comparison (eg. non-diabetic beta cells vs type 2 diabetic beta cells).

![alt text](https://github.com/pasquelab/scPancreasAtlas/blob/master/Screenshot_7.png?raw=true)
*RXRG regulon activity is higher in type 2 diabetic beta cells compared to non-diabetic beta cells, as shown in Figure 4D)*
