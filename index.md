---
layout: index
#title: page title
#tagline: page tagline
---

<p align="center"><a href="images/logo.png">
   <img src="images/logo.png" alt="spyke logo" width="250">
   </a>
</p>

The latest version is available from its [GitHub repository](http://github.com/spyke/spyke).
Documentation is currently very sparse. My [thesis (Chapter 3 and Appendix
C.2)](http://mspacek.github.io/mspacek_thesis.pdf) details the many steps involved. A recent
paper [(Spike sorting for polytrodes: a divide and conquer
approach)](http://www.frontiersin.org/Systems_Neuroscience/10.3389/fnsys.2014.00006/abstract)
describes an alternative implementation of the same general idea. I also plan on recording, at
some point, a short screencast demonstrating typical operation. This flowchart is an overview
of the process:


<p align="center"><a href="images/spike_sorting_flowchart.png">
   <img src="images/spike_sorting_flowchart.png" alt="spike sorting flowchart" width="200">
   </a>
</p>

Here are a couple of screenshots. The first shows the display of raw data, with higher
frequency spike data displayed in two different layouts (2D spatial on the left and 1D
vertical in the middle), and lower frequency LFP data displayed in a 1D vertical layout at
right:

<p><a href="images/raw_data.png">
   <img src="images/raw_data.png" alt="raw data screenshot">
   </a>
</p>

The second screenshot shows sorted data. In the list at middle right, out of all the single
units found (highlighted in green), 4 are selected (in blue). To their right are the 4
corresponding mean multichannel waveforms. Selected channels and spike time ranges are
highlighted by green horizontal lines, shown underneath the waveforms (difficult to see in
this case). The middle window is a fully manipulable 3D cluster plot of the resulting
dimension reduced space ([PCA](http://en.wikipedia.org/wiki/Principal_component_analysis),
[ICA](http://en.wikipedia.org/wiki/Independent_component_analysis), time, and/or spatial
position) with each point representing one spike:

<p><a href="images/sorted_data.png">
   <img src="images/sorted_data.png" alt="sorted data screenshot">
   </a>
</p>

<!---
Here is a test screencast, just to see how well it works (or doesn't):

<p><video src="images/test.webm" width="854" height="480" controls preload></video>
</p>
-->

For more details, see the current [README.md](https://github.com/spyke/spyke#readme) or the
brief [TUTORIAL.md](https://github.com/spyke/spyke/blob/master/TUTORIAL.md)

[Sample data](http://swindale.ecc.ubc.ca/spyke) is available, as is a [much older version]
(http://swindale.ecc.ubc.ca/spyke) of spyke, which was described in the paper
[Python for large-scale electrophysiology](http://www.frontiersin.org/Neuroinformatics/10.3389/neuro.11.009.2008/abstract).
