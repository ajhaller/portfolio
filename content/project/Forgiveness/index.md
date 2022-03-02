---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "A Chance of Forgiveness"
summary: "An Independent Research Experiment"
authors: []
tags:
categories: []
date: 2022-03-01T19:01:36-05:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Photo by PeopleImages"
  focal_point: Smart

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
## Introduction

We all know that forgiving someone in particular situations is sometimes easier said than done. Whether this is an easy or difficult choice usually depends on several factors. Who are you forgiving? What did they do? Can it be fixed, or is the damage done beyond repair? This project focuses on the factor I've called Percieved Emotional Damage (PED), which is described as how much the person who's granting forgiveness, feels they've been hurt emotionally by the person who asks for forgiveness.


## Hypotheses

In this experiment I asked, "How likely is a person to forgive someone else given how much perceived emotional damage was done to them?". I hypothesized 4 hypotheses: 

**1) I hypothesize that people will grant forgiveness differently across scenarios.**

**2) I hypothesize that people who got the “Maximal” scenario will be less likely to grant forgiveness than those who got the “Mediocre” scenario.**

**3) I hypothesize that people who got the “Maximal” scenario will be less likely to grant forgiveness than those who got the “Minimal” scenario.**

**4) I hypothesize that people who got the “Mediocre” scenario will be less likely to grant forgiveness than those who got the “Minimal” scenario.**

## Method

The explanatory factor was Percieved Emotional Damage, that had three levels, and the response was the likelihood of Forgiveness. To test my hypotheses, I created 3 scenarios based on the amount of Percieved Emotional Damage I wanted to invoke in the participants. All of the scenarios included the same story as follows:

*You had a doctor’s appointment and needed someone to babysit your pet until you got back home. You called your best friend to see if they were available to babysit your pet as usual, and they were happy to come over. When they arrived, you gave them specific instructions and said, “Feed them their favorite snack, watch them closely because they’ve been getting into messes lately, and make sure to let them play outside for a little while.*

The difference between the 3 scenarios occur in the siutation that requires forgiveness. The 3 Percieved Emotional Damage scenarios were divided into a Minimal, Mediocre, and Maximal Percieved Emotional Damage condition. After reading the story, the end changes according to the condition:

**Minimal: "When you got home from your doctor’s visit, your best friend told you that they accidentally gave your pet the wrong snack."**

**Mediocre: "When you got home from your doctor’s visit, your best friend told you that they got distracted watching tv, and your pet got into a mess. Your pet ruined your couch that your beloved family member gifted to you before they passed."**

**Maximal: "When you got home from your doctor’s visit, your best friend told you that they got distracted watching tv while your pet was outside, and they lost your pet. After weeks of searching, you’re unable to find your pet; they’re gone."**

The minimal PED is meant to invoke a small amount of PED, the medicore PED is meant to invoke a medium amount of PED, while the maximal PED is emant to invoke a large amount of PED. Then, the participants is asked on a 1-5 scale, "How likely are you to forgive your best friend in this scenario?". On a scale where, 1 = Extremely unlikely, 2 = Somewhat unlikely, 3 = Neither likely nor unlikely, 4 = Somewhat likely, and 5 = Extremely likely.

The participants, the experimental units, were randomly assigned one of the 3 scenarios to read and all were asked the same question at the end.

## Data Exploration

In evaluating the results of the experiment, I started out with some data exploration.

![screen reader text](peds.jpg "")

The visualization shows that as the Percieved Emotional Damage decreases (from maximal to minimal), the average likelihood of forgiveness increases. The Maximal PED and Mediocre PED share similar standard deviations, 1.08 and 1.15 respectively, while Minimal has the smallest standard deviation, 0.79. This shows that the participants likelihood of forgiveness was more varied in the Maximal and Mediocre scenarios, than they were in the Minimal scenario.

Since the conditions for an ANOVA are met, I will proceed with a one-way ANOVA analysis.

## Results

![screen reader text](anova.jpg "")

There are statistically significant differences in the average liklihood of Forgiveness across Percieved Emotional Damage F(2,107) = 30.06, p = 0.000. This supports hypothesis 1: *"I hypothesize that people will grant forgiveness differently across scenarios."*

### Pairwise Comparisons

To test hypothesis 2, 3 and 4, I conducted pairwise comparisons using LSD, and calculated confidence intervals and effect sizes for each pair with a 95% confidence interval.

All of the hypotheses were supported by LSD, confidence intervals, and effect sizes:

### Hypothesis 2: I hypothesize that people who got the “Maximal” scenario will be less likely to grant forgiveness than those who got the “Mediocre” scenario.

I am 95% confident that the true mean difference in between the maximal scenario and medicore scenario is between .4769 and 1.429. The difference between the likelihood of Forgiveness in the maximal scenario and mediocre scenario is .94 times the size of the typical within-group deviations in the likelihood of Forgiveness. This is a large effect size. Additionally, based on Fisher’s LSD there are statistically significant differences between likelihood of forgiveness in the maximal scenario and the mediocre scenario.

### Hypothesis 3: I hypothesize that people who got the “Maximal” scenario will be less likely to grant forgiveness than those who got the “Minimal” scenario.

I am 95% confident that the true mean difference in between the maximal scenario and minimal scenario is between 1.36 and 2.29. The difference between the likelihood of Forgiveness in the maximal scenario and minimal scenario is 1.81 times the size of the typical within-group deviations in the likelihood of Forgiveness. This is a large effect size. Based on Fisher’s LSD there are statistically significant differences between likelihood of forgiveness in the maximal scenario and the minimal scenario.

### Hypothesis 4: I hypothesize that people who got the “Mediocre” scenario will be less likely to grant forgiveness than those who got the “Minimal” scenario.

I am 95% confident that the true mean difference in between the minimal scenario and medicore scenario is between .410 and 1.34. The difference between the likelihood of Forgiveness in the minimal scenario and mediocre scenario is .86 times the size of the typical within-group deviations in the likelihood of Forgiveness. This is a large effect size. Based on Fisher’s LSD there are statistically significant differences between likelihood of forgiveness in the minimal scenario and the mediocre scenario.

## Conclusion

### Findings

In this experiment I sought out the answer to the question, "How likely is a person to forgive someone else given how much perceived emotional damage was done to them?". The PED levels were hierachal, with PED minimal being the least and PED maximal being the most damage. I've found statistically significant evidence that the more percieved emotional damage done, the less likely a person is to forgive someone. 

### Limitations

This study's sample is a convenience sample compromised of mostly Smith College students. Therefore, the population this study can most likely generalize to are female college students. In the future, I'd like to get a more diverse sample. Additionally, it's important to recognize that this study does not include other factors that may play into forgiveness, for example, the person who's being forgiven, how long you've known them, how likely you are to forgive people in general. This study only manipulates one of the many factors that grants forgiveness, percieved emotional damage. We can only state that when all other factors are controlled for, the more percieved emotional damage, the less likely forgiveness is. 

To improve my model, I'd like to add addtional factors, expanding on the ones above for example: Importance, are they your family, friend, or stranger?; Time Known, for how long have you known this person? I'd also like to add one or two blocking factors: Trauma, how many times have you been betrayed/hurt in the past?; Tendency, what is your tendency to forgive people in general? By adding these factors, my model would begin to be a little more realistic and generalizable to everyday situations. 

*Thank you for reading!*
