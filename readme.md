# Cosmic Compendium

<p align="center">
  <img src="https://www.nasa.gov/sites/default/files/styles/full_width_feature/public/thumbnails/image/potw2109a.jpg" width="50%" alt="Hubble Beholds a Big, Beautiful Blue Galaxy">
  <br>
  <small><em>Hubble Beholds a Big, Beautiful Blue Galaxy<br>NGC 2336 is the quintessential galaxy — big, beautiful, and blue — and it is captured here by the NASA/ESA Hubble Space Telescope.</em></small>
</p>

1. [Notebook](https://github.com/isi-mube/cosmic-compendium/blob/main/notebook.ipynb)
2. [Old script (will be deleted soon)](https://github.com/isi-mube/cosmic-compendium/blob/main/old_script.ipynb)

## About the Project
The objective of this **project** is to do binary image classification with galaxies, either spiral galaxies or non-spiral. The images are provided from the **Galaxy Zoo 2 project**, a Hubble open-source source dataset.

## About the Hubble sequence
<p style="text-align: justify;">
The <strong>Hubble sequence</strong> is a morphological classification for galaxies, published by <a href="https://en.wikipedia.org/wiki/Edwin_Hubble"><strong>Edwin Hubble</strong></a> in 1926, dividing regular galaxies into three main classes; ellipticals, lenticulars, and <strong>spirals</strong>.
</p>

<p style="text-align: justify;">
Spiral galaxies, which are abundant in the universe, display a distinctive disk with spiraling arms and a gas and dust-rich central bulge. Studying spiral galaxies gives us a peek into the universe's past and helps us understand galaxy evolution and cosmology.
</p>

<p style="text-align: justify;">
The <strong>Galaxy Zoo</strong> involved human volunteers for visual and pattern recognition through a decision-tree process, answering questions progressively about a galaxy's structure.
</p>

<p align="center">
  <img src="https://galaxyzooblog.files.wordpress.com/2015/03/screen-shot-2015-03-31-at-9-48-30-am.png" width="35%">
</p>

## Project development:

* 01/06/23: Data collection and defining the problem; image binary classification to detect either spiral galaxy or not.
* 15/06/23: The script is nearly done.
  * Reduced the number of images used for the model training and testing to a subset of 1000. 
* 15/06/23 to 21/06/23: Fixing errors and cleaning the code.
* 29/06/23:
  * Further cleaning of the code and bugs.
  * Got an 81% accuracy predicting spiral galaxies. Total number of epochs: 35. Added.
  * Removed some data directories from GitHub for optimization.

## Further project development:

* Include metrics visualization for comprehensive understanding and cross-validation for the report.
* Increase the number of epochs to improve accuracy.
* Further cleaning the code for readability.
* Develop a Streamlit app for more interactive model visualization.
* Take a break, keep focusing on Python basics, and move on to image segmentation and multiclassification.

## Model Results

Empty space for the future --> Haven't done all metrics yet.

## Testing the Model

Empty space for the future --> Haven't done all metrics yet.

## Toolkit:

* **JupyterLab**: Enviorment for Python scripts and managing files.

**Libraries**

* **Pandas**: Data manipulation and analysis.
* **Numpy**: Arrays and mathematical functions.
* **Os**: File managment.
* **Warnings**: Roses are red, violets are blue --> Warnings are annoying.
* **Matplotlib**: Data visualization.
* **Seaborn**: Runs on top of matplotlib, HD data visualization.
* **Shutil**: File operations (copying, deleting...).
* **TensorFlow:** Machine Learning for Computer Vision.
* **Keras:** High-level neural networks API for Deep Learning, running on top of TensorFlow.
* **Sklearn:** Machine Learning metrics.
* **PIL:** Python Imaging Library to manipulate images.
* **Random:** To generate random numbers.

## Bibliography:

- Lintott, C. J. et al. (2008). Galaxy Zoo: Morphologies derived from visual inspection of galaxies from the Sloan Digital Sky Survey. Monthly Notices of the Royal Astronomical Society, 389(3), 1179–1189.
- Willett, K. W. et al. (2013). Galaxy Zoo 2: detailed morphological classifications for 304,122 galaxies from the Sloan Digital Sky Survey. Monthly Notices of the Royal Astronomical Society, 435(3), 2835–2860.
