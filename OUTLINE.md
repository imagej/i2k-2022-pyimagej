## Essential PyImageJ image operations

* How to load data into PyImageJ.
* How to save data from PyImageJ.
* How to split image data (e.g. slicing).
* How to crop images.
* How to combine image data.
  * Combine Java (imglib2) images.
  * Combine Python (xarray/NumPy) images.
* How to use image data (Java/Python) in a 'for loop'.
  * For example, performing an operation per slice in a for loop.
* How to use the RAIOperators.
* ImagePlus vs ImgPlus/Dataset, whats the difference?
  * When to use ImagePlus vs ImgPlus.
* How to use imagej ops?
* Explain image dimension convention differences (t, pln, y, x, ch) vs (X, Y, Channel, Z, Time).
* API discovery, how to find code snippets (macro Recorder).
* Mix and matching demonstration:
  * open an image, do something, get results display in [seaborn](https://seaborn.pydata.org/).
  * open an image, convert to python, do something, convert back to Java.
* Legacy image stuff:
  * How to use the RoiManager, ResultsTable and WindowManager from PyImageJ (requires interactive or gui mode).
  * Working with ImageProcessors (e.g. reseting the min and max on an ImagePlus: `imp.getProcessor().resetMinAndMax()`)
  * Working with Overlays/Rois
