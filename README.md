# Demonstrating *p*-hacking with real data
*Paramita Saha Chaudhuri, PhD (paramita.sahachaudhuri@mcgill.ca)*

In this week's reading from [Simmons and colleagues (2011)](http://journals.sagepub.com/doi/10.1177/0956797611417632), we learned about "researcher degrees of freedom."
That is,

> exploratory behavior [that] is not the by-product of malicious intent, but rather the result of two factors:
> - ambiguity in how best to make these decisions and
> - the researcher’s desire to find a statistically significant result.

Here, we will see the pervasiveness of these two factors in analyzing data.

## Background
[Hypoxic Ischemic Encephalopathy (HIE)](https://www.birthinjuryguide.org/birth-injury/types/hypoxic-ischemic-encephalopathy-hie/) is a type of brain damage that occurs when an infant's brain doesn't receive enough oxygen and blood.
It is a dangerous condition that requires immediate medical intervention.

HIE affects 1.5 out of 1000 newborns in developing countries.
While there are some treatment options&mdash;such as [therapeutic hypothermia](https://www.birthinjuryguide.org/birth-injury/treatment/neonatal-therapeutic-hypothermia/)&mdash;that improve neurological outcomes, at least half of these infants still experience adverse effects in their early childhood.
There is therefore a pressing demand for reliable biomarkers to guide early clinical decisions and to help counsel parents.

The [included data](https://github.com/reprocourse/template-a5-chaudhuri-practical/blob/master/1-longitudinal-minimal%20data%20set-V2.csv) is a slightly altered version of data [from a published article](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0184593).
You will find definitions for all listed variables in the included [variable descriptions](https://github.com/reprocourse/template-a5-chaudhuri-practical/blob/master/variable_descriptions.md) file.


## The present study
You and your collaborators are interested in investigating [copeptin](https://www.ncbi.nlm.nih.gov/pubmed/18291667) and [neuron-specific enolase (NSE)](https://www.mayomedicallaboratories.com/test-catalog/Clinical+and+Interpretive/80913) as two novel biomarkers to predict long-term neurodevelopmental outcome after birth asphyxia.
For the present study, there is a primary aim:

**Aim 1:** Are copeptin and/or NSE associated with favorable neurological outcomes at two years post-HIE?

To investigate this aim, we have sketched out an analysis plan.
After you have examined the listed relationships, we encourage you to conduct additional exploratory analyses to find associations between long-term neurodevelopmental outcome and any biomarker or other characteristic available in the dataset.

Please record all code that you use in the associated [`hie_analysis.py`](https://github.com/reprocourse/template-a5-chaudhuri-practical/blob/master/hie_analysis.py) script.

### Analysis plan

---
1. Draft analysis plan for **Aim 1**.
These includes table shells that you plan to fill (in (b)) and figures you would like to see/show (including potential sensitivity analyses).
This will be similar in format to the "Methods" section of a journal article.
The length should be minimum one paragraph to 1 page.
- Analyze your data according to your plan and draft the corresponding "Results" section of your manuscript.
