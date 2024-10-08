

# Programming Platforms

This section provide a general overview of how to use Galaxy on AnVIL.

<br>


## Video overview on using Galaxy


Here is a video tutorial that describes the basics of using Galaxy on AnVIL.

<iframe src="https://drive.google.com/file/d/16QEY8x-gBsUkKEeO3w_H-I4SLIBPloXd/preview" width="640" height="360" allow="autoplay"></iframe>

### Objectives

- Start compute for your Galaxy on AnVIL
- Run tool to quality control sequencing reads
- Stop compute to minimize expenses

### Slides

The slides for this tutorial are are located [here](https://docs.google.com/presentation/d/1yYCg4cPVBMMDghT17B4XzROieqyMH99Ex9nMm_Scm9Q).

## Starting Galaxy

:::: {.borrowed_chunk}

Note that, in order to use Galaxy, you must have access to a Terra Workspace with permission to compute (i.e. you must be a "Writer" or "Owner" of the Workspace).

Open your Workspace, and click on the “NOTEBOOKS” tab. Next, click on “Create a Cloud Environment for Galaxy”. You should see a popup window on the right side of the screen. Click on “NEXT” and “CREATE” to keep all settings as-is. This will take 8-10 minutes. When it is done, click “LAUNCH GALAXY”.

<img src="06-using_galaxy_files/figure-html//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_788.png" alt="Screenshot of the Workspace Notebooks tab. The notebook tab name and the plus button that starts a cloud environment for Galaxy have been highlighted," width="100%" />
::::

## Navigating Galaxy

:::: {.borrowed_chunk}

Notice the three main sections.

**Tools** - These are all of the bioinformatics tool packages available for you to use.

**The Main Dashboard** - This contains flash messages and posts when you first open Galaxy, but when we are using data this is the main interface area.

**History** - When you start a project you will be able to see all of the documents in the project in the history. Now be aware, this can become very busy. Also the naming that Galaxy uses is not very intuitive, so you must make sure that you label your files with something that makes sense to you.

<img src="06-using_galaxy_files/figure-html//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_816.png" alt="Screenshot of the Galaxy landing page. The Tools and History headings have been highlighted." width="100%" />

On the welcome page, there are links to tutorials. You may try these out on your own. If you want to try a new analysis this is a good place to start.
::::

## Deleting Galaxy

:::: {.borrowed_chunk}

Once you are done with your activity, you’ll need to shut down your Galaxy cloud environment. This frees up the cloud resources for others and minimizes computing cost. The following steps will delete your work, so make sure you are completely finished at this point. Otherwise, you will have to repeat your work from the previous steps.

Return to AnVIL, and find the Galaxy logo that shows your cloud environment is running. Click on this logo:

<img src="06-using_galaxy_files/figure-html//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_gf243efded1_0_134.png" alt="Screenshot of the Workspace menu. The currently running Galaxy cloud environment logo on the top right of the page is highlighted." width="100%" />

Next, click on “DELETE ENVIRONMENT OPTIONS”:

<img src="06-using_galaxy_files/figure-html//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_gf243efded1_0_140.png" alt="Screenshot of the cloud environment pop out menu. The “DELETE ENVIRONMENT OPTIONS” link is highlighted." width="100%" />

Finally, select “Delete everything, including persistent disk”. Make sure you are done with the activity and then click “DELETE”.

<img src="06-using_galaxy_files/figure-html//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_gf243efded1_0_146.png" alt="Screenshot of the cloud environment pop out menu. The “Delete everything, including persistent disk” radio button has been checked and is highlighted. The “DELETE” button is highlighted." width="100%" />
::::

