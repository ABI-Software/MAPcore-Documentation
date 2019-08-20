3D Mapping and Visualization of 2D Experimental Data Stomach Afferents and Efferents
====================================================================================
			   
.. |scaffold-icon| image:: /_images/scaffold_map_icon.png
                      :width: 2 em

.. contents:: Contents: 
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********

A 3D scaffold of the rat stomach created using segmented microCT data from the Powley group is shown in a 3D window. The neurites including nerve endings (both IGLEs and IMAs) are displayed on the 3D scaffold. The scaffold can be cut and opened out flat to match the experimental whole-mount preparation, and to then display the experimental data. Note that 152 neurite maps (from 152 different rats) were each registered to a fitted scaffold for each rat and then morphed into the average flat mount scaffold. The data and models can also be seen at varying levels of stomach fills. This use-case demonstrates both the application of neural pathway data to the stomach, the use of a transformation between the normal 3D stomach anatomy and the 2D whole-mount preparation, and the ability to visualize data at varying levels of organ state (empty to full).  

Step-by-step instructions 
*************************

Follow these step-by-step instructions to familiarise yourself with the flow of the web interface.

**Step 1**. The default **Result** column displays the use cases available on the portal. Click on the
*3D Mapping and Visualization of 2D Experimental Data Stomach Afferents and Efferents* box. Click on the scaffold icon (|scaffold-icon|).

.. figure:: _images/stomach_2.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 2**. Allow a few seconds for the scaffold to load. Navigate between the 3D scaffold and layers view using the slider. Click on the play button to automate toggle between the configurations.

.. figure:: _images/stomach_3.png
   :figwidth: 95%
   :width: 95%
   :align: center

Scaffold Generation
*******************

A statistically representative and anatomically-based 3D scaffold of the rat stomach was created to map 230 nerve ending pathways. Micro-CT image data of 11 animals were used to construct this 3D scaffold. Imaging and  data segmentation was performed at the Powley laboratory using Neurolucida (MBF Bioscience). 
Initially, an approximate surface was generated for each case using gross morphometric measurements of the organ. These surfaces were then fitted to the segmented data using University of Auckland Bioengineering software (Fig. 1). The fitted scaffolds surfaces were combined to form an average stomach surface. A representative tissue thickness throughout the organ inferred by examination of all segmented data sets was included to generate the final 3D scaffold (Fig. 3), which was subsequently split into three anatomically-distinct tissue layers.

.. figure:: _images/stomach_fig1.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
.. figure:: _images/stomach_fig3.png
   :figwidth: 95%
   :width: 95%
   :align: center

230 neurite pathways imaged and segmented from whole mounts of 68 different rats were then mapped into the multi-layered 3D scaffold. Each neurite was first deformed in the X-Y plane to match its respective standard contour using a free-form deformation technique (Fig 6(a)). The standard contour was then transformed with its contents to its 3D counterpart (b). 2D to 3D transformation was carried out using University of Auckland Bioengineering software.

.. figure:: _images/stomach_fig6.png
   :figwidth: 95%
   :width: 95%
   :align: center  
   
The 2D neurite pathways were then mapped onto the 3D scaffold.

Future Steps
*************************

Plans are under way to acquire more detailed high-resolution images to better understand the tissue structural composition. Once that information is available, the 3D scaffold’s tissue layers will be updated accordingly. 
