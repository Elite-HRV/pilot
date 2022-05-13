<h1>Pilot<img src='https://github.com/Elite-HRV/pilot/blob/main/img/snek.png' align='right' width='180' height='104'></h1>

Welcome to Elite HRV's data science challenge!

Heart rate variability has been studied as an indicator for individuals' health and has been shown to correlate with perceived stress. For this data science challenge, we will be digging into the SWELL Knowledge Work dataset. Published in 2014, this dataset measures stress of individuals doing various knowledge work related tasks. Details of the dataset and some previous studies are outlined in the [papers](data/papers) included in this repository. You can find the dataset in [data](data). Training, validation, and test splits are provided, but feel free to combine the splits in any way that you find interesting. 


## Challenge Aims
In general, we want this take home assessment to be flexible and relatively open-ended. As we're very aware of the amount of time and energy data science tasks can take (it's fun, but can be challenging!), we've provided a list of prompts (in [data/ideas.md](data/ideas.md)) and ideas to get the ball rolling. Feel free to utilize any one of these for your assessment or follow along any one of the analyses outlined in the included research papers. We're not expecting a full-fledged analysis at all, we just want to see generally how you approach certain parts ot he data science pipeline and how that translates into your code. You can include inline comments, external notes, or any additional materials in your submission. Please also structure your work in whatever way you see fit. This optionally includes Jupyter notebooks, Python scripts, or a Python package (see below for bits on packaging). Clarity, reproducibility, and reusability are highly valued, even over novelty and (sometimes) performance!


Lastly, thank you for participating in our data science challenge. We are excited to talk through your ideas!


## The `pilot` package

To get things started, we have created a scaffold for a Python package, `pilot`, in case you choose to develop your code as a pip installable Python project. Note that some of the fields in [`setup.py`](setup.py) are intentionally left blank for you to fill in your name and associated details!

#### Setup

```
python setup.py install
```
