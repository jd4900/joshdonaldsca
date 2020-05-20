---
title: "CHBE Ball Model 2020"
date: 2020-02-17T13:00:44-07:00
draft: true
tags: [
    "chemical engineering",
    "coding",
    "python"
]
---

As part of E-Week one of the competetions is to create a model that represents your faculty, and these are shown off during Old Red New Red. To Represent Chemical Engineering I built and designed a simple two tank system with motorized ball valves that opens and closes based off certain inputs. A simple acid-base reaction is carried out if the answer is input to be correct, and if not "untreated effluent" is dispensed. The project code is available [here](https://github.com/jd4900/CHBE-Ball-Model)

The main components are the "hardness" of the water, the level of the Biological Oxygen Demand (BOD) and the pH of the effluent; all common quality control parameters in Waste Water Treatment.

#### Main Display
![Main Display](images/ball_model/main_display.jpg)

The main display is quite simple. The user chooses a setpoint for each parameter and clicks "Execute". If the input is correct, a "Neutralized" pop-up is displayed. If the input is incorrect, a "Toxic" pop-up is displayed. 

![Toxic](/images/ball_model/toxic.JPG)
