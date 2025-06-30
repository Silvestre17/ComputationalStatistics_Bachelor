# 🎲 Computational Statistics: A Project Portfolio 📊

<p align="center">
    <!-- Project Links -->
    <a href="https://github.com/Silvestre17/ComputationalStatistics_Bachelor"><img src="https://img.shields.io/badge/Project_Repo-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Repo"></a>
</p>

## 📝 Description

This repository is a curated collection of assignments completed for the **Computational Statistics** course. It showcases a practical journey through fundamental concepts of probability theory, statistical inference, and probabilistic modeling, with all solutions implemented in **R** and documented using **R Markdown**.

## 🎯 Learning Objectives

This collection of projects demonstrates the development of key skills in computational statistics, including:
*   Consolidating the use of **R** and **RStudio** for statistical analysis.
*   Calculating probabilities in various contexts, including through **simulation**.
*   Applying common **probabilistic models** (e.g., Poisson, Normal, Bernoulli).
*   Understanding the core principles of **statistical inference**, including parameter estimation and hypothesis testing.
*   Choosing and applying the most appropriate **inferential method** for a given problem.

## 🎓 Project Context

This work was completed for the **Estatística Computacional** (*Computational Statistics*) course as part of the **[Licenciatura em Ciência de Dados](https://www.iscte-iul.pt/degree/code/0322/bachelor-degree-in-data-science)** (*Bachelor Degree in Data Science*) at **ISCTE-IUL**, during the 2022/2023 academic year.

## 🛠️ Core Technologies

All assignments were developed using the R programming language and its ecosystem.

<p align="center">
    <a href="https://www.r-project.org/">
        <img src="https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white" alt="R" />
    </a>
    <a href="https://rmarkdown.rstudio.com/">
        <img src="https://img.shields.io/badge/R_Markdown-5178B8?style=for-the-badge&logo=r&logoColor=white" alt="R Markdown" />
    </a>
    <a href="https://www.tidyverse.org/">
        <img src="https://img.shields.io/badge/Tidyverse-1E90FF?style=for-the-badge&logo=rstudio&logoColor=white" alt="Tidyverse" />
    </a>
</p>

---

## 📚 Assignments Breakdown (TPCs)

This repository contains the solutions for all homework assignments (`TPC`), each exploring a different area of computational statistics. Each folder contains the `.Rmd` source file and the final compiled `.pdf`/`.html` report.

### TPC 1: Foundations of Probability
*   **Problem:** Analyzing the random experiment of rolling two different dice (6-sided and 8-sided).
*   **Core Concepts:** Defining sample spaces, calculating probabilities of events (e.g., sum of points > 8), and computing the probability of unions and intersections of events.

### TPC 2: Conditional Probability & Bayes' Theorem
*   **Problem:** Solving the "cutefish" problem, which involves identifying the proportion and likelihood of catching different types of fish based on prior knowledge.
*   **Core Concepts:** Application of the **Law of Total Probability**, **Conditional Probability**, and **Bayes' Formula**.

### TPC 3: Univariate Random Variables
*   **Problem:** Studying the sum of values from two dice rolls as a random variable (`U`).
*   **Core Concepts:** Constructing and plotting the **Probability Mass Function (PMF)** and the **Cumulative Distribution Function (CDF)**. Calculating the mean, variance, and standard deviation of `U`.

### TPC 4: Probabilistic Models
*   **Problem:** Modeling daily product demand and monthly fuel consumption.
*   **Core Concepts:**
    *   **Poisson Distribution:** Modeling discrete events (product demand) over a fixed interval.
    *   **Continuous Distributions:** Working with a given **Probability Density Function (PDF)** to calculate probabilities and expected values using numerical integration.

### TPC 5: Normal Distribution & Simulation
*   **Problem:** Analyzing water consumption in a tourist region, modeled by a **Normal distribution**.
*   **Core Concepts:** Applying properties of the Normal distribution, using the **Central Limit Theorem** for sums of random variables, and running simulations (`rnorm`) to estimate probabilities.

### TPC 6: Parameterization and Estimators
*   **Problem:** A theoretical exercise involving a sample from a **Bernoulli** population (e.g., presence of kittens in photos).
*   **Core Concepts:** Constructing a **Joint Probability Function**, understanding the properties of statistics like the sample sum (which follows a **Binomial distribution**) and the sample mean, and interpreting their expected values as estimators.

### TPC 7: Confidence Intervals
*   **Problem:** Estimating population parameters from a survey about sunglasses.
*   **Core Concepts:** Constructing and interpreting 99% **Confidence Intervals** for a population **mean** (e.g., importance of marketing) and a population **proportion** (e.g., percentage of people owning a specific brand).

### TPC 8: Hypothesis Testing
*   **Problem:** Analyzing survey data to determine if the perceived importance of price is above a certain threshold and if there is a difference between genders.
*   **Core Concepts:**
    *   **Hypothesis Testing for a Mean:** Using a one-sample t-test.
    *   **Hypothesis Testing for Two Means:** Using a two-sample t-test to compare groups.
    *   **Chi-Square Test of Independence:** Testing for association between two categorical variables (e.g., style of sunglasses and brand ownership).

---

## 🚀 How to Run the Solutions

Each TPC is a self-contained project within its folder. To view or reproduce the results:

1.  **Prerequisites:**
    *   Install [R](https://www.r-project.org/).
    *   Install [RStudio Desktop](https://www.rstudio.com/products/rstudio/download/).
2.  **Open the Project:**
    *   Navigate to a specific TPC folder.
    *   Open the `.Rmd` file in RStudio.
3.  **Install Packages:**
    *   The scripts may require packages, primarily from the `tidyverse` ecosystem. You can install them by running `install.packages("tidyverse")` in the RStudio console.
4.  **Generate the Report:**
    *   Click the **"Knit"** button in RStudio. This will execute the R code within the document and generate the final, formatted report in `.html` or `.pdf`.

## 🇵🇹 Note

These assignments were developed and written in Portuguese from Portugal 🇵🇹.