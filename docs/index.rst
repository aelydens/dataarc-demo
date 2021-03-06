.. DataARC Ecosystem Explorer documentation master file, created by
   sphinx-quickstart on Sat Jul 11 15:20:33 2020.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. |DEE| raw:: html

   <a href="https://github.com/ropitz/dataarc-demo" target="_blank">dataARC Ecosystem Explorer</a>
   
.. |DPW| raw:: html

   <a href="https://www.data-arc.org/" target="_blank">dataARC project website</a>

.. |DST| raw:: html

   <a href="https://ui.data-arc.org/" target="_blank">dataARC Search Tool</a>
   
.. |WS| raw:: html

   <a href="https://www.data-arc.org/contributors-toolbox/map-your-data/" target="_blank">These materials</a>
   
.. |WS2| raw:: html

   <a href="https://www.data-arc.org/contributors-toolbox/map-your-data/" target="_blank">Conceptual Guide</a>

.. |DNOA2| raw:: html

   <a href="https://github.com/ropitz/dataarc-demo/blob/master/Data%20Network%20Overview%20Analyses%20-%20Final.ipynb" target="_blank">The Data Network Overview Analyses notebook</a>


.. image:: _static/dataarc_logo_final_sml.png
   :class: align-center
  

.. toctree::
   :hidden:
   :maxdepth: 1

   index
   dataarc-tool-help
   dataarc-api
   ecosystem_explorer
   add-new-dataset
  
Accompanying the |DPW| and the |DST|, this guide provides "how-to" information on all things dataARC.  The result of two successful NSF awards (cyberNABO 1.0 and 2.0 - SMA 1439389 and1637076) and a strong international research collaboration, dataARC bridges data from the humanities to the environmental sciences to support the interdisciplinary study of human ecodynamics in the North Atlantic.  Read more about the project background, the research team, and the wide array of datasets available in dataARC on the |DPW| and learn how to use the |DST| in your research. You may also find the dataARC API useful in your project. Learn more about it by visiting the `API Documentation page <dataarc-api.html>`__.

Reference the `dataARC Search Tool Help <dataarc-tool-help.html>`__ to learn how to use the temporal, spatial, and conceptual visualization graphs, how to create and combine filters, and how to download and interpret your results.  Finally, interested in adding your data to dataARC?  DataARC is built to encourage and support open data and collaboration. :ref:`Interested in Adding your data?  Learn how...`.

Getting Started
================

Scientists and researchers who are interested in exploring concepts and datasets related to the changing landscape in the North Atlantic, consider starting with the :ref:`DataARC Search Tool` section.

For those interested in data analytics and automated data retrieval, you might be interested in the :ref:`DataARC API` and the :ref:`DataARC Ecosystem Explorer` tool boxes.

Maybe you have decided dataARC would be a great fit for your data, or you would like to map data to concepts. Navigate to the :ref:`Interested in Adding your data? Learn how...` section.

DataARC Search Tool
====================

.. image:: _static/dataarc.jpg
   :width: 400
   :class: align-left

The |dst| is the online interface that allows users to query the archaeological, textual, and environmental data in dataARC. Learn how to filter data temporally, spatially, conceptually, and by keyword search.  Use `this guide <dataarc-tool-help.html>`__ to better understand how the dynamic data visualization graphs work, how to filter and optimize your results, and also how to download your data.

DataARC API
===========

The dataARC REST API is a useful tool for gathering, exploring, and modifying dataARC information to help researchers interested in automation and deeper data analytics. Find more information about using the dataARC API by visiting the `API Documentation page <dataarc-api.html>`__.

Use cases are demonstrated in Python with `this Jupyter Notebook <https://github.com/ropitz/dataarc-notebook/blob/main/use_cases_examples.ipynb/>`__

DataARC Ecosystem Explorer
==========================

The |dee| is a virtual sandbox designed to help dataset contributors think through mapping their data to the dataARC community's knowledge map of the concept of "changing landscapes." It is also designed to help advanced users better understand how data and concepts are connected in the dataARC Ecosystem. Use `this guide <ecosystem_explorer.html>`__ to walk you through learning the Ecosystem Explorer tool set that is provided as a Jupyter Notebook.

|DNOA2| allows you to calculate graph metrics like betweenness centrality on the dataARC concept map.  It is a useful tool for beginning high-level exploration of how different concepts are connected and currently runs off of the dataARC API (check out the `dataARC API documentation <dataarc-api.html>`__).



Interested in Adding your data?  Learn how...
=============================================

Preparing your data for ingest into dataARC will be a multi-step process.  If you haven't already, familiarize yourself with the |DST| and take a thorough glance of the contents of the |DPW| to better understand the project context and how the data are structured.  Next, you will want to step through each of the sections below.
  

1. A |WS2| to Developing Good Mappings for your Data
----------------------------------------------------------------
.. image:: _static/dataARC_chart3.jpg
   :width: 400
   :class: align-left

Thinking about how to map your data to the dataARC community's shared concept map can be challenging. Graduate students working with the project team have developed materials to guide PhD students considering contributing their data. |ws| designed to be used in a workshop, are relevant to anyone considering contributing project data to the dataARC Ecosystem and should be reviewed before creating combinators for your dataset.
|
|

2. Add your dataset using Github
----------------------------------
.. image:: _static/GitHub.png
   :width: 150
   :class: align-left

Now that you have a better understanding of how to map your data to the dataARC concept map and you've experimented with creating combinators using the dataARC Ecosystem Explorer, you are ready to begin uploading your data into dataARC.  `Click here <add-new-dataset.html>`__ for step-by-step guidance for creating your dataset, uploading it to GitHub, and creating combinators in dataARC.



3. Register as a contributor
----------------------------

Fill out the `dataARC contributor form <https://www.data-arc.org/request-to-be-a-data-contributor/>`__ to register as a member of the dataARC contributors team.


