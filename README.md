# PixInsight Process Icons

:wave: These are the process icons that I use for my RGB and SHO image processing workflows.

Several of the icons are from [lukomatico and Bill
Blanshan](https://www.youtube.com/watch?v=SQmFFkF6XhM). Make sure to
watch the video.

- `RGB-Workflow.xpsm`
- `SHO-Workflow.xpsm`
- `FromLukeAndBill.xpsm`

You can download these as a zip file, or clone (or fork) the repo

### Repositories
These are the repositories that I have configured (in addition to the core PI repos):

- `https://raw.githubusercontent.com/jamiesmith/pixinsight-repo/main/`
- `https://elveteek.ch/pixinsight-updates/ez-processing-suite/`
- `https://foraxxpaletteutility.com/FPU/`
- `https://raw.githubusercontent.com/jamiesmith/pixinsight-repo/main/`
- `https://raw.githubusercontent.com/setiastro/pixinsight-updates/main/`
- `https://www.cosmicphotons.com/pi-modules/narrowbandnormalization/`
- `https://www.cosmicphotons.com/pi-scripts/bfke/`
- `https://www.cosmicphotons.com/pi-scripts/imageblend/`
- `https://www.cosmicphotons.com/pi-scripts/nbcolourmapper/`
- `https://www.cosmicphotons.com/pi-scripts/starreduction/`
- `https://www.ghsastro.co.uk/updates/`
- `https://www.ideviceapps.de/PixInsight/Utilities/`
- `https://www.rc-astro.com/BlurXTerminator/PixInsight/`
- `https://www.rc-astro.com/NoiseXTerminator/PixInsight/`
- `https://www.rc-astro.com/resources/StarXTerminator/PixInsight/`
- `https://www.skypixels.at/HVB_Repository/`

and here's what they look like in PixInsight
![PixInsight Repositories](/images/manage-repositories.png?raw=true "PixInsight Repositories")

They're not all in my standard flow (for example, I'm hoping to use the EZ suite
for live stacking). Also, note that some of the above repos aren't signed.

### How they're laid out

This is what the RGB & SHO workflow sets look like loaded. They're arranged in
columns, with a few "global" icons at the top, with RGB on the left and SHO on
the right. For me they land on the first workspace. If you can't see them,
scroll to the right in the workspace, select them, then drag them back. DON'T
just click on the workspace and arrange icons, or you'll lose the in-order flow
(DAMHIKT). Some of the scripts in the flow don't have new instance icons- for those, there's a `No-Op` placeholder with a description of what to call (for example, the `Script -> Toolbox -> AutoLinearFit` script)

I basically work from top to bottom.

![Processing Workflows](/images/rgb-and-sho-workflows.png?raw=true "Processing Workflows")

The Lukomatico/Bill has a similarly compact layout:
![Lukomatico/Bill icons](/images/lukomatico-and-bill.png?raw=true "Lukomatico/Bill icons")

### Compact Spacing
If you're curious how I got the icons to be so close together I'll tell you the
secret. I spent a lot of time looking for one simple setting: the icon
spacing. I set it to zero, on the `Edit -> Global Preferences` page:

![Nice and tidy](/images/grid-spacing.png?raw=true "Compact workflow")

Drop an issue if you, well, run into any issues, or just to let me know if you
use these or learned anything from them :grinning:

In the meantime, live long and prosper :vulcan_salute:
