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


## Project development:

* 01/06/23: Data collection and definining the problem; image binary classificator to detect either elliptical galaxy or not.
* 15/06/23: Script nearly done. Reduced the quantity of imges used for the training model and testing to 500.
* 15/06/23 to 21/06/23: Fixing errors, bugs, cleaning the code.
* 29/06/23: Futher cleaning the code and bugs. Got a 81% accuracy predicting spiral galaxies. Total number of epochs: 35.

## Model Results

Empty space for the future --> Haven't done all metrics yet]

## Testing the Model

Empty space for the future --> Haven't done all metrics yet]

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