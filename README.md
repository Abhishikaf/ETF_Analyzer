# ETF_Analyzer - Analyze an ETF
Analyze the performance of a ETF using Python, Voila library and data stored in an SQL database

![Voila Screen 1](Images/voila_output_1.png)
![Voila Screen 2](Images/voila_output_2.png)
![Voila Screen 3](Images/voila_output_3.png)
![Voila Screen 4](Images/voila_output_4.png)
![Voila Screen 5](Images/voila_output_5.png)


---

## Technologies

This project uses python 3.7 along with the following packages:

* [JupyterLab](https://jupyterlab.readthedocs.io/en/stable/) - Web based user interface for data analysis.

* [pandas](https://github.com/pandas-dev/pandas) - Data analysis and manipulation library.

* [voila](https://voila.readthedocs.io/en/stable/) - Voilà allows you to convert a Jupyter Notebook into an interactive dashboard that allows you to share your work with others.

* [sqlalchemy](https://pypi.org/project/SQLAlchemy/) - SQLAlchemy is the Python SQL toolkit and Object Relational Mapper.

* [hvplot](https://hvplot.holoviz.org/) - hvPlot provides a high-level plotting API built on HoloViews that provides a general and consistent API for plotting data
---

## Installation Guide

Please install the following before starting the application

```python
  pip install jupyterlab
  pip install pandas
  pip install voila
  pip install sqlalchemy
  pip install hvplot

```

Confirm installation by running:
```python
  conda list voila
  conda list sqlalchemy
```
---

## Usage

To use the financial planning tools, please download and open the **etf_analyzer.ipynb** in jupyter lab after executing
the following on the command line:

```python
jupyter lab
```
Jupytper Lab should open automatically in a browser. 
If it does not, please follow the instructions on the command line.

To launch voila

```python
voila etf_analyzer.ipynb
```
---

## Contributors

Abhishika Fatehpuria (abhishika@gmail.com)

---

## License

MIT
