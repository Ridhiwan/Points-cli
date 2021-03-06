
POINTS-CLI
----------
Use this program to display random points and measure angles and distances
between them.

Description:
-----------

Points-cli is a small program that takes a given number of randomly generated 
points in 3-Dimensions and plots them in multiple colors using matplotlib. It
then allows the user to obtain various measurements from distances and angles
of the points to the van de Waals potential between centers of noble gases'
molecules emulated by the random points. 

The points are restricted within boundaries of a box. The user interacts with
the program through both the command line interface and the matplotlib plot.
From the command line interface the user is taken through elaborative steps
that describe the proper arguments and options. The plot is a 3D scatter plot
with an extra feature that enables the user to hover the mouse over any point
to display the index assigned to that point.

After the plot has been displayed an access to a menu appears on the command
line with five options: Measure distance, Measure angle, vdW Lennard-Jones,
vdW Morse and Exit.


GETTING STARTED
---------------

Dependencies:
------------
1. Python 3.7.6
2. Numpy 1.18.1
3. Matplotlib 3.1.3
4. tqdm 4.47.0


Installing:
----------
pip install Points-cli


Executing program:
-----------------
Points-cli


Help:
----
To make the program run faster opt for a smaller number of points depending 
on the processing power and memory available at your disposal.

You can always use Ctrl+C to prematurely exit the program. 


Authors:
-------
1. Ridhiwan Ramadhan Mseya


Version History:
---------------
--> Version 0.1.2
	-Increased calculation speeds.
	-Added options to calculate van de Waals potentials.

--> Version 0.1.1
	-Downloads needed dependencies.

--> Version 0.1
	-Initial Official Release.


License:
-------
This project is licensed under the name Points-cli
License - see the LICENSE file for details.


Acknowledgments:
---------------
Inspiration from Antoine Marion.


References:
----------
Lennard-Jones parameters:
1. Oh, S., 2013. Modified Lennard-Jones Potentials with a Reduced Temperature-Correction Parameter for Calculating Thermodynamic and Transport Properties: Noble Gases and Their Mixtures (He, Ne, Ar, Kr, and Xe). Journal of Thermodynamics, 2013, pp.1-29.
2. Gopal, R., 2020. ON INTERMOLECULAR LENNARD-JONES POTENTIAL ENERGY PARAMETERS FOR RADON. [online] Osti.gov. Available at: <https://www.osti.gov/biblio/4765928> [Accessed 14 July 2020].

Morse parameters:
1. Matsumoto, A., 2020. Parameters Of The Morse Potential From Second Virial Coefficients Of Gases. [online] Semanticscholar.org. Available at: <https://www.semanticscholar.org/paper/Parameters-of-the-Morse-Potential-from-Second-of-Matsumoto/7f2ead7c7a8a964f1c90a6c3640a85b87c608688> [Accessed 15 July 2020]. 
