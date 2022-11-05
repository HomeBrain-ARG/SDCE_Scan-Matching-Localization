# *Udacity Self Driving Car Engineer Course*

## **Project Nº 4: Scan Matching Localization**

### [Go To Source Code Directly!!!](https://github.com/HomeBrain-ARG/SDCE_Scan-Matching-Localization/tree/main/01_Source_Code)

## **Project Workspace:**<br />
The project workspace is included further below; we have also copied the compile and run commands below to make usage easier. You will likely want to "Expand" the workspace window with the option in the bottom left of the workspace while writing and running your code.<br />

## **Compile:**<br />
```
cd /home/workspace/c3-project
cmake .
make
```

## **Run:**<br />
```
su - student // Ignore Permission Denied, if you see student@ you are good
cd /home/workspace/c3-project
./run_carla.sh

// Create new tab
cd /home/workspace/c3-project

// To run ICP method:
./cloud_loc ict // Might have core dump on start up, just rerun if so. Crash doesn't happen more than a couple of times

// To run NDT method:
./cloud_loc ndt // Might have core dump on start up, just rerun if so. Crash doesn't happen more than a couple of times

```

Note that any visualizations will appear only the remote desktop; if you work in the workspace IDE you will need to click on the "Desktop" button in the bottom right, and only run the executable from the terminal within the remote desktop to view them.<br />

## **RESULTS:**
### **ICP Method Results:**
** 1) ICP: Start position of ICP method.<br />
![alt text](https://github.com/HomeBrain-ARG/SDCE_Scan-Matching-Localization/blob/main/00_Img/01_ICP.JPG)<br />
** 2) ICP: Vehicle touring the map.<br />
![alt text](https://github.com/HomeBrain-ARG/SDCE_Scan-Matching-Localization/blob/main/00_Img/02_ICP.JPG)<br />


