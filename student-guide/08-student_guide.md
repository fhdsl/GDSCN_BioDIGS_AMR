# (PART\*) Student Guide to AnVIL {-}




# Using RStudio on AnVIL

In the next few steps, you will walk through how to get set up to use RStudio on the AnVIL platform. AnVIL is centered around different “Workspaces”. Each Workspace functions almost like a mini code laboratory - it is a place where data can be examined, stored, and analyzed. The first thing we want to do is to copy or “clone” a Workspace to create a space for you to experiment.

Use a web browser to go to the AnVIL website. In the browser type:

```
anvil.terra.bio
```

:::{.notice}
**Tip**
At this point, it might make things easier to open up a new window in your browser and split your screen. That way, you can follow along with this guide on one side and execute the steps on the other.
:::

Your instructor will give you information on which workspace you should clone.

## Video overview of RStudio on AnVIL


Here is a video tutorial that describes the basics of using RStudio on AnVIL.

<iframe src="https://drive.google.com/file/d/1v72ZG8JIRDUaewFQgGfcCO_qoM4eYmYX/preview" width="640" height="360" allow="autoplay"></iframe>

### Objectives

- Start compute for your RStudio environment
- Tour RStudio on AnVIL
- Stop compute to minimize expenses

### Slides

The slides for this tutorial are are located [here](https://docs.google.com/presentation/d/1eypYLLqD11-NwHLs4adGpcuSB07dYEJfAaALSMvgzqw).

## Launching RStudio


```
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
```






:::{.warning}
AnVIL is very versatile and can scale up to use very powerful cloud computers. It's very important that you select a cloud computing environment appropriate to your needs to avoid runaway costs.  If you are uncertain, start with the default settings; it is fairly easy to increase your compute resources later, if needed, but harder to scale down.
:::

Note that, in order to use RStudio, you must have access to a Terra Workspace with permission to compute (i.e. you must be a "Writer" or "Owner" of the Workspace).

1. Open Terra - use a web browser to go to [`anvil.terra.bio`](https://anvil.terra.bio/)

1. In the drop-down menu on the left, navigate to "Workspaces". Click the triple bar in the top left corner to access the menu. Click "Workspaces".

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g117989bd49c_0_150.png){width=100%}

1. Click on the name of your Workspace. You should be routed to a link that looks like: `https://anvil.terra.bio/#workspaces/<billing-project>/<workspace-name>`.

1. Click on the cloud icon on the far right to access your Cloud Environment options.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_22.png){width=100%}

1. In the dialogue box, click the "Settings" button under RStudio.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_18.png){width=100%}

1. You will see some details about the default RStudio cloud environment, and a list of costs because it costs a small amount of money to use cloud computing.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_35.png){width=100%}



1. If you are uncertain about what you need, the default configuration is a reasonable, cost-conservative choice.  It is fairly easy to increase your compute resources later, if needed, but harder to scale down. Click the “Create” button.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_41.png){width=100%}



1. Otherwise, click “CUSTOMIZE” to modify the environment for your needs.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_48.png){width=100%}

    

    

    

    

    

1. The dialogue box will close and you will be returned to your Workspace.  You can see the status of your cloud environment by hovering over the RStudio logo.  It will take a few minutes for Terra to request computers and install software.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_91.png){width=100%}

1. When your environment is ready, its status will change to “Running”.  Click on the RStudio logo to open a new dialogue box that will let you launch RStudio.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_95.png){width=100%}
    
1. Click the launch icon to open RStudio.  This is also where you can pause, modify, or delete your environment when needed.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_99.png){width=100%}

1. You should now see the RStudio interface with information about the version printed to the console.

    ![](resources/images/08-student_guide_files/figure-docx//1a35Mb8f0M-bQkBcHa1cyQc6YxXoBLtExCz96nv08vkA_g14ea2db115d_0_103.png){width=100%}

## Touring RStudio


```
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
```



Next, we will be using RStudio and the package `Glimma` to create interactive plots. See [this vignette](https://bioconductor.org/packages/release/bioc/vignettes/Glimma/inst/doc/limma_edger.html) for more information.

1. The Bioconductor team has created a very useful package to programmatically interact with Terra and Google Cloud. Install the `AnVIL` package. It will make some steps easier as we go along.

    

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_49.png)

1. You can now quickly install precompiled binaries using the AnVIL package’s `install()` function. We will use it to install the `Glimma` package and the `airway` package. The `airway` package contains a `SummarizedExperiment` data class. This data describes an RNA-Seq experiment on four human airway smooth muscle cell lines treated with dexamethasone. 

{Note: for some of the packages, you will have to install packaged from the CRAN repository, using the install.packages() function. The examples will show you which install method to use.}

    

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_56.png)

1. Load the example data.

    

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_56.png)

1. The multidimensional scaling (MDS) plot is frequently used to explore differences in samples. When this data is MDS transformed, the first two dimensions explain the greatest variance between samples, and the amount of variance decreases monotonically with increasing dimension. The following code will launch a new window where you can interact with the MDS plot.

    

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_70.png)

1. Change the `colour_by` setting to "groups" so you can easily distinguish between groups. In this data, the "group" is the treatment.

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_77.png)

1. You can download the interactive html file by clicking on "Save As".

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g1204ed6da7f_0_0.png)

1. You can also download plots and other files created directly in RStudio. To download the following plot, click on "Export" and save in your preferred format to the default directory. This saves the file in your cloud environment.

    

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g1204ed6da7f_0_12.png)

1. You should see the plot in the "Files" pane.

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g1204ed6da7f_0_19.png)

1. Select this file and click "More" > "Export"

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g1204ed6db6a_0_0.png)

1. Select "Download" to save the file to your local machine.

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g1204ed6db6a_0_8.png)

## Pausing RStudio


```
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
```



1. The right-hand side icon reminds you that you are accruing cloud computing costs. If you don’t see this icon, you may need to scroll to the right.

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_84.png){width=100%}

1. You should minimize charges when you are not performing an analysis. You can do this by clicking on the RStudio icon and selecting “Pause”. This will release the CPU and memory resources for other people to use. Note that your work will be saved in the environment and continue to accrue a very small cost.  This work will be lost if the cloud environment gets deleted.  If there is anything you would like to save permanently, it's a good idea to copy it from your compute environment to another location, such as the Workspace bucket, GitHub, or your local machine, depending on your needs.

    ![](resources/images/08-student_guide_files/figure-docx//1BLTCaogA04bbeSD1tR1Wt-mVceQA6FHXa8FmFzIARrg_g11f12bc99af_0_91.png){width=100%}

:::{.notice}
You can also pause your cloud environment(s) at https://anvil.terra.bio/#clusters.
:::


# Using Galaxy on AnVIL

In the next few steps, you will walk through how to get set up to use Galaxy on the AnVIL platform. AnVIL is centered around different “Workspaces”. Each Workspace functions almost like a mini code laboratory - it is a place where data can be examined, stored, and analyzed. The first thing we want to do is to copy or “clone” a Workspace to create a space for you to experiment.

Use a web browser to go to the AnVIL website. In the browser type:

```
anvil.terra.bio
```

:::{.notice}
**Tip**
At this point, it might make things easier to open up a new window in your browser and split your screen. That way, you can follow along with this guide on one side and execute the steps on the other.
:::

Your instructor will give you information on which workspace you should clone. After logging in, click “View Workspaces”. Select the “Public” tab.  In the top search bar type the activity workspace. 

Clone the workspace by clicking the teardrop button (![teardrop button](resources/images/teardrop.png){#id .class width=25 height=20px}). And selecting “Clone”.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_625.png)

In the first box, give your Workspace clone a name by adding an underscore (“_”) and your name. For example, “SARS-CoV-2-Genome_Ava_Hoffman”. Next, select the Billing project provided by your instructor. Leave the bottom two boxes as-is and click “CLONE WORKSPACE”.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_648.png)

## Video overview on using Galaxy


Here is a video tutorial that describes the basics of using Galaxy on AnVIL.

<iframe src="https://drive.google.com/file/d/16QEY8x-gBsUkKEeO3w_H-I4SLIBPloXd/preview" width="640" height="360" allow="autoplay"></iframe>

### Objectives

- Start compute for your Galaxy on AnVIL
- Run tool to quality control sequencing reads
- Stop compute to minimize expenses

### Slides

The slides for this tutorial are are located [here](https://docs.google.com/presentation/d/1yYCg4cPVBMMDghT17B4XzROieqyMH99Ex9nMm_Scm9Q).


## Starting Galaxy {#starting-galaxy}

Galaxy is a free, relatively easy to use bioinformatics implementation package. It changes command line programs into GUI based programs and is a great tool for performing bioinformatics analysis without having to update software or worry too much about coding. In order to use Galaxy, we need to create a cloud environment. This is like quickly renting a few computers from Google as the engine to power our Galaxy analysis. 

:::{.warning}
Currently, you will need to use Chrome or Safari as your browser for Galaxy cloud environments to work.
:::

In your new Workspace, click on the “ANALYSES” tab. Next, click on “START”. You should see a popup window on the right side of the screen. Click on the Galaxy logo to proceed.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_788.png)

Click on “NEXT” and “CREATE” to keep all settings as-is.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_798.png)

Click on the Galaxy icon. 

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_g2283b458fae_100_31.png)

You will see that the environment is still being set up.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_g2283b458fae_100_38.png)

This will take 8-10 minutes. When it is done, click “Open”. You might need to refresh the page.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_g2283b458fae_100_46.png)

:::{.notice}
Remember that you can refresh your browser or navigate away at any time. This is because the connection to the environment is in the cloud, not on your personal computer.
:::

You can also follow along with the first ~2 minutes of [this video](https://jhudatascience.org/AnVIL_Book_Getting_Started/starting-galaxy.html) to start Galaxy on AnVIL.

## Navigating Galaxy

Notice the three main sections.

**Tools** - These are all of the bioinformatics tool packages available for you to use.

**The Main Dashboard** - This contains flash messages and posts when you first open Galaxy, but when we are using data this is the main interface area.

**History** - When you start a project you will be able to see all of the documents in the project in the history. Now be aware, this can become very busy. Also the naming that Galaxy uses is not very intuitive, so you must make sure that you label your files with something that makes sense to you.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_ged15532ded_0_816.png)

On the welcome page, there are links to tutorials. You may try these out on your own. If you want to try a new analysis this is a good place to start.

## Deleting Galaxy


```
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
## Warning: Chunk option fig.alt is not supported for docx output
```




Once you are done with your activity, you’ll need to shut down your Galaxy cloud environment. This frees up the cloud resources for others and minimizes computing cost. The following steps will delete your work, so make sure you are completely finished at this point. Otherwise, you will have to repeat your work from the previous steps.

Return to AnVIL, and find the Galaxy logo that shows your cloud environment is running. Click on this logo:

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_gf243efded1_0_134.png)

Next, click on “DELETE ENVIRONMENT OPTIONS”:

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_gf243efded1_0_140.png)

Finally, select “Delete everything, including persistent disk”. Make sure you are done with the activity and then click “DELETE”.

![](resources/images/08-student_guide_files/figure-docx//182AOzMaiyrreinnsRX2VhH7YsVgvAp4xtIB_7Mzmk6I_gf243efded1_0_146.png)

