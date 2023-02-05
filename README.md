# In-Band-Telemetry--Group 3

### Step 1
Download code and unzip .rar/tar files

### Step 2
Move into group3 directory: cd group3

### Step 3
Run GUI using command: python3 main.py

### Step 4
Select required topology out of 3 options by clicking on respective topology button
e.g. Topology 1

### Step 5
Click on 'Start Mininet' button to start the Mininet process

### Step 6
Click on 'Start Controller' button to start the Controller 

### Step 7
Now that Mininet and controller are running, you can start the initial custom packet flow.


-Click on 'Start Receiver' button. You will be prompted to enter the destination of the packet flow and the switch for which you want the telemetry metrics to be plotted. Please specify the destination host first followed by comma and then the respective switch. Press the 'Ok' button to confirm. 

*You can use the topology diagram given in the GUI to check for the respective node and switch names

-Next, click on 'Activate Host' button to specify the host node of the packet flow. Press the 'Ok' button to confirm.

### Step 8
To visualize the results of the switch selected, click on the 'Plot' button

### Step 9
To add an additional 'ping' flow click on the 'Ping' button. Specify the host names with a comma in between. Press the 'Ok' button to confirm.

### Important note
Do make sure that the applications are running properly. Check the Mininet shell window running in background to see which commands have been executed. You may have to press 'Enter' once before pressing the 'Ok' buttons while specifying/starting the custom and ping flows
