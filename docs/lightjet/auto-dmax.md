# Create New Paper Target

---

When there is a new batch of paper you have two options in creating a new paper config. You can [copy from an existing target](#copy-an-existing-target) or [create a new target](#creating-calibration-new-target-with-auto-dmax).

!!! Warning
    Make sure developer is at full strenght before making a new paper calibration


## Copy an Existing Target

1. In Fusion click **Copy…**
2. Type a The new batch
3. Select the previous configuration that you want to copy  
![ ](/images/fusion-copy-config.png)
4. Click **Next…**
5. Re-print gray balance
6. Iterate gray balance is necessary
7. [Link new calibration](#linking-calibration-target-to-media) in Thrive RIP Queue


## Creating Calibration New Target with Auto-Dmax

- In Fusion click **New…**
- Select Corresponding target file
- Start with the default RGB laser compensations
- Change Resolution to 300 dots / inch
- Click **Print Auto Dmax Pattern**
- Wait the 5 minutes for latent image to stabilize and processed media
- After processing trim and dry with hairdryer (fiber only).
- Evaluate the evenness of the RGB patches. Ideally they should be similar tonality
- Read the first strip and evaluate dmax.
    - The dmax for a paper conig is saved in `C:\LightJetFE\blend\material30\\[NAME OF MATERIAL\]\default.tgt`
!!! warning
    If Dmax hasn't been reached you must go back to the laser comps and manually change them. The Fusion software is fooled by the black and white paper and will make an incorrect guess for new laser compensation.
- Read the remaining strips  
![](/images/fusion-dmax-strips.png)
- Click **Next**
    - If you don't get the dialog saying Auto Dmax is complete you will have to _Clean Current Gray Balance_aa and start over  
![](/images/fusion-auto-dmax-complete.png)
- Click **Print Gray Balance Pattern**
- Wait the 5 minutes for latent image to stabilize and processed media
- After processing trim and dry with hairdryer (fiber only).
- Read strips and evaluate cone
    - If the gray balance isn't in the cone click **Next** to **Iterate Gray Balance**
    - Repeat these steps until a good cone result
- [Link new calibration](#linking-calibration-target-to-media) in Thrive RIP Queue

## Linking Calibration Target to Media

1. In Thrive RIP-Queue click **Configure Printer**
2. click **Yes** to shutdown printer
3. Switch to the Device tab
4. Click **Features**
5. Click **Media Type** then **Configure…**
6. Select the media type you want to update
7. click **Edit** (If no **Edit** button appears you will need to double click the media type)
8. Type the name to match the paper type and batch number
9. Select the calibration for the corresponding batch
10. Click **OK**
11. Click **OK**
12. Click **Done**
13. Switch the **Media** tab
14. Select media type
15. Clcik **Options…**
16. Change Media Type in the drop down to match batch number
17. Click **OK**
18. Click **OK**


## Flashing Paper

In order to determin the maximum density of paper you will need to fully expose the paper to light then process it.

1. Cut off and expose paper fully to light for at least a few seconds
2. Feed paper into processor and fully processes
3. If fiber paper fully dry paper
4. On the densitometer press menu then pap to read paper dmax
5. Send through densitometer to read dmax. You will need to cut the paper to a small enough size to fit.
6. Dmax reading is the absolute maximum black density for the paper/chemistry combination.


