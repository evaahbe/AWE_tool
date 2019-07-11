# Airborne Wind Energy Trajectory Analysis

This software computes, for specified parameters of the kite flying in crosswind conditions, quantities such as the kite velocity, apparent wind, tether force and generated power. The computations are based on the assumption that the state of the kite moves in a constant force equilibrium where the forces exerted by the tether balance out the aerodynamic forces on the kite at every instant. The consequences of this assumption are that there is no acceleration of the kite, no tether drag and no gravitational forces, thus also the mass of the kite does not play a role. Note, that these are assumptions imposing strong simplifications on the dynamics of a kite flying in crosswind conditions. This applies, albeit in different ways, both for rigid wings as well as for soft kites. Nonetheless, since the forces regarded here are in standard operating conditions the dominating forces in crosswind flight, the analysis presented in this software provides a initial understanding of the variations and limits of the quantities of interest. The influence of the variation of parameters both relating to the kite as well as regarding the environmental conditions can be easily and quickly investigated. The software was written in MATLAB (version R2016b) App Designer and is available open source under the GPL 3.0 license. See also the License Statement at the end of this documentation (Chapter 4). 

## Installation

Double-click on the .mlappinstall file to install the software. After the successful installation an icon appears in the ‘Apps’ tab in MATLAB named ‘AWE Trajectory Analysis v1.0’. The application can be started by clicking on the icon.

## Physics & Use

Please see enclosed PDF.

## Acknowledgments

This project has received funding from the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie grant agreement No 642682 (AWESCO).

## Copyright & License

The copyright is with the Automatic Control Laboratory, ETH Zurich, 2017. This software is licensed under GPL 3.0. You can redistribute it and/or modify it under the terms of the GNU General Public License version 3 as published by the Free Software Foundation. Any resulting output from this software or modifications of it shall also be licensed under the GPL 3.0. This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details. For a copy of the GNU General Public License see http://www.gnu.org/licenses/.
