.. _Flatmap-Viewer:

Flatmap Viewer
==============

.. contents:: Contents:
   :local:
   :depth: 2
   :backlinks: top

.. |open-control| image:: /_images/open_control.png
                      :width: 2 em

Overview
********

The flatmap viewer tool available on the SPARC Data Portal is used to navigate a ``flatmap`` -- a zoomable
map showing representing anatomical features -- in order to easily search for knowledge about features
on the map.

A map consists of a number of image and vector tiles at different resolutions stored on a server. These are
displayed in the web-browser using similar technology to that used by interactive geographical maps.

Interactive map layers
^^^^^^^^^^^^^^^^^^^^^^

A map is made up of one or more interactive layers, and is initially displayed with a number of these layers
active. When there is more than one interactive layer, the ``layer-switcher`` control, represented by the
|open-control| icon at the top-left corner, can be used to manage active layers.

Querying a map's features
^^^^^^^^^^^^^^^^^^^^^^^^^


Some features in a layer are annotated as modelling one or more anatomical entities. These features show a
tooltip when the mouse pointer hovers over them,  and knowledge about the feature can can be searched for by clicking
on the highlighted feature.



Some layers, such as the ``neural`` layer, have been configured to allow queries to also be made against
the displayed ``nodes``. There are two types of such node queries:

1. Find all ``edges`` that belong to the node, that is edges that start, stop, or pass through the node.
2. Find all other nodes connected by some edge to the queried node. This query also results in knowledge
   searches being made for those found nodes that model an anatomical entity.

Queryable nodes are highlighted when the mouse pointer is over them -- they will only show a tooltip if they have
an anatomical identifier.

Node queries are made using the ``right-click`` context menu.


Map interaction
^^^^^^^^^^^^^^^

Besides zoom and pan, using standard mouse or touch-pad controls, a ``left-click`` will query for knowledge
about the current anatomical entity, and a ``right-click`` will show a context menu, allowing the different node
connectivity queries to be made.