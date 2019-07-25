
3D Mapping and Visualization of 2D Experimental Data Stomach Afferents and Efferents
====================================================================================
			   
.. contents:: Contents: 
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********
.. todo::
    add link to final portal URL that takes user straight to this dataset display.

A statistically representative and anatomically-based 3D scaffold of the rat stomach was created to map 230 nerve ending pathways traced from 68 2D rat stomach whole mounts. Micro-CT image data of 11 animals with an average volume of 9.9cm3 were used to construct this 3D scaffold. Imaging and subsequent data segmentation was performed at the Powley laboratory in Purdue University using MBF bioscience software Neurolucida. 
Initially, an approximate surface was generated for each case using gross morphometric measurements of the organ. These surfaces were then fitted to the segmented data using University of Auckland Bioengineering software (fig. 1). The fitted scaffolds surfaces (11) were combined to form an average stomach surface (fig 2). A representative tissue thickness throughout the organ inferred by careful examination of all segmented data sets was included to generate the final 3D scaffold (fig 3).

.. figure:: _images/stomach_fig1.png
   :figwidth: 95%
   :width: 95%
   :align: center

.. figure:: _images/stomach_fig2.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
.. figure:: _images/stomach_fig3.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
The tissue wall of this 3D scaffold was then split in to three different layers, namely, the outermost longitudinal smooth muscle layer, a layer beneath that to represent the circular smooth muscle layer followed by the mucosal/submucosal layer. A very thin membrane was also introduced to mimic the layer containing myenteric plexus between the smooth muscle layers (fig. 4). The thickness of different tissue layers in the current 3D scaffold is an approximate based on experimental observations. Plans are under way to acquire more detailed high resolution images to better understand the tissue structural composition. Once that information is available, the 3D scaffold’s tissue layers will be updated accordingly. 

.. figure:: _images/stomach_fig4.png
   :figwidth: 95%
   :width: 95%
   :align: center  

A total of 230 neurite pathways imaged and segmented from whole mounts of 68 different rats were then mapped in to the multi-layered 3D scaffold. Specimen preparation, imaging and tracing of nerve endings were conducted at the Powley laboratory and Neurolucida has been used for image processing (fig. 5). Each neurite, either from dorsal or ventral half, with its whole mount contour was first deformed in the X-Y plane to match its respective standard contour using a free-form deformation technique (fig 6). The standard contour (dorsal or ventral) was then transformed with its contents to its 3D counterpart (fig 6). The latter is either the dorsal or ventral half of the statistically representative 3D scaffold described earlier. Free-form deformation and subsequent 2D to 3D transformation was carried out using University of Auckland Bioengineering software.

.. figure:: _images/stomach_fig5.png
   :figwidth: 95%
   :width: 95%
   :align: center  

.. figure:: _images/stomach_fig6.png
   :figwidth: 95%
   :width: 95%
   :align: center  
   
The neurites consisted of three types of afferents- longitudinal intramuscular arrays (IMAs), intraganglionic laminar endings (IGLEs) and circular IMAs and efferents were mapped from their original 2D contours through the standard 2D contour and then finally to the 3D scaffold. The IGLEs (afferents) and efferents were placed between smooth muscle layers (myenteric plexus layer) while IMAs were included in the middle of respective smooth muscle layers (fig. 7). 

.. figure:: _images/stomach_fig7.png
   :figwidth: 95%
   :width: 95%
   :align: center     
   
   
   


Step-by-step instructions 
*************************
.. todo:: 
		Write steps + screenshots

Follow these step-by-step instructions to familiarise yourself with the flow of the web interface.

Explain the steps to be followed by the end user on the web interface. 

#. Step 1 ....

Add screenshot

.. .. figure:: _images/snip
   :figwidth: 61%
   :width: 51%
   :align: center
   
#. Step 2 ....

Add screenshot 

Working with the interface
**************************
This section explains how to use more specific features of the interface.

.. todo::
      Highlight features/capabilities that are particular to this use-case.
	   
:ref:`Flatmap-Viewer`
^^^^^^^^^^^^^^^^^^^^^
The :ref:`Flatmap-Viewer` represents a high-level view of overall connectivity of the autonomic nervous system.
	
:ref:`Scaffold-Viewer`
^^^^^^^^^^^^^^^^^^^^^^
:ref:`Scaffold-Viewer` is used to view the anatomical organ scaffold of the specific organ selected on the Flatmap.
	
:ref:`Data-Viewer`
^^^^^^^^^^^^^^^^^^
This viewer is used to view the *Electrocardiograph* data recorded with the experiment video. Refer the section :ref:`Data-Viewer`.













