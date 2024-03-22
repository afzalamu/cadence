# CADENCE
I am learning to use the Cadence Virtuoso tool. Starting as a beginner I will upload my progress here and update this documentation from time to time.

##  DC ANALYSIS
-   It is used to find Voltage and Current at a particular Operating Point.
-   Let us start by taking the example of a simple resistive divider.
RESISTIVE DIVIDER (DC ANALYSIS USING CADENCE)
1. open Cadence Virtuosoo
2. Create a New Library by clicking on File > New Library
3. Click on Add Library to existing Technology File
4. Here I have selected "gpdk180"
5. Click on apply and ok
6. Check the log file, It will show library is successfully created and the Technology file is attached to it.

- Creating Schematic
  1. Click on File > New > Cell View
  2. Select the library
  3. Give the schematic name ( here I have given resdiv)
  4. Select the Cell Type as "sch"
  5. That's it, the Schematic is successfully created.

Now, Schematic Editor will open
- To add the components or Instances (Press "I")
- Then, select "analoglib" to select components like Resistance/Capacitance/Voltage Sources/Ground
- Here, we select first the "res" of value "1Kohm"
- Click on apply, It will get attached with your cursor and then click to place it 


