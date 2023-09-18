
---------------------------------------------------

General curve fitting programme

---------------------------------------------------

The curve_fitter.ipynb file included is a Python programme designed to be used in Jupyter notebook to fit a line to experimental data.
It will not work in Jupyter labs.

Required packages that are not included with Jupyter:
- Pandas
- Numpy
- Matplotlib
- ipympl

3 CSV files are included to test the use of the programme on:
- noisy_gaussian_with_errors.csv	A series of points generated from a gaussian (normal distribution) with included uncertainties for both x and y values.
- noisy_gaussian.csv			A series of points generated from a gaussian (normal distribution) without any included uncertainties.
- noisy_linear_with_errors.csv		A series of points generated from a straight line with included uncertainties for both x and y values.

You should only have to edit the actual code for the first 2 boxes to change filename, axis names, which columns the data is stored in, the form of the function you're fitting to etc.
After that you can run each cell in order, doing any necessary actions along the way.

By default the programme is set up to deal with normally distributed data.

The method for propagating uncertainties from the data to the coefficients of the fit is known as Monte Carlo error propagation.



Code written by John Newnham.
