<h2>Session 5B: Buildings II</h2>
<p>
<b>Title:</b> <i> Template based code generation of  Modelica building energy simulation models </i> <br />
<b>Authors:</b> <a href="../authors/author_201.html">Christoph Nytsch-Geusen</a>, <a href="../authors/author_119.html">Alexander Inderfurth</a>, <a href="../authors/author_133.html">Werner Kaul</a>, <a href="../authors/author_185.html">Katharina Mucha</a>, <a href="../authors/author_225.html">Jörg Rädler</a>, <a href="../authors/author_272.html">Matthis Thorade</a> and <a href="../authors/author_282.html">Carles Ribas Tugores</a><br />
<b>Abstract:</b>This contribution describes an approach for a template based code generation for different detailed Modelica models for building energy simulation (BES). 
The information from several data sources, which describe the building geometry, the building construction, the building location and the building itself, is used to fill a building data model. This intermediate data structure is still independent of a certain building simulation tool. 
A new developed tool for template based code generation (CoTeTo) uses the building data model and combines it with a set of different code generators, which are able to generate Modelica building models with a different level of detail: Strong simplified low-order building models for district energy simulation with a large population of buildings, more advanced multi-zone building models for building energy simulation and 3D space resolved room models for a detailed indoor climate analysis.
Three case studies for the mentioned building model types demonstrate the code generation approach.<br />
<b>Links:</b> <a href="../submissions/ecp17132199_NytschgeusenInderfurthKaulMuchaRadlerThoradeTugores.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Modelling and Simulation of Standardised Control Functions from Building Automation </i> <br />
<b>Authors:</b> <a href="../authors/author_242.html">Georg Ferdinand Schneider</a>, <a href="../authors/author_213.html">Georg Ambrosius Peßler</a> and <a href="../authors/author_255.html">Simone Steiger</a><br />
<b>Abstract:</b>Despite the accepted fact that control logic deployed in
future and existing buildings through building automation
systems constitutes a key factor for increasing their energy
efficiency, the support for modelling and simulation
of these in current state-of-the-art simulation tools and libraries
is rather limited. In particular a gap exists for modelling
and simulation of standardised control functions. In
this work we present an approach for modelling standardised
control logic using Modelica. We evaluated the interoperability
of the modelling approach by simulating a test
case of an automation solution controlling the sunshade of
a room and by reimplementing a state-based control for an
air handling unit reusing models from two Annex60 compliant
libraries.<br />
<b>Links:</b> <a href="../submissions/ecp17132209_SchneiderPelerSteiger.pdf">Full paper</a></p>
<hr />
<p>
<b>Title:</b> <i> Modelling of Heat Pumps with Calibrated Parameters Based on Manufacturer Data </i> <br />
<b>Authors:</b> <a href="../authors/author_44.html">Massimo Cimmino</a> and <a href="../authors/author_298.html">Michael Wetter</a><br />
<b>Abstract:</b>A Modelica model for the simulation of heat pumps is presented. The model uses a simplified vapor compression cycle with only five refrigerant states. Parameters to the model are evaluated using an optimization procedure to minimize the differences between the model predicted heating capacities and power input and those provided in the manufacturer technical data. The optimization process is done from a Python implementation of the heat pump model.
The model is first tested by verifying that calibration from performance data generated by the heat pump model results in the same parameters as the ones used in the generation of the performance data. In the presented example, calibrated parameters were found close to the original parameters used to generate the data, except for the evaporator heat transfer coefficient for which the model was found not to be very sensitive. In a second example, the model is calibrated against manufacturer data. The heating capacities and power input calculated from the calibrated model are within 2.7% and 4.7% of the manufacturer data, respectively. Finally, the computational performance of the model is tested in a system simulation of a hydronic heating system. The simulation using the presented heat pump model was executed in 152 seconds, compared to 140 seconds for the same system using a simple boiler model.<br />
<b>Links:</b> <a href="../submissions/ecp17132219_CimminoWetter.pdf">Full paper</a></p>