[![Discord](https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/mw7xjJ7b7s)
[![Youtube](https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UC4AFOG1a8b9r46G9w0CacUA)
[![Medium](https://img.shields.io/badge/Medium-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/data-centric-ai-community)
[![YData Synthetic](https://img.shields.io/badge/ydata%20synthetic-12100E?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ydataai/ydata-synthetic)


# NIST Privacy Collaborative Reseach 

**The Data-Centric AI Community just launched a small community project to experiment with the [NIST Challenge](https://pages.nist.gov/privacy_collaborative_research_cycle/pages/participate.html)!**


- **Goal:** To learn about Synthetic Data and how it can be used to prepare sensitive private data for public release!
- **Dates:** From April to July. You can also join at any time, follow the weekly plan, and post questions on our Discord.
- **Where:** ***🤖-nist-challenge*** channel in our [Discord Server](https://discord.gg/46wAzZxpFy)
- **Touch Points:** We meet every Friday around 4 PM GTM on the ***🧠-code-with-me channel*** to discuss the project.

## Overview
🎯 The **overall goal** of the project is to **explore synthetic data** to prepare sensitive private data for public release. 

📀 NIST has launched a **benchmark of 3 datasets**, `MA`, `TX` (Texas), and `NATIONAL` which you can use in the project.

📊 To provide an **evaluation of the de-identified data** against the target/real data, NIST has created the [`sdnist`](https://github.com/usnistgov/SDNist) package that can be installed according to the instructions below.

💻 To **create the de-identified data**, we'll use [`ydata-synthetic`](https://github.com/ydataai/ydata-synthetic) package, explore different model settings and study the effect this has on the final results.

## 🧭 Learning Outcomes
| Week        | What you will learn           | 
| :-------------: |-------------| 
| **1**      |**Goal and objectives of the project.** You'll connect with other learners in the [DCAI Discord Server](https://discord.gg/46wAzZxpFy) and be added to the NIST Team to access the **🤖-nist-challenge** channel and receive permissions to collaborate on the GitHub project.|
| **2**  | **Basics of Synthetic Data.** You will learn more about what is synthetic data, how is it generated, what are the main applications.|
| **3** | **Basics of Data Profiling.** You will learn what is data profiling, how to understand your data with descriptive statistics, and what are common data quality issues. You will also **explore the NIST datasets** with [`ydata-profiling`](https://github.com/ydataai/ydata-profiling) and **preprocess the data** according to your findings.  |
| **4 & 5** | **Generation of Synthetic Data.** You will explore Deep Learning models (Generative Adversarial Networks -- GAN) to generate realistic synthetic data using [`ydata-synthetic`](https://github.com/ydataai/ydata-synthetic).|
| **6 & 7** | **Basics of Evaluating Synthetic Data.** You will explore some strategies to evaluate synthetic data and investigate possible improvements to your solution. We will explore the [`sdnist`](https://github.com/usnistgov/SDNist) package to evaluate our synthetic data.|
| **8** | **Project Showcase.** You will learn how to best **showcase and publicize your project** in your data portfolio, CV, GitHub, or Medium Account.| 


# 🔨 Tasks

#### Week 1:
- Read the [instructions and information](https://pages.nist.gov/privacy_collaborative_research_cycle/pages/participate.html) about the challenge
- Learn about the benchmark data released -- [The NIST Diverse Communities Data Excerpts](https://github.com/usnistgov/SDNist/tree/main/nist%20diverse%20communities%20data%20excerpts)
- Post questions and ideas on the *[🤖-nist-challenge](https://discord.gg/46wAzZxpFy)* channel


#### Week 2:
- Learn about the basic aspects of **Synthetic Data**:
	- [10 Most Frequently Asked Questions About Synthetic Data](https://ydata.ai/resources/10-most-frequently-asked-questions-about-synthetic-data)
	- [Synthetic Tabular Data Generation](https://towardsdatascience.com/synthetic-tabular-data-generation-34eb94a992ed)
	- [Synthetic Data for Data Science Development](https://ydata.ai/resources/synthetic-data-the-future-standard-for-data-science-development)
	- [Applications of Synthetic Data - The role of Synthetic Data in Privacy Engineering](https://ydata.ai/resources/the-role-of-synthetic-data-in-privacy-engineering)
- Post questions and comments on the *[🤖-nist-challenge](https://discord.gg/46wAzZxpFy)* channel
- Meet us on Friday (**May 5**) to discuss what you've learned (*check the available slots on our 📅 Discord Calendar*)



#### Week 3:
- Learn about the basic aspects of **Data Profiling**:
	- [📺 Auditing Data Quality with ydata-profiling](https://www.youtube.com/watch?v=5EH_OkCd6TQ&t=1s): learn about what is **data profiling**, what common **data quality issues** we find in real-world domains (*can you spot a few in the NIST datasets?*), and how `ydata-profiling` can help you diagnose and overcome them
	- [📖 Awesome Data Science Tools to Master in 2023: Data Profiling Edition](https://towardsdatascience.com/awesome-data-science-tools-to-master-in-2023-data-profiling-edition-29d29310f779): learn more about **data profiling** and existing **open source tools** to understand your data to the fullest!
	- [📖 Auditing Data Quality with YData Profiling](https://medium.com/ydata-ai/auditing-data-quality-with-pandas-profiling-b1bf1919f856): an overview of `ydata-profiling` functionalities and how-to's


- Start profiling the NIST data:
	- Install[`ydata-profiling`](https://github.com/ydataai/ydata-profiling) (check the **Installation Instructions** below) and **don't forget to star it, thank you!** ⭐️
	- Choose one of the NIST datasets (`MA`, `TX`, or `NATIONAL`):
		- The datasets are [available here](https://github.com/usnistgov/SDNist/tree/main/nist%20diverse%20communities%20data%20excerpts)
		- Run a **Profile Report** on your data (check the **Installation Instructions** below)
		- Create an excel file to register your learnings. **Suggestion for the columns:** `Feature Name | Data Type (Numeric/Categorical) | Missing Values (Y/N) | Notes/Observations`. Your observations should be based on the profiling report, but also on the [description of the features provided](https://github.com/usnistgov/SDNist/tree/main/nist%20diverse%20communities%20data%20excerpts)

- Post questions and comments on the *[🤖-nist-challenge](https://discord.gg/46wAzZxpFy)* channel.
- Meet us on Friday (**May 12**) to discuss what you've learned (*check the available slots on our 📅 Discord Calendar*). **Don't forget to bring your excel file with the data description and your profiling report!**



#### Weeks 4 & 5:
- Investigate `ydata-synthetic` and some of the models used to **Generate Synthetic Data**:
	- [📖 GANs for Synthetic Data Generation](https://ydata.ai/resources/gans-for-synthetic-data-generation)
	- [📖 10 Most Asked Questions in ydata-synthetic](https://ydata.ai/resources/10-most-asked-questions-on-ydata-synthetic)
	- [📖 Synthetic Data Generation with Gaussian Mixture Models](https://ydata.ai/resources/synthetic-data-generation-with-gaussian-mixture-models)
	- [📖 Generating Synthetic Tabular Data with GANs - Part 1](https://medium.com/ydata-ai/generating-synthetic-tabular-data-with-gans-part-1-866705a77302)
	- [📖 Generating Synthetic Tabular Data with GANs - Part 2](https://medium.com/ydata-ai/generating-synthetic-tabular-data-with-gans-part-2-a0aba150539)
	- [📖 How to Generate Synthetic Tabular Data](https://towardsdatascience.com/how-to-generate-synthetic-tabular-data-bcde7c28038a)
- Start experimenting with [`ydata-synthetic`](https://github.com/ydataai/ydata-synthetic) (check the **Installation Instructions** below and **don't forget to star it, thank you!** ⭐️). If you prefer a UI experience, you can also **leverage the Streamlit App** in version 1.0.0:
	- [📺 How to "pip install ydata-synthetic" without errors!](https://www.youtube.com/watch?v=jj9X1_cKRwI&t=1s)
	- [📺 Install ydata-synthetic in 5 min](https://www.youtube.com/watch?v=aESmGcxtBdU)
	- [📖 How to Generate Real-World Synthetic Data with CTGAN](https://medium.com/towards-data-science/how-to-generate-real-world-synthetic-data-with-ctgan-af41b4d60fde)
	- [📺 How to Generate Synthetic Data with ydata-synthetic's Streamlit app](https://www.youtube.com/watch?v=6Lzi26szKNo)
- Compare your **synthetic** data with the **real** data using the `.compare()` functionality of [`ydata-profiling`](https://github.com/ydataai/ydata-profiling):
	- [📖 How to compare 2 datasets with ydata-profiling](https://pub.towardsai.net/how-to-compare-2-dataset-with-pandas-profiling-2ae3a9d7695e). *What are the obtained results? Are there any aspects that you can improve?*
- Post questions and comments on the *[🤖-nist-challenge](https://discord.gg/46wAzZxpFy)* channel! You can upload your profiling reports the the channel so that we can discuss changes and improvements.


# ⚙️ Installation Instructions
<details>
  <summary><b> 📦 How to create and use Virtual Environments?</b></summary>

A lot of troubleshooting arises due to **misalignments between environments and package requirements**. If you're new to data science development, maybe you just install packages unto your global Python environment. This may turn into a lot of headaches when project requirements are conflicting.

[Virtual Environments](https://serpapi.com/blog/python-virtual-environments-using-virtualenv-and-poetry/) are ideal to overcome this issue: they **isolate your installations from the "global" environment**, so that you don't have to worry about conflicts. If you've never used virtual environments for your data science projects, you can start by installing [anaconda](https://www.anaconda.com). If you need a little convincing that this is a nice tool to have on your belt, then [check this post](https://codesolid.com/conda-vs-pip/?utm_content=cmp-true) comparing `conda` with `pip`, `venv`, and  `pyenv`.

Once anaconda is installed, **creating a new environment** is as easy as running this on your shell:

```bash
conda create --name synth-env python=3.10
```

This creates a new environment called **synth-env** with Python version 3.10.X. You can then switch to this environment by **activating it**:

```bash
conda activate synth-env
```

In this new environment, you can still **call `pip` to install python packages**, such as `ydata-synthetic`:

```bash
pip install ydata-synthetic
```

Now you can open up your **Python editor or Jupyter Notebook** and use the `synth-env` as your development environment, without having to worry with conflicting versions or packages between projects! Once you're done, you can **deactivate the environment** using:

```bash
conda deactivate synth-env
```

#### Suggested Materials
  - [📖 Environments, Conda, Pip, aaaaah!](https://towardsdatascience.com/environments-conda-pip-aaaaah-d2503877884c): How to manage Python Environments without a headache
  - [📺 How to "pip install ydata-synthetic" without errors!](https://www.youtube.com/watch?v=jj9X1_cKRwI): How to install anaconda, create a virtual environment using `conda`, install packages with `pip`, and use the virtual environments in PyCharm or Jupyter Notebooks
 
</details>

###
<details>
  <summary><b> 📊 How to install ydata-profiling and create a Profiling Report?</b></summary>

You may start by **creating your virtual environment and installing the package**:

```bash
conda create -n synth-env python=3.10
conda activate synth-env
pip install ydata-profiling==4.1.2
```

Then, in your Jupyter Notebook or other editor (e.g., PyCharm), **load your Pandas DataFrame** as you normally would and the **generation of the profiling report** is straightforward:

```python
import pandas as pd
from pandas_profiling import ProfileReport

# Read the data from a csv file (NIST "MA" data in the example)
df = pd.read_csv("ma2019.csv")

# Generate the data profiling report 
original_report = ProfileReport(df, title='Original Data')
original_report.to_file("original_report.html")
```

You can then navigate the report to **investigate the data quality issues** generated, and study the basic **descriptive statistics** of your data! 


#### Additional Materials
  - [📚 Examples with real-world datasets](https://ydata-profiling.ydata.ai/docs/master/pages/getting_started/examples.html): A list of examples and data profiling reports and usage of ydata-profiling
  - [🙇🏽‍♂️ Read the Docs: Documentation](https://ydata-profiling.ydata.ai/docs/master/pages/getting_started/overview.html): from installation and quickstart to integrations and advanced usage

  </details>

###
<details>
  <summary><b> 🤖 How to install ydata-synthetic and create a synthesizer?</b></summary>

You may use you previous **virtual environment** (`synth-env`). **Activate** it and and **install** the package:

```bash
conda activate synth-env
pip install ydata-synthetic==1.1.0
```

Then, you can leverage one of the models available in the package. In this example, we will be using **CTGAN**:

```python
# Load data
data = fetch_data('adult')
num_cols = ['age', 'fnlwgt', 'capital-gain', 'capital-loss', 'hours-per-week']
cat_cols = ['workclass','education', 'education-num', 'marital-status', 'occupation', 'relationship', 'race', 'sex', 'native-country', 'target']

# Defining the training and model parameters
batch_size = 500
epochs = 500+1
learning_rate = 2e-4
beta_1 = 0.5
beta_2 = 0.9

# Create and train the model
ctgan_args = ModelParameters(batch_size=batch_size,
                             lr=learning_rate,
                             betas=(beta_1, beta_2))

train_args = TrainParameters(epochs=epochs)

synth = RegularSynthesizer(modelname='ctgan', model_parameters=ctgan_args)
synth.fit(data=data, train_arguments=train_args, num_cols=num_cols, cat_cols=cat_cols)

# Generate new samples
synth_data = synth.sample(1000)

print(synth_data)
```

You can also check further [examples with other models](https://github.com/ydataai/ydata-synthetic/tree/dev/examples/regular/models).
</details>


