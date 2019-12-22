## Sparkify - Analysis of data from a hypothetical music streaming service
Udacity Data Science Capstone Project
<br><br>

### Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Analytical process and results](#analytical_process)
5. [Licensing, Authors, and Acknowledgements](#licensing)
<br><br>

### Installation <a name="installation"></a>

The code should run smoothly using Python versions 3.*. The project heavily depends on the PySpark package. The project is based on PySpark version 2.4.3. The libraries I used are all distributed via Anaconda. 
<br><br>

### Project Motivation<a name="motivation"></a>

The churning of users has a negative impact on business outcomes. Early prediction of potential churning provides a chance to strengthen endangered client relationships. The purpose of this project is to utilize big data to implement a machine learning model which is able to predict potential churning.
<br><br>

### File Descriptions <a name="files"></a>

There are two notebooks available: 
- `sparkify_notebook__small_dataset.ipynb`: Uses a small subset of the available data. The code within the notebook was run on a local machine.
- `sparkify_notebook__complete_dataset.ipynb`: Uses the complete set of the available data. The code within the notebook was run on an AWS cluster. The results on the full dataset differ from the analysis on the reduced dataset, although the analytical process is substantially the same.

Both notebooks are also available in an html format.
<br><br>

### Analytical process and results<a name="analytical_process"></a>

The major analytical steps as well as my findings are available in a [blog post](https://medium.com/@christian_sauka/prevent-losing-customers-a648a02d280b) on Medium.
<br><br>

### Licensing<a name="licensing"></a>

This project is licensed under the MIT License - see the [License.txt](License.txt) file for details.
