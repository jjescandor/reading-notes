JupyterLab

JupyterLab is a next-generation web-based user interface for Project Jupyter.

JupyterLab enables you to work with documents and activities such as Jupyter notebooks (Links to an external site.), text editors, terminals, and custom components in a flexible, integrated, and extensible manner. 

Numpy

NumPy (Links to an external site.) is a commonly used Python data analysis package.

By using NumPy, you can speed up your workflow, and interface with other packages in the Python ecosystem, like scikit-learn (Links to an external site.), that use NumPy under the hood.

NumPy was originally developed in the mid 2000s, and arose from an even older package called Numeric.

Creating A NumPy Array

We can create a NumPy array using the numpy.array (Links to an external site.) function.

If we pass in a list of lists, it will automatically create a NumPy array with the same number of rows and columns.

Because we want all of the elements in the array to be float elements for easy computation, we’ll leave off the header row, which contains strings.

One of the limitations of NumPy is that all the elements in an array have to be of the same type, so if we include the header row, all the elements in the array will be read in as strings.

This longevity means that almost every data analysis or machine learning package for Python leverages NumPy in some way.