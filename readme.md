# R in Jupyter Notebook Setup Guide

This guide walks you through the process of setting up **R** in **Jupyter Notebook**. By following these instructions, you will be able to run R code in Jupyter Notebook and make use of the interactive features of Jupyter while leveraging the power of R for data analysis.

## Prerequisites

Before you begin, make sure you have the following installed:

- **Python** (required for Jupyter Notebook)
- **Jupyter Notebook**
- **R** (the language you will use in the notebook)
- **RStudio** (Optional but recommended for easier R interaction)

---

## Steps to Install and Use R in Jupyter Notebook

### 1. Install R

If you don’t have **R** installed, download and install it from the official CRAN website:

- **Download R**: [https://cran.r-project.org/](https://cran.r-project.org/)

Follow the installation instructions based on your operating system.

---

### 2. Install RStudio (Optional but Recommended)

**RStudio** is an Integrated Development Environment (IDE) for R that makes it easier to work with R code. While it's not strictly necessary for Jupyter, it is highly recommended for development and debugging.

- **Download RStudio**: [https://www.rstudio.com/products/rstudio/download/](https://www.rstudio.com/products/rstudio/download/)

---

### 3. Install the `IRkernel` Package in RStudio

After installing **R** and **RStudio**, you need to install the **IRkernel** package, which allows Jupyter Notebook to recognize R as a kernel.

1. Open **RStudio**.
2. Run the following commands in the RStudio console:

   ```R
   install.packages('IRkernel')
   IRkernel::installspec(user = FALSE)
