# Visual Communication in Data Science
### Abstract
The most important skill for a Data Scientist to develop is communication.  It is their responsibility to discover insights with data to drive decision-making, but not to make the decisions themselves.  For this reason, I would argue that accurate and effective communication is more important than any algorithm, model, or package.

### Not so abstract after all
Each type of communication is different, but provides a well-rounded way of providing the same information.  We can classify these into four categories, aligned with four types of learners:  visual, written, hearing, and tacital.  Here, we concern ourselves with the visual learner.

### Why should we care?
Plots are vital to not only getting the point across but also to ensure that the message stays with the individual.  Not only that, but people have a tendency to gloss over long paragraphs of text.  Are you still reading this, or have you already skipped to the graphics below?  Even so, we find that overly complicated or cluttered plots are used all too frequently within our industry.  Instead of bombarding you with the [typical military graphic](https://www.nytimes.com/2010/04/27/world/27powerpoint.html), we can take a look at an example that is easy to fix.

### Get to the point...
Cluttered plots are like long sentences and paragraphs that never seem to end and just keep adding more information than is truly needed to convey the point almost as if they are trying to be more esoteric just for the sake of it.  Exhausted yet?  I sure am.  Let's take a look at this in plot form.

### ... or rather, the plot.
![A plot depicting four weather variables as a line chart.  They are all overlaid and make it difficult to understand the point of the plot.](Plots/Fig11.png)
**Figure 1:**  A plot depicting four weather variables as a line chart.  They are all overlaid and make it difficult to understand the point of the plot.

### Is this cleaner, or just more complicated?
![A plot depicting four variables as a scatter chart.  Wind is depicted by the X-axis, Temperature is depicted by the Y-axis, Solar Radiation is depicted by the dot color, and Ozone is depicted by dot size.  It is less cluttered, but harder to compare the data.](Plots/Fig14.png)
**Figure 2:**  A plot depicting four variables as a scatter chart.  Wind is depicted by the X-axis, Temperature is depicted by the Y-axis, Solar Radiation is depicted by the dot color, and Ozone is depicted by dot size.  It is less cluttered, but harder to compare the data.

### They aren't overlaid, but the point is so much easier to gather.
![A graphic depicting four variables as a scatter chart.  It makes use of the facet_wrap() function to depict each variable separately.  The y-axis is not equal across all four plots as to better depict the range and variation of the individual variable.  Take note of the title, the subtile, and the brief description that all aid in getting further information.](Plots/Fig12.png)
**Figure 3:** A graphic depicting four variables as a scatter chart.  It makes use of the facet_wrap() function to depict each variable separately.  The y-axis is not equal across all four plots as to better depict the range and variation of the individual variable.  Take note of the title, the subtile, and the brief description that all aid in getting further information.
