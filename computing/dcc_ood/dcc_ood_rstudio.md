
# Starting up RStudio on DCC OnDemand
1. Go to [DCC OnDemand](https://dcc-ondemand-01.oit.duke.edu/)
2. Sign in with your NetID and password
3. Click on **Interactive Apps** at the top and select **MIC Course** 
    - If you don't see **Interactive Apps** and only see three lines in the top right, click on the three lines, then **Interactive Apps**, then **MIC Course**
4. A new page should open that says **MIC Course** at the top.
5. You should leave the settings at their defaults (below) for most purposes:
    - *Walltime:* 4
    - *CPUs:* 2
    - *Memory:* 2
    - *GPUs:* 0
    - *Account:* chsi-mic-2022
    - *Partition:* chsi-high
    - *Singularity Image:* MIC Course
6. Scroll to the bottom and click **Launch**
7. A new page should open with a box that says **MIC Course**, you may see the following messages:
    - "Please be patient as your job currently sits in queue. The wait time depends on the number of cores as well as time requested."
    - "Your session is currently starting... Please be patient as this process can take a few minutes."
8. You are waiting for a blue button to appear that says **Connect to RStudio Server**. This could take a minute or so. When it appears, click on it.
9. After a minute or so, RStudio should open in your webbrowser.

# Shutting Down
1. In RStudio click on **File** in the top left, then select **Quit Session**
2. A box should pop up that says **R Session Ended**. At this point you can close the tab that contains the RStudio session.
3. In the DCC OnDemand browser window click on the red **Delete** button in the **MIC Course** box, then click **Confirm** in the box that pops up.
4. You can now click on the logout button in the top right, which is an arrow pointing to the right.
5. You are done!