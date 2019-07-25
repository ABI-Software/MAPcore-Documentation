Mapping Cellular Gene Expression in the Rat Heart from Image to Scaffold
=========================================================================
.. |open-control| image:: /_images/open_control.png
                      :width: 2 em
					  
.. contents:: Contents:
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********

Rat heart geometric 3Scan (www.3scan.com) data for both ventricles and both atria from the Schwaber/Vadigepalli/Cheng
group has been fitted with a 3D rat heart scaffold. The locations of a cluster of 151 ICN cell samples that have been
lifted for RNA-Seq analysis (molecular cell body transcript data) from a region of the left atrium, from a different animal,
are indicated on the 3D scaffold. Clicking on one of these tissue locations displays the RNA message level for the 154
genes examined. To visualize the spatial distribution of the RNA message, the 151 samples have been fitted with a
continuous field description using scaffold nodal parameters. Any one of the 154 genes can be selected to show the
spatial variation of that transcript as a heat map. Rat heart neural pathway data showing the efferent connectome
linking ICN cells in the left atrium and the SA node cells on the right atrium will be visualised in the next iteration
of this use-case. *Note* that the treatment process needed to extract the cells for RNA-Seq analysis left that rat heart
in a very distorted state which was therefore not fitted with a scaffold. Instead corresponding locations of the ICN
cells in the much less distorted 3Scan-processed heart were identified by eye and the cell information was transferred
to that heart.

.. figure:: _images/use_case4_workflow_white.png
   :figwidth: 95%
   :width: 90%
   :align: center

Step-by-step instructions 
*************************

Follow these step-by-step instructions to familiarise yourself with the flow of the web interface.

**Step 1**. Click on the Heart on the flatmap to generate search results for heart.

.. figure:: _images/Slide1.png
   :figwidth: 95%
   :width: 72%
   :align: center
   
**Step 2**. Hover on 'Molecular Phenotype Distribution of Single Rat ICN Neurons' search result.

.. figure:: _images/Slide2.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 3**. Select the blue circle.

.. figure:: _images/Slide3.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 4**. The Scaffold Viewer tab opens and the fitted heart scaffold can be visualised. A number of lifted neuronal cells have been mapped and registered on the scaffold (purple spheres).

.. figure:: _images/Slide4.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 5**. Click on |open-control| icon to pop-up the drop-down menu. Visibility can be turned ON or OFF for each item.

.. figure:: _images/Slide4aa.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 6**. Hover on different regions to highlight the chambers separately.

.. figure:: _images/Slide5.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 7**. Each cell has been lifted and assayed for the expression of 154 genes selected as associated with neuromodulation and cardiac function using qPCR or RNASeq. These have been mapped on the registered cells on the scaffold. Each cell has a unique ID.

.. figure:: _images/Slide5a.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 8**. Click on the Flatmap tab again.

.. figure:: _images/Slide6.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 9**. Now click on the green circle in the same search result.

.. figure:: _images/Slide7.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 10**. The Data Viewer tab opens to view the gene expression data. Currently only a raw barplot is supported.
In future, additional visualisation capabilities such as heatmap and clustering will be added.

.. figure:: _images/Slide8.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 11**. From the dropdown menu, more genes can be added to the plot.

.. figure:: _images/Slide9.png
   :figwidth: 95%
   :width: 72%
   :align: center

**Step 12**. The plot will show the expression of each gene with a unique color for all the registered cells on the scaffold.

.. figure:: _images/Slide10.png
   :figwidth: 95%
   :width: 72%
   :align: center


