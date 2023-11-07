Hello there. Internet etiquette dictates that any website that deals with stats starts with a GIF to signal that this will be fun. I'm not one to breach etiquette, so here we go:

![](https://media.giphy.com/media/MCZ39lz83o5lC/giphy.gif)

## This website

This website collects the materials for a 2-day workshop on simulating power with R that [I'm](https://www.niklasjohannes.com/) giving as part of the [GESIS training portfolio](https://training.gesis.org/?site=pDetails&child=full&pID=0xE0F8F1C4FE124C6CB7B6AAC9E2E83E61).

Rather than dumping the materials in zip folder somewhere, I thought this format will be better for a) participants to revisit, b) those who might be interested in the content but couldn't make it. That's also the reason most of the materials are so annoyingly verbose: I wanted readers to be able to follow along by themselves and re-visit.

## Goal

The goal of the workshop is for you to (1) have an understanding of the philosophy behind using data to test claims, (2) get an intuition of how data generation processes work, (3) learn the technical skills in R to turn these processes into data, and (4) use these skills to simulate power for an informative study.

## Schedule

Below is the 2-day schedule. From experience, there's quite a lot of variability on how far in the schedule we can get in 2 days. It'll mostly depend on how much time you need to go through the exercises (and most likely we won't do all of them). Technically, after Exercise 2, you'll have everything you need, but I aim to at least make it to interactions. The rest you can also do at home in case we don't make it all the way.

**Day 1**

| When          | What                                                                 |
| ------------- | -------------------------------------------------------------------- |
| 09:30 - 12:30 | Intro<br>What's power?<br>Simulations in R<br>Exercise 1             |
| 12:30 - 14:00 | Lunch break                                                          |
| 14:00-17:30   | Effect sizes<br>Exercise 2<br>Alpha, beta, sensitivity<br>Exercise 3 |

**Day 2**

| When          | What                                                                 |
| ------------- | -------------------------------------------------------------------- |
| 09:30 - 12:30 | Categorical predictors<br>Exercise 4<br>Interactions                 |
| 12:30 - 14:00 | Lunch break                                                          |
| 14:00-17:30   | Exercise 5<br>Continnuous predictors<br>Exercise 6                   |

## Takeaways

Each of these blocks has a several learning outcomes. They are:

### What's power

-   Understanding of the logic behind NHST
-   Intuition about what power is
-   See why power, perhaps, potentially isn't just a hoop to jump through

### Simulations in R

- Understand why simulations are useful
- Logic of Monte Carlo Simulations
- Learn basic tools in R for simulating data

### Effect sizes

- Understand the importance of effect sizes
- How to formulate a smallest effect size of interest
- Know when you don't have enough information

### Alpha, beta, sensitivity

- Question the default of $\alpha$ = 0.05 and power = 80%
- Understand how terribly complex designing an informative study is
- Know where to turn when you don't have enough information

### Categorical predictors

- Understand the logic behind the data generating process
- See how the linear model is our data generating process
- Apply this to a setting with multiple categories in a predictor

### Interactions

- Understand what an interaction is from the perspective of the linear model
- Make yourself think in more detail about the form of interactions
- Be able to translate that detail to generating data

### Continuous predictors

- Understand that continuous predictors are just another case of the linear model
- Extend this understanding to continuous (by categorical) interactions
- Be able to translate that extension to generating data


## Prerequisites

I expect that you're somewhat familiar (though not deeply) with R and vaguely remember your undergrad stats classes. Other than that, you should be good to go. That said, if you only have a couple of hours of R experience or have only done a short introduction, you'll struggle. It'll be difficult to learn both programming and the concepts you're supposed to implement.

What you'll need for the workshop:

- A laptop (with a webcam, preferably)
- A working installation of [R](https://www.r-project.org/) and preferably [RStudio](https://www.rstudio.com/)
- [GPower](https://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower) installed
- For communication, please join this discord channel that we'll use throughout the 2 days: <https://discord.gg/EeEWx4r5>

## Structure

The workshop will follow a structure of learn, do, recall. So typically, for each topic, I'll introduce theoretical concepts; then you'll do lots of exercise where you try to apply and extend these concepts; afterwards, there will be a short quiz.

On this website, only the first two are present: On the left-hand side, you see the slides per topic and the exercises.

## Getting a local copy

If you want a local copy of this website, just download the entire project from Github: <https://github.com/niklasjohannes/power-workshop> (Code --> Download Zip). Unzip and then go to the `docs` folder, where you can double click on `index`. Alternatively, you can select individual slides/exercises within the docs folder. If you want to look at the source code, check the `content` folder. (Here you'll also find the code for the solutions for the exercises.)

## Copyright

This content is licensed under a [GPL-3.0 License](https://www.gnu.org/licenses/gpl-3.0.en.html), so feel free to use the materials as you please (just not for commercial purposes). I'd appreciate attribution, though; making this workshop was a **lot** of work.