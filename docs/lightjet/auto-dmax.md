# Creating Calibration Target with Auto-Dmax

## Calibration Check

* Open _Fusion 3_ application
* Create new
* Click `next`
* Click `Re-print auto-dmax`
* Wait for imaging to finish
* Wait at least and additional 5min for latent image to stabilize
* In _**complete darkness**_ open LightJet and cut off paper. Close LightJet after cutting off paper.
* Feed paper's left edge first with the emulsion facing up into the processor.
	* Processing time takes 17 minutes. Set a timer.
* After processing trim and dry with hairdryer (fiber only).
* In Fusion click `OK` that the plot is ready to be processed and then click `next`
* Read strips one at a time starting with strip 1 (the right most strip).
* Evaluate cone
	* The cone is the white area which shows the tollerance of deltaE values from the patches 
	* Cone should be wide with most lines inside.

![Very good cone](images/cone.png)

* If good cone cancel and exit _Fusion 3_ 
* **Do not click `next`**

* If too light (lines lower than cone) means that the developer is too weak and needs to be replenished
* If too dark (lines higher than cone) means that the developer density is too high and needs to be deluted. 
	* Add water to dilute developer

* Repeat steps above until there's a good result
* Once cone is good launch LightJet Spooler
* Turn off display

## Advancing Media for Printing

The media needs to be advanced far enough to 
* On LightJet controll panel press the following buttons to advance the media 8 inches. This is advances enough paper to tape onto the take up core before exposing.
1. `Online` 
2. `Media`
3. `Down arrow`
4. `8`
5. `Enter` 



---

### Connecting to Thrive Hot Folders 

Finder on the menu bar click the `Go` menu then `Connect to Server…` or use the keyboard shortcut ⌘+K

![Connect to Server](images/connect-server.png)


**Server Address:** smb://Thrive-PC/Oce LightJet 430/
**User:** thrive
**Password:** dsi2008

Use the the hot folder that corresponds with the paper you are printing with.

![List of hot folders](images/thive-hot-folder.png)


### Printing files from Thrive RIP Queue to LightJet Spooler

* Launch both Thrive RIP-Queue and Spooler Controller (FPC)
* Go to RIP-Queue and highlight Océ LightJet 430
* On the right side click `Change…` and select the paper type list that is loaded in the LightJet from the Media.

![ ](images/thrive-media.png)

* On Mac copy prepared files to hot folder.
	* Files rendered from ROES can be copied straight to hot folder
* Files dropped into hot folder will show up in RIP-Queue in the _Jobs Ready to Print_ pane
* When you are ready to rip images select the files you want and click the blue pause button. They will start ripping one-by-one
* Ripped files move down to _Buffered Jobs_. These can be re-processed without copying from Mac again

* When all images are ripped go to Spooler Controller and click the green `Online` button to put the printer online
* Select the correct media

![ ](images/spooler-media.png)

*  To start exposure click `Print Now`

![ ](images/spooler-print-now.png)

### Unloading paper

* Press `Online`, `Media`, `Down`, `Down`, `Enter`
* When the LightJet finished advancing media cut and feed into processor
* You are prompted with two options. Unload Media or advance for printing again.
	* Press `Ecape` to eject paper
	* Press `Enter` to advance and tape to core
	


---

## Shutdown

### Lightjet Shutdown

* Turn off LightJet using the power switch on back left
	* The cooling fan will run for 10 minutes after the LightJet is turned off
* Shut down both workstations

## Cleaning Lightjet

* Sweeping out drum
* Cleaning output rollers


## Trouble Shooting

### Elite Technical Service

All questions about the LightJet or Onyx workstations

Mark Felice:

* 201-696-8771
* mfelice@elitetechservice.com



Working directories

