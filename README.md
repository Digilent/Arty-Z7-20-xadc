Arty Z7-20 XADC Demo
==============
  
Description
--------------
This project is a Vivado demo using the Arty Z7-20's analog-to-digital converter ciruitry, LED's and switches, written in Verilog. When programmed onto the board, voltage levels between 0 and 1 Volts are read off of the JXADC header. The LEDs brightness increases as the voltage increases. When SW0 is on and SW1 is off the xadc is on channel 12. When SW1 is on and SW0 is off the xadc is on channel 0. See the Arty Z7-20's [Reference Manual](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/reference-manual) for more information about how the ZYNQ's XADC is connected to header JXADC.


  
Requirements
--------------
* **Arty Z7-20**: To purchase a Arty Z7-20, see the [Digilent Store](https://store.digilentinc.com/arty-z7-apsoc-zynq-7000-development-board-for-makers-and-hobbyists/)
* **Vivado 2018.2 Installation**: To set up Vivado, see the [Installing Vivado and Digilent Board Files Tutorial](https://reference.digilentinc.com/vivado/installing-vivado/start).
* **MicroUSB Cable**
* **Wires and a Circuit to Measure**

Demo Setup
--------------
1. Download and extract the most recent release ZIP archive from this repository's [Releases Page](https://github.com/Digilent/Arty-Z7-20-xadc/releases).
2. Open the project in Vivado 2018.2 by double clicking on the included XPR file found at "\<archive extracted location\>/vivado_proj/Arty-Z7-20-xadc.xpr".
3. In the Flow Navigator panel on the left side of the Vivado window, click **Open Hardware Manager**.
4. Plug the Arty Z7-20 into the computer using a MicroUSB cable.
5. In the green bar at the top of the window, click **Open target**. Select "Auto connect" from the drop down menu.
6. In the green bar at the top of the window, click **Program device**.
7. In the Program Device Wizard, enter "\<archive extracted location\>vivado_proj/Arty-Z7-20-xadc.runs/impl_1/XADCdemo.bit" into the "Bitstream file" field. Then click **Program**.
8. The demo will now be programmed onto the Arty Z7-20. See the Introduction section of this README for a description of how this demo works.

Next Steps
--------------
This demo can be used as a basis for other projects, either by adding sources included in the demo's release to those projects, or by modifying the sources in the release project.

Check out the Arty Z7-20's [Resource Center](https://reference.digilentinc.com/reference/programmable-logic/arty-z7/start) to find more documentation, demos, and tutorials.

For technical support or questions, please post on the [Digilent Forum](https://forum.digilentinc.com).

Additional Notes
--------------
For more information on how this project is version controlled, refer to the [Digilent Vivado Scripts Repository](https://github.com/digilent/digilent-vivado-scripts)


