# Machine Learning Engineer Nanodegree
# Capstone Project
## Project: Breast Cancer Diagnosis

### Install

This project requires **Python 2.7** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [scikit-learn](http://scikit-learn.org/stable/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. Make sure that you select the Python 2.7 installer and not the Python 3.x installer.

### Code

Template code is provided in the `breast_cancer.ipynb` notebook file. You will also be required to use the `cancer_data.csv` dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project.

### Run

In a terminal or command window, navigate to the top-level project directory `breast_cancer/` (that contains this README) and run one of the following commands:

```bash
ipython notebook breast_cancer.ipynb
```
or
```bash
jupyter notebook breast_cancer.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The dataset used in this project is included as `cancer_data.csv`. Ten real-valued features are computed for each cell nucleus:

- `radius` : mean of distances from centre to points on the perimeter
- `texture` : standard deviation of grey-scale values
- `perimeter`
- `area`
- `smoothness` : local variation in radius lengths
- `compactness` : perimeter^2 / area - 1.0
- `concavity` : severity of concave portions of the contour
- `concave points` : number of concave portions of the contour
- `symmetry`
- `fractal dimension` : "coastline approximation" - 1

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.
