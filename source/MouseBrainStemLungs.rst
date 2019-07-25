
Mapping Gene Expression in the Mouse Lungs from Images to Scaffold
===================================================================		
.. |open-control| image:: /_images/open_control.png
                      :width: 2 em	
					  
.. contents:: Contents: 
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********

A 3D scaffold of the mouse thoracic cavity created using segmentation of longitudinal microCT scans from the SIMBA VIA (Vision and Image Analysis) public database is visualized in the webGL window. The trachea and main bronchi are also shown as rings of segmented points. Confocal stained images from Taylor-Clark group for mouse lungs are embedded into the scaffold. The confocal images were obtained from the right middle lobe (RML). The scaffold was registered to ensure alignment with the airway branch visible on the confocal. This use-case will be the first of many that link the organ systems with the brain stem.

.. figure:: _images/use_case5_lung.png
   :figwidth: 100%
   :width: 91%
   :align: center
   
Below is an **introductory video** which explains how an anatomically based 3D thoracic shape of the lungs are generated. 

.. raw:: html

	<iframe width="560" height="315" src="https://www.youtube.com/embed/8FDcPuwWAQo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>   


.. todo::
	provide demo link 


Step-by-step instructions 
*************************
Follow these step-by-step instructions to familiarise yourself with the flow of the web interface.

**Step 1.** Click on the **Lungs** on the flatmap to generate search results for lungs.

.. figure:: _images/lungs_01.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
**Step 2.** Select **Data for Mouse Lungs** from the search results. Click on scaffold icon. 

.. figure:: _images/lungs_02.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
**Step 3.** Click on the left and right lungs to highlight them in **green**.

.. figure:: _images/lungs_03.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 4.** Click on |open-control| icon to pop-up the drop-down menu.

.. figure:: _images/lungs_04.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 5.** Visibility can be turned ON or OFF for the items. 

.. figure:: _images/lungs_05.png
   :figwidth: 95%
   :width: 95%
   :align: center

Working with the interface
**************************
This section explains how to use more specific features of the interface.
	   
:ref:`Flatmap-Viewer`
^^^^^^^^^^^^^^^^^^^^^
The :ref:`Flatmap-Viewer` represents a high-level view of overall connectivity of the autonomic nervous system.
	
:ref:`Scaffold-Viewer`
^^^^^^^^^^^^^^^^^^^^^^
:ref:`Scaffold-Viewer` is used to view the anatomical organ scaffold of the specific organ selected on the Flatmap.
	
:ref:`Data-Viewer`
^^^^^^^^^^^^^^^^^^
This viewer is used to view the *Electrocardiograph* data recorded with the experiment video. Refer the section :ref:`Data-Viewer`.






















