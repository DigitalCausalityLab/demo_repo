# A Demo GitHub Repository for a Causal Case Study <a href="https://digitalcausalitylab.github.io/"><img src="figures/logo.png" align="right" width = "120" /></a>

This repository is created for demonstration purposes. Version control with Git and GitHub is taught in the [Digital Causality Lab](https://digitalcausalitylab.github.io/).

## First steps in GitHub

Participants of the [Digital Causality Lab](https://digitalcausalitylab.github.io/) should use this repo as a template and do the following steps.

1. Create your own GitHub repository.
  * You can either navigate to your GitHub profile, go to the repositories tab and click on **new**, or, 
  * You can use this template by clicking on the **Use this template** button.
![](figures/use_template_button.png)
2. Open an issues with a task. For example, the title could be "*Add some content to the `README.md` file*".
3. Create a new branch, e.g., named `changes-to-readme`.
4. Make changes to your files on this branch and commit them with a message. Push the changes.
5. Open a pull request and review your changes.
6. Merge the pull request and pull the `main` branch again. Verify that your changes have been merged.


## Repo Structure

After you've completed the previously described steps, please remove the content above. Include the following information in this readme file:

### Title of Case Study

- [ ] Please include the title of your case study; an overview of all case studies is available [here](https://github.com/DigitalCausalityLab/causal-case-studies/issues)

### Participants

- [ ] Please list the names and GitHub user names here

### Abstract

- [ ] Insert a brief description of the goals and results of your case study (around 250 words, English)
- [ ] You can upload and include figures, too

### Current State and Call for Extension

- [ ] Briefly summarize the state of your data product as of the end of the course
- [ ] Briefly summarize what could be added or improved in the future


## Organization of the Repo

We'd recommend you to organize your repo as follows.

* Include figures (`.jpg`, `.png`, ...) in a subdirectory called `figures/`, see [this example](figures/logo.png)
* Include data files (`.csv`, `.rda`, ...) in a subdirectory called `data/`, see [this example](data/experiment_data_counterfactual.rda)
* Include your R code (`.R` files) in a subdirectory called `R`, see [this example](R/my_function.R)
* In case you use quarto for your data product, include your `.qmd` files here, see [this example](demo_repo.qmd)

These basic recommendations are intended to give you a bit structure. You can deviate from them as you like but please make sure others should be able to understand what you did.
