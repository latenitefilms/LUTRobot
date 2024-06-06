# How To Use

When you first run LUT Robot from the Mac App Store you'll be presented with this:

![](/static/install.png)

Clicking **Launch Final Cut Pro** will launch Final Cut Pro and close the LUT Robot application.

You can now access LUT Robot from the Workflow Extension button in Final Cut Pro:

![](/static/toolbar.png)

You can also access it from the Workflow Extension menubar:

![](/static/menubar.png)

The first time you open the LUT Robot Workflow Extension you'll be presented with the below alert, explaining that LUT Robot needs permission to access your Camera LUTs folder:

![](/static/permission-required.png)

Click **OK**, and then click **Grant Permission** in the next window:

![](/static/permission-required-02.png)

You'll then be presented with the main user interface:

![](/static/lut-robot.png)

First, select the **Search Folder** you want to search.

It works recursively, so if you select **Camera LUTs** it will search every sub-folder for a match.

Once you have a Search Folder selected, simply drag the **Event** you want to process from the Final Cut Pro Browser to the Drop Zone.

The drag zone at the bottom of the user interface will turn from grey to blue:

![](/static/after-drag.png)

You can now drag this from the Workflow Extension to your Final Cut Pro **Library**.

This will create a new temporary event, which you can delete straight away, as **Camera LUTs** apply globally - so the updated Camera LUT in the new event, also affect the same source clips in the existing event.

For example, if you had a clip in your Event with the filename of `A002_01281732_C001.mov`, if there was a matching `A002_01281732_C001.cube` file in the **Search Folder** you selected (or a subfolder of that folder), then LUT Robot will apply this LUT as a Camera LUT.
