
# Description of included variables

In [the included spreadsheet](https://github.com/reprocourse/template-a5-chaudhuri-practical/blob/master/1-longitudinal-minimal%20data%20set-V2.csv), a number of demographic, biomarker, and outcome variables are defined.

Each of these variables may be useful for better understanding the predictive power of [copeptin](https://www.ncbi.nlm.nih.gov/pubmed/18291667) and [Neuron-specific enolase (NSE)](https://www.mayomedicallaboratories.com/test-catalog/Clinical+and+Interpretive/80913) as biomarkers for neurodevelopmental outcomes following [Hypoxic Ischemic Encephalopathy (HIE)](https://www.birthinjuryguide.org/birth-injury/types/hypoxic-ischemic-encephalopathy-hie/).
A description for each of the provided variables is listed in the table below.

For all variables, missing data values are indicated either by empty cells or by the string `nd`, short for "No Data".  

| Variable | Data Type | Description |
|:---------|:----------|:------------|
|Sample # | Integer | Participant ID |
| Cooling | Categorical | Whether the newborn was cooled to prevent adverse impact of hypoxia |
| TOBY-trial | Categorical | Whether the newborn was included in the TOBY trial <br> *(you can disregard this variable for now)* |
| copeptin 6h (pmol/l) | Float | Copeptin measurements at 6 hours |
| copeptin 12h (pmol/l) | Float | Copeptin measurements at 12 hours |
| copeptin 24h (pmol/l) | Float | Copeptin measurements at 24 hours |
| copeptin 48h (pmol/l) | Float | Copeptin measurements at 48 hours |
| copeptin 72h (pmol/l) | Float | Copeptin measurements at 72 hours |
| copeptin 168h (pmol/l) | Float | Copeptin measurements at 168 hours |
| NSE 6h (ng/ml) | Float |  NSE measurements at 6 hours |
| NSE 12h (ng/ml) | Float | NSE measurements at 12 hours |
| NSE 24h (ng/ml) | Float | NSE measurements at 24 hours |
| NSE 48h (ng/ml) | Float | NSE measurements at 48 hours |
| NSE 72h (ng/ml) | Float | NSE measurements at 72 hours |
| NSE 168h (ng/ml) | Float | NSE measurements at 168 hours |
| pH 6h | Float | Blood pH levels at 6 hours |
| pH 12h | Float | Blood pH levels at 12 hours |
| base excess 6h | Float | Blood base excess levels at 6 hours |
| base excess 12h | Float | Blood base excess levels at 12 hours |
| lactate 6h | Float | Blood lactate levels at 6 hours |
| lactate 12h | Float | Blood lactate levels at 12 hours |
| outcome | Categorical | Neurological outcome at 2 years. <br> A 'severe' outcome indicates severe disability; or [Mental Developmental Index (MDI) and Psychomotor Developmental Index (PDI)](http://www.healthofchildren.com/B/Bayley-Scales-of-Infant-Development.html)  < 70 |
| gestational age | Integer | Gestational age (in weeks) of the infant at birth |
| birthweight (g) | Integer | Weight (in grams) of the infant at birth |
| gender (male=1) | Categorical | Gender of the infant where 1: male, 2: female |
| Apgar 5min | Integer | [Apgar score](https://www.acog.org/Clinical-Guidance-and-Publications/Committee-Opinions/Committee-on-Obstetric-Practice/The-Apgar-Score) at 5 minutes |
| Apgar 10min | Integer | [Apgar score](https://www.acog.org/Clinical-Guidance-and-Publications/Committee-Opinions/Committee-on-Obstetric-Practice/The-Apgar-Score) at 10 minutes |
| target T reached (h) | Float | Time (in hours) at which target temperature (33-34&deg;C), is reached |
| delivery mode | Categorical | How the infant was delivered, either vaginal delivery or emergency c-section |
