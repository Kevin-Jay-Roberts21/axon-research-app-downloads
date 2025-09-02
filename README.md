# axon-research-app-downloads

Windows: https://github.com/Kevin-Jay-Roberts21/axon-research-app-downloads/releases/latest/download/axon-research-app-windows.msi

Apple Silicon: https://github.com/Kevin-Jay-Roberts21/axon-research-app-downloads/releases/latest/download/axon-research-app-macos-arm64.dmg

Intel Macs: https://github.com/Kevin-Jay-Roberts21/axon-research-app-downloads/releases/latest/download/axon-research-app-macos-x64.dmg

## Axon Simulator App Information
The Axon Simulator App allows a user to experiment axon voltage behaviors based on various axonal properties via user inputs. The app consists of four main pages which are described below.

### Run Simulation
In this page, a user has the option to run a Hodgkin-Huxley (HH), Single Cable (SC) or Double Cable (DC) simulation. In each simulation tab, a user is prompted to enter Mesh and Axon Geometry Parameters, Material and "Per unit Length" Parameters and Other Parameters. If a user is unsure about which parameters to enter are reason or appropriate, then they may make use of the Default Buttons, which automatically fill in the inputs with reasonable values. In each simulation page there is a question mark button "?" which may help the user understand more about the inputs and their simulation.

After all inputs are filled, a user must enter a simulation name and click "Run Simulation". While a simulation is running, a user also has the option to "Cancel Simulation". After the simulation is complete, the data from the simulation is saved in a new folder that is automatically created in \Documents\ called \Axon Simulations\. After a simulation has been saved, a user may view the saved simulation in the Plot Animation or Plot Time and Space Shots tabs. WARNING: Data is not automatically deleted, each user is responsible for deleting their own saved simulations via \Documents\Axon Simulations\, or through the app. 

### Plot Animation
This page is designed to plot the animation of a saved simulations. A user must first "Select a saved Simulation" from the dropdown. Then select a variable to plot (could be Vm, Vmy, n, m or h). Then a user must choose to plot the Variable vs Time or Variable vs Space. The following 3 buttons are used to "Play", "Pause" or "Reset" the animation. The "Speed" slider controls the speed of the animation. Finally, a user may decide to delete a saved simulation by clicking on "Delete Saved Simulation". After deleting a saved simulation, it will no longer appear in the Simulation dropdown, and it is deleted from the \Documents\Axon Simulations\ folder. 

### Plot Time and Space Shots
Similar to the Plot Animation page, the user must pick a saved simulation, a variable, and a Plot Type (Variable vs Time or Variable vs Space). The next input is the number of time (or space) shots, and the final input is the physical units of the time (or space shots). After all is selected, the graph will automatically plot the time (or space) shots. Finally, a user has the option to delete a simulation in this page as well.

### Additional Info
There are 4 tabs in this page. The first 3 tabs describe the 3 models (HH, SC, and DC), their circuits diagrams, and their corresponding model equations and boundary/initial conditions. Finally, the Variable Descriptions tab provides a detailed explaination of each variable used in the equations, as well as other important equation relationships.
