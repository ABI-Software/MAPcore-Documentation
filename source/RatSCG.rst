
Rat Superior Cervical Ganglion
==============================
.. todo::
		Title for this usecase.
			   
.. contents:: Contents: 
   :local:
   :depth: 2
   :backlinks: top
   
Overview
********

Mapping of neuroanatomical connectivity is illustrated using rat superior cervical ganglion (SCG) data from Steve Lewis’ group at CWRU and rat brainstem data from Don Bolser’s group at UFL. This knowledge is modelled in `ApiNATOMY <http://open-physiology.org/demo/open-physiology-viewer/docs/>`_, and assimilated into the SPARC SciGraph, to demonstrate cross-domain data linkage. The Bolser and Lewis work has three major areas of physiological complementarity:

**Larynx/Trachea**: The sensory (Bolser) and motor (Lewis) limbs of protective mechanisms for the upper respiratory tract are captured in the connectivity model. 

**Carotid Body**: Chemosensing for oxygen partial pressure by the Carotid Body is key to respiratory control (Bolser). The SCG (Lewis) sends effector projections to the Carotid Body that modulate its chemosensing.

**Carotid Sinus**: Non-intuitively, blood pressure sensing by the carotid sinus is also key to respiratory control (Bolser). The SCG (Lewis) sends effector projections to the Carotid Sinus that modulate its barosensing.

Knowledge that links the above pathways provides a key means to discover multiple datasets (usually siloed behind institutional and collaborative divides) in these diverse physiology domains.

.. figure:: _images/uc9_1.png
   :figwidth: 95%
   :width: 95%
   :align: center

.. todo::
	This document guides a user of the SPARC Data Portal through the steps required to .......
	
	Add link to final portal URL that takes user straight to this dataset display.

Step-by-step instructions 
*************************

Follow these step-by-step instructions to familiarise yourself with the flow of the web interface.

**Step 1**. *Right-click* on **pink rectangles** that symbolizes portion of nerve.

.. figure:: _images/uc9_2.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 2**. *Left-click* on ‘Find edges connected to node’ to find neuronal routes conveyed by the selected nerve.

.. figure:: _images/uc9_3.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
**Step 3**. Neuronal routes conveyed by the SLN as shown below.

.. figure:: _images/uc9_4.png
   :figwidth: 95%
   :width: 95%
   :align: center

**Step 4**. *Left-click* on ‘Find nodes and edges connected to node’ to find data relevant to structures connected by the selected nerve.

.. figure:: _images/uc9_5.png
   :figwidth: 95%
   :width: 95%
   :align: center
   
**Step 5**. Structures connected by the SLN as shown below.

.. figure:: _images/uc9_6.png
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




























