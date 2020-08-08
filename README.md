# Introduction

## Trigger Warning: career-related anxiety

This notebook discusses the potentially negative employment outcomes of certain engineering major choices in very blunt terms. If you are an engineering student and prone to anxiety, reading this notebook may be a significant trigger. Proceed with caution.

NOTE: to help honor this trigger warning, results and conclusions will not be included in this README. Please see the Juypter notebook in this same directory for them.

## Goal

The goal of this project is to make some educated, data-driven guesses as to how likely an new engineering graduate is to find an entry-level engineering job in their discipline within a given year in the United States. As it currently stands, ***engineering majors are not created equal!*** Some are in high demand while others have extremely saturated job markets and, unfortunately, this is not common knowledge.

## Objectives

The objectives behind this goal are:
* For high-school and incoming college students, inform their educational decisions
* For current engineering students, help them assess how their current academic program may or may not match their career expectations
    * For some students, this may entail right out switching majors
    * For others, this may mean complementing their education through work experience, relevant extracurricular activities and/or ramping up their networking effort with industry professionals
At the very least, this effort should serve the purpose of informing them of what to expect as they graduate, something that simply is not done enough.

## Justification

Likelihood of finding a job is not the **ONLY** factor that should be taken into account when making career choices; but, on the other hand, it is currently underweighed by large swaths of the higher education student body.

Getting a bachelor's degree is a large investment of time, money and effort. Specifically, the money investment is split between education costs (tuition, fees, housing near college, living expenses, commuting costs, etc.) and foregone full-time wages while in school (usually these are much larger than tuition and fees, and you do not escape them even in countries with fully subsidized higher education). Therefore, not being able to find a full-time job relevant to one's college degree soon is a real, bonafide tragedy for most graduates.

## Note from the author

This effort has been done in good faith. I realize this may upset or discourage some (especially students in the final stages of one of the engineering programs described as having saturated job markets); this is not the intention. Nevertheless, I believe finding out about this early enough at the cost of anxiety is a much lesser tragedy than actually graduating after investing 4 or so years just to end up in less than favorable circumstances w.r.t. employment, in addition to the same anxiety (or worse).

Please feel free to run this Jupyter Notebook, check the results, judge the assumptions made and, if appropriate, contest the conclusions. Feedback (as filed issues or pull requests) is not only appreciated but encouraged.

# How to run the code

This project was developed using:

* Python 3.7.8
* Pandas 1.1.0
* Jupyter 1.0.0

The easiest path to running it and modifying it is as follows:
* Install Anaconda (Python distribution installer, https://www.anaconda.com/products/individual).
* Open the Anaconda terminal (this varies according to operating system).
* Run the following command to create an Anaconda Python environment with everything needed to execute the code: <br>`conda create -n eng_major_analytics -c conda-forge python=3 numpy pandas jupyter numpy`
* Activate the environment: <br>`conda activate eng_major_analytics`
* Use the terminal to navigate to the directory where this project has been downloaded/cloned to.
* Start the Jupyter notebook service: <br>`jupyter notebook`
* The last step should also open a web browser; if not, go ahead and open one and navigate to http://localhost:8888/
* Click on the `EngineeringMajorAnalytics.ipynb` link to open the notebook.
* If necessary, set the kernel in the notebook to `Python 3`
* Execute cells, observe results, modify values if you wish.