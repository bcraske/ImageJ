# ImageJ

This repository contains the Imagej plugin used to quantify photobleaching steps.

Open the macro in ImageJ/FIJI. Then open the file containing photobleaching experiment. A message will appear stating 'Make new ROIs (Yes) or open previous ROI (file) > click Yes

Use the 'point' tool to select the most central pixel of each individual fluorescent molecule attached to a coverslip, then press 't' to add each coordinate to the ROI manager.

Once you've marked all points click 'OK' in the message box, then click Save. This will run the plugin and plot the background-corrected intensity for each ROI  over time and added to a table.

This table contains the raw data for the photobleaching traces for each ROI.
