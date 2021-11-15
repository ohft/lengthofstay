---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
---
<img style="float: right;" src="https://raw.githubusercontent.com/ohft/lengthofstay/master/ohft%20logo%20smaller%20new.png">

# Length of inpatient stays in adult acute care

Predicting hospital demand entails estimating a patient's length of stay (LOS) and the probability that a patient will require longer-term admission and more resources (beds, staff, equipment). Estimating LOS is challenging as it requires investigating patients' trajectories whilst accounting for complexities in the data.

<span style="color:red">This site is under development and accompanies the manuscript *"Risk prediction model of length of stays, delayed discharges and readmissions in adult psychiatric inpatient units in England: a mixed methods study"* pending submission for journal peer-review. **The content should not be used until the final article has been published. The information is not intended for clinical use.** </span>

## Why?
------------------------------------------

**This project aimed to:**

* Interview and analyse themes from clinicians and social workers to understand barriers and facilitators to early discharges and delays?

> “…I mean writing a protocol, a “red2green” schedule, doing the reviews, or building an entire system - that’s all right. But, if you haven’t got enough staff with the skill set to deliver it, then no matter how good I am operationalising it, the rest of it is just never going to work....” — Participant 1

* Predict which patients are most likely to become "long stayers" (stay in hospital for more than 56 days)

* Predict which patient, clinical and service level factors (internal/external) influence LOS in our adult inpatient units?

 > *“I think there is a place for working out or projecting how somebody is going to be, because very often is that “they’re back again, and they’ve done what they did four times previously, they’re going to be in…” - Participant 2*

## How long will a patient stay in hospital? 
------------------------------------------

**A graphical risk prediction model:** 
We estimated the probability of LOS for different patient and service characteristics whilst adjusting for differences between wards, ages and gender.
The graph estimates patients probability of staying in hospital over time by type of mental health problem with the option to add risk factors.
*More features will be added soon.*

For example, how many weeks will a patient with psychosis who is homeless stay? *Answer: Almost 1/5 of admissions will stay over a year in hospital*

Use the graph to:
* Compare the length of stay for different risk groups
* Check which patients are likely to stay for a longer period
* Focus on specific time periods using the drop down menu labelled "All".

<div class="flourish-embed flourish-chart" data-src="visualisation/7620590" data-width="800px" data-height="600px"><script src="https://public.flourish.studio/resources/embed.js"></script></div>


## What is the lenght of stays on our adult wards?
----------------------

### Average lengths of stays*

 | Primary diagnosis | Average in days (95% CI) | + >50 years | Deprived |
 | --- | --- | --- | --- | 
 | **Overall estimate (2016-2021)** | 58.4 (50.9-65.49) | 64.3 (57.4-71.3) | 73.1 (65.5-80.7)	
 | **Bipolar disorders** | 93.4 (74.2-112.7) | 95.5 (75.7-115.3) | 105.9 (85.7-126.1)	
 | **Learning/Intellectual disability** | 86.0 (32.7-139.2) | 86.4 (32.3-140.5) | 97.6 (43.4-151.8) 
 | **Psychosis** | 77.2 (71.9-82.5) | 82.9 (75.5-90.4) | 91.6 (83.8-99.5) 
 | **Dementia** | 65.2 (6.8-123.5) | 68.1 (9-127.2) | 81.7 (22.4-141.1) 
 | **Anxiety disorders** | 55.7 (34.4-76.9) | 62.1 (39.7-84.4) | 73.3 (50.5-96.1)	
 | **Any comorbid substance misuse** | 46.7 (40.0-53.4) | 56.8 (48-65.6) | 65.5 (56.5-74.4) 
 | **Neurodevelopmental disorder** | 43.0 (19.4-66.6) | 49.5 (24.5-74.5) | 58.8 (33.9-83.6)	
 | **Eating disorders** | 40.3 (-5, 85.7) | 	45 (-0.5-90.6) | 54 (8.6-99.5) 
 | **Depressive episode** | 31.3 (21.5-41.1) | 34.6 (24-45.3) | 46.7 (34.7-58.7) 
 | **Mental health problem NOS** | 20.5 (-4.6, 45.6) | 25.4 (-0.3-51) | 32.5 (7.0-57.9)	
 | **Personality disorder** | 20.0 (10.6-29.3) | 26.4 (14.8-38) | 34.8 (23.5-46.1) 
 | **Drug misuse (primary admission cause)** | 19.5 (4.2-34.8) | 24.5 (7.9-41.1) | 33.1 (16.7-49.6)	
 | **Trauma- and stressor-related disorders** | 14.4 (-0.8, 29.6) | 19.8 (3.2-36.4) | 29.2 (12.4-46) 
 
*Adjusted for age, sex, admission year, and ward of discharge

## Contact
-------------------

If you have any concerns, questions or feedback, please contact:

* **Researcher:** Shabeer Syed,<sup>1</sup> Trainee Clinical Psychologist, shabeer.syed@oxfordhealth.nhs.uk 
* **Supervisor:** Prof Paul Salkovskis,<sup>1</sup>  Professor of Clinical Psychology, paul.salkovskis@oxfordhealth.nhs.uk

For Oxford Health oversight:

* Angela Bird,<sup>2</sup> Patient Flow Transformation lead
* Catherine Sage,<sup>3</sup> Head of Service, Adult Mental Health Urgent Care and Social Care
* Dr Rob Bale,<sup>3</sup> Clinical Director and Consultant Psychatrist

<sup>1</sup>[Oxford Institute of Clinical Psychology Training and Research](https://oxicptr.web.ox.ac.uk/people#/), University of Oxford and Oxford Health NHS Foundation Trust, Warneford Hospital, Headington, Oxford, OX3 7JX

<sup>2</sup>[Adult Directorate Management Team, Oxford Health NHS Foundation Trust](https://www.oxfordhealth.nhs.uk/about-us/), Oxford Health NHS Foundation Trust

<sup>1</sup>[Mental Health Urgent Care and Social Care, Oxfordshire BSW Mental Health Directorate](https://www.oxfordhealth.nhs.uk/about-us/), Oxford Health NHS Foundation Trust


[![](https://www.oxfordhealth.nhs.uk/wp-content/uploads/2017/12/sign-wintle-1140x300.jpg)](https://www.oxfordhealth.nhs.uk/)


<script src="http://code.jquery.com/jquery-1.4.2.min.js"></script> <script> var x = document.getElementsByClassName("site-footer-credits"); setTimeout(() => { x[0].remove(); }, 10); </script>
