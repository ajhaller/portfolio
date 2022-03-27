---
title: "BellaBeat Case Study"
summary: "New and Upcoming Business in Women's Health"
tags: [R]
date: "2022-03-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by gustavofrazao - Fotolia
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Follow
  url: https://github.com/ajhaller
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

# BELLABEAT CASE STUDY

## New and Upcoming Business in Women's Health
Bellabeat is a high-tech company that manufactures health-focused smart products. Since it was founded in 2013, Bellabeat has grown rapidly and quickly positioned itself as a tech-driven wellness company for women; but Bellabeat can grow so much more! Urška Sršen and Sando Mur, Bellabeat's founders, know that an analysis of Bellabeat’s available consumer data would reveal more opportunities for growth.

### Business Objective:
Focus on one Bellabeat product and analyze smart device usage data in order to gain insight into how people are already using their smart devices.

### Questions to Consider:
What are some trends in smart device usage?
How could these trends apply to Bellabeat customers?
How could these trends help influence Bellabeat marketing strategy?

### Steps & Notes for Preparation:
Datasets information: Contains personal fitness tracker from thirty fitbit users. Thirty-three eligible Fitbit users consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habits. This dataset was derived from FitBit Fitness Tracker Data, which establishes reliablity, orginality, and credibility.

Tools: R is able to clean, transform, analyze and visualize data all in one place. The datasets I've used are small enough to work in R, if not SQL would have been used.

# Identifying Trends
### How Often did Participants Use Their Fitbit?

Here I wanted to know if the participants kept their fitbits on the entire month, all seconds of the day. Considering this could significantly change the data. There wasn't specific variable that asked participants if they'd worn the fitbit on a given date, so I had to get a little creative with figuring out how to determine this. The following code explains this process.

![screen reader text](trends.jpg "")

UNDER THE ASSUMPTION that 1440 Sedentary Minutes = 24 Sedentary Hours, which is an entire day with little to no movement, 17 participants went atleast one day without using their fitbit. Unless somehow 17 participants went the entire day hardly moving in bed, I believe it's reasonable to assume these fitbits were not on for days when 1440 Sedentary Minutes were logged.

Based on this assumption, I calculated some percentages based on the amount of days recorded.

{{< gallery album="graphsone" >}}

About half of the participants kept their fitbit on the entire month of observation. A quarter did not use their fitbit on one day. 12% did not use their fitbit between 1-7 days and 16% did not use their fitbit for a week. However, these days where the fitbit was unused, are still being counted as Sedentary minutes, skewing our data to show that the majority of these fitbit participants don't move as much as they actually do when wearing the fitbit. Let's see what happens when we take these unused fitbit days out.

![screen reader text](Intensity.jpg "")

As shown, when accounting for the days the fitbits weren't used, the majority of the participants are Very Active. This makes sense, as people who buy fitbits are most likely interested in their health and fitness; therefore they'd tend to be more conscious about being active.

### What Trends Can We Identify in Participants' Habits?

{{< gallery album="graphstwo" >}}

These participants tend to lose 1500 to 2500 calories and take 5000 to 10000 steps daily on average.

![screen reader text](cals.jpg "")
![screen reader text](intensity2.jpg "")
![screen reader text](steps.jpg "")


All charts shows trends of more intensity, more calories burned and more steps during mid-day to evening, suggests a relationship between all three (which makes sense!)

### Could Date Reflect Changes in Sleep Trends?

![screen reader text](sleep.jpg "")
![screen reader text](sleep_days.jpg "")

There's a statistically significant association between day of the week and hours of sleep for the participants. The trend shows the participants getting the most sleep on Sundays and less in the middle of the week.

### Is There a Relationship Between Intensity Type of Participant and Average Amount of Sleep?

![screen reader text](type.jpg "")

Based on the participant intensity categories, there doesn't seem to be a relationship between Intensity and Average hours of sleep. So regardless of activity, participants seem to be getting the same amount of sleep on average.

# Proposal For Bellabeat based on Analysis
**Alot of information was just shown. Let's sum up the main points of the analysis before giving recommendations:**

* 75% of fitbit participants wore their fitbit consistently
* The majority of participants are Very Active
* These participants tend to lose 1500 to 2500 calories and take 5000 to 10000 steps daily on average
* There are trends of more intensity, more calories burned and more steps during mid-day to evening times
* There's a significant relationship between day of the week and average hours of sleep, where mid-week show less sleep; however, there doesn't seem to be a relationship between Intensity and Average hours of sleep.

![screen reader text](woman.jpg "")

**Here's some recommendations based on these insights:**

**Suggested Product to Market:**

Bellabeat's product, Time, is the product most similar to the fitbit. Therefore, I'd recommend applying these findings to marketing strategies for Time.

**Customer Base:**

Bellabeat should target their marketing strategy towards very active women. People who are very active tend to invest in high-tech health-focused products like Time. It's important to note that the fitbit data did not provide the gender of participants. This is a limitation of the data, however, it's safe to assume the data can be generalized to people in general. Additonal data and further analysis is needed for gender specific conclusions.

**Tips to Improve Sales:**

Bellabeat should emphasize that Time includes the Bellabeat app which tracks health data related to their sleep schedules. In the fitbit data, the analysis showed people are getting less sleep during mid-week. Therefore, Bellabeat should highlight that Bellabeat can help users get consistent average hours of sleep throughout the week, whether it's the weekend or Wednesday! Advertise Bellabeat's commitment to help users better understand their current sleep habits and make healthy decisions.

**Thank you for your interest in my case study!**
