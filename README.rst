=====
FCD2VANET
=====

:Date: Jun, 2013
:Author: Agata Grzybek
:Organization: University of Luxembourg
:Contact: agata.grzybek@uni.lu
:Version: 0.1
:Copyright: 2013, University of Luxembourg

Description
-----------

.. This document is a general introduction to the project. Check the wiki for more information. 

FCD2VANET project allows to present floating car data (FCD) as a vehicular ad hoc network (VANET).

FCD is floating car data, i.e. localisation data collected from moving vehicles `fcd`_.

VANETs is a vehicular ad hoc network, i.e. wireless networks consiting of moving vehicles `vanet`_
VANETs are a key technology in a concept of Connected Vehicles, that aims in improving traffic efficiency, safety and convenience `cc`_. 

Real-world experiments of large-scale VANETs are imposible, thus computer simulations are necessary.
Simulation of VANETs is complex, becuase the underlying network topology reproduces a specific mobility of vehicles, that impacts the connectivity among nodes.
Moreover, networks are highly dynamic, time-vairand and often of large scale.

Features
--------

SUMO2VANET allows to:

(1) `Generate floating car data FCD`_ of any road network with traffic simulator SUMO `SUMO`_ .

(2) `Generate your VANET`_ -a dynamic graph with vehicles as nodes and connections between vehicles as edges. 
	
	Edges can be specified based on:
	
	- Euclidean distance
	
	- DSRC wireless range (using NS3 simulator `ns-3`_ )
	
	VANET graph generated to a general format file .csv. 
	
(3) `Analyse and visualise VANET`_ in different ways:
	- Calculate connectivity statistics with a python script
	- Present as a dynamic graph in GraphStream .dgs format
	
For more information please check the `Wiki`_ pages. 


.. _Wiki: https://github.com/agacia/fcd2vanet/wiki/
.. _fcd: http://en.wikipedia.org/wiki/Floating_car_data
.. _vanet: http://en.wikipedia.org/wiki/Vehicular_ad-hoc_network
.. _cc: http://www.its.dot.gov/connected_vehicle/connected_vehicle.htm
.. _ns-3: http://www.nsnam.org/
.. _SUMO: http://sumo.sourceforge.net/
.. _Generate floating car data (FCD): github.com/agacia/fcd2vanet/wiki/FCD_generation
.. _Generate your VANET: github.com/agacia/fcd2vanet/wiki/VANET_generation
.. _Analyse and visualise VANET: github.com/agacia/fcd2vanet/wiki/VANET_analysis_and_visualisation