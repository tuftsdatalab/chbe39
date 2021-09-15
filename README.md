[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/chbe39/main?urlpath=lab)&nbsp;
[![Download Zip](https://tuftsdatalab.github.io/badges/zip.svg)](https://github.com/tuftsdatalab/chbe39/archive/main.zip)&nbsp;
![total size](https://img.shields.io/github/repo-size/tuftsdatalab/chbe39?label=total%20size)&nbsp;
![last updated](https://img.shields.io/github/last-commit/tuftsdatalab/chbe39?label=last%20updated)

# Introduction to Python and NumPy for ChBE39
**A Tufts University Data Lab Workshop**\
Written by Uku-Kaspar Uustalu

[![datalab.tufts.edu](https://tuftsdatalab.github.io/badges/datalab.svg)](https://sites.tufts.edu/datalab)&nbsp;
[![@TuftsDataLab](https://tuftsdatalab.github.io/badges/twitter.svg)](https://twitter.com/intent/follow?screen_name=tuftsdatalab)

Python resources: [go.tufts.edu/python](https://sites.tufts.edu/datalab/python/)\
Questions: [datalab-support@elist.tufts.edu](mailto:datalab-support@elist.tufts.edu)\
Feedback: [uku-kaspar.uustalu@tufts.edu](mailto:uku-kaspar.uustalu@tufts.edu)

Slides: [tufts.box.com/v/chbe39-python](https://tufts.box.com/v/chbe39-python)

---
## Table of Contents

- [Part 1/2: Introduction to Programming with Python](https://github.com/tuftsdatalab/chbe39#part-12-introduction-to-programming-in-python)
- [Part 2/2: A Gentle Introduction to NumPy and Matplotlib](https://github.com/tuftsdatalab/chbe39#part-22-a-gentle-introduction-to-numpy-and-matplotlib)
- [Bonus: File I/O with Python and NumPy](https://github.com/tuftsdatalab/chbe39#bonus-file-io-with-python-and-numpy)
- [Additional Resources](https://github.com/tuftsdatalab/chbe39#additional-resources)

---
## Part 1/2: Introduction to Programming with Python

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuftsdatalab/chbe39/blob/main/chbe39-intro-python.ipynb)&nbsp;
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/chbe39/main?urlpath=lab/tree/chbe39-intro-python.ipynb)&nbsp;
[![Download Notebook](https://tuftsdatalab.github.io/badges/jupyter.svg)](https://cdn.jsdelivr.net/gh/tuftsdatalab/chbe39/chbe39-intro-python.ipynb)&nbsp;

A hands-on introductory notebook that is suitable for self-guided study and covers the following:

- Using Python in a **notebook** environment
- Working with **lists**, **dictionaries**, and **tuples**
- Basic **string** manipulation
- Writing your own **functions**
- **Loops** and **conditionals**
- Reading **documentation** and modifying **function** behavior
- Difference between **functions** and **methods**
- **Lambda** (anonymous) functions and **map** functions
- **View** (*pass-by-reference*) vs **copy** (*pass-by-value*)

---
## Part 2/2: A Gentle Introduction to NumPy and Matplotlib

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuftsdatalab/chbe39/blob/main/chbe39-numpy-matplotlib.ipynb)&nbsp;
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/chbe39/main?urlpath=lab/tree/chbe39-numpy-matplotlib.ipynb)&nbsp;
[![Download Notebook](https://tuftsdatalab.github.io/badges/jupyter.svg)](https://cdn.jsdelivr.net/gh/tuftsdatalab/chbe39/chbe39-numpy-matplotlib.ipynb)&nbsp;

An interactive introduction to NumPy and Matplotlib that makes comparisons with MATLAB and covers the following:

- **Importing** Python **packages** and common **aliases**
- The NumPy **`numpy.ndarray`** a.k.a. **`np.array`** data structure
- Different ways of **creating**, **indexing**, and **slicing** NumPy arrays
- **Broadcasting** and using mathematical operators with `np.array`
- **Universal** functions and **aggregation** functions
- **Iterating** and **mapping** over elements in NumPy arrays
- ***Row-major*** vs ***column-major*** order and array **flattening**
- **Shape manipulation** and the difference between ***copies*** and ***views***
- Quick overview of **creating** and **styling plots** with Matplotlib
- Creating a figure with multiple **subplots** in Matplotlib

---
## Bonus: File I/O with Python and NumPy

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tuftsdatalab/chbe39/blob/main/chbe39-file-io-numpy.ipynb)&nbsp;
[![Launch Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/tuftsdatalab/chbe39/main?urlpath=lab/tree/chbe39-file-io-numpy.ipynb)&nbsp;
[![Download Notebook](https://tuftsdatalab.github.io/badges/jupyter.svg)](https://cdn.jsdelivr.net/gh/tuftsdatalab/chbe39/chbe39-file-io-numpy.ipynb)&nbsp;

Supplemental material on reading and writing files using both methods included in NumPy and standard Python functionality. Topics covered include:

- Various options for **importing** and **exporting** NumPy arrays
- Difference between **binary** and **text** files
- Tweaking the textual representation of numbers using **format strings**
- **Loss of significance** when exporting floating-point numbers
- Reading files with Python using **`with`** and **`open()`**
- Additional examples of **nested loops** and **iterating over indices**

---
## Additional Resources

- **Python Basics**
    - [Kaggle Python Tutorial](https://www.kaggle.com/learn/python
)  *(contains interactive hands-on exercises with hints and solutions)*
- **NumPy**
    - [University of Helsinki Data Analysis with Python MOOC](https://csmastersuh.github.io/data_analysis_with_python_2020/numpy.html) *(contains exercise prompts)*
    - [NumPy Quickstart Tutorial](https://numpy.org/doc/stable/user/quickstart.html)
    - [NumPy Basics for Absolute Beginners](https://numpy.org/doc/stable/user/absolute_beginners.html)
    - [NumPy for MATLAB Users](https://numpy.org/doc/stable/user/numpy-for-matlab-users.html)
- **Matplotlib**
    - [University of Helsinki Data Analysis with Python MOOC](https://csmastersuh.github.io/data_analysis_with_python_2020/matplotlib.html) *(contains exercise prompts)*
    - [Official Matplotlib Tutorials](https://matplotlib.org/tutorials/index.html)
- **Package Management with Conda**
    - [Getting Started with Conda](https://conda.io/projects/conda/en/latest/user-guide/getting-started.html)
    - [Managing Packages with Conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-pkgs.html)
    - [Managing Environments with Conda](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
    - [Differences Between Conda and Pip](https://www.anaconda.com/blog/understanding-conda-and-pip)