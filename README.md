# WASP Activity Recognition

Solution for the activity recognition  assignment of WASP course Autonomous Systems I

## Task Description

To do this assignment you will need access to a phone running Android, i.e. each group should have at least one person with an Android phone.

Download the (free) application Sensor Fusion from Google Play. It has been developed at LiU. More information is available here: http://sensorfusion.se/sfapp/ 

Your task is to implement an "app" (it is ok if it runs offline on saved data) that does activity recognition based on the data from the phone's sensors.

**Requirements:** The algorithm should be able to discriminate between, standing still, walking and running. You don't have to implement the algorithm on the phone, you can work offline on collected data. Handin a presentation where your solution is presented as well as code+data. 


# Solution

## Installation guide

First install [R](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=2ahUKEwiR6IWYqMLoAhXE4aYKHQ_QA_kQFjAAegQIARAB&url=https%3A%2F%2Fwww.r-project.org%2F&usg=AOvVaw1dEKAtw6XqNnWPRNby8Tne) and [RStudio](https://rstudio.com/).

Then, install the following packages:
- tidyverse
- latex2exp
- xgboost
- patchwork
- extrafont

Clone the repo and run the `main.Rmd` notebook located in the directory `Notebooks`.

Then, the raw data located in the directory `Data` will be processed and the generated figures will be written to the directory called `Figures`. 

For a summary of the analysis, look at the `Presentation`: [https://github.com/cesarsotovalero/wasp-act-recognition/tree/master/Presentation](https://github.com/cesarsotovalero/wasp-act-recognition/tree/master/Presentation)

